<template>
<div class="header">
        <div class="header__logo"></div>
        <div class="header__text">
            <h1>{{heading}}</h1>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Hero',
  props: ['heading'],
};
</script>

<style scoped lang="scss">
.header{
    font-family: Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
