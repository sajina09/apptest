<template>
  <div id="Navigation">
    <ul>
      <li>Home </li>
      <li>Faculty </li>
      <li>FAQ</li>
      <li>Contact </li>
      <li>Queries?</li>
    </ul>
  </div>
</template>
//------------------
<script>
export default {
  name : 'Navigation'
}
</script>
//------------------
"<style lang="scss">
#Navigation{
  display: flex;
  width: 100%;
  background-color: cornflowerblue;

  ul{
    display: flex;
    list-style: none;
    margin : 0 20px 0 0;
    li{
      font-size: 2rem;
      padding: 2px 10px;
      cursor: pointer;
      &:hover{
        color: darkkhaki;
      }
    }

  }

}
</style>