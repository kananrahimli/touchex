<template>
  <div class="positon-relative">
       <img
          class="round-close-sales position-absolute"
          src="../assets/svg/round-close-sales.svg"
          alt=""
        />
    <div id="logo" class="">
      <img src="../assets/svg/touch-express-logo.svg" alt="" />
    </div>

    <div class="text-container d-flex justify-content-center  ">
      <div class="d-flex justify-content-center align-items-center flex-column">
        <h3>Tezliklə</h3>
        <p>Lorem Ipsum is simply dummy</p>
        <img src="../assets/svg/daire.svg" alt="" />
      </div>
      
    </div>
   
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#logo {
  img {
    max-width: 224px;
    height: 71px;
    margin-top: 21px;
    margin-left: 42px;
  }
}

.round-close-sales{
    right: 0px;
    max-width: 1000px;
}

.text-container {
  background-color: rgba(50, 50, 68, 1);
  max-width: 930px;
  height: 272px;
  margin-top: 130px;
  margin-left: 42px;
  border-radius: 40px;
  border-top-right-radius: 0px;
  position: relative;

  img{
    max-width: 118px;
    height: 118px;
    position: absolute;
    top: -56px;
    left: 100px;
  }
  h3 {
    color: rgba(253, 99, 31, 1);
    font-weight: 800;
    font-size: 62px;
  }
  p {
    font-weight: 200 !important;
    font-size: 20px;
    color: #fff;
  }
}
</style>
