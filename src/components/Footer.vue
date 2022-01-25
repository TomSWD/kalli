<template>
  <div class="footer-main">
    <div class="footer-container container">
      <div class="footer-sitemap-column">
        <div class="footer-sitemap-title">Sitemap</div>
        <div class="footer-sitemap-nav">
          <ul class="nav-links">
            <li class=""><a href="#" class="nav-link"> About </a></li>
            <li class=""><a href="#" class="nav-link"> Portfolio </a></li>
            <li class=""><a href="#" class="nav-link"> Blog </a></li>
            <li class=""><a href="#" class="nav-link"> Careers </a></li>
            <li class=""><a href="#" class="nav-link"> Press </a></li>
          </ul>
        </div>
      </div>
      <div class="footer-info-column">
        <div class="footer-info-title">Info</div>
        <div class="footer-info-nav">
          <ul class="nav-links">
            <li class=""><a href="#" class="nav-link"> FAQ </a></li>
            <li class=""><a href="#" class="nav-link"> Privacy Policy </a></li>
            <li class=""><a href="#" class="nav-link"> Contact Us </a></li>
          </ul>
        </div>
      </div>
      <div class="footer-newsletter-column">
        <div class="footer-newsletter-title">Newsletter</div>
        <form class="newsletter-subscribe-container">
          <div class="subscribe-label">Email Address</div>
          <input class="email-input" type="email" />
          <a class="sign-up" href="#">SIGN UP</a>
        </form>
      </div>
    </div>
    <div class="footer-last-column container">
      <div class="footer-logo">
        <a class="logo" href="/">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="56"
            height="24"
            viewBox="0 0 56 24"
          >
            <path
              fill="white"
              d="M10.0487106,15.09375 L16.0659026,23.625 L9.95845272,23.625 L5.05444126,16.15625 L4.96418338,16.15625 L4.96418338,23.625 L0,23.625 L0,0 L4.96418338,0 L4.96418338,14.375 L5.05444126,14.375 L9.83810888,8.0625 L15.8252149,8.0625 L10.0487106,15.09375 Z M26.034384,17.375 L26.034384,16.84375 L25.4025788,16.84375 C23.2363897,16.84375 20.7994269,17.125 20.7994269,18.96875 C20.7994269,20.15625 21.9426934,20.5625 22.9355301,20.5625 C24.9212034,20.5625 26.034384,19.3125 26.034384,17.375 Z M19.4756447,12.96875 L16.97851,10.1875 C18.7234957,8.46875 21.2206304,7.5625 23.6575931,7.5625 C28.6819484,7.5625 30.5472779,10.125 30.5472779,15.78125 L30.5472779,23.625 L26.034384,23.625 L26.034384,21.96875 L25.9441261,21.96875 C25.1919771,23.25 23.4770774,24 21.7020057,24 C19.3252149,24 16.256447,22.78125 16.256447,19.125 C16.256447,14.625 21.52149,13.875 25.8839542,13.875 L25.8839542,13.625 C25.8839542,12.09375 24.7106017,11.375 23.1762178,11.375 C21.7621777,11.375 20.3782235,12.09375 19.4756447,12.96875 Z M38.7707736,23.625 L33.7765043,23.625 L33.7765043,0 L38.7707736,0 L38.7707736,23.625 Z M47.234957,23.625 L42.2406877,23.625 L42.2406877,0 L47.234957,0 L47.234957,23.625 Z M56,3.09375 C56,4.6875 54.7363897,5.90625 53.1719198,5.90625 C51.5773639,5.90625 50.3438395,4.625 50.3438395,3.09375 C50.3438395,1.59375 51.5773639,0.28125 53.1719198,0.28125 C54.7363897,0.28125 56,1.53125 56,3.09375 Z M55.6389685,23.625 L50.7048711,23.625 L50.7048711,8.0625 L55.6389685,8.0625 L55.6389685,23.625 Z"
            />
          </svg>
        </a>
      </div>
      <div class="footer-copyright">Copyright © 2019 Kalli</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer-main {
  background-color: #f2f2f2;
  width: 100%;
  margin-top: 80px;
  padding-bottom: 80px;
  padding-top: 80px;
}

.footer-container {
  display: flex;
  width: 1110px;
  height: 208px;
  margin-bottom: 80px;
}

.footer-sitemap-column {
  width: 158px;
  height: 208px;
  margin-right: 32px;
}

.footer-info-column {
  width: 158px;
  height: 208px;
  margin-right: 222px;
  padding-right: 30px;
}

.footer-newsletter-column {
  width: 540px;
  height: 208px;
  padding-left: 0px 15px 0px 15px;
}

.footer-last-column {
  display: flex;
  align-self: flex-end;
  width: 1110px;
  height: 32px;
}

.newsletter-subscribe-container {
  border-bottom: solid 2px #222;
  padding-bottom: 7px;
  width: 445px;
}

.footer-sitemap-title,
.footer-info-title,
.footer-newsletter-title {
  color: #222;
  font-size: 16px;
  font-weight: 500;
  opacity: 0.6;
  margin-bottom: 40px;
}

.nav-link {
  color: #222;
  text-decoration: none;
  font-size: 16px;
  font-weight: 500;
  line-height: 1.9;
  transition: opacity 0.2s;
}

.nav-link:hover {
  opacity: 0.6;
}

.subscribe-label {
  color: #222;
  font-size: 12px;
  font-weight: 500;
  text-transform: uppercase;
}

.email-input {
  width: 339px;
  height: 46px;
  border: 0;
  background-color: #f2f2f2;
  font-size: 16px;
  font-weight: 400;
}

.email-input:focus {
  outline: 0;
}

.sign-up {
  float: right;
  text-transform: uppercase;
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 1px;
  text-decoration: none;
  color: #222;
  background-color: #fff;
  border: 2px solid #fff;
  padding: 14px 18px;
  line-height: 14.4px;
}

.sign-up:hover {
  background-color: #aaa;
  border-color: #aaa;
  transition: 0.2s;
}

.footer-logo {
  width: 570px;
  height: 32px;
}

.logo {
  color: #222;
  transition: opacity 0.2s;
}

.logo:hover {
  opacity: 0.6;
}

.footer-copyright {
  width: 540px;
  height: 32px;
  font-family: "Roboto", sans-serif;
  color: #222;
  font-size: 18px;
  font-weight: 400;
  opacity: 0.6;
  line-height: 1.77778;
}
</style>