<template>
  <section class="section">
    <div class="posRel slide-in-bck-center">
      <div class="posAbs"></div>
      <img class="mainLogo" src="../assets/main.png" alt>
    </div>
    <div class="hero-body">
      <div>
        <h1 class="title">Awesome JS</h1>
        <h2 class="subtitle">Explore awesome JS libraries in one place</h2>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  text-align: center;
  padding: 6rem 0rem;
}

.posRel {
  position: relative;
}
@-webkit-keyframes slide-in-bck-center {
  0% {
    -webkit-transform: translateZ(600px);
    transform: translateZ(600px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    opacity: 1;
  }
}
@keyframes slide-in-bck-center {
  0% {
    -webkit-transform: translateZ(600px);
    transform: translateZ(600px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    opacity: 1;
  }
}

.slide-in-bck-center {
  -webkit-animation: slide-in-bck-center 2.7s
    cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
  animation: slide-in-bck-center 2.7s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
}

.posAbs {
  position: absolute;
  top: 40%;
  left: 50%;
  transform: translate(-50%, -50%);
  height: 250px;
  width: 250px;
  background-size: cover;
  /* border-radius: 50%; */
  background-image: url("../assets/moon.png");
  /* background: linear-gradient(-45deg, #6a9cfc, #4370ba, #476089, #476089, #424a59); */
  /* background-size: 400% 400%;
  -webkit-animation: Gradient 15s ease infinite;
  -moz-animation: Gradient 15s ease infinite;
  animation: Gradient 15s ease infinite; */
}

@-webkit-keyframes Gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

@-moz-keyframes Gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

@keyframes Gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

.title {
  font-size: 3.5rem;
  margin-bottom: 2.5rem !important;
  color: #fff;
}
.subtitle {
  color: #adadad;
}

.mainLogo {
  animation: float 7s ease-in-out infinite;
}

@keyframes float {
  0% {
    transform: translatey(0px);
  }
  50% {
    transform: translatey(-20px);
  }
  100% {
    transform: translatey(0px);
  }
}
</style>

