<template>
  <div class="home">
    <gnav></gnav>
    <chero></chero>
    <newsletter></newsletter>
     <gfoot></gfoot>
  </div>
 
</template>

<script>
// @ is an alias to /src
import gnav from '@/components/navbar'
import gfoot from '@/components/footer'
import chero from '@/components/contact/chero'
import newsletter from '@/components/Home/newsletter'


export default {
  name: 'contact',
  components: {
    gnav, gfoot,chero, newsletter
  }
}
</script>
