<template>
    <div>
        <h1>La mia prima app con Vue CLI!</h1>
        
    </div>
</template>


<script>
export default{
  name: 'mioTitolo',
  props: {
    msg: String
  }
}
</script>


<style scoped lang="scss">
h1{
  color: #fff;
}
</style>