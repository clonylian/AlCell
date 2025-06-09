<template>
  <div class="main">
    <!-- background -->
    <div class="leftbg absolute"></div>
    <div class="rightbg absolute"></div>
    <!-- header -->
    <div class="headbox absolute w-full">
      <div class="container relative flex">
        <img
          alt="logo"
          width="98"
          height="98"
          decoding="async"
          data-nimg="1"
          class="transition-all"
          style="color: transparent"
          src="../assets/logo.png"
        />
        <div class="flex items-center gap-6">
          <a href="https://x.com/BlueWBNB" target="_blank" class="alink">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="none"
              viewBox="0 0 24 24"
              class="svg-icon inline-block"
            >
              <path
                fill="currentColor"
                d="M17.176 4h2.76l-6.03 6.777L21 20h-5.554l-4.35-5.593L6.116 20H3.355l6.45-7.25L3 4h5.695l3.933 5.113zm-.969 14.375h1.53L7.864 5.54h-1.64z"
              ></path>
            </svg>
          </a>
          <a href="https://t.me/BLWONBSC" target="_blank" class="alink">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="none"
              viewBox="0 0 24 24"
              class="svg-icon inline-block"
            >
              <path
                fill="currentColor"
                d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm5.894 8.221-1.97 9.28c-.145.658-.537.818-1.084.508l-3-2.21-1.446 1.394c-.14.14-.26.26-.534.26l.213-3.053 5.56-5.022c.24-.213-.054-.334-.373-.12l-6.87 4.326-2.96-.924c-.64-.203-.658-.64.135-.954l11.57-4.46c.538-.196 1.006.13.832.94z"
              ></path>
            </svg>
          </a>
        </div>
      </div>
    </div>
    <!-- first -->
    <div class="onebox w-full relative">
      <div
        class="container text-center flex flex-col items-center gap-4 dipadding"
      >
        <div class="onetxt">
          From Intelligent Cells to Civilizational Evolution
        </div>
        <div class="onetxtt">
          Empowering a decentralized future through intelligent collaboration,
          modular design, <br />
          and ecosystem-driven growth
        </div>
      </div>
      <div class="relative w-full oneboxbg flex justify-center modelonebox">
        <div class="address">
          <div class="addressbox relative">
            <img
              src="../assets/viXzUrVSvggJuuQdNh2zJoh7wtI.svg"
              class="absolute copybg"
              alt=""
            />
            <p>{{ textToCopy }}</p>
            <div class="copybox" @click="copyCA()">
              <h5>{{ copied ? "COPIED" : "COPY" }}</h5>
              <div class="copyicon"></div>
            </div>
          </div>
        </div>
        <img src="../assets/slider1-bg-dark.png" class="logoone img" alt="" />
      </div>
      <div class="container flex justify-between items-center onetxtbox">
        <div class="onetxtleft">
          <div class="onetxttit">ABOUT AICELL GUILD</div>
          <div class="onetxttxt">The Heart of Civilization Governance</div>
          <div class="onetxttxtt">
            Our DAO Treasury serves as the economic core of the AiCell
            ecosystem. By aggregating liquidity and meme tokens from Agent
            projects, it acts as a resource hub that fuels innovation and
            ensures sustainable growth.
          </div>
          <div
            class="justify-center items-center gap-3 inline-flex cursor-pointer onebutto"
          >
            DAO
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="23"
              fill="none"
              viewBox="0 0 24 23"
              class="svg-icon inline-block"
            >
              <path
                fill="currentColor"
                d="m11.898 20.534 7.174-7.761H.005v-2.611H19.09l-7.193-7.773L13.813.615l9.21 9.953v1.773l-9.21 9.964z"
              ></path>
            </svg>
          </div>
        </div>
        <div class="flex flex-col onetxtright text-center numsbox">
          <div>
            <div class="onenumtit">$2.75M</div>
            <div class="onenumtxt">MarketCap</div>
          </div>
          <div>
            <div class="onenumtit">$<!-- -->15.95K</div>
            <div class="onenumtxt">DAO Value</div>
          </div>
        </div>
      </div>
      <div class="relative w-full oneboxbg flex justify-center">
        <img class="imgtwo" src="../assets/slider1-bg-dark4.png" alt="" />
      </div>
    </div>
    <!-- Design  -->
    <div class="w-full twobox">
      <div class="container">
        <div class="flex justify-between twotop">
          <div class="twotoptit">Design The Cell</div>
          <div class="twotoptxt flex items-center">
            <span
              >Just as cells form the building blocks of life, AiCell creates
              intelligent Agents as the fundamental units of a decentralized
              civilization. These Agents are designed to evolve independently,
              collaborate dynamically, and form advanced ecosystems that drive
              continuous innovation.</span
            >
          </div>
        </div>
        <div class="flex items-center justify-between flex-wrap twolists">
          <div class="flex items-center twolistimg">
            <div class="twolist">
              <img src="../assets/slider1-bg-dark2.png" alt="" />
            </div>
            <div class="text-center __className_2f4fcf twolisttxt">
              Individual Agents: The foundation of our civilization, capable of
              specialized tasks and self-evolution.
            </div>
          </div>
          <div class="flex items-center twolistimg">
            <div class="twolist">
              <img src="../assets/slider1-bg-dark3.png" alt="" />
            </div>
            <div class="text-center __className_2f4fcf twolisttxt">
              Collaborative Swarms: Intelligent networks that combine Agents to
              handle complex workflows.
            </div>
          </div>
          <div class="flex items-center twolistimg">
            <div class="twolist">
              <img src="../assets/slider1-bg-dark7.png" alt="" />
            </div>
            <div class="text-center __className_2f4fcf twolisttxt">
              Decentralized Ecosystems: Governance through DAOs and
              community-driven growth for a sustainable civilization.
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Roadmap -->
    <div class="w-full threebox">
      <div class="container text-center flex flex-col items-center">
        <div class="threestit mb-4">Roadmap</div>
        <div class="threetit mb-12">Meet the AICell On BNB Chain</div>
        <div
          class="roadmap-slider modelbox swiper-initialized swiper-horizontal swiper-backface-hidden"
        >
          <div
            class="swiper-wrapper"
            ref="ivubox"
            id="swiper-wrapper-7b449d64a28b2998"
            aria-live="polite"
            style="
              transition-duration: 300ms;
              transform: translate3d(0px, 0px, 0px);
              transition-delay: 0ms;
            "
          >
            <div
              class="swiper-slide complited swiper-slide-active"
              role="group"
              aria-label="1 / 9"
            >
              <div class="roadmap-date">Q4'23</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">development started</div>
            </div>

            <div
              class="swiper-slide complited swiper-slide-next"
              role="group"
              aria-label="2 / 9"
            >
              <div class="roadmap-date">Q2'24</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div
                style="text-align: left; padding-left: 30px"
                class="roadmap-text"
              >
                <div class="roadmap-title">public beta:</div>
                <ul
                  style="padding-inline-start: 0px !important; margin-top: 12px"
                  class="roadmap-list"
                >
                  <li>ETH, ARB, BASE</li>
                  <li>limit + trailing orders</li>
                  <li>TP+SL combos</li>
                </ul>
              </div>
            </div>

            <div class="swiper-slide complited" role="group" aria-label="3 / 9">
              <div class="roadmap-date">Q3'24</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">
                <ul class="roadmap-list">
                  <li>DEX Screener</li>
                  <li>BSC support</li>
                </ul>
              </div>
            </div>

            <div class="swiper-slide complited" role="group" aria-label="4 / 9">
              <div class="roadmap-date">Q4'24</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">DCA bot</div>
            </div>

            <div class="swiper-slide complited" role="group" aria-label="5 / 9">
              <div class="roadmap-date">Q1'25</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">Solana support</div>
            </div>

            <div class="swiper-slide complited" role="group" aria-label="6 / 9">
              <div class="roadmap-date">Q2'25</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">sniper bot</div>
            </div>

            <div class="swiper-slide" role="group" aria-label="7 / 9">
              <div class="roadmap-date">Q3'25</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">grid bot</div>
            </div>

            <div class="swiper-slide" role="group" aria-label="8 / 9">
              <div class="roadmap-date">Q4'25</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">TradingView bot</div>
            </div>

            <div class="swiper-slide" role="group" aria-label="9 / 9">
              <div class="roadmap-date">2026</div>
              <div class="roadmap-marker">
                <div class="roadmap-marker__line"></div>
              </div>
              <div class="roadmap-text">GOOD protocol</div>
            </div>
          </div>

          <div
            @click="left()"
            :class="
              nums == 0
                ? 'swiper-button-prev swiper-button-disabled'
                : 'swiper-button-prev'
            "
            id="x-roadmap"
            tabindex="-1"
            role="button"
            aria-label="Previous slide"
            aria-controls="swiper-wrapper-7b449d64a28b2998"
            aria-disabled="true"
          ></div>
          <div
            @click="right()"
            :class="
              nums == 5
                ? 'swiper-button-next swiper-button-disabled'
                : 'swiper-button-next'
            "
            id="x-roadmap"
            tabindex="0"
            role="button"
            aria-label="Next slide"
            aria-controls="swiper-wrapper-7b449d64a28b2998"
            aria-disabled="false"
          ></div>
        </div>
        <div class="threetxt">
          Built on BNB Chain, AiCell offers enhanced scalability and DeFi
          integration, creating a robust ecosystem. Unlike Solana's AI16z which
          focuses on DAO-driven community creation, AiCell builds a
          comprehensive ecosystem centered on civilization development.
        </div>
      </div>
    </div>
    <!-- Join  -->
    <div class="relative w-full fourbox">
      <div class="relative z-10 flex text-center flex-col items-center">
        <h5 class="fourtit">Join the AICell Civilization</h5>
        <p class="fourtxt">
          Create custom AI Agents with our toolkit and shape the future of
          decentralized innovation.
        </p>
        <div
          class="inline-flex cursor-pointer items-center fourbut"
          style="background-image: linear-gradient(to right, #ffbf5e, #eced03)"
        >
          Contact Us
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="lucide lucide-arrow-right ml-2"
          >
            <path d="M5 12h14"></path>
            <path d="m12 5 7 7-7 7"></path>
          </svg>
        </div>
      </div>
      <div
        class="absolute w-full fourbg"
        style="
          background: linear-gradient(
            177deg,
            rgb(237 211 30) 2.39%,
            rgba(19, 17, 20, 0.8) 46.2%
          );
        "
      ></div>
      <div class="fourlogo absolute">
        <img src="../assets/slider1-bg-dark5.png" alt="" />
      </div>
    </div>
    <!-- foot -->
    <div class="w-full flex justify-center footbox">
      <div class="container flex items-center justify-between footconbox">
        <img src="../assets/logo.png" class="footimg" alt="" /><span
          class="foottxt"
          >Connect and build on the Decentralized AI Finance</span
        >
        <div class="flex items-center gap-6">
          <a
            class="cursor-pointer alink"
            href="https://x.com/BlueWBNB"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="none"
              viewBox="0 0 24 24"
              class="svg-icon inline-block"
            >
              <path
                fill="currentColor"
                d="M17.176 4h2.76l-6.03 6.777L21 20h-5.554l-4.35-5.593L6.116 20H3.355l6.45-7.25L3 4h5.695l3.933 5.113zm-.969 14.375h1.53L7.864 5.54h-1.64z"
              ></path></svg></a
          ><a
            class="cursor-pointer alink"
            href="https://t.me/BLWONBSC"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="none"
              viewBox="0 0 24 24"
              class="svg-icon inline-block"
            >
              <path
                fill="currentColor"
                d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm5.894 8.221-1.97 9.28c-.145.658-.537.818-1.084.508l-3-2.21-1.446 1.394c-.14.14-.26.26-.534.26l.213-3.053 5.56-5.022c.24-.213-.054-.334-.373-.12l-6.87 4.326-2.96-.924c-.64-.203-.658-.64.135-.954l11.57-4.46c.538-.196 1.006.13.832.94z"
              ></path></svg
          ></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

