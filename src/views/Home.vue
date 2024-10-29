<script setup>
import html2pdf from "html2pdf.js";
const exportToPDF = () => {
  html2pdf(document.getElementById("element-to-convert"), {
        margin: 0,
        html2canvas:  { scale: 1 },
        image:        { type: 'jpeg', quality: 2 },
        filename: "YuraKorobeynikResume.pdf",
      });
    };
</script>

<template>
  <div class="container" ref="document" id="element-to-convert">
    <div class="left-item">
      <div class="photo"></div>
      <div class="about">
        <div class="l-item">
          <div class="l-title">About</div>
          <div class="l-item-text">
            6+ years of experience in commercial web development.
            Vue.js developer with 4 years of experience in designing and implementing innovative web applications.
          </div>
        </div>
        <div class="l-item">
          <div class="l-title">Skills</div>
          <ul class="l-item-text">
            <li>JavaScript ES6 </li>
            <li>Vue.js Options API & Composition API</li>
            <li>TypeScript</li>
            <li>Familiarity with GitHub/Lab processes</li>
            <li>HTML5/CSS</li>
            <li>API Integration: Experience with RESTful APIs using Axios or Fetch.</li>
            <li>Responsive Design: Ability to create applications for various devices.</li>
            <li>Nuxt.js: Knowledge of server-side rendering.</li>
            <li>Expereriens with PHP, NODE JS</li>
          </ul>
        </div>
        <div class="l-item">
          <div class="l-title">Links</div>
          <div class="links">
            <a class="link" href="https://t.me/korobeynikY" target="_blank">
              <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path d="M16,2c-7.732,0-14,6.268-14,14s6.268,14,14,14,14-6.268,14-14S23.732,2,16,2Zm6.489,9.521c-.211,2.214-1.122,7.586-1.586,10.065-.196,1.049-.583,1.401-.957,1.435-.813,.075-1.43-.537-2.218-1.053-1.232-.808-1.928-1.311-3.124-2.099-1.382-.911-.486-1.412,.302-2.23,.206-.214,3.788-3.472,3.858-3.768,.009-.037,.017-.175-.065-.248-.082-.073-.203-.048-.29-.028-.124,.028-2.092,1.329-5.905,3.903-.559,.384-1.065,.571-1.518,.561-.5-.011-1.461-.283-2.176-.515-.877-.285-1.574-.436-1.513-.92,.032-.252,.379-.51,1.042-.773,4.081-1.778,6.803-2.95,8.164-3.517,3.888-1.617,4.696-1.898,5.222-1.907,.116-.002,.375,.027,.543,.163,.142,.115,.181,.27,.199,.379,.019,.109,.042,.357,.023,.551Z" fill-rule="evenodd"></path></svg>
            </a>
            <a href="https://www.linkedin.com/in/yura-korobeynik-56b535a4/" class="link" target="_blank">
              <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path d="M26.111,3H5.889c-1.595,0-2.889,1.293-2.889,2.889V26.111c0,1.595,1.293,2.889,2.889,2.889H26.111c1.595,0,2.889-1.293,2.889-2.889V5.889c0-1.595-1.293-2.889-2.889-2.889ZM10.861,25.389h-3.877V12.87h3.877v12.519Zm-1.957-14.158c-1.267,0-2.293-1.034-2.293-2.31s1.026-2.31,2.293-2.31,2.292,1.034,2.292,2.31-1.026,2.31-2.292,2.31Zm16.485,14.158h-3.858v-6.571c0-1.802-.685-2.809-2.111-2.809-1.551,0-2.362,1.048-2.362,2.809v6.571h-3.718V12.87h3.718v1.686s1.118-2.069,3.775-2.069,4.556,1.621,4.556,4.975v7.926Z" fill-rule="evenodd"></path></svg>
            </a>
            <a class="link" href="https://join.skype.com/invite/E9eaEET0hMof" target="_blank">
            <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path id="1706619708419-4618629_Shape" d="M16.057,24.427c-4.651,0-6.776-2.369-6.776-4.107,0-.415,.17-.811,.47-1.096,.301-.285,.706-.434,1.12-.411,1.991,0,1.471,2.987,5.186,2.987,1.899,0,3.015-1.143,3.015-2.217,0-.645-.369-1.383-1.623-1.678l-4.149-1.046c-3.333-.848-3.914-2.701-3.914-4.421,0-3.568,3.264-4.859,6.371-4.859,2.863,0,6.265,1.581,6.265,3.72,0,.922-.77,1.415-1.664,1.415-1.701,0-1.415-2.388-4.836-2.388-1.701,0-2.595,.797-2.595,1.913s1.323,1.494,2.485,1.747l3.061,.691c3.356,.756,4.25,2.724,4.25,4.61,0,2.9-2.245,5.14-6.67,5.14m12.848-6.136c.133-.761,.199-1.532,.198-2.305,.016-3.881-1.689-7.569-4.656-10.071-2.967-2.502-6.891-3.559-10.713-2.887-1.175-.676-2.507-1.031-3.863-1.028-2.783,.017-5.348,1.508-6.739,3.918-1.391,2.41-1.4,5.377-.024,7.795-.768,4.221,.577,8.551,3.603,11.592,3.025,3.042,7.348,4.411,11.573,3.666,1.173,.676,2.504,1.03,3.858,1.028,2.781-.018,5.345-1.509,6.736-3.917,1.391-2.408,1.401-5.374,.027-7.792"></path></svg>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="right-item">
      <div class="title">Yura Korobeynik</div>
      <div class="description">Middle+ Frontend Developer</div>
      <button id="download" @click="exportToPDF">Download</button>
      <div class="experience">
        <div class="experience-title"><span>Work Experience</span></div>
        
        <div class="experience-item">
          <div class="item-title">Middle Frontend Developer / Wordpress developer</div>
          <div class="item-date">Freelance | 09.2023 - present</div>
          <div class="item-description">
            Building a Progressive Web App (PWA) using Vue 3, developing custom WordPress themes with Vue 3 integration, implementing custom themes on WordPress, including setting up templates, styles, and functionality.
          </div>
        </div>  

        <div class="experience-item">
          <div class="item-title">Middle Frontend Developer</div>
          <div class="item-date">Aimprosoft | 11.2020 - 10.2023</div>
          <div class="item-description">
            Develop large-scale projects in Vue 2 focused on building responsive and high-performance applications with component-based architecture. Knowledge of Vuex state management, API integration and optimization for scalability and maintainability. Skilled in implementing advanced UI/UX features and providing a smooth user experience across all devices.
          </div>
        </div>

        <div class="experience-item">
          <div class="item-title">Front-end / Fullstack Developer</div>
          <div class="item-date">LumoSpark | 11.2017 - 07.2020</div>
          <div class="item-description">
              More than 20 websites of varying complexity have been developed. Developed front end using Bootstrap.js, Vue.js, Nuxt 2.
              Developed dynamic responsive Web Application by integrating Vue.js with Bootstrap which is further integrated with Web Services.
              Website development with wordpress, and theme development for WP.
          </div>
        </div>

        <div class="experience-item">
          <div class="item-title">Front-end Developer</div>
          <div class="item-date">4-marketing | 07.2016 - 08.2017</div>
          <div class="item-description">
            Develop landing pages. Creating online shops on opencart.
            Used JQuery JavaScript libraries for providing richer user interface and facilitates asynchronous request invocations using AJAX.
          </div>
        </div>

      </div>
    </div>
  </div>    
    
 
