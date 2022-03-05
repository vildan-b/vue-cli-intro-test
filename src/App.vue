<template>
  <div class="container">
   <app-header></app-header>
    <hr>
    <div class="row">
      <app-test1></app-test1>
     <app-test2></app-test2>
    </div>
    <hr>
   <app-footer></app-footer>
  </div>
</template>

<script>
import header from './components/common/header'
import footer from './components/common/footer'
import test1 from './components/server/test1'
import test2 from './components/server/test2'
export default {
  components:{
    "app-header": header,
    "app-footer": footer,
    "app-test1" : test1,
    "app-test2" : test2

  }



}
</script>



 




