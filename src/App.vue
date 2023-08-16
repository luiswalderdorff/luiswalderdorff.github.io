<template>
  <div>
    <div class="container container--black">
      <header class="links header">
        <span class="links__name header__name">luiswalderdorff</span>
        <div class="icons">
          <a
            class="icons__icon icons__icon--github"
            href="https://github.com/luiswalderdorff"
            target="_blank"
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="24">
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M12.304 0C5.506 0 0 5.506 0 12.304c0 5.444 3.522 10.042 8.413 11.672.615.108.845-.261.845-.584 0-.292-.015-1.261-.015-2.291-3.091.569-3.891-.754-4.137-1.446-.138-.354-.738-1.446-1.261-1.738-.43-.23-1.046-.8-.016-.815.97-.015 1.661.892 1.892 1.261 1.107 1.86 2.876 1.338 3.584 1.015.107-.8.43-1.338.784-1.646-2.738-.307-5.598-1.368-5.598-6.074 0-1.338.477-2.446 1.26-3.307-.122-.308-.553-1.569.124-3.26 0 0 1.03-.323 3.383 1.26.985-.276 2.03-.415 3.076-.415 1.046 0 2.092.139 3.076.416 2.353-1.6 3.384-1.261 3.384-1.261.676 1.691.246 2.952.123 3.26.784.861 1.26 1.953 1.26 3.307 0 4.721-2.875 5.767-5.613 6.074.446.385.83 1.123.83 2.277 0 1.645-.015 2.968-.015 3.383 0 .323.231.708.846.584a12.324 12.324 0 0 0 8.382-11.672C24.607 5.506 19.101 0 12.304 0Z"
              />
            </svg>
          </a>
          <a
            class="icons__icon icons__icon--linkedin"
            href="https://www.linkedin.com/in/luis-walderdorff-564650163"
            target="_blank"
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="24">
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M5.551 3.304c-1.14 0-2.067.926-2.067 2.064 0 1.14.928 2.066 2.067 2.066a2.066 2.066 0 0 0 0-4.13ZM3.767 8.998v11.453h3.562L7.33 8.998H3.767Zm5.798 0V20.45l3.554.002.002-5.668c0-1.454.253-2.941 2.132-2.941 1.851 0 1.851 1.755 1.851 3.036v5.571l3.559-.001v-6.28c0-2.834-.517-5.457-4.27-5.457-1.763 0-2.916.997-3.368 1.85h-.05V8.997h-3.41ZM22.435 24H1.982c-.976 0-1.77-.777-1.77-1.732V1.731C.212.776 1.006 0 1.982 0h20.453c.98 0 1.777.776 1.777 1.73v20.538c0 .955-.797 1.732-1.777 1.732Z"
              />
            </svg>
          </a>
        </div>
      </header>

      <div class="intro border-bottom">
        <!-- TODO: Richtige Bildgröße einbauen (do for all img tags) -->
        <svg
          class="intro__rings"
          xmlns="http://www.w3.org/2000/svg"
          width="530"
          height="129"
        >
          <g fill="none" fill-rule="evenodd" stroke="#FFF" opacity=".25">
            <ellipse cx="265" cy="40" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="52" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="65" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="77" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="89" rx="264.5" ry="39.5" />
          </g>
        </svg>
        <!-- TODO: Creates whitespace outside of html. Fix
        <svg
          class="intro__circle"
          xmlns="http://www.w3.org/2000/svg"
          width="129"
          height="129"
        >
          <circle
            cx="830.5"
            cy="585.5"
            r="64"
            fill="none"
            stroke="#FFF"
            transform="translate(-766 -521)"
          />
        </svg>
        -->
        <!--<img class="intro__image" :src="require('@/assets/images/image-profile-tablet.webp')"
           alt="Profilbild"/>-->

        <img
          class="intro__image"
          :src="require('@/assets/images/profile-grey.jpg')"
          alt="Profilbild"
        />
        <h1 class="intro__title">
          Nice to meet you! I'm
          <span class="intro__name">Luis Walderdorff.</span>
        </h1>

        <p class="intro__text">
          Based in the Dresden, Germany, I'm a front-end developer passionate
          about building accessible web apps that users love.
        </p>

        <a class="link-button" href="#contact-container"> Contact me </a>
      </div>

      <div class="skills border-bottom">
        <svg
          class="skills__rings"
          xmlns="http://www.w3.org/2000/svg"
          width="530"
          height="129"
        >
          <g fill="none" fill-rule="evenodd" stroke="#FFF" opacity=".25">
            <ellipse cx="265" cy="40" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="52" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="65" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="77" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="89" rx="264.5" ry="39.5" />
          </g>
        </svg>
        <div class="skill">
          <div class="skill__skill">HTML</div>
          <div class="skill__time">3 Years Experience</div>
        </div>
        <div class="skill">
          <div class="skill__skill">CSS</div>
          <div class="skill__time">3 Years Experience</div>
        </div>
        <div class="skill">
          <div class="skill__skill">SCSS</div>
          <div class="skill__time">3 Years Experience</div>
        </div>
        <div class="skill">
          <div class="skill__skill">JavaScript</div>
          <div class="skill__time">3 Years Experience</div>
        </div>
        <div class="skill">
          <div class="skill__skill">TypeScript</div>
          <div class="skill__time">1.5 Years Experience</div>
        </div>
        <div class="skill">
          <div class="skill__skill">Vue</div>
          <div class="skill__time">1.5 Years Experience</div>
        </div>
      </div>

      <div class="projects">
        <div class="projects__header">
          <h2 class="projects__title h2">Projects</h2>
          <a class="link-button" href="#contact-container"> Contact me </a>
        </div>
        <div class="projects-container">
          <!-- TODO: Create Component -->
          <div class="project">
            <div class="project__img">
              <img
                :src="require('@/assets/images/kanban-img.png')"
                alt="Projekt Vorschau"
              />
              <div class="project__hover-layer">
                <span class="project__hover-layer-text">
                  <a
                    class="project__view-project-text link-button"
                    href="https://luiswalderdorff.github.io/kanban-task-management-web-app"
                    target="_blank"
                    >View project</a
                  >
                </span>
                <span class="project__hover-layer-text">
                  <a
                    class="project__view-project-text link-button"
                    href="https://github.com/luiswalderdorff/kanban-task-management-web-app"
                    target="_blank"
                    >View code</a
                  >
                </span>
              </div>
            </div>
            <h3 class="project__title">Kanaban Board</h3>
            <div class="project__skills">
              <span class="project__skill">SCSS</span>
              <span class="project__skill">Vue</span>
              <span class="project__skill">TypeScript</span>
            </div>
            <div class="project__view-project">
              <a
                class="project__view-project-text link-button"
                href="https://luiswalderdorff.github.io/kanban-task-management-web-app"
                target="_blank"
                >View project</a
              >
              <a
                class="project__view-project-text link-button"
                href="https://github.com/luiswalderdorff/kanban-task-management-web-app"
                target="_blank"
                >View code</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container container--grey" id="contact-container">
      <div class="contact">
        <svg
          class="contact__rings"
          xmlns="http://www.w3.org/2000/svg"
          width="530"
          height="129"
        >
          <g fill="none" fill-rule="evenodd" stroke="#FFF" opacity=".25">
            <ellipse cx="265" cy="40" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="52" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="65" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="77" rx="264.5" ry="39.5" />
            <ellipse cx="265" cy="89" rx="264.5" ry="39.5" />
          </g>
        </svg>
        <div class="contact__text-container">
          <h2 class="contact__title h2">Contact</h2>
          <p class="contact__text">
            I would love to hear about your project and how I could help. Please
            fill in the form, and I’ll get back to you as soon as possible.
          </p>
        </div>
        <form class="contact__form" @submit.prevent="onSubmit">
          <!-- TODO: Inputs dont have labels? And create component -->
          <div class="contact__input-container">
            <input
              type="text"
              class="contact__input contact__text-input border-bottom"
              :class="{
                'contact__input--error': form.name.error,
                'contact__input--success':
                  form.name.input.length && !form.name.error,
              }"
              placeholder="name"
              name="name"
              v-model="form.name.input"
            />
            <svg
              v-if="form.name.error"
              class="contact__error-icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <circle cx="12" cy="12" r="11.5" stroke="#FF6F5B" />
              <rect x="11" y="6" width="2" height="9" rx="1" fill="#FF6F5B" />
              <rect x="11" y="17" width="2" height="2" rx="1" fill="#FF6F5B" />
            </svg>
            <span v-if="form.name.error" class="contact__error-message">{{
              form.name.errorMessage
            }}</span>
          </div>
          <div class="contact__input-container">
            <input
              type="text"
              class="contact__input contact__text-input border-bottom"
              :class="{
                'contact__input--error': form.email.error,
                'contact__input--success':
                  form.email.input.length && !form.email.error,
              }"
              placeholder="email"
              name="email"
              v-model="form.email.input"
            />
            <svg
              v-if="form.email.error"
              class="contact__error-icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <circle cx="12" cy="12" r="11.5" stroke="#FF6F5B" />
              <rect x="11" y="6" width="2" height="9" rx="1" fill="#FF6F5B" />
              <rect x="11" y="17" width="2" height="2" rx="1" fill="#FF6F5B" />
            </svg>
            <span v-if="form.email.error" class="contact__error-message">{{
              form.email.errorMessage
            }}</span>
          </div>
          <div class="contact__input-container">
            <textarea
              class="contact__input contact__text-area border-bottom"
              :class="{
                'contact__input--error': form.message.error,
                'contact__input--success':
                  form.message.input.length && !form.message.error,
              }"
              placeholder="message"
              name="message"
              v-model="form.message.input"
            />
            <svg
              v-if="form.message.error"
              class="contact__error-icon"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
            >
              <circle cx="12" cy="12" r="11.5" stroke="#FF6F5B" />
              <rect x="11" y="6" width="2" height="9" rx="1" fill="#FF6F5B" />
              <rect x="11" y="17" width="2" height="2" rx="1" fill="#FF6F5B" />
            </svg>
            <span v-if="form.message.error" class="contact__error-message">{{
              form.message.errorMessage
            }}</span>
          </div>
          <input
            class="link-button contact__submit"
            type="submit"
            value="Send message"
          />
          <p class="message-sent--success" v-if="form.sent && form.sentSuccess">
            Ihre Nachricht wurde erfolgreich abgeschickt!
          </p>
          <p
            class="message-sent--failure"
            v-if="form.sent && !form.sentSuccess"
          >
            Es ist ein Fehler aufgetreten. Versuchen Sie es später noch einmal.
          </p>
        </form>
      </div>

      <footer class="links footer">
        <!-- TODO: make into component -->
        <span class="links__name footer__name">luiswalderdorff</span>
        <div class="icons">
          <a
            class="icons__icon icons__icon--github"
            href="https://github.com/luiswalderdorff"
            target="_blank"
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="24">
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M12.304 0C5.506 0 0 5.506 0 12.304c0 5.444 3.522 10.042 8.413 11.672.615.108.845-.261.845-.584 0-.292-.015-1.261-.015-2.291-3.091.569-3.891-.754-4.137-1.446-.138-.354-.738-1.446-1.261-1.738-.43-.23-1.046-.8-.016-.815.97-.015 1.661.892 1.892 1.261 1.107 1.86 2.876 1.338 3.584 1.015.107-.8.43-1.338.784-1.646-2.738-.307-5.598-1.368-5.598-6.074 0-1.338.477-2.446 1.26-3.307-.122-.308-.553-1.569.124-3.26 0 0 1.03-.323 3.383 1.26.985-.276 2.03-.415 3.076-.415 1.046 0 2.092.139 3.076.416 2.353-1.6 3.384-1.261 3.384-1.261.676 1.691.246 2.952.123 3.26.784.861 1.26 1.953 1.26 3.307 0 4.721-2.875 5.767-5.613 6.074.446.385.83 1.123.83 2.277 0 1.645-.015 2.968-.015 3.383 0 .323.231.708.846.584a12.324 12.324 0 0 0 8.382-11.672C24.607 5.506 19.101 0 12.304 0Z"
              />
            </svg>
          </a>
          <a
            class="icons__icon icons__icon--linkedin"
            href="https://www.linkedin.com/in/luis-walderdorff-564650163"
            target="_blank"
          >
            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="24">
              <path
                fill="#FFF"
                fill-rule="evenodd"
                d="M5.551 3.304c-1.14 0-2.067.926-2.067 2.064 0 1.14.928 2.066 2.067 2.066a2.066 2.066 0 0 0 0-4.13ZM3.767 8.998v11.453h3.562L7.33 8.998H3.767Zm5.798 0V20.45l3.554.002.002-5.668c0-1.454.253-2.941 2.132-2.941 1.851 0 1.851 1.755 1.851 3.036v5.571l3.559-.001v-6.28c0-2.834-.517-5.457-4.27-5.457-1.763 0-2.916.997-3.368 1.85h-.05V8.997h-3.41ZM22.435 24H1.982c-.976 0-1.77-.777-1.77-1.732V1.731C.212.776 1.006 0 1.982 0h20.453c.98 0 1.777.776 1.777 1.73v20.538c0 .955-.797 1.732-1.777 1.732Z"
              />
            </svg>
          </a>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import * as EmailValidator from "email-validator";

