<template> 
  <div>
    <navheader/>
    <sidebar/>
    <Footer/>
    <nuxt />
    
  </div>
</template>
</style>
<script>
import navheader from '@/components/navigation/navheader'
import sidebar from '@/components/navigation/sidebar'
import Footer from '@/components/Footer/Footer'
export default{
  components:{
    navheader,
    sidebar,
    Footer
}
}

      
</script> 
<style>
html, body {
  font-family:'Nunito Sans', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}


 