let ivubox = ref("null");

let nums = ref(0);

const textToCopy = ref("0xD5CB08E3653eD8F78C781d8AC7F32B98F47E4444");
//COPYtype
const copied = ref(false);

//COPYadd
let copyCA = async () => {
  await navigator.clipboard.writeText(textToCopy.value);

  copied.value = true;
  setTimeout(() => (copied.value = false), 2000);
};

let right = () => {
  nums.value = Math.min(nums.value + 1, 5);

  const screenWidth = window.innerWidth;
  let moveDistance;

  if (screenWidth >= 1400) {
    moveDistance = 20.25; // 默认值
  } else if (screenWidth >= 1200) {
    moveDistance = 17.4375;
  } else {
    moveDistance = 15;
  }

  ivubox.value.style.transform = `translate3d(${
    -nums.value * moveDistance
  }rem, 0, 0)`;
};

let left = () => {
  nums.value = Math.max(0, nums.value - 1);

  const screenWidth = window.innerWidth;
  let moveDistance;

  if (screenWidth >= 1400) {
    moveDistance = 20.25; // 默认值
  } else if (screenWidth >= 1200) {
    moveDistance = 17.4375;
  } else {
    moveDistance = 15;
  }

  ivubox.value.style.transform = `translate3d(${
    -nums.value * moveDistance
  }rem, 0, 0)`;
};
</script>