export default {
  name: "App",
  data() {
    return {
      form: {
        sent: false,
        sentSuccess: false,
        name: {
          input: "",
          error: false,
          errorMessage: "This field is required", //Feld muss ausgefüllt werden.
        },
        email: {
          input: "",
          error: false,
          errorMessage: "This field is required",
        },
        message: {
          input: "",
          error: false,
          errorMessage: "This field is required",
        },
      },
    };
  },
  watch: {
    "form.email.input"() {
      if (!this.form.email.input.length) {
        this.form.email.error = true;
        this.form.email.errorMessage = "This field is required";
      } else if (!EmailValidator.validate(this.form.email.input)) {
        this.form.email.error = true;
        this.form.email.errorMessage = "Sorry, invalid format here"; // Die E-Mail-Adresse ist valide.
      } else {
        this.form.email.error = false;
      }
    },
  },
  methods: {
    async onSubmit() {
      this.form.name.error = !this.form.name.input.length;

      if (!this.form.email.input.length) {
        this.form.email.error = true;
        this.form.email.errorMessage = "This field is required";
      } else if (!EmailValidator.validate(this.form.email.input)) {
        this.form.email.error = true;
        this.form.email.errorMessage = "Sorry, invalid format here"; // Die E-Mail-Adresse ist valide.
      } else {
        this.form.email.error = false;
      }

      this.form.message.error = !this.form.message.input.length;

      if (
        !this.form.name.error &&
        !this.form.email.error &&
        !this.form.message.error
      ) {
        const response = await fetch("https://api.web3forms.com/submit", {
          method: "POST",
          headers: {
            "Content-Type": "application/json",
            Accept: "application/json",
          },
          body: JSON.stringify({
            access_key: "7f5b1c60-b5e2-4576-9794-4bd4fcc2ab6c",
            name: this.form.name.input,
            email: this.form.email.input,
            message: this.form.message.input,
          }),
        });
        const result = await response.json();
        if (result.success) {
          this.form.name.input = "";
          this.form.email.input = "";
          this.form.message.input = "";
          this.form.sentSuccess = true;
        } else {
          this.form.sentSuccess = false;
        }
        this.form.sent = true;
      }
    },
  },
};
</script>

