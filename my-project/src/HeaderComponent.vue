<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://ik.imagekit.io/tvlk/image/imageResource/2023/04/28/1682672109394-137e522e47c482f2dfcbde08189274b7.png?tr=q-75',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://ik.imagekit.io/tvlk/image/imageResource/2023/07/10/1688960330466-6fbc9234d0672d3a668c8af1edda0700.png?tr=q-75',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://ik.imagekit.io/tvlk/image/imageResource/2023/07/10/1688960330466-6fbc9234d0672d3a668c8af1edda0700.png?tr=q-75',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://ik.imagekit.io/tvlk/image/imageResource/2023/07/17/1689561016697-4f5e39db51742afa7d404525715619ed.jpeg?tr=q-75',
    'alt': 'Picture 4',
  },
  {
    'src': 'https://ik.imagekit.io/tvlk/image/imageResource/2023/07/12/1689127936953-719dde62596460a7f60e8ff2979ffc35.png?tr=q-75',
    'alt': 'Picture 5',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>


