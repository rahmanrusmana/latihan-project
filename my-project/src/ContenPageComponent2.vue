<script setup>
import { TheCard,Button } from 'flowbite-vue'
</script>
<template>
    <p class="m-5 mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Promo terbaik buat liburan irit!</p>
    <Button class="m-5" color="default" pill>Tiket Pesawat</Button>
    <Button class="m-2" color="alternative" pill>Hotel</Button>
    <Button class="m-2" color="alternative" pill>Tiket Kereta Api</Button>
    <Button class="m-2" color="alternative" pill>Tiket Bus & Shutle</Button>
    <Button class="m-2" color="alternative" pill>Antar Jemput Bandara</Button>
    <Button class="m-2" color="alternative" pill>Aktivitas</Button>
    
    <div class="flex flex-row m-5" >
        <div class="basis-1/3 m-2">
            <the-card variant="image" img-src="https://ik.imagekit.io/tvlk/image/imageResource/2023/07/10/1688960330466-6fbc9234d0672d3a668c8af1edda0700.png?tr=q-75" img-alt="Desk">
                <h5 class=" mb-2 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Tur Dan Atraksi</h5>
  
    </the-card></div>
        <div class="basis-1/3 m-2"><the-card variant="image" img-src="https://ik.imagekit.io/tvlk/image/imageResource/2023/07/12/1689127936953-719dde62596460a7f60e8ff2979ffc35.png?tr=q-75" img-alt="Desk">
    <h5 class="mb-2 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Fun Dan Activities</h5>

  </the-card></div>
        <div class="basis-1/3 m-2"><the-card variant="image" img-src="https://ik.imagekit.io/tvlk/image/imageResource/2023/07/12/1689127936953-719dde62596460a7f60e8ff2979ffc35.png?tr=q-75" img-alt="Desk">
    <h5 class="mb-2 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">International Data Plans</h5>
   
  </the-card></div>
    </div>
  
</template>
