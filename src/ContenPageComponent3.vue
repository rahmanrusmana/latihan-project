<script setup>
import { TheCard,Button,Rating } from 'flowbite-vue'
</script>
<template>
    <p class="m-5 mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Vila & Resor di Indonesia</p>
    <Button class="m-5" color="default" pill>Bali</Button>
    <Button class="m-2" color="alternative" pill>Bandung</Button>
    <Button class="m-2" color="alternative" pill>Malang</Button>
    <Button class="m-2" color="alternative" pill>Yogyakarta</Button>
    <Button class="m-2" color="alternative" pill>Bogor</Button>
    <Button class="m-2" color="alternative" pill>Aktivitas</Button>
    
    <div class="flex flex-row m-5" >
        <div class="basis-1/3 m-2">
            <the-card variant="image" img-src="https://ik.imagekit.io/tvlk/apr-asset/dgXfoyh24ryQLRcGq00cIdKHRmotrWLNlvG-TxlcLxGkiDwaUSggleJNPRgIHCX6/hotel/asset/10000848-2000x1333-FIT_AND_TRIM-393c2e9eeb8cc6d90fa5593b1f040630.jpeg?_src=imagekit&tr=c-at_max,h-569,q-40,w-320" img-alt="Desk">
                <h5 class=" mb-2 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Kadiga Villa</h5>
                <Rating
                    :rating="4"
                    :scale="4"
      review-text="73 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
      </template>
    </Rating>
    <span class="text-lg text-sm text-gray-900 line-through dark:text-white">Rp 2.500.000</span> <br>
    <span class="text-lg text-base text-red-500">Rp 1.600.000</span>
  
    </the-card></div>
        <div class="basis-1/3 m-2"><the-card variant="image" img-src="https://ik.imagekit.io/tvlk/apr-asset/dgXfoyh24ryQLRcGq00cIdKHRmotrWLNlvG-TxlcLxGkiDwaUSggleJNPRgIHCX6/hotel/asset/10002061-3888x2592-FIT_AND_TRIM-9e0fc9b5c11f3ef35eb426e43074e9ac.jpeg?_src=imagekit&tr=c-at_max,h-569,q-40,w-320" img-alt="Desk">
    <h5 class="mb-2 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Bali Rich Villas Seminyak</h5>
    <Rating
                    :rating="4"
                    :scale="4"
      review-text="73 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
      </template>
    </Rating>
    <span class="text-lg text-sm text-gray-900 line-through dark:text-white">Rp 2.500.000</span> <br>
    <span class="text-lg text-base text-red-500">Rp 1.600.000</span>
  </the-card></div>
        <div class="basis-1/3 m-2"><the-card variant="image" img-src="https://ik.imagekit.io/tvlk/apr-asset/dgXfoyh24ryQLRcGq00cIdKHRmotrWLNlvG-TxlcLxGkiDwaUSggleJNPRgIHCX6/hotel/asset/10000823-1152x768-FIT_AND_TRIM-0e2bf74ec5eb23531d514c76cdc266ae.jpeg?_src=imagekit&tr=c-at_max,h-569,q-40,w-320" img-alt="Desk">
    <h5 class="mb-2 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">The Banyumas Villa</h5>
    <Rating
                    :rating="4"
                    :scale="4"
      review-text="73 reviews"
      review-link="#"
    >
      <template #besideText>
        <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
      </template>
    </Rating>
    <span class="text-lg text-sm text-gray-900 line-through dark:text-white">Rp 2.500.000</span> <br>
    <span class="text-lg text-base text-red-500">Rp 1.600.000</span>
  </the-card></div>
    </div>
    <center><Button color="default" pill outline square>
    Lihat Semua Hotel
    <template #suffix>
      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
    </template>
  </Button></center>
</template>

<style>
  
</style>
