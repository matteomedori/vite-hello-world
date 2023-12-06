<script>
export default {
  data() {
    return {
      paragraphText:
        "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui, excepturi quos velit accusamus exercitationem culpa laborum sapiente aperiam veritatis, earum omnis expedita praesentium tempora quis libero dignissimos! Maiores, voluptatibus ex?",
      jumboTitle: "Jumbotron",
      imgUrl:
        "https://www.raicultura.it/cropgd/900x520/dl/img/2020/04/08/1586351246504_abstract-2468874_1920.jpg",
    };
  },
};
</script>

<template>
  <div class="jumbo">
    <p>
      {{ paragraphText }}
    </p>
    <h2>{{ jumboTitle }}</h2>
    <img :src="imgUrl" alt="img-jumbo" />
  </div>
</template>

<style>
.jumbo {
  text-align: center;
}

h2 {
  color: red;
}

img {
  width: 400px;
  height: 200px;
}
</style>
