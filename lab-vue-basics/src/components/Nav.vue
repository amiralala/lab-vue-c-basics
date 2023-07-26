<script setup>
</script>

<template>
<nav>
    <!-- Added classes in order not to "contaminate" other component default styling -->
    <ul class="nav-ul">
        <li class="nav-li">home</li>
        <li class="nav-li">projects</li>
        <li class="nav-li">contact us</li>
    </ul>
</nav>

</template>

<style>
.nav-ul{
    display:flex ;
    flex-direction: row;
    justify-content:space-around;
}

.nav-li{
  list-style: none;  
  margin-right: 4px;
}
</style>