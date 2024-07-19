<template>
    <div class="container">
        <div class="logo">
       <img src="@/assets/Mask group.png" alt="Global Edulink"> 
        </div>
      <div class="content">
        <div class="rounded-background" />
        <div class="light-background" />
        <div class="orange-background" />
       
        <div class="info-box">
          <div class="info-item" style="top: 299.97px; left: 44px;">
            <div class="info-icon">
              <div class="icon-content">
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part" />
              </div>
            </div>
            <div class="info-text">Accredited<br/>Programs</div>
          </div>
          <div class="info-item" style="top: 388.97px; left: 0px;">
            <div class="info-icon">
              <div class="icon-content">
                <div class="icon-part orange-part" />
                <div class="icon-part" />
                <div class="icon-part" />
              </div>
            </div>
            <div class="info-text">Interactive<br/>Learning</div>
          </div>
          <div class="info-item" style="top: 210.97px; left: 79px;">
            <div class="info-icon">
              <div class="icon-content">
                <div class="icon-part" />
                <div class="icon-part" />
                <div class="icon-part orange-part" />
              </div>
            </div>
            <div class="info-text">Expert <br/>Instructors</div>
          </div>
          <img class="placeholder-image" src="../assets/image.png" />
        </div>
        <!-- <HeaderContents></HeaderContents> -->
        <div class="empty-box" />
      </div>
    </div>
  </template>
  
  <script>
  import HeaderContents from './HeaderContents.vue';

  export default {
    name: 'Header',
    HeaderContents
  };
  </script>
  
  <style scoped>
  .container {
    width: 100%;
    height: 100%;
    position: relative;
  }
  
  .background {
    width: 1920px;
    height: 700px;
    position: absolute;
    background: #FBF6F1;
  }
  
  .content {
    width: 100%;
    height: 40%;
    position: absolute;
    left: -803px;
    top: -999px;
  }
  
  .rounded-background {
    width: 100%;
    height: 40%;
    background: #FBF6F1;
    border-radius: 9999px;
  }
  
  .light-background {
    width: 960px;
    height: 518px;
    background: #F4EEE8;
    position: absolute;
    
  }
  
  .orange-background {
    width: 539px;
    height: 485.10px;
    position: absolute;
    left: 1947.67px;
    top: 1214.93px;
  }
  
  .info-box {
    width: 547.33px;
    height: 557.16px;
    position: absolute;
    left: 1777px;
    top: 1145px;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  
  .info-item {
    width: 261px;
    height: 76px;
    padding: 10px;
    background: white;
    box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.05);
    border-radius: 8px;
    position: absolute;
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
    font-size: 20px;
    font-family: Plus Jakarta Sans, sans-serif;
    font-weight: 500;
    line-height: 25px;
    word-wrap: break-word;
  }
  
  .placeholder-image {
    width: 354.33px;
    height: 557.16px;
    position: absolute;
    left: 193px;
    top: 0px;
  }
  
  .empty-box {
    width: 352.39px;
    height: 456.82px;
    position: absolute;
    left: 1911.15px;
    top: 1128.03px;
  }
  </style>  