</template>

<style scoped lang="scss">

.link {
  display: inline-block;
  margin-right: 15px;
  svg {
    fill: white;
  }
}

.experience-item {
  font-size: 13px;
  margin-bottom: 20px;
  line-height: 1.4;
  .item-date {
    color: #a6a6a6;
    margin-bottom: 5px 0 10px 0;
    font-size: 14px;
    margin-bottom: 5px;
  }
  .item-title {
    font-weight: bold;
    font-size: 16px;
  }
}

.container {
  width: 100%;
  display: flex;
  max-width: 900px;
  background: #000;
  height: 100%;
  margin: 0 auto;
  padding: 0 50px;
  color: white;
  #download {
    background-color: blue;
    border: none;
    color: white;
    padding: 5px 15px;
    border-radius: 5px;
    font-weight: bold;
    position: absolute;
    right: 0;
    z-index: 100;
    &:hover {
      cursor: pointer;
    }
    }
  .right-item {
    position: relative;
    width: 50%;
    padding: 40px 50px;
    padding-bottom: 20px;
    position: relative;
    .description {
      font-size: 18px;
      font-weight: bold;
      color: #a6a6a6;
      margin-bottom: 10px;
    }
    .experience-title {
      font-size: 18px;
      margin-bottom: 15px;
      position: relative;
      z-index: 10;
      &:before {
        content: '';
        display: block;
        width: 30px;
        height: 30px;
        background-color: blue;
        position:absolute;
        left: -10px;
        top: -5px;
        border-radius: 50%;
        z-index: 0;
      }
      span {
        display: block;
        font-size: 18px;
        font-weight: bold;
        position: relative;
      }
    }
    .title {
      font-size: 30px;
      color: white;
      font-weight: bold;
    }
  }
  .about {
    padding: 30px;
    .l-title {
      font-size: 24px;
      font-weight: bold;
      color: #a6a6a6;
      margin-bottom: 5px;
    }
    ul.l-item-text {
      padding: 0;
      li {
        display: inline-block;
        position: relative;
        padding-right: 10px;
      }
    }
  }
  .left-item {
    width: 50%;
    background: darkblue;
    .l-item {
      margin-bottom: 20px;
    }
    .photo {
      background-color: #000;
      height: 310px;
      width: 100%;
      background-size: 100%;
      background-position: bottom;
      background-repeat: no-repeat;
      background-image: url("../assets/photo.jpg");
      filter: grayscale(100%);
    }
  }
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>