<style scoped>
/* gg */
img,
video {
  max-width: 100%;
  height: auto;
}

.__className_2f4fcf {
  font-family: "JustMeAgainDownHere";
  font-weight: 400;
  font-style: normal;
}

.overflow-hidden {
  overflow: hidden;
}

.w-full {
  width: 100%;
}
.relative {
  position: relative;
}
.irelative {
  position: relative !important;
}
.absolute {
  position: absolute;
}

.flex {
  display: flex;
}

.items-center {
  align-items: center;
}

.gap-6 {
  gap: 1.5rem;
}

.gap-4 {
  gap: 1rem;
}

.gap-3 {
  gap: 0.75rem;
}

.flex-col {
  flex-direction: column;
}

.cursor-pointer {
  cursor: pointer;
}

.inline-flex {
  display: inline-flex;
}

.text-center {
  text-align: center;
}

.justify-center {
  justify-content: center;
}

.object-contain {
  object-fit: contain;
}

.justify-between {
  justify-content: space-between;
}

.flex-wrap {
  flex-wrap: wrap;
}

.text-right {
  text-align: right;
}

.flex-1 {
  flex: 1 1 0%;
}

.mb-4 {
  margin-bottom: 1rem;
}

.mb-12 {
  margin-bottom: 3rem;
}

