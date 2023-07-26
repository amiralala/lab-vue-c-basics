<script setup>
</script>

<template>
<footer>
    <!-- Added classes in order not to "contaminate" other component default styling -->
    <ul class="footer-ul">
        <li class="footer-li">About Us</li>
        <li class="footer-li">General Conditions</li>
        <li class="footer-li">How to find us</li>
    </ul>
</footer>

</template>

<style>
.footer-ul{
    display:flex ;
    flex-direction: row;
    justify-content:space-around;
}

.footer-li{
  list-style: none;  
  margin-right: 4px;
}
</style>