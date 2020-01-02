<template>
  <div class="home">
    <gnav></gnav>
    <copage></copage>
     <gfoot></gfoot>
  </div>
 
</template>

<script>
// @ is an alias to /src
import gnav from '@/components/navbar'
import gfoot from '@/components/footer'
import copage from '@/components/coming/copage'



export default {
  name: 'home',
  components: {
    gnav, gfoot, copage
  }
}
</script>
