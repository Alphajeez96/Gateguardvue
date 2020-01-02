<template>
  <div class="home">
    <gnav></gnav>
    <hero></hero>
    <features></features>
    <gateguard></gateguard>
    <customers></customers>
    <newsletter></newsletter>
    
  </div>
 
</template>

<script>
// @ is an alias to /src
import gnav from '@/components/navbar'
import hero from '@/components/Home/hero'
import gfoot from '@/components/footer'
import features from '@/components/Home/features'
import gateguard from '@/components/Home/gateguard'
import customers from '@/components/Home/customers'
import newsletter from '@/components/Home/newsletter'


export default {
  name: 'home',
  components: {
    gnav, hero, gfoot, features, gateguard, customers,  newsletter
  }
}
</script>
