
<script>

import TarifaComponet from '@/components/tarifa/TarifaComponet.vue';
</script>


<template>

    <div class="tarifa">
        <TarifaComponet />

        <h3>Tarifas</h3>
        <p id="precios">para el 2024</p>
    </div>

</template>

<style>

.tarifa {
    background-image: url(../../src/assets/image/tarifa.jpg);
    display: flex; 
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 50vh;
    background-repeat: no-repeat;
    background-size: cover; 
    background-position: center;
}

#precios, h3{
    color: white;
    justify-content: center;

}

h3{
font-weight: 600;
font-size: 9rem;
}



</style>