<!-- Trungquandev -->
<a href="#" target="_blank">
  <img src="svg/trungquandev.svg" width="1200" alt="trungquandev-official" />
</a>

<br>
<h2 align="center">👽 Where to find me 👽</h2>
<br>
<!-- https://icons8.com -->
<div align="center">
  <a href="https://www.facebook.com/phmt612?mibextid=LQQJ4d" target="blank">
    <img src="https://img.icons8.com/bubbles/100/000000/facebook-new.png" alt="trungquandev-facebook" />
  </a>
  <a href="https://www.youtube.com/@Manhtrien" target="blank">
    <img src="https://img.icons8.com/bubbles/100/000000/youtube-squared.png" alt="trungquandev-youtube" />
  </a>
  <a href="https://www.linkedin.com/in/hu%E1%BB%B3nh-m%E1%BA%A1nh-tri%E1%BB%83n-phu-3b177b324/" target="blank">
    <img src="https://img.icons8.com/bubbles/100/000000/linkedin.png" alt="trungquandev-linkedin" />
  </a>
  <a href="https://www.instagram.com/neirt_03?igsh=NWs0dzc5bm5zNDFy&utm_source=qr" target="blank">
    <img src="https://img.icons8.com/bubbles/100/000000/instagram.png" alt="trungquandev-instagram" />
  </a>
  <a href="mailto:trien8642@gmail.com" target="top">
    <img src="https://img.icons8.com/bubbles/100/000000/apple-mail.png" alt="trungquandev-email" />
  </a>
</div>

<!-- Animated Wave Section -->
<div class="animation-wrapper">
  <div class="water">
    <ul class="waves">
      <li class="wave-one" style="background-image: url('https://i.postimg.cc/7LtCC11Y/wave1.png');"></li>
      <li class="wave-two" style="background-image: url('https://i.postimg.cc/P5hv05rh/wave2.png');"></li>
      <li class="wave-three" style="background-image: url('https://i.postimg.cc/63Dyc91k/wave3.png');"></li>
      <li class="wave-four" style="background-image: url('https://i.postimg.cc/1tg8DgM0/wave4.png');"></li>
    </ul>
  </div>
  <div class="boat" style="background-image: url('https://i.postimg.cc/GmQTRnHD/boat2.png');"></div>
  <div class="cloud" style="background-image: url('https://i.postimg.cc/VNkrLZCV/cloud-md.png');"></div>
  <div class="cloud2" style="background-image: url('https://i.postimg.cc/VNkrLZCV/cloud-md.png');"></div>
</div>

<!-- CSS Section -->
<style>
  body {
    font-family: 'arial';
    margin: 0;
    overflow-x: hidden;
    padding: 0;
  }

  .animation-wrapper {
    background: #ace5ee;
    bottom: 0;
    left: 0;
    position: absolute;
    right: 0;
    top: 0;
  }

  .water {
    bottom: 0;
    left: 0;
    position: absolute;
    width: 100%;
  }

  .water ul.waves {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .water ul.waves li {
    background-repeat: repeat-x;
  }

  .water ul.waves li.wave-one {
    animation: wave 8.7s linear infinite;
    -webkit-animation-fill-mode: forwards;
    -o-animation-fill-mode: forwards;
    animation-fill-mode: forwards;
    bottom: 0px;
    height: 50px;
    left: 0;
    position: absolute;
    right: 0;
    z-index: 10;
  }

  .water ul.waves li.wave-two {
    -webkit-animation-fill-mode: forwards;
    -o-animation-fill-mode: forwards;
    animation-fill-mode: forwards;
    animation: wave 10s linear infinite;
    bottom: 0px;
    height: 84px;
    left: 0;
    position: absolute;
    right: 0;
    z-index: 9;
  }

  .water ul.waves li.wave-three {
    -webkit-animation-fill-mode: forwards;
    -o-animation-fill-mode: forwards;
    animation-fill-mode: forwards;
    animation: wave 25s linear infinite;
    bottom: 0;
    height: 190px;
    left: 0;
    position: absolute;
    right: 0;
    z-index: 8;
  }

  .water ul.waves li.wave-four {
    -webkit-animation-fill-mode: forwards;
    -o-animation-fill-mode: forwards;
    animation-fill-mode: forwards;
    animation: wave 25s linear infinite;
    bottom: 0;
    height: 205px;
    left: 0;
    position: absolute;
    right: 0;
  }

  .boat {
    animation: boat 3s linear infinite;
    background-repeat: no-repeat;
    bottom: 175px;
    height: 145px;
    left: 50%;
    position: absolute;
    width: 250px;
  }

  .cloud {
    animation: cloud 30s linear infinite;
    background-repeat: no-repeat;
    height: 165px;
    left: 0;
    position: absolute;
    width: 297px;
  }

  .cloud2 {
    animation: cloud 25s linear infinite;
    background-repeat: no-repeat;
    bottom: 320px;
    height: 165px;
    left: 140px;
    position: absolute;
    width: 297px;
  }

  .dolphin {
    animation: fish 15s linear infinite;
    background-repeat: no-repeat;
    bottom: 45px;
    height: 80px;
    left: 20%;
    position: absolute;
    width: 124px;
    z-index: 9;
  }

  /* Animation Keyframes */
  @keyframes wave {
    0% {
      background-position: 0 0;
    }

    100% {
      background-position: 1920px 0;
    }
  }

  @keyframes boat {
    0% {
      transform: rotate(0);
    }

    50% {
      transform: rotate(-3deg);
    }

    100% {
      transform: rotate(0);
    }
  }

  @keyframes cloud {
    0% {
      left: -30%;
    }

    100% {
      left: 100%;
    }
  }
</style>
