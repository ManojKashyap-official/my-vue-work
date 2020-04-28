<template>
    <header class="header">
        <ul class="nav-item">
            <li>
                <nuxt-link to="/">Home</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/users">Users</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/Contact">Contact Us.</nuxt-link>
            </li>
        </ul>
    </header>
</template>
<style scoped>
.header{
    background-color: darkgray;
    width: 100;
    height: 80px;
}
.nav-item
{
    list-style: none;
     justify-content: space-around;
     align-items: center;
     display: flex;
     padding-top: 25px;
     color:black;
     
}
.nav-item li:hover{
color: white;
}
</style>>

