<template>
    <div class="svg-container">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
        <rect x="10" y="10" width="80" height="80" stroke="black" fill="none" stroke-width="2" />
        <rect x="25" y="25" width="50" height="50" stroke="black" fill="none" stroke-width="2" />
        <rect x="40" y="40" width="20" height="20" stroke="black" fill="none" stroke-width="2" />
        <line x1="10" y1="50" x2="40" y2="50" stroke="black" stroke-width="2" />
        <line x1="60" y1="50" x2="90" y2="50" stroke="black" stroke-width="2" />
        <line x1="50" y1="10" x2="50" y2="40" stroke="black" stroke-width="2" />
        <line x1="50" y1="60" x2="50" y2="90" stroke="black" stroke-width="2" />
        <circle cx="10" cy="10" r="3" fill="black" />
        <circle cx="10" cy="50" r="3" fill="black" />
        <circle cx="10" cy="90" r="3" fill="black" />
        <circle cx="50" cy="10" r="3" fill="black" />
        <circle cx="50" cy="90" r="3" fill="black" />
        <circle cx="90" cy="10" r="3" fill="black" />
        <circle cx="90" cy="50" r="3" fill="black" />
        <circle cx="90" cy="90" r="3" fill="black" />
        <circle cx="25" cy="25" r="3" fill="black" />
        <circle cx="25" cy="50" r="3" fill="black" />
        <circle cx="25" cy="75" r="3" fill="black" />
        <circle cx="50" cy="25" r="3" fill="black" />
        <circle cx="50" cy="75" r="3" fill="black" />
        <circle cx="75" cy="25" r="3" fill="black" />
        <circle cx="75" cy="50" r="3" fill="black" />
        <circle cx="75" cy="75" r="3" fill="black" />
      </svg>
    </div>
  </template>
  
  <script>
  export default {
    name: "SVGComponent"
  };
  </script>
  
  <style scoped>
    .svg-container {
      margin-bottom: 20px;
      background-color: white;
      padding: 10px;
      border-radius: 50%;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      width: 30vw;
      height: 30vw;
      max-width: 25vh;
      max-height: 25vh;
    }
  </style>
  