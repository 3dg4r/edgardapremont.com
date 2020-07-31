<script>
import NavigationBar from '@/components/navigation-bar.vue';

export default {
  name: 'Header',
  components: {
    NavigationBar,
  },
};
</script>

<template>
  <div class="header">
    <div class="header-text">
      <h1 class="header-h1">
        <span class="text-yellow">Edgar</span>&nbsp;
        <span class="text-yellow switch">Dapremont</span>&nbsp;&nbsp;
        <span>UI Developer</span>
      </h1>
      <ul class="subhead">
        <li class="header-h1 dates no-box">2007 thru 2020</li>
        <li>Web</li>
        <li>Mobile</li>
        <li>Javascript</li>
        <li>Vue</li>
        <li>React</li>
        <li>HTML5</li>
        <li>CSS/Sass</li>
      </ul>
      <NavigationBar></NavigationBar>
    </div>
    <div class="header-flag">
      <div class="center-stripe"></div>
      <div class="brand-logo text-default">UI/UX</div>
    </div>
    <div class="banner">Engineer Reference Manual</div>
  </div>
  <!--     <p>Edgar Dapremont</p> <p>UI/UX Developer for Websites and Mobile
  Apps</p> <p>New Orleans, LA</p> <p>Remote Employee</p> <ul> <li>Javscript</li>
  <li> <ul> <li>Vue</li> <li>React</li> <li>Angular</li> <li>Node</li>
  <li>jQuery</li> </ul> </li> <li>Git</li> <li>CSS</li> <li>HTML5</li> <li>REST
  APIs</li> </ul> <div> <p>14 years experience working with front end
  technologies</p> <p>Agile and Kanban environments</p> <p>Responsive website and
  app development</p> <p>Solo and team experience as a developer</p> <p>User
  interfaces used by 1000s of site visitors</p> <p>Contributed to two patents</p>
  </div> -->
</template>