<style lang="scss">
@font-face {
  font-family: SpaceGrotesk;
  src: url("assets/fonts/SpaceGrotesk-VariableFont_wght.ttf");
}
html,
body,
#app {
  width: 100%;
  margin: 0px;
  padding: 0px;
  overflow-x: hidden;
}
html {
  scroll-behavior: smooth;
}
body {
  font-family: SpaceGrotesk, sans-serif;
  color: white;
  margin: 0;
}
</style>

<style scoped lang="scss">
.header {
  position: absolute;
  top: 20px;
  left: 50%;
  transform: translateX(-50%);
  background: linear-gradient(
    0deg,
    rgba(21, 21, 21, 0) 0%,
    rgba(21, 21, 21, 0.5158438375350141) 50%,
    rgba(21, 21, 21, 1) 100%
  );

  @media only screen and (min-width: 768px) {
    display: flex;
    position: initial;
    justify-content: space-between;
    width: 100%;
    transform: none;
    background: transparent;
  }

  .icons {
    @media only screen and (min-width: 768px) {
      margin-right: 30px;
    }
  }
}

.icons {
  justify-content: center;
  display: flex;
  margin-top: 25px;
  z-index: 1;

  @media only screen and (min-width: 768px) {
    margin-top: 0;
  }

  &__icon {
    &:not(:first-child) {
      margin-left: 30px;
    }

    @media only screen and (min-width: 768px) {
      height: 25px;
      width: auto;
    }

    &:hover {
      svg path {
        fill: #4ee1a0;
        transition: fill 0.3s;
      }
    }
  }
}