.z-10 {
  z-index: 10;
}

/* maim */
.main {
  padding-top: 10rem;
}

/* background */

.leftbg {
  left: -6.375rem;
  top: 0;
  width: 18.75rem;
  height: 18.75rem;
  border-radius: 50%;
  background: radial-gradient(
    circle at center,
    rgb(165 149 36) 0%,
    rgba(19, 17, 20, 0.8) 70%
  );
}

.rightbg {
  right: 5.75rem;
  top: 28.5rem;
  width: 25rem;
  height: 25rem;
  background: radial-gradient(
    circle at center,
    rgb(97 86 5) 0%,
    rgba(237, 211, 30, 0) 70%
  );
}
/* header */
.headbox {
  left: 0;
  top: 0;
  z-index: 10;
  color: white;
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 0.3s;
}

.headbox .container {
  height: 8.5rem;
  align-items: center;
  justify-content: space-between;
}

.container {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
  padding-right: 1rem;
  padding-left: 1rem;
}

.alink {
  cursor: pointer;
  font-size: 1.5rem;
  line-height: 2rem;
  color: white;
  opacity: 0.4;
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 0.15s;
}

.svg-icon.use-em,
.svg-icon {
  width: 1.5rem;
  height: 1.5rem;
}

.alink:hover {
  opacity: 1;
}

/* first */
.onebox {
  color: white;
  padding-bottom: 8.125rem;
  z-index: 2;
}

.dipadding {
  padding-bottom: 3rem;
}

.onetitle {
  font-family: "Hanken-Grotesk-Black";
  font-size: 1.4375rem;
  font-weight: 700;
  line-height: 100.174%;
}

