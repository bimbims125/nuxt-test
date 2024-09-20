<template>
  <!-- BEGIN NAVBAR -->
  <div class="navbar">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </div>
    <!-- END NAVBAR -->

    <div class="container">

      <!-- HEADER -->
      <div class="jumbotron">
        <div class="jumbotron-text">
          <h1>Brandon Morelli</h1>
          <p>Full-Stack Web Developer in Boston, Ma.</p>
        </div>
        <div class="jumbotron-social">
          <ul class="ul-social">
            <li class="li-social-links">
              <a class="social" href="https://github.com/" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://linkedin.com" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://www.facebook.com/" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://twitter.com/" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
            </li>
            <li class="li-social-links">
              <a class="social" href="https://plus.google.com/" target="_blank"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
            </li>
          </ul>
        </div>
        <div id="down-arrow">
          <span><a href="#about"><i class="fa fa-chevron-down" aria-hidden="true"></i></a></span>
        </div>
      </div>
      <!-- END HEADER -->

      <!-- BEGIN ABOUT -->
      <div class="row white box-shadow">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="about"></a>
            <h2>About</h2>
          </div>
          <div class="content-body">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END ABOUT -->

      <!-- BEGIN EXPERIENCE -->
      <div class="row">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="experience"></a>
            <h2>Experience</h2>
          </div>
          <!-- CARD #1 -->
          <div class="content-body">
            <div class="card" v-for="experience in experiences">
              <div class="card-header">
                <h4>{{experience.company}} <span class="job-title">{{experience.job_title}}</span></h4>
              </div>
              <div class="card-content">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END EXPERIENCE -->

      <!-- BEGIN EDUCATION -->
      <div class="row white box-shadow">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="education"></a>
            <h2>Education</h2>
          </div>
          <div class="content-body">

            <!-- EDUCATION DATA -->
            <div class="card" v-for="education in educations">
              <div class="card-header">
                <h4>{{education.name}} <span class="job-title">{{education.date_attended}}</span></h4>
              </div>
              <div class="card-content">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
              </div>
            </div>

          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END EDUCATION -->

      <!-- BEGIN PROJECTS -->
      <div class="row">
        <div class="side-content-sm"></div>
        <div class="main-content-lg">
          <div class="content-header">
            <a class="anchor" name="projects"></a>
            <h2>Projects</h2>
          </div>
          <div class="content-body">
            <!-- CARD #1 -->
            <div class="project-card" v-for="project in projects">
              <div class="project-image">
                <img src="http://placehold.it/250x350">
              </div>
              <div class="project-content">
                <h4>{{project.project_name}}</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                <a href="#">Link Text</a>
              </div>
            </div>
          </div>
        </div>
        <div class="side-content-sm"></div>
      </div>
      <!-- END PROJECTS -->

      <!-- BEGIN SKILLS -->
      <div class="row white box-shadow">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
            <a class="anchor" name="skills"></a>
            <h2>Skills</h2>
          </div>
          <div class="content-body">
            <ul class="ul-skills">
              <li class="li-skills" v-for="skill in skills">{{ skill }}</li>
            </ul>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END SKILLS -->

      <!-- BEGIN FOOTER -->
      <div class="row">
        <div class="side-content"></div>
        <div class="main-content">
          <div class="content-header">
          </div>
          <div class="content-body">
            <p>Copyright YOUR NAME 2017</p>
          </div>
        </div>
        <div class="side-content"></div>
      </div>
      <!-- END FOOTER -->
    </div>
</template>
<style>
@import url("~/assets/style.css");
</style>

<script>
export default {
  data(){
    return{
      // Data Personal
      skills: ["HTML", "Javascript", "PHP", "Laravel", "Python"],

      educations: [
        {name: "Universitas Terbuka", date_attended:"2024 - Now", description:""},
        {name: "SMK PLUS PELITA NUSANTARA", date_attended:"2019 - 2022", description:""},
      ],

      experiences: [
        {company: "Gojek", job_title: "Mobile Developer", description:""},
        {company: "Tokopedia", job_title: "Backend Developer", description:""},
      ],

      projects: [
        {project_name: "Web Apalah", description: "", image:""},
        {project_name: "Web Laundry", description: "", image:""},
      ]
    }
  }
}
</script>