.intro {
  text-align: center;
  padding-bottom: 89px;
  margin-bottom: 58px;

  @media only screen and (min-width: 768px) {
    text-align: left;
  }

  @media only screen and (min-width: 1200px) {
    padding-bottom: 230px;
    margin-bottom: 72px;
    position: relative;
  }

  &__rings {
    position: absolute;
    z-index: 0;
    left: 0;
    transform: translateX(-60%);
    top: 140px;
    @media only screen and (min-width: 768px) {
      top: 90px;
    }
    @media only screen and (min-width: 1200px) {
      top: 40px;
    }
  }

  &__circle {
    position: absolute;
    top: 300px;
    right: 0;
    transform: translateX(47%);
    @media only screen and (min-width: 768px) {
      top: 470px;
      z-index: 5;
    }
    @media only screen and (min-width: 1200px) {
      transform: none;
      right: 380px;
      top: 440px;
    }
  }

  &__image {
    width: 200px;
    margin: 44px auto;
    display: block;
    z-index: 1;
    position: relative;

    @media only screen and (min-width: 768px) {
      position: absolute;
      right: 0;
      top: 0;
      height: 450px;
      width: auto;
      margin: auto;
    }

    @media only screen and (min-width: 1200px) {
      right: 0;
      right: 0;
      height: 500px;
      top: 50%;
      transform: translateY(-50%);
    }
  }

  &__title {
    font-size: 40px;
    font-weight: bold;
    z-index: 1;
    position: relative;

    @media only screen and (min-width: 768px) {
      font-size: 72px;
      line-height: 72px;
      margin-bottom: 60px;
      margin-top: 70px;
      width: 64%;
      max-width: 700px;
    }

    @media only screen and (min-width: 1200px) {
      font-size: 78px;
      margin-top: 110px;
    }
  }

  &__name {
    border-bottom: #4ee1a0 5px solid;
    display: inline-block;
    line-height: 42px;
    white-space: nowrap;

    @media only screen and (min-width: 768px) {
      padding-bottom: 18px;
    }
  }

  &__text {
    color: #d9d9d9;
    line-height: 26px;
    z-index: 1;
    position: relative;

    @media only screen and (min-width: 768px) {
      width: 445px;
      margin-bottom: 34px;
    }
  }
}