.onetxt {
  font-family: "JustMeAgainDownHere";
  font-size: 6rem;
  font-weight: 900;
  line-height: 100%;
}

.onetxtt {
  font-family: "JustMeAgainDownHere";
  font-size: 1.5rem;
  font-weight: 400;
  line-height: 141.667%;
  padding-left: 20%;
  padding-right: 20%;
}

.oneboxbg {
  height: 15.75rem;
}

.oneboxbg .img {
  position: absolute;
  width: 21rem;
  height: 21rem;
  right: 32rem;
  animation: float 2.5s ease-in-out infinite;
}

.oneboxbg .logoone {
  top: -4rem;
  right: 15.4%;
}

.oneboxbg .imgtwo {
  position: absolute;
  width: 21rem;
  height: 21rem;
  animation: float 2.5s ease-in-out infinite;
}

.oneboxbg .imgtwo {
  left: 45%;
}

@keyframes float {
  0%,
  100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-1.5rem);
  }
}

.addressbox {
  width: 40rem;
  height: 5.375rem;
  display: flex;
  padding: 0 2.1875rem;
  box-sizing: border-box;
  align-items: center;
  justify-content: space-between;
}

.copybg {
  z-index: -1;
  top: 0;
  left: 0;
}

.addressbox p {
  color: rgb(84, 84, 84);
  font-size: 18px;
  font-weight: 700;
  font-family: "Hanken-Grotesk-Black";
}

.copybox {
  display: flex;
  gap: 0.5rem;
  align-items: center;
  cursor: pointer;
}

.copybox h5 {
  color: rgb(16, 12, 24);
  font-size: 18px;
  font-weight: 900;
  font-family: "JustMeAgainDownHere";
}

.copyicon {
  background-color: rgb(16, 12, 24);
  mask: url(../assets/ntlS9V0k5C5M7xaZTL2O5Jf5E9I.svg) center center / cover
    no-repeat alpha;
  transform: none;
  transform-origin: 50% 50% 0px;
  aspect-ratio: 1 / 1;
  flex: none;
  height: 1.5rem;
  overflow: hidden;
  position: relative;
  width: 1.5rem;
}

.onetxtleft {
  max-width: 100%;
  width: 60%;
}

.onetxttit {
  font-family: "Hanken-Grotesk-Black";
  margin-bottom: 1rem;
  font-size: 1.4375rem;
  font-weight: 700;
  line-height: 100.174%;
}

.onetxttxt {
  font-family: "JustMeAgainDownHere";
  margin-bottom: 1rem;
  font-size: 4.31875rem;
  font-weight: 900;
  line-height: 100.029%;
}

.onetxttxtt {
  font-family: "JustMeAgainDownHere";
  margin-bottom: 2.6875rem;
  padding-right: 2.5rem;
  font-size: 1.4375rem;
  font-weight: 400;
  line-height: 150.261%;
}

