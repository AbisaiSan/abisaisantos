<template>
  <footer>
  
    <div class="icons-footer"> 
      <li>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon github" style="color:#fff;" :icon = "['fab', 'github']" size="2x"/>
         </a>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon linkedin" style="color:#fff;" :icon = "['fab', 'linkedin']" size="2x"/>
         </a>
         <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon twitter" style="color:#fff;" :icon = "['fab', 'twitter']" size="2x"/>
         </a>
         <a href="https://github.com/AbisaiSan" target="_blank">
             <font-awesome-icon class="icon instagram" style="color:#fff;" :icon = "['fab', 'instagram']" size="2x"/>
         </a>
      </li>
    </div>
    
    <div class="copy">Desenvolvido por Abisai Santos</div>
</footer>
</template>

<script>
export default {

}
</script>

<style scoped>
  /*===FOOTER===*/
footer{
  width: 100%;
  padding: 16px;
  margin-top: 5%;
  background-color: #0e2431;
  text-align: center;
}

.icons-footer li {
  margin-top: 5%;
  list-style: none;
}
.icons-footer   a {
  list-style: none;
  padding:0 15px;
}

.copy{
   margin-top: 15px;
  color: #fff;
  font-weight: 600;
}
</style>