.skills {
  text-align: center;
  position: relative;
  padding-bottom: 33px;

  @media only screen and (min-width: 768px) {
    display: flex;
    text-align: left;
    flex-wrap: wrap;
    padding-bottom: 0;
  }

  &__rings {
    position: absolute;
    bottom: -66px;
    right: 0;
    transform: translateX(70%);
  }
}

.skill {
  padding-bottom: 25px;

  @media only screen and (min-width: 768px) {
    width: 50%;
  }

  @media only screen and (min-width: 1200px) {
    width: 33%;
  }

  &__skill {
    font-weight: bold;
    font-size: 48px;
  }

  &__time {
    color: #d9d9d9;
    font-size: 18px;

    @media only screen and (min-width: 768px) {
      width: 50%;
    }
  }
}

.projects {
  margin-top: 60px;
  margin-bottom: 92px;

  @media only screen and (min-width: 768px) {
    margin-top: 130px;
  }

  &__header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}

.projects-container {
  @media only screen and (min-width: 768px) {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
}

.project {
  margin-bottom: 52px;

  @media only screen and (min-width: 768px) {
    width: 48%;
  }

  &__img {
    position: relative;
    img {
      max-width: 100%;
    }
  }

  &__hover-layer {
    display: none;

    @media only screen and (min-width: 1200px) {
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.75);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      opacity: 0;
      transition: opacity 0.3s;

      &:hover {
        opacity: 1;
      }
    }

    &-text {
      &:first-child {
        margin-bottom: 50px;
      }
    }
  }

  &__title {
    font-size: 24px;
    font-weight: bold;
    text-transform: uppercase;
    margin-top: 20px;
    margin-bottom: 7px;
  }

  &__skills {
    margin-bottom: 20px;
  }

  &__skill {
    color: #d9d9d9;
    font-size: 18px;
    margin-right: 18px;
    line-height: 28px;
  }

  &__view-project {
    @media only screen and (min-width: 1200px) {
      display: none;
    }
    &-text {
      margin-right: 32px;
    }
  }
}

