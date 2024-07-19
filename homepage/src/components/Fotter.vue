<template>
    <div class="container">
      <div class="section1">
        <div class="header">
          <div class="logo">
            <div class="logo-icon">
              <div class="outer-circle"></div>
              <div class="inner-circle">
                <div class="inner-circle-overlay"></div>
              </div>
              <div class="inner-circle">
                <div class="inner-circle-overlay"></div>
              </div>
              <div class="inner-circle">
                <div class="inner-circle-overlay"></div>
              </div>
            </div>
            <div class="logo-text">
              <div class="text-bold">Global</div>
              <div class="text-light">Edulink</div>
            </div>
          </div>
          <p class="description">Global Edulink offers accessible, high-quality online education for all, with flexible programs tailored to fit into daily life, empowering learners worldwide to achieve personal and professional goals.</p>
        </div>
        <div class="icons">
          <div class="icon-item">
            <div class="icon-bg"></div>
            <img class="icon-img" src="https://via.placeholder.com/24x24" />
          </div>
          <!-- Repeat similar structure for other icons -->
        </div>
        <div class="verify-button">
          <div class="verify-text">Verify your certificate</div>
        </div>
      </div>
      <div class="section2">
        <div class="resources">
          <div class="resource-title">Resources</div>
          <ul class="resource-list">
            <li>Free Courses</li>
            <li>Practical Lab</li>
            <li>Blogs</li>
            <li>Pay with PayPal</li>
            <li>Course extension fee</li>
            <li>Retake exam fee</li>
          </ul>
        </div>
        <div class="quick-links">
          <div class="links-title">Quick Links</div>
          <ul class="links-list">
            <li>Become an Instructor</li>
            <li>Corporate Training</li>
            <li>Our Partners</li>
            <li>Accrediting bodies</li>
            <li>Live online classes</li>
            <li>Online courses</li>
            <li>Classroom courses</li>
          </ul>
        </div>
        <div class="support">
          <div class="support-title">Support</div>
          <ul class="support-list">
            <li>FAQ</li>
            <li>Our partners</li>
            <li>Terms and conditions</li>
            <li>Privacy policy</li>
            <li>Contact us</li>
            <li>Complaint form</li>
            <li>Student ID card</li>
            <li>Books</li>
          </ul>
        </div>
        <div class="contact-info">
          <div class="contact-title">Contact Info</div>
          <p class="phone">+4420-3409-7966</p>
          <p class="address">CityPoint, 1 Ropemaker Street, London, EC2Y 9HU</p>
        </div>
      </div>
      <div class="footer">
        <div class="language-select">
          <p class="language-text">Choose your preferred language</p>
          <div class="language-options">
            <div class="language-item">
              <div class="language-icon">
                <div class="icon-line"></div>
                <div class="icon-line vertical"></div>
                <div class="icon-line horizontal"></div>
              </div>
              <div class="language-name">English</div>
            </div>
            <div class="apply-button">
              <div class="apply-text">Apply</div>
            </div>
          </div>
        </div>
        <div class="logos">
          <img class="logo-img" src="../assets/Facebook.png" />
          <img class="logo-img" src="../assets/Instagram.png" />
          <img class="logo-img" src="https://via.placeholder.com/58x63" />
          <img class="logo-img" src="https://via.placeholder.com/60x65" />
        </div>
        <div class="copyright">
          <p>Copyright © 2015 - 2024 -Global Edulink All rights reserved</p>
          <div class="certifications">
            <img class="certification-logo" src="https://via.placeholder.com/106x26" />
            <img class="certification-logo" src="https://via.placeholder.com/86x26" />
            <img class="certification-logo" src="https://via.placeholder.com/53x41" />
            <img class="certification-logo" src="https://via.placeholder.com/85x41" />
            <img class="certification-logo" src="https://via.placeholder.com/88x41" />
            <img class="certification-logo" src="https://via.placeholder.com/79x41" />
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'fotter',
  };
  </script>
  
  <style scoped>
  .container {
    width: 100%;
    height: 100%;
    padding-top: 66px;
    padding-bottom: 54px;
    padding-left: 234px;
    padding-right: 234px;
    background: #F4EEE8;
    display: flex;
    flex-direction: column;
    gap: 64px;
  }
  
  .section1 {
    display: flex;
    justify-content: space-between;
  }
  
  .header {
    display: flex;
    gap: 145px;
  }
  
  .logo {
    display: flex;
    gap: 36px;
  }
  
  .logo-icon {
    position: relative;
    width: 47.11px;
    height: 47.11px;
  }
  
  .outer-circle {
    width: 47.11px;
    height: 47.11px;
    background: #1F1F1F;
    border-radius: 6.28px;
  }
  
  .inner-circle {
    position: absolute;
    width: 30.36px;
    height: 30.36px;
    top: 8.37px;
    left: 8.37px;
  }
  
  .inner-circle-overlay {
    width: 30.36px;
    height: 30.36px;
    background: white;
    border-radius: 9999px;
  }
  
  .icon-item {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  .icon-bg {
    width: 60px;
    height: 60px;
    background: #FFFCFA;
    border-radius: 9999px;
  }
  
  .icon-img {
    width: 24px;
    height: 24px;
  }
  
  .verify-button {
    width: 343px;
    padding: 10px 15px;
    background: #4AC994;
    border-radius: 8px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .verify-text {
    color: white;
    font-size: 18px;
    font-family: Plus Jakarta Sans;
    font-weight: 700;
  }
  
  .section2 {
    display: flex;
    gap: 62px;
  }
  
  .resources,
  .quick-links,
  .support,
  .contact-info {
    display: flex;
    flex-direction: column;
    gap: 30px;
  }
  
  .resources .resource-title,
  .quick-links .links-title,
  .support .support-title,
  .contact-info .contact-title {
    color: #3D3D3D;
    font-size: 16px;
    font-family: Plus Jakarta Sans;
    font-weight: 600;
  }
  
  .resource-list,
  .links-list,
  .support-list {
    list-style: none;
    padding: 0;
  }
  
  .resource-list li,
  .links-list li,
  .support-list li {
    color: #3D3D3D;
    font-size: 14px;
    font-family: Plus Jakarta Sans;
    font-weight: 400;
  }
  
  .contact-info .phone {
    color: #3D3D3D;
    font-size: 14px;
    font-family: Plus Jakarta Sans;
    font-weight: 400;
  }
  
  .contact-info .address {
    width: 184px;
    color: #3D3D3D;
    font-size: 14px;
    font-family: Plus Jakarta Sans;
    font-weight: 400;
    line-height: 24px;
  }
  
  .footer {
    display: flex;
    flex-direction: column;
    gap: 62px;
  }
  
  .language-select {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 641px;
  }
  
  .language-text {
    color: #3D3D3D;
    font-size: 16px;
    font-family: Plus Jakarta Sans;
    font-weight: 400;
  }
  
  .language-options {
    display: flex;
    gap: 7px;
  }
  
  .language-item {
    width: 206px;
    height: 48px;
    padding: 10px 15px;
    background: white;
    border-radius: 4px;
    border: 1px #E7E7E7 solid;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  
  .language-icon {
    width: 24px;
    height: 24px;
  }
  
  .icon-line {
    width: 2px;
    height: 10px;
    background: black;
  }
  
  .icon-line.vertical {
    height: 24px;
  }
  
  .icon-line.horizontal {
    width: 10px;
  }
  
  .language-name {
    color: #3D3D3D;
    font-size: 14px;
    font-family: Plus Jakarta Sans;
    font-weight: 400;
  }
  
  .apply-button {
    width: 70px;
    height: 36px;
    background: #4AC994;
    border-radius: 4px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .apply-text {
    color: white;
    font-size: 14px;
    font-family: Plus Jakarta Sans;
    font-weight: 400;
  }
  
  .logos {
    display: flex;
    gap: 20px;
  }
  
  .logo-img {
    height: 63px;
  }
  
  .footer .certifications {
    display: flex;
    gap: 10px;
  }
  
  .certification-logo {
    height: 41px;
  }
  </style>
  