<template>
     <div class="container">
        <main class="main">
            <section class="hero">
            <h1>
                <span class="upskill-font">Upskill from Anywhere with </span><br/>
                <span>Industry-Recognized Learning</span></h1>
            <p>Flexible, accredited courses to help you learn and advance from anywhere in the world.</p>
            <div class="search-bar">
                <input type="text" placeholder="What will you be learning today?" />
                <button>Explore</button>
            </div>
            <div class="features">
                <div class="feature">
                <span>Expert Instructors</span>
                </div>
                <div class="feature">
                <span>Accredited Programs</span>
                </div>
                <div class="feature">
                <span>Interactive Learning</span>
                </div>
            </div>
            </section>
        </main>
      </div>
  </template>
  
  <script>
  export default {
    name: 'HeroSection'
  }
  </script>
  <style scoped>
  .container {
    font-family: Arial, sans-serif;
  }
  
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #f8f8f8;
    padding: 1rem 2rem;
  }
  
  .logo img {
    width: 150px;
  }
  
  .nav ul {
    list-style: none;
    display: flex;
    gap: 1rem;
  }
  
  .nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
  }
  
  .cta-button {
    background-color: #ff6600;
    color: #fff;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    text-decoration: none;
  }
  
  .main {
    background-color: #f0f0f0;
    padding: 2rem;
    text-align: center;
  }
  
  .hero h1 {
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  
  .hero h1 span {
    color: #ff6600;
  }
  
  .hero p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
  }
  
  .search-bar {
    display: flex;
    justify-content: center;
    margin-bottom: 2rem;
  }
  
  .search-bar input {
    padding: 0.5rem;
    width: 300px;
    border: 1px solid #ccc;
    border-radius: 5px 0 0 5px;
  }
  
  .search-bar button {
    padding: 0.5rem;
    background-color: #28a745;
    color: #fff;
    border: none;
    border-radius: 0 5px 5px 0;
    cursor: pointer;
  }
  
  .features {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
  }
  
  .feature {
    background-color: #fff;
    padding: 1rem;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  .feature span {
    font-weight: bold;
  }

  .upskill-font{
    font-weight: 100;
    color: black !important;
  }
  </style>
  