.contact {
  text-align: center;
  padding-top: 60px;
  padding-bottom: 87px;
  position: relative;

  @media only screen and (min-width: 768px) {
    max-width: 445px;
    margin: auto;
  }
  @media only screen and (min-width: 1200px) {
    display: flex;
    text-align: left;
  }

  & > * {
    @media only screen and (min-width: 1200px) {
      flex-basis: 50%;
    }
  }

  &__rings {
    position: absolute;
    left: 0;
    transform: translateX(-70%);
    bottom: 50px;
  }

  &__text-container {
    @media only screen and (min-width: 1200px) {
      margin-right: 200px;
    }
  }

  &__title {
    margin-top: 0;
    margin-bottom: 20px;
  }

  &__text {
    color: var(--grey, #d9d9d9);
    line-height: 26px;
  }

  /* Remove default styles for input text and textareas */
  &__input {
    border: none;
    padding: 0;
    margin: 0;
    outline: none;
    background: none;
    color: inherit;
    font-family: inherit;
  }

  &__submit {
    border-left: none;
    border-right: none;
    border-top: none;
    padding-left: 0;
    padding-right: 0;
    padding-top: 0;
    margin: 0 0 0 auto;
    outline: none;
    background: none;
    color: inherit;
    cursor: pointer;
    font-family: inherit;
    display: block;
  }

  /* My styles for inputs */
  &__input {
    display: block;
    width: 100%;
    color: white;
    font-weight: 500;
    padding-left: 24px;
    font-size: 16px;
    text-transform: uppercase;
    margin-bottom: 32px;
    box-sizing: border-box;

    &::placeholder {
      color: #979797;
      font-weight: 500;
      font-size: 16px;
      text-transform: uppercase;
    }

    &--success {
      border-bottom: 2px solid #4ee1a0 !important;
    }

    &--error {
      border-bottom: 2px solid #ff6f5b !important;
    }
  }

  &__input-container {
    position: relative;
  }

  &__error-message {
    position: absolute;
    right: 0;
    bottom: -22px;
    color: #ff6f5b;
    font-size: 12px;
  }

  &__error-icon {
    position: absolute;
    top: 0;
    right: 0;
  }

  &__text-input {
    padding-bottom: 23px;

    &::placeholder {
      padding-bottom: 16px;
    }
  }

  &__text-area {
    height: 100px;
  }
}

.message-sent {
  &--success {
    color: #4ee1a0;
  }

  &--failure {
    color: #ff6f5b;
  }
}

.footer {
  padding: 40px 0 60px 0;
  width: 100%;
  border-top: #979797 solid 2px;
  @media only screen and (min-width: 768px) {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 40px 0 8px 0;
  }

  &__name {
    display: block;
  }
}

/* Components */
.container {
  padding: 16px;
  display: flex;
  flex-direction: column;
  align-items: center;

  @media only screen and (min-width: 768px) {
    padding: 32px 0;
  }

  & > * {
    width: 100%;

    @media only screen and (min-width: 768px) {
      max-width: 720px;
    }

    @media only screen and (min-width: 992px) {
      max-width: 860px;
    }

    @media only screen and (min-width: 1200px) {
      max-width: 1140px;
    }
  }

  &--black {
    background-color: #151515;
  }

  &--grey {
    background: #242424;
  }
}

.h2 {
  font-size: 40px;
  font-weight: bold;

  @media only screen and (min-width: 768px) {
    font-size: 72px;
  }
}

p {
  font-size: 16px;
  @media only screen and (min-width: 768px) {
    font-size: 18px;
  }
}

.link-button {
  border-bottom: #4ee1a0 2px solid;
  text-transform: uppercase;
  padding-bottom: 10px;
  letter-spacing: 2.29px;
  font-weight: bold;
  line-height: 26px;
  font-size: 16px;
  cursor: pointer;
  transition: color 0.3s;
  color: white;
  text-decoration: none;

  &:hover {
    color: #4ee1a0;
  }
}

.border-bottom {
  border-bottom: #979797 solid 2px;

  &.skills {
    @media only screen and (min-width: 768px) {
      border-bottom: none;
    }
  }
}

.links {
  width: 200px;
  text-align: center;
  z-index: 10;

  @media only screen and (min-width: 768px) {
    width: 100%;
  }

  &__name {
    font-weight: bold;
    font-size: 24px;
    margin-bottom: 20px;
    letter-spacing: 0.5px;

    @media only screen and (min-width: 768px) {
      font-size: 32px;
    }
  }
}
</style>
