<template>
  <div >
    <gnav></gnav>
    <ahero></ahero>
    <team></team>
     <gfoot></gfoot>
  </div>
 
</template>

<script>
// @ is an alias to /src
import gnav from '@/components/navbar'
import gfoot from '@/components/footer'
import ahero from '@/components/About/ahero'
import team from '@/components/About/team'



export default {
  name: 'home',
  components: {
    gnav, gfoot, ahero, team
  }
}
</script>
