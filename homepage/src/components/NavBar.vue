<template>
    <nav class="navbar">
      <div class="navbar-left">
        <img src="@/assets/site_logo.jpeg" alt="GlobalEdulink Logo" class="logo" />
      </div>
      <ul class="navbar-center">
        <li><a href="#">Explore Courses</a></li>
      </ul>
      <ul class="navbar-right">
        <li><a href="#">Corporate Training</a></li>
        <li><a href="#">Become an Instructor</a></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'NavBar'
  }
  </script>
  
  <style scoped>
.navbar {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 450px;
  background-color: #f5f5f5; /* Background color similar to the image */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Optional: adds a subtle shadow for better separation from content */
  z-index: 1000; /* Ensures the navbar stays above other content */
}

.logo {
  height: 30px; /* Adjust the height according to your logo size */
}

.navbar-center,
.navbar-right {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}

.navbar-center li,
.navbar-right li {
  margin-left: 20px;
}

.navbar-center li a,
.navbar-right li a {
  text-decoration: none;
  color: #000; /* Black color for text */
  font-weight: bold;
}

.navbar-center li a::after {
  content: ' ▼';
  font-size: 0.8em; /* Adjust the size of the dropdown arrow */
}
</style>