.onebutto {
  color: white;
  font-weight: 700;
  font-size: 1.5rem;
  line-height: 2rem;
  padding: 1rem 2rem;
  background-image: linear-gradient(to right, #ffbf5e, #eced03);
  border-radius: 1.25rem;
}

.onetxtright {
  gap: 4.0625rem;
}

.onenumtit {
  font-family: "JustMeAgainDownHere";
  font-size: 5.125rem;
  font-weight: 900;
  line-height: 100%;
}

.onenumtxt {
  font-family: "Hanken-Grotesk-Black";
  font-size: 1.5rem;
  font-weight: 700;
  line-height: 133.333%;
}

/* Design */
.twobox {
  color: #fff;
  padding-top: 6.625rem;
  padding-bottom: 6.625rem;
  background-color: #000;
}

.twotop {
  gap: 4.3125rem;
  margin-bottom: 6rem;
}

.twotoptit {
  font-family: "JustMeAgainDownHere";
  width: 26.1875rem;
  max-width: 100%;
  font-size: 4.31875rem;
  font-weight: 900;
  line-height: 107.091%;
}

.twotoptxt {
  font-family: "JustMeAgainDownHere";
  flex: 1 1 0%;
  font-size: 1.4375rem;
  font-weight: 400;
  line-height: 150.261%;
}

.twolists {
  gap: 4rem;
}

.twolist {
  width: 14.75rem;
  flex-shrink: 0;
}

.twolisttxt {
  width: 13.8125rem;
  font-size: 2.25rem;
  line-height: 96%;
}

/* Ecosystem */
.threebox {
  padding-top: 6.625rem;
  padding-bottom: 6.625rem;
  color: white;
}

.threestit {
  font-size: 1.4375rem;
  font-weight: 700;
  line-height: 100.174%;
  font-family: "Hanken-Grotesk-Black";
}

.threetit {
  font-size: 4.31875rem;
  font-weight: 900;
  line-height: 100.029%;
  font-family: "JustMeAgainDownHere";
}

.threetxt {
  width: 64.5rem;
  max-width: 100%;
  font-size: 1.375rem;
  font-weight: 400;
  line-height: 157.091%;
  font-family: "JustMeAgainDownHere";
}

.swiper-horizontal {
  touch-action: pan-y;
}

.roadmap-slider {
  width: 100%;
  overflow: hidden;
  position: relative;
}

.swiper-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
  z-index: 1;
  display: flex;
  transition-property: transform;
  transition-timing-function: initial;
  box-sizing: content-box;
}

.swiper-slide {
  flex-shrink: 0;
  width: 100%;
  height: 100%;
  position: relative;
  transition-property: transform;
  display: block;
}

