<template>
  <section
    class="mycards"
    v-infinite-scroll="appendLib"
    infinite-scroll-disabled="busy"
    infinite-scroll-distance="limit"
  >
    <b-loading :is-full-page="isFullPage" :active.sync="isLoading" :can-cancel="true"></b-loading>
    <article class="mycard" v-for="(library, index) in libraries" :key="index">
      <a :href="library.homepage" target="_blank">
        <div class="mycard-content">
          <h2 class="is-size-5 titleColor has-text-weight-semibold">{{library.name}}</h2>
          <br>
          <br>
          <p>{{library.description}}</p>                    
        </div>
      </a>
    </article>
  </section>
</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
      isLoading: false,
      libraries: [],
      limit: 12,
      receivedData: [],
      isFullPage: true
    };
  },
  methods: {
    appendLib() {
      this.isLoading = true;
      const append = this.receivedData.slice(
        this.libraries.length,
        this.libraries.length + this.limit
      );
      this.libraries = this.libraries.concat(append);
      this.isLoading = false;
    },
    getLibraries() {
      axios
        .get(
          "https://api.cdnjs.com/libraries?fields=description,repository,homepage"
        )
        .then(response => {
          this.receivedData = response.data.results;
          this.appendLib();
        });
    }
  },
  created() {
    this.getLibraries();
  }
};
</script>



<style scoped>
.titleColor {
  color: #3a4b52;
  letter-spacing: 1.5px;
}
.mycard {
  background: white;
  margin-bottom: 2em;
  border-radius: 8px;
  box-shadow: 0 2px 10px 0 rgba(7, 31, 49, 0.06);
}

.mycard a {
  color: #5c5c5d;
  transition: all 0.3s;
}
.mycard:hover {
  box-shadow: 0 0 0 2px #1487FF;
}

.mycard-content {
  padding: 1.4em;
}

@media screen and (min-width: 40em) {
  .mycards {
    margin-top: -1em;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .mycard {
    margin-bottom: 1em;
    display: flex;
    flex: 0 1 calc(50% - 0.5em);
  }
}

@media screen and (min-width: 60em) {
  .mycards {
    margin-top: inherit;
  }

  .mycard {
    margin-bottom: 2em;
    display: flex;
    flex: 0 1 calc(33% - 0.5em);
  }
}
</style>
