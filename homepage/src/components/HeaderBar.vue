<template>
    <div class="container">
      <div class="content">
        <div class="text-section">
          <div class="headline">
            <span class="highlighted">Renew, Refresh</span>
            <span class="separator"> </span>
            <span class="main-text">24!</span>
            <span class="separator"> </span>
          </div>
          <div class="subtext">Save up to 40%! Hurry, offer ends June 15th.</div>
        </div>
        <div class="offer-button">
          <div class="button-text">Claim offer</div>
          <div class="arrow">
            <div class="arrow-body">
              <div class="arrow-line vertical"></div>
              <div class="arrow-line horizontal"></div>
            </div>
          </div>
        </div>
        <div class="dot"></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HeaderBar'
  };
  </script>
  
  <style scoped>
  .container {
    width: 100%;
    height: 100%;
    padding: 12px 234px 12px 546px;
    background: #FFDA6E;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }
  
  .content {
    display: flex;
    align-items: center;
    gap: 304px;
  }
  
  .text-section {
    display: flex;
    align-items: center;
    gap: 108px;
  }
  
  .headline {
    display: flex;
    align-items: center;
    gap: 32px;
  }
  
  .highlighted {
    color: #F04706;
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 600;
  }
  
  .main-text {
    color: #1C1C1C;
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 600;
  }
  
  .separator {
    color: black;
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 600;
  }
  
  .subtext {
    color: black;
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 400;
  }
  
  .offer-button {
    width: 145px;
    padding: 10px 15px;
    background: #18191D;
    border-radius: 8px;
    display: flex;
    align-items: center;
    gap: 5px;
  }
  
  .button-text {
    color: white;
    font-size: 16px;
    font-family: 'Plus Jakarta Sans', sans-serif;
    font-weight: 700;
  }
  
  .arrow {
    width: 24px;
    height: 24px;
    transform: rotate(90deg);
    position: relative;
  }
  
  .arrow-body {
    width: 11.15px;
    height: 15.35px;
    position: absolute;
    top: 4.65px;
    left: 6px;
  }
  
  .arrow-line {
    border: 1.71px white solid;
    position: absolute;
  }
  
  .arrow-line.vertical {
    width: 0;
    height: 15px;
    left: 5.57px;
    top: 0.35px;
  }
  
  .arrow-line.horizontal {
    width: 11.15px;
    height: 5.57px;
    top: 0;
  }
  
  .dot {
    width: 18px;
    height: 18px;
    position: relative;
  }
  
  .dot div {
    width: 15.02px;
    height: 15.02px;
    border: 2px #1C1C1C solid;
    position: absolute;
  }
  
  .dot div:nth-child(1) {
    left: 1.49px;
    top: 1.49px;
  }
  </style>
  