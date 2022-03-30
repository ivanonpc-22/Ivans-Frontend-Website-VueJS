<template>
  <div class="contact-container">
    <div data-role="Header" class="contact-navbar-container">
      <div class="contact-navbar">
        <img
          alt="image"
          src="https://cdn.discordapp.com/attachments/858548231808745483/958763941318754374/Ivansweb.png"
          class="contact-image"
        />
        <div class="contact-links-container">
          <span class="contact-link navbar-Link">Contact</span>
        </div>
        <div data-type="BurgerMenu" class="contact-burger-menu">
          <svg viewBox="0 0 1024 1024" class="contact-icon">
            <path
              d="M128 256h768v86h-768v-86zM128 554v-84h768v84h-768zM128 768v-86h768v86h-768z"
            ></path>
          </svg>
        </div>
        <div data-type="MobileMenu" class="contact-mobile-menu">
          <div class="contact-container1">
            <span class="card-Heading contact-heading">Logo</span>
            <div data-type="CloseMobileMenu" class="contact-close-menu">
              <svg viewBox="0 0 1024 1024" class="contact-icon2">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <div class="contact-links-container1">
            <span class="contact-link1 navbar-Link">About</span>
            <span class="contact-link2 navbar-Link">Experience</span>
            <span class="contact-link3 navbar-Link">Portofolio</span>
            <span class="navbar-Link">Contact</span>
          </div>
        </div>
      </div>
    </div>
    <div class="contact-section-separator"></div>
    <div class="contact-section-separator1"></div>
    <div class="contact-container2"></div>
    <div class="contact-section-separator2"></div>
    <div class="contact-footer-container">
      <div class="contact-footer">
        <div class="contact-container3">
          <div class="contact-social-links"></div>
          <div class="contact-container4">
            <a
              href="https://discord.gg/BFuuGcWbxZ"
              target="_blank"
              rel="noreferrer noopener"
              class="contact-link5"
            >
              <img
                alt="image"
                src="/playground_assets/download-200h.png"
                class="contact-image1"
              />
            </a>
          </div>
        </div>
        <div class="contact-copyright-container">
          <span class="contact-link6 anchor">Copyright, 2022</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact',
  metaInfo: {
    title: "Contact - Ivan's Website",
    meta: [
      {
        property: 'og:title',
        content: "Contact - Ivan's Website",
      },
    ],
  },
}
</script>

<style scoped>
.contact-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.contact-navbar-container {
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
.contact-navbar {
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
.contact-image {
  width: 304px;
  height: 93px;
  object-fit: cover;
}
.contact-links-container {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.contact-link {
  color: #ffffff;
}
.contact-burger-menu {
  display: none;
  align-items: flex-start;
  flex-direction: column;
}
.contact-icon {
  width: 36px;
  height: 36px;
}
.contact-mobile-menu {
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
.contact-container1 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: row;
  justify-content: space-between;
}
.contact-close-menu {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.contact-icon2 {
  width: 24px;
  height: 24px;
}
.contact-links-container1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.contact-link1 {
  margin-bottom: var(--dl-space-space-unit);
}
.contact-link2 {
  margin-bottom: var(--dl-space-space-unit);
}
.contact-link3 {
  margin-bottom: var(--dl-space-space-unit);
}
.contact-section-separator {
  width: 100%;
  height: 1px;
  display: flex;
  margin-top: var(--dl-space-space-tenunits);
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.contact-section-separator1 {
  width: 100%;
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #fffefe;
}
.contact-container2 {
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 402px;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #000000;
}
.contact-section-separator2 {
  width: 100%;
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-gray-900);
}
.contact-footer-container {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-gray-white);
}
.contact-footer {
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
.contact-container3 {
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: space-between;
  flex-direction: column;
}
.contact-social-links {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.contact-container4 {
  display: flex;
  position: relative;
}
.contact-link5 {
  display: contents;
}
.contact-image1 {
  width: 40px;
  height: 40px;
  object-fit: cover;
  text-decoration: none;
}
.contact-copyright-container {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.contact-link6 {
  color: #ffffff;
}
@media(max-width: 991px) {
  .contact-heading {
    text-align: center;
  }
}
@media(max-width: 767px) {
  .contact-navbar {
    position: relative;
  }
  .contact-links-container {
    display: none;
  }
  .contact-burger-menu {
    display: flex;
    padding: var(--dl-space-space-halfunit);
    margin-left: var(--dl-space-space-tripleunit);
    border-radius: var(--dl-radius-radius-radius4);
    background-color: var(--dl-color-gray-black);
  }
  .contact-icon {
    fill: var(--dl-color-gray-white);
  }
}
@media(max-width: 479px) {
  .contact-burger-menu {
    margin-left: var(--dl-space-space-doubleunit);
  }
}
</style>
