<template>
    <div class="header"> 
        <router-link :to="{name:'root'}">
            <img src="../assets/cnodejs_light.svg">
        </router-link>
        <ul>
            <router-link :to="{name:'root'}"><li><a href="#">首页</a></li></router-link>
            <li><a href="#">新手入门</a></li>
            <li><a href="#">API</a></li>
            <li><a href="#">关于</a></li>
            <li><a href="#">注册</a></li>
            <li><a href="#">登录</a></li>
        </ul>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.header{
    background-color:#444;
    height: 50px;
    margin: -8px -8px 0px -8px;
}
img{
    max-width:120px;
    margin-left:60px;
    margin-top:10px;
    padding-left: 100px;
}
ul{
    list-style:none;
    float: right;
    margin: 7px 0;
    padding-right: 250px;
}
li{
    display: inline-block;
    padding: 0 10px;
}
a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
    text-shadow: none;
}
</style>