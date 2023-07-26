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
  </the-card></div>
    </div>
</template>
