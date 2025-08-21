<script setup lang="ts">

</script>

<template>
  <div class="header">
    <a href="/notebook"><h1>Shea Wadman</h1></a>
    <p>Science Notebook</p>
  </div>

  <div class="topnav">
    <a href="/pro">About Me</a>
    <a href="/demos">Demos</a>
    <a href="/projects">Projects</a>
  </div>

  <div>
    <p>This is the area for professional info and resume</p>
  </div>

</template>

<style scoped>
.topnav {
  overflow: hidden;
  background-color: black;
}
.topnav a {
  float: left;
  display: block;
  color: #cf4602;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.topnav a:hover {
  background-color: #cf4602;
  color: black;
}
*{
  box-sizing: border-box;
}

body {
  margin: 0;
}

/* Style the header */
.header {
  background-color: #f1f1f1;
  padding: 20px;
  text-align: center;
}
.column {
  float: left;
  width: 33.33%;
  padding: 15px;
}

/* Clear floats after the columns */
.row::after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width:600px) {
  .column {
    width: 100%;
  }
}
</style>