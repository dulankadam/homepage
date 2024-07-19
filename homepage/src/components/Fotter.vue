<template>
  <div class="footer-container">
    <div class="footer-top">
      <div class="footer-brand">
        <div class="brand-logo">
          <div class="outer-circle"></div>
          <div class="inner-circle">
            <div class="dot"></div>
          </div>
        </div>
        <div class="brand-text">
          <p class="brand-title">Global</p>
          <p class="brand-subtitle">Edulink</p>
        </div>
        <p class="brand-description">
          Global Edulink offers accessible, high-quality online education for all, with flexible programs tailored to fit into daily life, empowering learners worldwide to achieve personal and professional goals.
        </p>
        <div class="social-links">
          <div class="social-icon"><img src="https://via.placeholder.com/24x24" /></div>
          <div class="social-icon"><img src="https://via.placeholder.com/24x24" /></div>
          <div class="social-icon"><img src="https://via.placeholder.com/24x24" /></div>
          <div class="social-icon"><img src="https://via.placeholder.com/24x24" /></div>
          <div class="social-icon"><img src="https://via.placeholder.com/24x24" /></div>
        </div>
        <div class="verify-button">
          <span>Verify your certificate</span>
        </div>
      </div>
      <div class="footer-links">
        <div class="resources">
          <h4>Resources</h4>
          <ul>
            <li>Free Courses</li>
            <li>Practical Lab</li>
            <li>Blogs</li>
            <li>Pay with PayPal</li>
            <li>Course extension fee</li>
            <li>Retake exam fee</li>
          </ul>
        </div>
        <div class="quick-links">
          <h4>Quick Links</h4>
          <ul>
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
          <h4>Support</h4>
          <ul>
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
          <h4>Contact Info</h4>
          <p>+4420-3409-7966</p>
          <p>CityPoint, 1 Ropemaker Street, London, EC2Y 9HU</p>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="language-selector">
        <div class="language-option">
          <div class="checkmark"></div>
          <span>English</span>
        </div>
        <button class="apply-button">Apply</button>
      </div>
      <div class="footer-logos">
        <img src="https://via.placeholder.com/189x63" />
        <img src="https://via.placeholder.com/80x62" />
        <img src="https://via.placeholder.com/58x63" />
        <img src="https://via.placeholder.com/60x65" />
      </div>
      <div class="footer-copyright">
        <div class="copyright-text">
          Copyright © 2015 - 2024 - Global Edulink All rights reserved
        </div>
        <div class="certification-logos">
          <img src="https://via.placeholder.com/106x26" />
          <img src="https://via.placeholder.com/86x26" />
          <img src="https://via.placeholder.com/53x41" />
          <img src="https://via.placeholder.com/85x41" />
          <img src="https://via.placeholder.com/88x41" />
          <img src="https://via.placeholder.com/79x41" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Fotter',
};
</script>

<style scoped>
.footer-container {
  width: 100%;
  height: 100%;
  padding: 66px 234px 54px;
  background: #f4eee8;
  display: flex;
  flex-direction: column;
  gap: 64px;
}

.footer-top {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 145px;
}

.footer-brand {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 36px;
}

.brand-logo {
  display: flex;
  align-items: center;
  gap: 7.85px;
}

.outer-circle {
  width: 47.11px;
  height: 47.11px;
  background: #1f1f1f;
  border-radius: 6.28px;
  position: relative;
}

.inner-circle {
  width: 30.36px;
  height: 30.36px;
  position: absolute;
  background: white;
  border-radius: 9999px;
  top: 8.37px;
  left: 8.37px;
}

.dot {
  width: 6.28px;
  height: 6.28px;
  background: white;
  border-radius: 9999px;
  position: absolute;
  top: 2.09px;
  left: 19.89px;
}

.brand-text {
  
  flex-direction: column;
  gap: 24px;
}

.brand-title {
  color: black;
  font-size: 47.11px;
  font-family: Outfit;
  font-weight: 700;
}

.brand-subtitle {
  color: black;
  font-size: 47.11px;
  font-family: Outfit;
  font-weight: 400;
}

.brand-description {
  width: 344px;
  color: black;
  font-size: 14px;
  font-family: Plus Jakarta Sans;
  font-weight: 400;
  line-height: 24px;
}

.social-links {
  display: flex;
  gap: 4px;
}

.social-icon {
  width: 60px;
  height: 60px;
  background: #fffcfa;
  border-radius: 9999px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.verify-button {
  width: 343px;
  padding: 10px 15px;
  background: #4ac994;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-size: 18px;
  font-family: Plus Jakarta Sans;
  font-weight: 700;
}

.footer-links {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
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

h4 {
  color: #3d3d3d;
  font-size: 16px;
  font-family: Plus Jakarta Sans;
  font-weight: 600;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  color: #3d3d3d;
  font-size: 14px;
  font-family: Plus Jakarta Sans;
  font-weight: 400;
}

.footer-bottom {
  display: flex;
  flex-direction: column;
  gap: 62px;
}

.language-selector {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 641px;
}

.language-option {
  width: 206px;
  height: 48px;
  padding: 10px 15px;
  background: white;
  border-radius: 4px;
  border: 1px #e7e7e7 solid;
  display: flex;
  align-items: center;
  gap: 8px;
}

.checkmark {
  width: 20.69px;
  height: 20.69px;
  border: 1.5px #2c2c2c solid;
}

.apply-button {
  width: 130px;
  height: 48px;
  padding: 15px;
  background: #2c2c2c;
  border-radius: 8px;
  border: 1px black solid;
  color: white;
  font-size: 20px;
  font-family: Plus Jakarta Sans;
  font-weight: 600
}
</style>