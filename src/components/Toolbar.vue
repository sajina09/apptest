<template>
    <div id ="Toolbar">
        <span >TOOLBar</span>
    <button id="signout">
        <span>Sign Out</span>
    </button>
        
    </div>
</template>
//----------------
<script>
export default {
    name : 'Toolbar'    
}
</script>
//-----------
<style lang="scss">
#Toolbar{
    align-content: center;
    padding: 2px 2px;
    background-color: darkseagreen;
    align-items: flex-end;
}
#signout{
    align-items: flex-end;
    align-content: center;
    margin: 0 20px 0 0;
    padding: 10px 10px;
    position: right;

}
</style>