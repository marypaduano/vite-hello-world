<template>
  <div class="title_style">
    {{ title }}
  </div>
</template>

<script>
export default {
    data(){
        return {
            title: 'Il mio primo nuovo componente !'
        }
    }
}
</script>

<style>
.title_style {
    font-size: 28px;
    text-transform: capitalize;
    border: 1px dotted black;
    padding: 10px;}
</style>