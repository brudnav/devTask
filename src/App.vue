<script setup></script>

<template>
  <div class="container">
    <div class="wrapper">
      <div class="btn mb-4">Vaše klientela</div>
      <h2>Více zákazníků</h2>
      <h2 class="mb-4">Větší tržby</h2>
      <p class="mb-6">
        Zvyšte viditelnost vašeho salonu! Díky online profilu a snadné správě
        rezervací <b>zvýšíte vaše tržby, přilákáte nové zákazníky</b> a budete
        mít o všem lepší přehled.
      </p>
      <div class="btn--fullwidth mb-12">Registrovat salon</div>
    </div>
    <div class="img-container">
      <img src="./assets/small_image.png" alt="" />
    </div>
  </div>
</template>

<style>
.container {
  /* background-color: crimson; */
  width: 100%;
}
.btn {
  background-color: #520dc2;
  width: fit-content;
  padding: 12px 8px;
  color: white;
  font-weight: bold;
  border-radius: 8px;
}
h2 {
  font-size: 36px;
  color: white;
  white-space: nowrap;
}
p {
  color: white;
  min-width: 303px;
  max-width: 60ch;
  line-height: 1.6;
}

.btn--fullwidth {
  background-color: white;
  width: 100%;
  padding: 24px 12px;
  color: black;
  border-radius: 6px;
  text-align: center;
  font-weight: bold;
}

.img-container {
  width: 100%;
  /* background-color: bisque; */
  display: flex;
  border-top-left-radius: 12px;
  justify-content: end;
  overflow: hidden;
}

.img-container img {
  content: url("./assets/small_image.png");
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.wrapper {
  padding-right: 20px;
}

@media screen and (min-width: 700px) {
  body {
    padding: 116px 0 116px 88px;
    min-height: 100vh;
    overflow: hidden;
  }

  .btn--fullwidth {
    display: flex;
    width: 199px;
    height: 60px;
    justify-content: center;
    align-items: center;
  }

  .container {
    display: flex;
    gap: 46px;
    overflow: visible;
  }

  .img-container {
    position: relative;
    top: -40px;
    max-width: 100%;
    min-width: 412px;
    max-height: 450px;
  }

  .img-container img {
    content: url("./assets/large_image.png");
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .wrapper {
    width: 431px;
    height: 388px;
    flex-shrink: 0;
    padding: 0;
  }
}
</style>
