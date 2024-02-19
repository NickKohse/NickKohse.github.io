<template>
    <header>
      <h1>{{ title }}</h1>
      <nav>
        <ul>
          <li><a href="https://github.com/NickKohse">GitHub</a></li>
          <li><a href="https://linkedin.com/in/nick-kohse">Linkedin</a></li>
          <li><a href="nick-resume.pdf" download>Resume</a></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    data() {
      return {
        title: 'Nick Kohse',
      };
    },
  };
  </script>
  
  <style scoped>
  header {
    background-color: #57c295;
    border: 2px solid #2c3e50;
    padding: 5px;
  }
  
  h1 {
    margin: 0;
  }
  
  ul {
    list-style: none;
    padding: 0;
  }
  
  li {
    display: inline;
    margin-right: 10px;
  }
  
  a {
    color: #2c3e50;
    text-decoration: none;
  }
  </style>