.swiper-backface-hidden .swiper-slide {
  transform: translateZ(0);
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.roadmap-slider .swiper-slide {
  display: flex;
  flex-direction: column;
  flex: 1 0 20%;
  min-width: 15rem;
}

.roadmap-slider .swiper-slide {
  flex: 1 0 25%;
}

.roadmap-date {
  color: #79828a;
  margin: 0 auto;
}

.roadmap-marker {
  position: relative;
  background: no-repeat url("../assets/roadmap-marker.svg") center;
  height: 3.875rem;
}

.roadmap-slider .swiper-slide .roadmap-marker:before,
.roadmap-slider .swiper-slide .roadmap-marker:after {
  content: "";
  display: block;
  z-index: 1;
  position: absolute;
  top: 50%;
  height: 1px;
}

.roadmap-slider .swiper-slide .roadmap-marker:before {
  left: 0;
  right: calc(50% + 7px);
  background: #79828a;
}

.roadmap-slider .swiper-slide .roadmap-marker:after {
  left: calc(50% + 7px);
  right: 0;
  background: #79828a;
}

.roadmap-slider .swiper-slide.complited .roadmap-marker:before,
.roadmap-slider .swiper-slide.complited .roadmap-marker:after {
  background: rgb(245, 214, 47);
}

.roadmap-slider .swiper-slide.complited:first-child .roadmap-marker:before {
  background: linear-gradient(
    270deg,
    rgb(245, 214, 47) 40%,
    rgba(1, 239, 103, 0) 100%
  );
}

.roadmap-marker__line {
  left: 50%;
  display: block;
  position: absolute;
  top: 50%;
  width: 1rem;
  height: 1rem;
  transform: translate(-50%, -50%);
  border-radius: 50%;
  background: var(--Border);
}

.roadmap-slider
  .swiper-slide.complited:not(.last-complited)
  .roadmap-marker__line {
  background: rgb(245, 214, 47);
}

.roadmap-slider .swiper-slide.complited:first-child .roadmap-marker__line {
  left: 50%;
}

.roadmap-text {
  font-family: "JustMeAgainDownHere";
  text-align: center;
  font-size: 1.125rem;
  line-height: 1.334;
  font-weight: 700;
  margin: 0 auto;
}

.roadmap-slider .swiper-slide > * {
  padding: 0 2rem;
  box-sizing: border-box;
}

.roadmap-list {
  list-style: none;
  padding: 0 !important;
  padding-inline-start: 55px !important;
  margin: 0;
  text-align: left;
}

.roadmap-list li {
  position: relative;
  padding-left: 20px !important;
}

.roadmap-list li::before {
  content: "•" !important;
  position: absolute;
  left: 0;
  color: #ffffff;
  margin: 0 !important;
}

.swiper-button-next,
.swiper-button-prev {
  position: absolute;
  top: 50%;
  width: calc(2.75rem / 44 * 27);
  height: 2.75rem;
  margin-top: calc(0px - (2.75rem / 2));
  z-index: 10;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #007aff;
}

.swiper-button-prev,
.swiper-rtl .swiper-button-next {
  left: 0.625rem;
  right: auto;
}

.swiper-button-next,
.swiper-rtl .swiper-button-prev {
  right: 0.625rem;
  left: auto;
}

.swiper-button-next,
.swiper-button-prev {
  --arrow: url("../assets/jiantou.svg");
  --arrow-disabled: url("../assets/yjiantou.svg");
  width: 2.5rem;
  height: 2.5rem;
  border-radius: 50%;
  border: 1px solid #79828a;
  background: var(--arrow) no-repeat center #010b13;
  transition: 0.2s;
  top: 3.375rem;
}

.swiper-button-prev,
.swiper-container-rtl .swiper-button-next {
  transform: rotate(180deg);
  left: 0;
}

.swiper-button-next.swiper-button-disabled,
.swiper-button-prev.swiper-button-disabled {
  opacity: 0.35;
  cursor: auto;
  pointer-events: none;
}

.swiper-button-next.swiper-button-disabled,
.swiper-button-prev.swiper-button-disabled {
  opacity: 1;
  background-image: var(--arrow-disabled);
  border-color: #3d464e;
}

.swiper-button-next,
.swiper-container-rtl .swiper-button-prev {
  right: 0;
}

/* Join */
.fourbox {
  background-color: rgb(15 15 15);
  padding-top: 8.25rem;
  padding-bottom: 8.25rem;
  color: white;
}

.fourtit {
  font-size: 3.375rem;
  font-weight: 900;
  line-height: 118%;
  font-family: "JustMeAgainDownHere";
}

.fourtxt {
  font-family: "JustMeAgainDownHere";
  margin-bottom: 3rem;
  margin-top: 1.5rem;
  width: 43.25rem;
  font-size: 1.125rem;
  line-height: 133.333%;
}

.fourbut {
  cursor: pointer;
  border-radius: 1.25rem;
  padding-left: 2rem;
  padding-right: 2rem;
  padding-top: 1rem;
  padding-bottom: 1rem;
  line-height: 1;
}

.fourbg {
  opacity: 0.8;
  filter: blur(5.65412rem);
  transform: translate(-50%, 0) rotate(0) skewX(0) skewY(0) scaleX(1) scaleY(1);
  background: linear-gradient(
    177deg,
    rgb(237 211 30) 2.39%,
    rgba(19, 17, 20, 0.8) 46.2%
  );
  height: 19.875rem;
  left: 50%;
  top: 2.5rem;
}

.fourlogo {
  right: 15.7%;
  top: 5.5rem;
}

.fourlogo img {
  width: 21rem;
  height: 21rem;
}
/* foot */
.footbox {
  height: 7.5rem;
  border-top: 0.0625rem solid rgba(234, 238, 245, 0.12);
  background-color: #0f0f0f;
  color: #fff;
}

.footimg {
  width: 7rem;
}

.foottxt {
  font-size: 1.125rem;
  font-family: "JustMeAgainDownHere";
}

@media (min-width: 576px) {
  .modelbox {
    max-width: 540px;
  }
}

@media (min-width: 640px) {
  .container {
    max-width: 40rem;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 48rem;
  }

  .modelbox {
    max-width: 720px;
  }
}

@media not all and (min-width: 768px) {
  .main {
    padding-top: 6.6875rem;
  }

  .headbox .container {
    height: 5.1875rem;
  }

  .addressbox {
    width: 19.6875rem;
    height: 7.8125rem;
    flex-direction: column;
    justify-content: center;
    gap: 0.5rem;
  }

  .addressbox img {
    width: 100%;
    height: 100%;
  }

  .addressbox p {
    text-align: center;
    word-wrap: break-word;
    width: 100%;
  }

  .oneboxbg {
    height: 20.75rem;
  }

  .modelonebox {
    height: 25rem;
  }

  .oneboxbg .logoone {
    top: 6rem;
  }

  .oneboxbg .img {
    top: 0rem;
    left: 0 !important;
    right: 0 !important;
    margin: 0 auto;
  }

  .onebox {
    padding-top: 2rem;
    padding-bottom: 2rem;
  }

  .onebox .container {
    margin-bottom: 2.5rem;
  }
  .dipadding {
    padding-bottom: 0;
  }

  .onetitle {
    font-size: 1rem;
    line-height: 1.5rem;
  }

  .onetxt {
    font-size: 2.625rem;
    line-height: 114.286%;
  }

  .onetxtt {
    font-size: 1.125rem;
    padding-left: 0;
    padding-right: 0;
    line-height: 122.222%;
  }

  .onetxtbox {
    flex-wrap: wrap;
    margin-top: 2rem;
  }

  .onetxtleft {
    margin-bottom: 5rem;
    width: 100%;
  }

  .onetxttit {
    font-size: 1rem;
    line-height: 100%;
  }

  .onetxttxt {
    font-size: 1.875rem;
    line-height: 106.667%;
  }

  .onetxttxtt {
    padding-right: 0;
  }

  .onebutto {
    padding-top: 1.375rem;
    padding-bottom: 1.375rem;
    font-size: 1.25rem;
    line-height: 1.75rem;
  }

  .numsbox {
    width: 100%;
  }

  .twobox {
    padding-top: 3rem;
    padding-bottom: 3rem;
  }

  .twotop {
    margin-bottom: 2rem;
    flex-wrap: wrap;
    gap: 1rem;
  }

  .twotoptit {
    font-size: 1.875rem;
    text-align: center;
  }

  .twotoptxt {
    font-size: 1.125rem;
  }

  .twolists {
    gap: 3.375rem;
    flex-direction: column;
  }

  .twolistimg {
    flex-direction: column;
  }

  .twolisttxt {
    width: 100%;
  }

  .threetit {
    font-size: 1.875rem;
    line-height: 2.25rem;
  }

  .threetxt {
    text-align: left;
  }

  .fourbox {
    padding-top: 5.6875rem;
    padding-bottom: 5.6875rem;
  }

  .fourtit {
    font-size: 1.875rem;
    width: 80%;
  }

  .fourtxt {
    font-size: 1.125rem;
    line-height: 1.75rem;
    width: 90%;
  }

  .fourbut {
    padding-left: 2rem;
    padding-right: 2rem;
  }

  .footbox {
    padding-top: 1.5rem;
    padding-bottom: 1.5rem;
    height: auto;
  }

  .footconbox {
    flex-direction: column;
  }

  .foottxt {
    margin-top: 0.9375rem;
    margin-bottom: 0.9375rem;
    font-size: 0.75rem;
  }

  .fourlogo {
    display: none;
  }
}

@media (min-width: 992px) {
  .modelbox {
    max-width: 960px;
  }
}

@media (min-width: 1024px) {
  .container {
    max-width: 64rem;
  }
}

@media (min-width: 1200px) {
  .modelbox {
    max-width: 1140px;
  }
}

@media (min-width: 1280px) {
  .container {
    max-width: 80rem;
  }
}

@media (min-width: 1400px) {
  .modelbox {
    max-width: 1320px;
  }
}

@media (min-width: 1536px) {
  .container {
    max-width: 96rem;
  }
}

@media (max-width: 1650px) {
  .oneboxbg .logoone {
    right: 5.9%;
  }

  .fourlogo {
    right: 5.9%;
  }
}

@media (max-width: 1375px) {
  .oneboxbg .logoone {
    right: 3.5%;
  }

  .fourlogo {
    right: 3.5%;
  }
}

@media (max-width: 1200px) {
  .oneboxbg .logoone {
    top: 4rem;
    right: 20.6%;
  }

  .fourlogo {
    display: none;
  }
}

@media (max-width: 500px) {
  .oneboxbg .logoone {
    top: 19.2%;
  }
}
</style>
