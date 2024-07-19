<template>
    <div class="container">
      <div class="background" />
      <div class="content">
        <div class="rounded-background" />
        <div class="light-background" />
        <div class="orange-background" />
        <div class="info-box">
          <div class="info-item" style="top: 30%; left: 10%;">
            <div class="info-icon">
              <div class="icon-content">
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part" />
              </div>
            </div>
            <div class="info-text">Accredited<br />Programs</div>
          </div>
          <div class="info-item" style="top: 50%; left: 0%;">
            <div class="info-icon">
              <div class="icon-content">
                <div class="icon-part orange-part" />
                <div class="icon-part" />
                <div class="icon-part" />
              </div>
            </div>
            <div class="info-text">Interactive<br />Learning</div>
          </div>
          <div class="info-item" style="top: 10%; left: 20%;">
            <div class="info-icon">
              <div class="icon-content">
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part orange-part" />
              </div>
            </div>
            <div class="info-text">Expert <br />Instructors</div>
          </div>
          <img class="placeholder-image" src="../assets/image.png" />
        </div>
        <div class="empty-box" />
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Header'
  };
  </script>
  
  <style scoped>
  .container {
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    background: #FBF6F1;
  }
  
  .background {
    width: 100%;
    height: 100%;
    position: absolute;
    background: #FBF6F1;
  }
  
  .content {
    width: 80%;
    height: 80%;
    position: relative;
  }
  
  .rounded-background {
    width: 100%;
    height: 100%;
    background: #FBF6F1;
    border-radius: 50%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  
  .light-background {
    width: 50%;
    height: 30%;
    background: #F4EEE8;
    position: absolute;
    left: 25%;
    top: 35%;
  }
  
  .orange-background {
    width: 30%;
    height: 28%;
    background: #FF965B;
    position: absolute;
    left: 35%;
    top: 70%;
  }
  
  .info-box {
    width: 30%;
    height: 35%;
    position: absolute;
    left: 35%;
    top: 60%;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  
  .info-item {
    width: 100%;
    height: auto;
    padding: 10px;
    background: white;
    box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.05);
    border-radius: 8px;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  
  .info-icon {
    width: 32px;
    height: 32px;
    background: #FDD6C9;
    border-radius: 4px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .icon-content {
    position: relative;
    width: 27.60px;
    height: 27.60px;
  }
  
  .icon-part {
    position: absolute;
    width: 6.37px;
    height: 12.74px;
    background: white;
    border: 1.71px black solid;
  }
  
  .icon-part:nth-of-type(1) {
    width: 0;
    height: 8.49px;
    left: 13.80px;
    top: 19.11px;
  }
  
  .icon-part:nth-of-type(2) {
    width: 14.86px;
    height: 0;
    left: 6.37px;
    top: 27.60px;
  }
  
  .icon-part:nth-of-type(3) {
    width: 6.37px;
    height: 12.74px;
    left: 0px;
    top: 0px;
  }
  
  .icon-part:nth-of-type(4) {
    width: 6.37px;
    height: 12.74px;
    left: 21.23px;
    top: 0px;
  }
  
  .icon-part:nth-of-type(5) {
    width: 14.86px;
    height: 19.11px;
    left: 6.37px;
    top: 0px;
  }
  
  .icon-part.orange-part {
    border-color: #F95510;
  }
  
  .info-text {
    color: black;
    font-size: 1.25rem;
    font-family: Plus Jakarta Sans, sans-serif;
    font-weight: 500;
    line-height: 1.5;
    word-wrap: break-word;
  }
  
  .placeholder-image {
    width: 50%;
    height: auto;
    position: absolute;
    left: 25%;
    top: 10%;
  }
  
  .empty-box {
    width: 20%;
    height: 20%;
    position: absolute;
    left: 40%;
    top: 60%;
  }
  </style>
  