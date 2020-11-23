<template>
<section class="section">
    <div class="skill-title">
      <h2>Professional Skills</h2>
    </div>
    <div class="skills">
       <li>
        <a  href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon html"  :icon = "['fab', 'html5']" size="4x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon css" style="color:#0e2431;" :icon = "['fab', 'css3-alt']" size="4x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon js" style="color:#0e2431;" :icon = "['fab', 'js-square']" size="4x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon node" style="color:#0e2431;" :icon = "['fab', 'node']" size="4x"/>
        </a>
      </li>
       <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon react" style="color:#0e2431;" :icon = "['fab', 'react']" size="4x"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon laravel" style="color:#0e2431;" :icon = "['fab', 'laravel']" size="4x"/>
        </a>
      </li>
      <li>
        <a href="https://github.com/AbisaiSan" target="_blank">
            <font-awesome-icon class="icon vue" style="color:#0e2431;" :icon = "['fab', 'vuejs']" size="4x"/>
        </a>
      </li>
  </div>
   <!--<img id="img-skills" src="../assets/skills.jpg" alt="Foto de Lukas no Pexels">-->
</section>
</template>

<script>
export default {

}
</script>

<style scoped>
/*===SKILLS===*/
li {
  list-style: none;
}

.section {
  padding: 100px 50px;
}

.skill-title {
  margin-top:5%;
}

.skill-title h2 {
  padding-bottom: 10%;
  text-align: center;
  font-size: 2.5rem;
  line-height: 4rem;
  color: #4070f4;
}
.skill-title h3 {
  padding-top: 2%;
  text-align:center;
  font-size:2rem;
  line-height: 3rem;
  color: #0e2431;
}
.skills {
  display: flex;
  justify-content: center;
  padding: 20px;
  
}


.skills a {
  margin: 0 35px;
  text-decoration: none;
  font-size: 15px;
  color:#0e2431;
  font-weight: 500;
}

/*HOVER COLORS*/

.icon:hover{
  -webkit-transform: scale(0);
  transform: scale(2.5);
  transition: all 0.5s;
}

.skills .html:hover {
   color: #f16528!important;
}
.skills .css:hover {
   color:#239ad8!important;
}
.skills .js:hover {
   color: #efd81d!important;
}
.skills .node:hover {
   color: #529a43!important;
}
.skills .react:hover {
   color: #48cef7!important;
}
.skills .laravel:hover {
   color:#f74138!important;
}
.skills .vue:hover {
   color:#346165!important;
}

@media (max-width:700px){
 .skills a {
  
  margin: 0 10px;
}
.icon {
  width: 30px;
}

}

</style>