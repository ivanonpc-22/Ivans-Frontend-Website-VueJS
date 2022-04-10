<template>
  <div class="home-container">
    <div data-role="Header" class="home-navbar-container">
      <div class="home-navbar">
        <img
          alt="image"
          src="https://cdn.discordapp.com/attachments/858548231808745483/958763941318754374/Ivansweb.png"
          class="home-image"
        />
        <div data-type="BurgerMenu" class="home-burger-menu">
          <svg viewBox="0 0 1024 1024" class="home-icon">
            <path
              d="M128 256h768v86h-768v-86zM128 554v-84h768v84h-768zM128 768v-86h768v86h-768z"
            ></path>
          </svg>
        </div>
        <div data-type="MobileMenu" class="home-mobile-menu">
          <div class="home-container1">
            <span class="card-Heading home-heading">Logo</span>
            <div data-type="CloseMobileMenu" class="home-close-menu">
              <svg viewBox="0 0 1024 1024" class="home-icon2">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <div class="home-links-container">
            <span class="home-link navbar-Link">About</span>
            <span class="home-link1 navbar-Link">Experience</span>
            <span class="home-link2 navbar-Link">Portofolio</span>
            <span class="navbar-Link">Contact</span>
          </div>
        </div>
      </div>
    </div>
    <div class="home-section-separator"></div>
    <div class="home-section-separator1"></div>
    <div class="home-container2">
      <div class="home-hero">
        <div class="home-hero-text-container">
          <h1 class="home-heading1 section-Heading">Hello World!</h1>
          <span class="home-text">
            <span>
              My name is Ivan Ryan. I am a programmer, hosting provider and static
              web designer
            </span>
            <span><span v-html="rawbygv"></span></span>
          </span>
          <div class="home-cta-btn-container"></div>
        </div>
      </div>
    </div>
    <div class="home-features">
      <h1 class="home-text3">Projects</h1>
      <span class="home-text4">Oden Game</span>
      <div class="home-container3">
        <img
          src="https://media.discordapp.net/attachments/942084835625795624/962617945979228210/FMCxSmsaMAM_3OE.jpg?width=1202&amp;height=676"
          alt="image"
          class="home-image1"
        />
      </div>
    </div>
    <div class="home-section-separator2"></div>
    <div class="home-container4">
      <h1 class="home-text5">Custom Pterodactyl Panel Setup</h1>
      <img
        alt="image"
        src="https://cdn.discordapp.com/attachments/938769835763060766/960019073201242122/ezgif.com-gif-maker.gif"
        loading="lazy"
        class="home-image2"
      />
      <div class="home-container5">
        <img
          alt="image"
          src="https://cdn.discordapp.com/attachments/938769835763060766/960088253757808650/IvansPanel1_2.PNG"
          loading="lazy"
          class="home-image3"
        />
      </div>
    </div>
    <div class="home-footer-container">
      <div class="home-footer">
        <div class="home-container6">
          <div class="home-social-links"></div>
          <div class="home-container7">
            <a
              href="https://discord.gg/BFuuGcWbxZ"
              target="_blank"
              rel="noreferrer noopener"
              class="home-link4"
            >
              <img
                alt="image"
                src="/playground_assets/download-200h.png"
                class="home-image4"
              />
            </a>
          </div>
        </div>
        <span class="home-text6">Powered on VueJS</span>
        <div class="home-copyright-container">
          <span class="home-link5 anchor">Copyright, 2022</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',

  data() {
    return {
      rawbygv: ' ',
    }
  },

  metaInfo: {
    title: "Ivan's Website",
    meta: [
      {
        property: 'og:title',
        content: "Ivan's Website",
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-navbar-container {
  width: 100%;
  display: flex;
  z-index: 100;
  position: fixed;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-gray-white);
}
.home-navbar {
  width: 100%;
  display: flex;
  max-width: 100%;
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-tripleunit);
  justify-content: space-between;
  background-color: #000000;
}
.home-image {
  width: 304px;
  height: 93px;
  object-fit: cover;
}
.home-burger-menu {
  display: none;
  align-items: flex-start;
  flex-direction: column;
}
.home-icon {
  width: 36px;
  height: 36px;
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: var(--dl-space-space-tripleunit);
  position: absolute;
  align-items: flex-start;
  flex-direction: column;
  background-color: #fff;
}
.home-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: row;
  justify-content: space-between;
}
.home-close-menu {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-icon2 {
  width: 24px;
  height: 24px;
}
.home-links-container {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-link {
  margin-bottom: var(--dl-space-space-unit);
}
.home-link1 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-link2 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-section-separator {
  width: 100%;
  height: 1px;
  display: flex;
  margin-top: var(--dl-space-space-tenunits);
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.home-section-separator1 {
  width: 100%;
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #fffefe;
}
.home-container2 {
  width: 100%;
  height: 402px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #000000;
}
.home-hero {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxcontent);
  margin-top: var(--dl-space-space-fiveunits);
  align-items: center;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-tripleunit);
  margin-bottom: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-fiveunits);
  justify-content: space-between;
  background-color: #0e0e0e;
}
.home-hero-text-container {
  width: 1162px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading1 {
  color: #ffffff;
  width: 1150px;
  height: 45px;
  margin-bottom: var(--dl-space-space-tripleunit);
}
.home-text {
  color: #ffffff;
  font-size: 18px;
  font-family: Arial;
  font-weight: 600;
  line-height: 1.55;
  margin-bottom: var(--dl-space-space-fiveunits);
  letter-spacing: 2;
  text-transform: none;
  list-style-type: disc;
  text-decoration: none;
  list-style-image: none;
  list-style-position: outside;
}
.home-cta-btn-container {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: flex-start;
}
.home-features {
  width: 100%;
  height: 636px;
  display: flex;
  max-width: 100%;
  align-items: center;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: 43px;
  justify-content: flex-start;
  background-color: #000000;
}
.home-text3 {
  color: #ffffff;
  width: 128px;
  height: 46px;
}
.home-text4 {
  color: #ffffff;
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
}
.home-container3 {
  width: auto;
  height: 585px;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.home-image1 {
  width: 859px;
  height: 486px;
  align-self: center;
  object-fit: cover;
}
.home-section-separator2 {
  width: 100%;
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.home-container4 {
  width: 100%;
  height: 1343px;
  display: flex;
  align-items: center;
  border-color: #000000;
  border-style: dashed;
  border-width: 2px;
  flex-direction: column;
  justify-content: center;
  background-color: #000000;
}
.home-text5 {
  color: #f9f9f9;
  height: 73px;
}
.home-image2 {
  width: 746px;
  height: 519px;
  object-fit: cover;
}
.home-container5 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.home-image3 {
  width: 100%;
  height: 497px;
  object-fit: cover;
}
.home-footer-container {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-gray-white);
}
.home-footer {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 100%;
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-tripleunit);
  justify-content: space-between;
  background-color: #000000;
}
.home-container6 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: space-between;
  flex-direction: column;
}
.home-social-links {
  display: flex;
  align-items: flex-start;
  border-color: #000000;
  border-style: dashed;
  border-width: 2px;
  flex-direction: row;
}
.home-container7 {
  display: flex;
  position: relative;
}
.home-link4 {
  display: contents;
}
.home-image4 {
  width: 40px;
  height: 40px;
  object-fit: cover;
  text-decoration: none;
}
.home-text6 {
  color: #ffffff;
  align-self: center;
  text-align: center;
}
.home-copyright-container {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-link5 {
  color: #ffffff;
}
@media(max-width: 991px) {
  .home-heading {
    text-align: center;
  }
  .home-hero {
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .home-hero-text-container {
    width: 80%;
    align-items: center;
    margin-bottom: var(--dl-space-space-fourunits);
  }
  .home-heading1 {
    text-align: center;
  }
}
@media(max-width: 767px) {
  .home-navbar {
    position: relative;
  }
  .home-burger-menu {
    display: flex;
    padding: var(--dl-space-space-halfunit);
    margin-left: var(--dl-space-space-tripleunit);
    border-radius: var(--dl-radius-radius-radius4);
    background-color: var(--dl-color-gray-black);
  }
  .home-icon {
    fill: var(--dl-color-gray-white);
  }
}
@media(max-width: 479px) {
  .home-burger-menu {
    margin-left: var(--dl-space-space-doubleunit);
  }
  .home-hero-text-container {
    width: 100%;
  }
  .home-image1 {
    flex: 0;
    width: 472px;
    height: 50%;
  }
  .home-container4 {
    height: 760px;
  }
  .home-text5 {
    height: 114px;
    text-align: center;
  }
  .home-image2 {
    width: 100%;
    height: auto;
  }
  .home-image3 {
    width: 100%;
    height: 100%;
  }
}
</style>
