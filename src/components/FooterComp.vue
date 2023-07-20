<template>
<div class="footer">

    <h1>teleport Component</h1>
    <p>Copyright @reserved All rights</p>

    </div>
</template>
<script>
export default {
    name:"FooterComp"
}
</script>
<style scoped>
h1{
    background-color: blueviolet;
    color: blanchedalmond;
}
.footer
{
    color: rgb(170, 126, 48);
    position: absolute;
    bottom: 0%;
    background-color: antiquewhite;
    width: 90%;
    left: 0%;
    padding-left: 10%;
}
</style>