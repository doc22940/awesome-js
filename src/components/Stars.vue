<template>
  <div class="stars">
    <div v-for="n in 100" :key="n" class="starContainer">
      <div class="star"></div>
    </div>
  </div>
</template>
<style>
.stars .starContainer {
  position: absolute;
  animation: stars linear infinite;
}
.stars .starContainer .star {
  animation: twinkle linear infinite;
  border-radius: 100%;
  transform: translateZ(0);
}
.stars .starContainer:nth-child(0) {
  width: 3px;
  height: 3px;
  left: 99.5vw;
  animation-delay: -994.4666666666667s;
  animation-duration: 92.60000000000001s;
}
.stars .starContainer:nth-child(0) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.7s;
  animation-duration: 28.2s;
  background: rgba(222, 239, 154, 0.9);
}
.stars .starContainer:nth-child(1) {
  width: 3px;
  height: 3px;
  left: 97vw;
  animation-delay: -997.1333333333333s;
  animation-duration: 88.53333333333335s;
}
.stars .starContainer:nth-child(1) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.5s;
  animation-duration: 39.8s;
  background: rgba(222, 216, 253, 0.8);
}
.stars .starContainer:nth-child(2) {
  width: 2px;
  height: 2px;
  left: 85.5vw;
  animation-delay: -991.2s;
  animation-duration: 145.4s;
}
.stars .starContainer:nth-child(2) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.4s;
  animation-duration: 21.5s;
  background: #dca8b8;
}
.stars .starContainer:nth-child(3) {
  width: 2px;
  height: 2px;
  left: 38vw;
  animation-delay: -993.1s;
  animation-duration: 147.9s;
}
.stars .starContainer:nth-child(3) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.7s;
  animation-duration: 33.9s;
  background: rgba(244, 170, 196, 0.8);
}
.stars .starContainer:nth-child(4) {
  width: 3px;
  height: 3px;
  left: 51vw;
  animation-delay: -995.3333333333334s;
  animation-duration: 53s;
}
.stars .starContainer:nth-child(4) .star {
  width: inherit;
  height: inherit;
  animation-delay: -43.7s;
  animation-duration: 25s;
  background: rgba(239, 243, 251, 0.7);
}
.stars .starContainer:nth-child(5) {
  width: 2px;
  height: 2px;
  left: 97vw;
  animation-delay: -997s;
  animation-duration: 34.4s;
}
.stars .starContainer:nth-child(5) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.6s;
  animation-duration: 5.8s;
  background: #efccfa;
}
.stars .starContainer:nth-child(6) {
  width: 3px;
  height: 3px;
  left: 83.5vw;
  animation-delay: -997.5333333333333s;
  animation-duration: 79.73333333333333s;
}
.stars .starContainer:nth-child(6) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.4s;
  animation-duration: 42.9s;
  background: rgba(208, 238, 128, 0.8);
}
.stars .starContainer:nth-child(7) {
  width: 3px;
  height: 3px;
  left: 49.5vw;
  animation-delay: -994.3333333333334s;
  animation-duration: 87.13333333333333s;
}
.stars .starContainer:nth-child(7) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.8s;
  animation-duration: 45.6s;
  background: rgba(226, 204, 253, 0.8);
}
.stars .starContainer:nth-child(8) {
  width: 2px;
  height: 2px;
  left: 26vw;
  animation-delay: -996.6s;
  animation-duration: 101.2s;
}
.stars .starContainer:nth-child(8) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.5s;
  animation-duration: 36.7s;
  background: rgba(203, 197, 214, 0.9);
}
.stars .starContainer:nth-child(9) {
  width: 2px;
  height: 2px;
  left: 65vw;
  animation-delay: -998.9s;
  animation-duration: 41.5s;
}
.stars .starContainer:nth-child(9) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.6s;
  animation-duration: 46s;
  background: rgba(201, 171, 213, 0.8);
}
.stars .starContainer:nth-child(10) {
  width: 3px;
  height: 3px;
  left: 0vw;
  animation-delay: -997.7333333333333s;
  animation-duration: 47.46666666666667s;
}
.stars .starContainer:nth-child(10) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.9s;
  animation-duration: 24.7s;
  background: rgba(223, 157, 240, 0.9);
}
.stars .starContainer:nth-child(11) {
  width: 3px;
  height: 3px;
  left: 2vw;
  animation-delay: -997.6666666666666s;
  animation-duration: 68.46666666666667s;
}
.stars .starContainer:nth-child(11) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47.3s;
  animation-duration: 17.5s;
  background: rgba(253, 230, 114, 0.7);
}
.stars .starContainer:nth-child(12) {
  width: 2px;
  height: 2px;
  left: 38vw;
  animation-delay: -993.4s;
  animation-duration: 143.5s;
}
.stars .starContainer:nth-child(12) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.6s;
  animation-duration: 10.9s;
  background: #f3c0ab;
}
.stars .starContainer:nth-child(13) {
  width: 1px;
  height: 1px;
  left: 46.5vw;
  animation-delay: -985.8s;
  animation-duration: 246.2s;
}
.stars .starContainer:nth-child(13) .star {
  width: inherit;
  height: inherit;
  animation-delay: -43s;
  animation-duration: 37.1s;
  background: rgba(200, 157, 182, 0.8);
}
.stars .starContainer:nth-child(14) {
  width: 1px;
  height: 1px;
  left: 52vw;
  animation-delay: -982.8s;
  animation-duration: 248.6s;
}
.stars .starContainer:nth-child(14) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.6s;
  animation-duration: 48.1s;
  background: rgba(212, 155, 180, 0.7);
}
.stars .starContainer:nth-child(15) {
  width: 3px;
  height: 3px;
  left: 71vw;
  animation-delay: -994.4s;
  animation-duration: 97.93333333333334s;
}
.stars .starContainer:nth-child(15) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.7s;
  animation-duration: 28.1s;
  background: rgba(251, 154, 230, 0.9);
}
.stars .starContainer:nth-child(16) {
  width: 2px;
  height: 2px;
  left: 73.5vw;
  animation-delay: -991.7s;
  animation-duration: 35.1s;
}
.stars .starContainer:nth-child(16) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48s;
  animation-duration: 6.6s;
  background: #e2bda6;
}
.stars .starContainer:nth-child(17) {
  width: 2px;
  height: 2px;
  left: 93vw;
  animation-delay: -998.1s;
  animation-duration: 80.9s;
}
.stars .starContainer:nth-child(17) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.2s;
  animation-duration: 26.2s;
  background: rgba(221, 241, 184, 0.9);
}
.stars .starContainer:nth-child(18) {
  width: 1px;
  height: 1px;
  left: 19.5vw;
  animation-delay: -990.8s;
  animation-duration: 168.2s;
}
.stars .starContainer:nth-child(18) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.4s;
  animation-duration: 9.3s;
  background: #dcb9f4;
}
.stars .starContainer:nth-child(19) {
  width: 2px;
  height: 2px;
  left: 5vw;
  animation-delay: -993.6s;
  animation-duration: 55.1s;
}
.stars .starContainer:nth-child(19) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47.4s;
  animation-duration: 5.2s;
  background: rgba(211, 202, 228, 0.8);
}
.stars .starContainer:nth-child(20) {
  width: 3px;
  height: 3px;
  left: 60vw;
  animation-delay: -999.7333333333333s;
  animation-duration: 82.66666666666667s;
}
.stars .starContainer:nth-child(20) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46s;
  animation-duration: 20.6s;
  background: rgba(210, 163, 113, 0.7);
}
.stars .starContainer:nth-child(21) {
  width: 2px;
  height: 2px;
  left: 36.5vw;
  animation-delay: -992.3s;
  animation-duration: 32.8s;
}
.stars .starContainer:nth-child(21) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40s;
  animation-duration: 6.9s;
  background: #e59afb;
}
.stars .starContainer:nth-child(22) {
  width: 3px;
  height: 3px;
  left: 69vw;
  animation-delay: -997.2666666666667s;
  animation-duration: 122.39999999999999s;
}
.stars .starContainer:nth-child(22) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.6s;
  animation-duration: 49s;
  background: rgba(207, 214, 252, 0.8);
}
.stars .starContainer:nth-child(23) {
  width: 1px;
  height: 1px;
  left: 79.5vw;
  animation-delay: -998.6s;
  animation-duration: 120.6s;
}
.stars .starContainer:nth-child(23) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.2s;
  animation-duration: 32.2s;
  background: rgba(226, 239, 198, 0.7);
}
.stars .starContainer:nth-child(24) {
  width: 1px;
  height: 1px;
  left: 24vw;
  animation-delay: -995.6s;
  animation-duration: 280s;
}
.stars .starContainer:nth-child(24) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.7s;
  animation-duration: 23.4s;
  background: rgba(252, 163, 147, 0.9);
}
.stars .starContainer:nth-child(25) {
  width: 2px;
  height: 2px;
  left: 7vw;
  animation-delay: -992.5s;
  animation-duration: 118.9s;
}
.stars .starContainer:nth-child(25) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.5s;
  animation-duration: 6.7s;
  background: rgba(215, 209, 231, 0.8);
}
.stars .starContainer:nth-child(26) {
  width: 3px;
  height: 3px;
  left: 65.5vw;
  animation-delay: -997.0666666666667s;
  animation-duration: 39.6s;
}
.stars .starContainer:nth-child(26) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.4s;
  animation-duration: 29.4s;
  background: rgba(226, 194, 226, 0.9);
}
.stars .starContainer:nth-child(27) {
  width: 2px;
  height: 2px;
  left: 51.5vw;
  animation-delay: -998.9s;
  animation-duration: 50.9s;
}
.stars .starContainer:nth-child(27) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.4s;
  animation-duration: 17.1s;
  background: rgba(225, 179, 115, 0.7);
}
.stars .starContainer:nth-child(28) {
  width: 3px;
  height: 3px;
  left: 21vw;
  animation-delay: -996.8s;
  animation-duration: 121.33333333333333s;
}
.stars .starContainer:nth-child(28) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47.4s;
  animation-duration: 45.8s;
  background: rgba(229, 203, 190, 0.8);
}
.stars .starContainer:nth-child(29) {
  width: 3px;
  height: 3px;
  left: 55vw;
  animation-delay: -995.4666666666667s;
  animation-duration: 80.93333333333334s;
}
.stars .starContainer:nth-child(29) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42s;
  animation-duration: 24.1s;
  background: #d1cc85;
}
.stars .starContainer:nth-child(30) {
  width: 3px;
  height: 3px;
  left: 94.5vw;
  animation-delay: -995.1333333333333s;
  animation-duration: 110.2s;
}
.stars .starContainer:nth-child(30) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.4s;
  animation-duration: 43.4s;
  background: rgba(212, 216, 125, 0.8);
}
.stars .starContainer:nth-child(31) {
  width: 2px;
  height: 2px;
  left: 48vw;
  animation-delay: -993s;
  animation-duration: 70.7s;
}
.stars .starContainer:nth-child(31) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.4s;
  animation-duration: 44.9s;
  background: rgba(207, 227, 105, 0.7);
}
.stars .starContainer:nth-child(32) {
  width: 1px;
  height: 1px;
  left: 46.5vw;
  animation-delay: -998.6s;
  animation-duration: 200.6s;
}
.stars .starContainer:nth-child(32) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.6s;
  animation-duration: 40.4s;
  background: rgba(218, 186, 108, 0.8);
}
.stars .starContainer:nth-child(33) {
  width: 2px;
  height: 2px;
  left: 27vw;
  animation-delay: -992.6s;
  animation-duration: 120.2s;
}
.stars .starContainer:nth-child(33) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.5s;
  animation-duration: 42.6s;
  background: rgba(225, 234, 230, 0.8);
}
.stars .starContainer:nth-child(34) {
  width: 2px;
  height: 2px;
  left: 3.5vw;
  animation-delay: -998s;
  animation-duration: 125s;
}
.stars .starContainer:nth-child(34) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.5s;
  animation-duration: 48.3s;
  background: rgba(242, 218, 206, 0.8);
}
.stars .starContainer:nth-child(35) {
  width: 1px;
  height: 1px;
  left: 33.5vw;
  animation-delay: -989.4s;
  animation-duration: 228.8s;
}
.stars .starContainer:nth-child(35) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.4s;
  animation-duration: 26s;
  background: rgba(243, 156, 170, 0.7);
}
.stars .starContainer:nth-child(36) {
  width: 3px;
  height: 3px;
  left: 52vw;
  animation-delay: -996.2666666666667s;
  animation-duration: 45.6s;
}
.stars .starContainer:nth-child(36) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47s;
  animation-duration: 44.7s;
  background: rgba(219, 190, 107, 0.8);
}
.stars .starContainer:nth-child(37) {
  width: 1px;
  height: 1px;
  left: 32vw;
  animation-delay: -992.4s;
  animation-duration: 167s;
}
.stars .starContainer:nth-child(37) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.8s;
  animation-duration: 11.1s;
  background: rgba(238, 173, 199, 0.8);
}
.stars .starContainer:nth-child(38) {
  width: 2px;
  height: 2px;
  left: 95vw;
  animation-delay: -995.6s;
  animation-duration: 44.1s;
}
.stars .starContainer:nth-child(38) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.9s;
  animation-duration: 10.9s;
  background: rgba(234, 181, 125, 0.8);
}
.stars .starContainer:nth-child(39) {
  width: 1px;
  height: 1px;
  left: 30vw;
  animation-delay: -998.4s;
  animation-duration: 262.8s;
}
.stars .starContainer:nth-child(39) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.6s;
  animation-duration: 29.3s;
  background: rgba(200, 175, 112, 0.7);
}
.stars .starContainer:nth-child(40) {
  width: 3px;
  height: 3px;
  left: 59vw;
  animation-delay: -994.8s;
  animation-duration: 100.8s;
}
.stars .starContainer:nth-child(40) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.5s;
  animation-duration: 30.5s;
  background: rgba(222, 204, 184, 0.7);
}
.stars .starContainer:nth-child(41) {
  width: 3px;
  height: 3px;
  left: 36vw;
  animation-delay: -998.8s;
  animation-duration: 61.199999999999996s;
}
.stars .starContainer:nth-child(41) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41s;
  animation-duration: 36.4s;
  background: rgba(222, 182, 202, 0.9);
}
.stars .starContainer:nth-child(42) {
  width: 1px;
  height: 1px;
  left: 66.5vw;
  animation-delay: -982s;
  animation-duration: 254s;
}
.stars .starContainer:nth-child(42) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.7s;
  animation-duration: 33.3s;
  background: rgba(249, 201, 103, 0.7);
}
.stars .starContainer:nth-child(43) {
  width: 1px;
  height: 1px;
  left: 31.5vw;
  animation-delay: -986.2s;
  animation-duration: 140.6s;
}
.stars .starContainer:nth-child(43) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.4s;
  animation-duration: 46.7s;
  background: rgba(207, 246, 150, 0.7);
}
.stars .starContainer:nth-child(44) {
  width: 2px;
  height: 2px;
  left: 90.5vw;
  animation-delay: -993.4s;
  animation-duration: 69.7s;
}
.stars .starContainer:nth-child(44) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.3s;
  animation-duration: 24.5s;
  background: rgba(247, 171, 145, 0.8);
}
.stars .starContainer:nth-child(45) {
  width: 1px;
  height: 1px;
  left: 81vw;
  animation-delay: -991.6s;
  animation-duration: 103.6s;
}
.stars .starContainer:nth-child(45) .star {
  width: inherit;
  height: inherit;
  animation-delay: -43.4s;
  animation-duration: 41.4s;
  background: #fbfb9b;
}
.stars .starContainer:nth-child(46) {
  width: 3px;
  height: 3px;
  left: 23.5vw;
  animation-delay: -998.0666666666667s;
  animation-duration: 43.06666666666666s;
}
.stars .starContainer:nth-child(46) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.1s;
  animation-duration: 28.6s;
  background: #dbb0ba;
}
.stars .starContainer:nth-child(47) {
  width: 1px;
  height: 1px;
  left: 74.5vw;
  animation-delay: -987.2s;
  animation-duration: 375.4s;
}
.stars .starContainer:nth-child(47) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.2s;
  animation-duration: 35.1s;
  background: #eab391;
}
.stars .starContainer:nth-child(48) {
  width: 2px;
  height: 2px;
  left: 7vw;
  animation-delay: -994.3s;
  animation-duration: 165.3s;
}
.stars .starContainer:nth-child(48) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44s;
  animation-duration: 45.9s;
  background: #ebbf7f;
}
.stars .starContainer:nth-child(49) {
  width: 3px;
  height: 3px;
  left: 33.5vw;
  animation-delay: -997.7333333333333s;
  animation-duration: 26.066666666666666s;
}
.stars .starContainer:nth-child(49) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.1s;
  animation-duration: 20.6s;
  background: rgba(219, 220, 141, 0.9);
}
.stars .starContainer:nth-child(50) {
  width: 2px;
  height: 2px;
  left: 42vw;
  animation-delay: -993.8s;
  animation-duration: 114.2s;
}
.stars .starContainer:nth-child(50) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.3s;
  animation-duration: 42.3s;
  background: rgba(218, 161, 159, 0.8);
}
.stars .starContainer:nth-child(51) {
  width: 1px;
  height: 1px;
  left: 55.5vw;
  animation-delay: -988.2s;
  animation-duration: 52.6s;
}
.stars .starContainer:nth-child(51) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.8s;
  animation-duration: 48.2s;
  background: #e4a1ba;
}
.stars .starContainer:nth-child(52) {
  width: 1px;
  height: 1px;
  left: 42.5vw;
  animation-delay: -986.4s;
  animation-duration: 96.4s;
}
.stars .starContainer:nth-child(52) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.1s;
  animation-duration: 34s;
  background: #f8da7b;
}
.stars .starContainer:nth-child(53) {
  width: 3px;
  height: 3px;
  left: 40.5vw;
  animation-delay: -998.3333333333334s;
  animation-duration: 99.2s;
}
.stars .starContainer:nth-child(53) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.8s;
  animation-duration: 35.8s;
  background: rgba(250, 221, 251, 0.9);
}
.stars .starContainer:nth-child(54) {
  width: 3px;
  height: 3px;
  left: 55.5vw;
  animation-delay: -999.8666666666667s;
  animation-duration: 36.53333333333333s;
}
.stars .starContainer:nth-child(54) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.3s;
  animation-duration: 8.5s;
  background: rgba(230, 226, 116, 0.9);
}
.stars .starContainer:nth-child(55) {
  width: 3px;
  height: 3px;
  left: 97.5vw;
  animation-delay: -998.2s;
  animation-duration: 44.93333333333334s;
}
.stars .starContainer:nth-child(55) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.7s;
  animation-duration: 24s;
  background: #ff99a0;
}
.stars .starContainer:nth-child(56) {
  width: 2px;
  height: 2px;
  left: 29vw;
  animation-delay: -991.2s;
  animation-duration: 191s;
}
.stars .starContainer:nth-child(56) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.7s;
  animation-duration: 40s;
  background: rgba(233, 239, 210, 0.7);
}
.stars .starContainer:nth-child(57) {
  width: 2px;
  height: 2px;
  left: 88vw;
  animation-delay: -997s;
  animation-duration: 126.8s;
}
.stars .starContainer:nth-child(57) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.1s;
  animation-duration: 45.9s;
  background: rgba(254, 153, 229, 0.8);
}
.stars .starContainer:nth-child(58) {
  width: 2px;
  height: 2px;
  left: 86vw;
  animation-delay: -992.7s;
  animation-duration: 96.1s;
}
.stars .starContainer:nth-child(58) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.1s;
  animation-duration: 28.9s;
  background: rgba(234, 208, 147, 0.8);
}
.stars .starContainer:nth-child(59) {
  width: 2px;
  height: 2px;
  left: 10.5vw;
  animation-delay: -999.5s;
  animation-duration: 68.6s;
}
.stars .starContainer:nth-child(59) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42s;
  animation-duration: 32.8s;
  background: #e7ebad;
}
.stars .starContainer:nth-child(60) {
  width: 1px;
  height: 1px;
  left: 63.5vw;
  animation-delay: -980s;
  animation-duration: 334.2s;
}
.stars .starContainer:nth-child(60) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.1s;
  animation-duration: 27.9s;
  background: rgba(253, 163, 161, 0.7);
}
.stars .starContainer:nth-child(61) {
  width: 1px;
  height: 1px;
  left: 84vw;
  animation-delay: -997.2s;
  animation-duration: 196.6s;
}
.stars .starContainer:nth-child(61) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.9s;
  animation-duration: 23.1s;
  background: rgba(205, 224, 169, 0.8);
}
.stars .starContainer:nth-child(62) {
  width: 3px;
  height: 3px;
  left: 37.5vw;
  animation-delay: -996.8666666666667s;
  animation-duration: 122s;
}
.stars .starContainer:nth-child(62) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.6s;
  animation-duration: 41.7s;
  background: rgba(254, 243, 119, 0.7);
}
.stars .starContainer:nth-child(63) {
  width: 3px;
  height: 3px;
  left: 3vw;
  animation-delay: -998.9333333333333s;
  animation-duration: 67.86666666666666s;
}
.stars .starContainer:nth-child(63) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.1s;
  animation-duration: 15s;
  background: rgba(203, 195, 222, 0.8);
}
.stars .starContainer:nth-child(64) {
  width: 3px;
  height: 3px;
  left: 29.5vw;
  animation-delay: -998.6s;
  animation-duration: 103.60000000000001s;
}
.stars .starContainer:nth-child(64) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.7s;
  animation-duration: 40s;
  background: rgba(226, 232, 108, 0.9);
}
.stars .starContainer:nth-child(65) {
  width: 1px;
  height: 1px;
  left: 86.5vw;
  animation-delay: -982.6s;
  animation-duration: 223.8s;
}
.stars .starContainer:nth-child(65) .star {
  width: inherit;
  height: inherit;
  animation-delay: -43.1s;
  animation-duration: 17.5s;
  background: rgba(232, 184, 250, 0.9);
}
.stars .starContainer:nth-child(66) {
  width: 2px;
  height: 2px;
  left: 97vw;
  animation-delay: -991.2s;
  animation-duration: 189.7s;
}
.stars .starContainer:nth-child(66) .star {
  width: inherit;
  height: inherit;
  animation-delay: -43s;
  animation-duration: 34.8s;
  background: rgba(207, 174, 108, 0.8);
}
.stars .starContainer:nth-child(67) {
  width: 3px;
  height: 3px;
  left: 85.5vw;
  animation-delay: -999.6s;
  animation-duration: 51.53333333333333s;
}
.stars .starContainer:nth-child(67) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.4s;
  animation-duration: 31.6s;
  background: rgba(250, 166, 202, 0.8);
}
.stars .starContainer:nth-child(68) {
  width: 1px;
  height: 1px;
  left: 96vw;
  animation-delay: -981.8s;
  animation-duration: 244.8s;
}
.stars .starContainer:nth-child(68) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.4s;
  animation-duration: 12.2s;
  background: #c8a5cf;
}
.stars .starContainer:nth-child(69) {
  width: 2px;
  height: 2px;
  left: 54.5vw;
  animation-delay: -997.1s;
  animation-duration: 57.2s;
}
.stars .starContainer:nth-child(69) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.8s;
  animation-duration: 20.3s;
  background: rgba(204, 215, 209, 0.9);
}
.stars .starContainer:nth-child(70) {
  width: 2px;
  height: 2px;
  left: 44vw;
  animation-delay: -998s;
  animation-duration: 165.7s;
}
.stars .starContainer:nth-child(70) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.8s;
  animation-duration: 15.7s;
  background: rgba(209, 168, 201, 0.9);
}
.stars .starContainer:nth-child(71) {
  width: 2px;
  height: 2px;
  left: 83vw;
  animation-delay: -995.5s;
  animation-duration: 67.2s;
}
.stars .starContainer:nth-child(71) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40s;
  animation-duration: 41.1s;
  background: rgba(201, 170, 156, 0.8);
}
.stars .starContainer:nth-child(72) {
  width: 3px;
  height: 3px;
  left: 97.5vw;
  animation-delay: -997.0666666666667s;
  animation-duration: 54.73333333333333s;
}
.stars .starContainer:nth-child(72) .star {
  width: inherit;
  height: inherit;
  animation-delay: -40.4s;
  animation-duration: 47.3s;
  background: #fdaa6b;
}
.stars .starContainer:nth-child(73) {
  width: 2px;
  height: 2px;
  left: 89.5vw;
  animation-delay: -990s;
  animation-duration: 54.4s;
}
.stars .starContainer:nth-child(73) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.7s;
  animation-duration: 27.4s;
  background: rgba(210, 177, 145, 0.7);
}
.stars .starContainer:nth-child(74) {
  width: 1px;
  height: 1px;
  left: 28.5vw;
  animation-delay: -982.6s;
  animation-duration: 294s;
}
.stars .starContainer:nth-child(74) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47.4s;
  animation-duration: 13.4s;
  background: rgba(240, 206, 167, 0.9);
}
.stars .starContainer:nth-child(75) {
  width: 3px;
  height: 3px;
  left: 45vw;
  animation-delay: -997.5333333333333s;
  animation-duration: 130.06666666666666s;
}
.stars .starContainer:nth-child(75) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.9s;
  animation-duration: 30.8s;
  background: rgba(246, 157, 121, 0.7);
}
.stars .starContainer:nth-child(76) {
  width: 3px;
  height: 3px;
  left: 90.5vw;
  animation-delay: -997.8666666666667s;
  animation-duration: 28.133333333333336s;
}
.stars .starContainer:nth-child(76) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.9s;
  animation-duration: 8.5s;
  background: rgba(214, 208, 139, 0.9);
}
.stars .starContainer:nth-child(77) {
  width: 3px;
  height: 3px;
  left: 38.5vw;
  animation-delay: -994.3333333333334s;
  animation-duration: 22.666666666666668s;
}
.stars .starContainer:nth-child(77) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46s;
  animation-duration: 15.6s;
  background: #f1bb77;
}
.stars .starContainer:nth-child(78) {
  width: 1px;
  height: 1px;
  left: 41.5vw;
  animation-delay: -981.2s;
  animation-duration: 288.4s;
}
.stars .starContainer:nth-child(78) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.2s;
  animation-duration: 49.8s;
  background: rgba(248, 193, 197, 0.8);
}
.stars .starContainer:nth-child(79) {
  width: 2px;
  height: 2px;
  left: 60.5vw;
  animation-delay: -996.2s;
  animation-duration: 114.6s;
}
.stars .starContainer:nth-child(79) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.1s;
  animation-duration: 35.9s;
  background: rgba(239, 218, 117, 0.9);
}
.stars .starContainer:nth-child(80) {
  width: 3px;
  height: 3px;
  left: 93.5vw;
  animation-delay: -999.7333333333333s;
  animation-duration: 87.66666666666667s;
}
.stars .starContainer:nth-child(80) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.6s;
  animation-duration: 43.5s;
  background: rgba(255, 161, 105, 0.8);
}
.stars .starContainer:nth-child(81) {
  width: 1px;
  height: 1px;
  left: 84.5vw;
  animation-delay: -987.2s;
  animation-duration: 266s;
}
.stars .starContainer:nth-child(81) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47s;
  animation-duration: 30.5s;
  background: #f3a278;
}
.stars .starContainer:nth-child(82) {
  width: 1px;
  height: 1px;
  left: 58vw;
  animation-delay: -999.6s;
  animation-duration: 126.4s;
}
.stars .starContainer:nth-child(82) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.5s;
  animation-duration: 19.6s;
  background: rgba(255, 250, 143, 0.7);
}
.stars .starContainer:nth-child(83) {
  width: 1px;
  height: 1px;
  left: 92.5vw;
  animation-delay: -986.6s;
  animation-duration: 365.2s;
}
.stars .starContainer:nth-child(83) .star {
  width: inherit;
  height: inherit;
  animation-delay: -49.5s;
  animation-duration: 16.7s;
  background: rgba(208, 208, 158, 0.9);
}
.stars .starContainer:nth-child(84) {
  width: 1px;
  height: 1px;
  left: 1.5vw;
  animation-delay: -983.2s;
  animation-duration: 291.6s;
}
.stars .starContainer:nth-child(84) .star {
  width: inherit;
  height: inherit;
  animation-delay: -45.8s;
  animation-duration: 9.5s;
  background: rgba(209, 161, 120, 0.9);
}
.stars .starContainer:nth-child(85) {
  width: 2px;
  height: 2px;
  left: 77.5vw;
  animation-delay: -999s;
  animation-duration: 58.9s;
}
.stars .starContainer:nth-child(85) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.7s;
  animation-duration: 27.8s;
  background: rgba(254, 204, 224, 0.9);
}
.stars .starContainer:nth-child(86) {
  width: 2px;
  height: 2px;
  left: 39vw;
  animation-delay: -999.7s;
  animation-duration: 162.1s;
}
.stars .starContainer:nth-child(86) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.9s;
  animation-duration: 5.3s;
  background: #e6eec2;
}
.stars .starContainer:nth-child(87) {
  width: 1px;
  height: 1px;
  left: 37vw;
  animation-delay: -993.6s;
  animation-duration: 393.6s;
}
.stars .starContainer:nth-child(87) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.5s;
  animation-duration: 6.6s;
  background: #e0fcc5;
}
.stars .starContainer:nth-child(88) {
  width: 3px;
  height: 3px;
  left: 1vw;
  animation-delay: -993.9333333333333s;
  animation-duration: 98.53333333333335s;
}
.stars .starContainer:nth-child(88) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.5s;
  animation-duration: 16.5s;
  background: rgba(252, 201, 122, 0.9);
}
.stars .starContainer:nth-child(89) {
  width: 3px;
  height: 3px;
  left: 56.5vw;
  animation-delay: -997.8666666666667s;
  animation-duration: 78.73333333333333s;
}
.stars .starContainer:nth-child(89) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.2s;
  animation-duration: 32.8s;
  background: #d3d48d;
}
.stars .starContainer:nth-child(90) {
  width: 2px;
  height: 2px;
  left: 72.5vw;
  animation-delay: -998s;
  animation-duration: 72.7s;
}
.stars .starContainer:nth-child(90) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.6s;
  animation-duration: 44.3s;
  background: #ecdfc4;
}
.stars .starContainer:nth-child(91) {
  width: 3px;
  height: 3px;
  left: 79.5vw;
  animation-delay: -993.7333333333333s;
  animation-duration: 46.6s;
}
.stars .starContainer:nth-child(91) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47.4s;
  animation-duration: 7.1s;
  background: rgba(200, 180, 137, 0.7);
}
.stars .starContainer:nth-child(92) {
  width: 3px;
  height: 3px;
  left: 22.5vw;
  animation-delay: -994s;
  animation-duration: 60.46666666666667s;
}
.stars .starContainer:nth-child(92) .star {
  width: inherit;
  height: inherit;
  animation-delay: -41.9s;
  animation-duration: 34.1s;
  background: rgba(238, 216, 183, 0.7);
}
.stars .starContainer:nth-child(93) {
  width: 2px;
  height: 2px;
  left: 9vw;
  animation-delay: -993.9s;
  animation-duration: 41s;
}
.stars .starContainer:nth-child(93) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.8s;
  animation-duration: 14s;
  background: rgba(206, 186, 220, 0.8);
}
.stars .starContainer:nth-child(94) {
  width: 2px;
  height: 2px;
  left: 64vw;
  animation-delay: -990.1s;
  animation-duration: 76.7s;
}
.stars .starContainer:nth-child(94) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.1s;
  animation-duration: 6.3s;
  background: rgba(241, 189, 170, 0.8);
}
.stars .starContainer:nth-child(95) {
  width: 3px;
  height: 3px;
  left: 74vw;
  animation-delay: -999.7333333333333s;
  animation-duration: 37.93333333333333s;
}
.stars .starContainer:nth-child(95) .star {
  width: inherit;
  height: inherit;
  animation-delay: -46.9s;
  animation-duration: 24.2s;
  background: #d7daf6;
}
.stars .starContainer:nth-child(96) {
  width: 3px;
  height: 3px;
  left: 64vw;
  animation-delay: -996.8666666666667s;
  animation-duration: 130.66666666666666s;
}
.stars .starContainer:nth-child(96) .star {
  width: inherit;
  height: inherit;
  animation-delay: -48.1s;
  animation-duration: 18.2s;
  background: #e09b82;
}
.stars .starContainer:nth-child(97) {
  width: 3px;
  height: 3px;
  left: 27vw;
  animation-delay: -996s;
  animation-duration: 21.2s;
}
.stars .starContainer:nth-child(97) .star {
  width: inherit;
  height: inherit;
  animation-delay: -47.4s;
  animation-duration: 45.1s;
  background: rgba(246, 250, 208, 0.9);
}
.stars .starContainer:nth-child(98) {
  width: 2px;
  height: 2px;
  left: 100vw;
  animation-delay: -992.7s;
  animation-duration: 30.7s;
}
.stars .starContainer:nth-child(98) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.7s;
  animation-duration: 13.5s;
  background: #f3d0df;
}
.stars .starContainer:nth-child(99) {
  width: 1px;
  height: 1px;
  left: 43.5vw;
  animation-delay: -990.2s;
  animation-duration: 114.8s;
}
.stars .starContainer:nth-child(99) .star {
  width: inherit;
  height: inherit;
  animation-delay: -42.5s;
  animation-duration: 22.9s;
  background: #fec36a;
}
.stars .starContainer:nth-child(100) {
  width: 1px;
  height: 1px;
  left: 68vw;
  animation-delay: -996s;
  animation-duration: 235s;
}
.stars .starContainer:nth-child(100) .star {
  width: inherit;
  height: inherit;
  animation-delay: -44.3s;
  animation-duration: 36s;
  background: rgba(203, 165, 194, 0.8);
}
@-moz-keyframes stars {
  0% {
    transform: translateY(110vh) translateZ(0);
  }
  100% {
    transform: translateY(-10vh) translateZ(0);
  }
}
@-webkit-keyframes stars {
  0% {
    transform: translateY(110vh) translateZ(0);
  }
  100% {
    transform: translateY(-10vh) translateZ(0);
  }
}
@-o-keyframes stars {
  0% {
    transform: translateY(110vh) translateZ(0);
  }
  100% {
    transform: translateY(-10vh) translateZ(0);
  }
}
@keyframes stars {
  0% {
    transform: translateY(110vh) translateZ(0);
  }
  100% {
    transform: translateY(-10vh) translateZ(0);
  }
}
@-moz-keyframes twinkle {
  0%,
  80%,
  100% {
    opacity: 0.7;
    box-shadow: 0 0 0 #fff, 0 0 0 #fff;
  }
  95% {
    opacity: 1;
    box-shadow: 0 0 2px #fff, 0 0 4px #fff;
  }
}
@-webkit-keyframes twinkle {
  0%,
  80%,
  100% {
    opacity: 0.7;
    box-shadow: 0 0 0 #fff, 0 0 0 #fff;
  }
  95% {
    opacity: 1;
    box-shadow: 0 0 2px #fff, 0 0 4px #fff;
  }
}
@-o-keyframes twinkle {
  0%,
  80%,
  100% {
    opacity: 0.7;
    box-shadow: 0 0 0 #fff, 0 0 0 #fff;
  }
  95% {
    opacity: 1;
    box-shadow: 0 0 2px #fff, 0 0 4px #fff;
  }
}
@keyframes twinkle {
  0%,
  80%,
  100% {
    opacity: 0.7;
    box-shadow: 0 0 0 #fff, 0 0 0 #fff;
  }
  95% {
    opacity: 1;
    box-shadow: 0 0 2px #fff, 0 0 4px #fff;
  }
}
</style>

