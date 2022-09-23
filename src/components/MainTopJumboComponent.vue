<template>
  <div class="jumbo-bg-main">
    <div class="container main-jumbo-container">
        <h3>CURRENT SERIES</h3>
    </div>
  </div>
</template>

<script>
export default {
name: 'MainTopJumboComponent'
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';

    .jumbo-bg-main {
        background-image: url(../assets/img/jumbotron.jpg);
        height: 400px;


        h3 {
            background-color: $bg-blue;
            padding: 8px;
            position: absolute;
            left: 0;
            bottom: -19px;
        }
    }

    .main-jumbo-container {
        height: 100%;
        position: relative;
    }

</style>