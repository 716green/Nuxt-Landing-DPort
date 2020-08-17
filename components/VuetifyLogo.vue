<template>
  <img
    class="DPLogo"
    alt="Debt Portfol.io Logo"
    src="/debt-portfolio.svg"
  >
</template>

<style>
.DPLogo {
  height: 60px;
  width: 350px;
  transform: rotateX(90deg);
  animation: turn 1.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
