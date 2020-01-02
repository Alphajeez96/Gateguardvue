<template>
  <div class="home">
    <gnav></gnav>
    <phero></phero>
    <newsletter></newsletter>
     <gfoot></gfoot>
  </div>
 
</template>

<script>
// @ is an alias to /src
import gnav from '@/components/navbar'
import gfoot from '@/components/footer'
import phero from '@/components/partners/phero'
import newsletter from '@/components/Home/newsletter'



export default {
  name: 'partners',
  components: {
    gnav, gfoot, phero, newsletter
  }
}
</script>
