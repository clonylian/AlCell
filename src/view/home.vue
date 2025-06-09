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
          height="40"
          decoding="async"
          data-nimg="1"
          class="transition-all"
          style="color: transparent"
          src="../assets/logo-dark.svg"
        />
        <div class="flex items-center gap-6">
          <a href="https://x.com/AICell_World" target="_blank" class="alink">
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
          <a
            href="https://github.com/AIcell-labs"
            target="_blank"
            class="alink"
          >
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
                d="M12 0c6.63 0 12 5.37 12 12a12.02 12.02 0 0 1-8.175 11.385c-.6.12-.825-.255-.825-.57 0-.405.015-1.695.015-3.3 0-1.125-.375-1.845-.81-2.22 2.67-.3 5.475-1.32 5.475-5.925 0-1.32-.465-2.385-1.23-3.225.12-.3.54-1.53-.12-3.18 0 0-1.005-.33-3.3 1.23-.96-.27-1.98-.405-3-.405s-2.04.135-3 .405c-2.295-1.545-3.3-1.23-3.3-1.23-.66 1.65-.24 2.88-.12 3.18-.765.84-1.23 1.92-1.23 3.225 0 4.59 2.79 5.625 5.46 5.925-.345.3-.66.825-.765 1.605-.69.315-2.415.825-3.495-.99-.225-.36-.9-1.245-1.845-1.23-1.005.015-.405.57.015.795.51.285 1.095 1.35 1.23 1.695.24.675 1.02 1.965 4.035 1.41 0 1.005.015 1.95.015 2.235 0 .315-.225.675-.825.57A11.99 11.99 0 0 1 0 12C0 5.37 5.37 0 12 0"
              ></path>
            </svg>
          </a>
        </div>
      </div>
    </div>
    <!-- 首屏 -->
    <div class="onebox w-full relative">
      <div class="container text-center flex flex-col items-center gap-4">
        <div class="onetitle">Welcome To AICell</div>
        <div class="onetxt">
          From Intelligent Cells to Civilizational Evolution
        </div>
        <div class="onetxtt">
          Empowering a decentralized future through intelligent collaboration,
          modular design, and ecosystem-driven growth
        </div>
      </div>
      <div class="relative w-full oneboxbg flex justify-center">
        <img
          src="../assets/slider1-bg-dark.png"
          alt=""
          class="onebimg object-contain"
        />
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
        <div class="flex flex-col onetxtright text-center">
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
          <div class="flex items-center">
            <div class="twolist">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="157"
                height="251"
                fill="none"
                viewBox="0 0 157 251"
                class="w-full h-auto"
              >
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M63.198 122.849c8.235 6.314 28.258 17.009 58.707-14.903s25.83-48.71 19.603-55.439c-6.228-6.728-22.2-8.906-34.438 1.772-12.237 10.677-37.585 30.443-43.28 42.397-5.694 11.955-8.828 19.859-.592 26.173"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M106.386 73.812c14.058-8.37 14.407-27.005 4.657-39.691S87.849 2.889 70.248 13.084C52.648 23.28 45.674 41.34 57.246 54.292s35.082 27.89 49.14 19.52M38.725 45.247c8.401 6.44 15.455 16.045 1.768 33.897s-27.56 10.92-35.046 4.75C-2.04 77.727 1.833 63.08 8.388 54.53s21.935-15.725 30.337-9.284"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M58.77 85.597c-2.334-9.681-14.233-23.642-27.222-13.76-12.99 9.88-24.67 20.68-18.694 30.878 5.977 10.197 24.962 14.911 34.737 8.164s13.514-15.6 11.18-25.282"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M95.164 93.522c-1.145 1.494-.851 3.642.657 4.798 1.507 1.156 3.658.882 4.803-.612s.852-3.642-.656-4.798-3.658-.882-4.804.612M118.146 91.816c-1.146 1.493-.852 3.642.656 4.798s3.659.882 4.804-.612.851-3.642-.656-4.798-3.659-.882-4.804.612M100.832 63.51c-1.145 1.494-.851 3.642.657 4.798 1.507 1.156 3.658.882 4.803-.611 1.146-1.494.852-3.642-.656-4.798s-3.658-.882-4.804.611M73.531 42.58c-1.145 1.493-.851 3.642.657 4.798s3.658.882 4.804-.612c1.145-1.494.851-3.642-.657-4.798-1.507-1.156-3.658-.882-4.804.612M83.9 29.056c-1.145 1.493-.85 3.641.657 4.797 1.508 1.157 3.659.883 4.804-.611s.851-3.642-.657-4.798c-1.507-1.156-3.658-.882-4.803.611M93.076 42.529c-1.145 1.494-.851 3.642.657 4.798 1.507 1.156 3.658.882 4.804-.612 1.145-1.494.851-3.642-.657-4.798s-3.658-.882-4.804.612M28.395 78.836c-1.146 1.494-.852 3.642.656 4.798s3.659.882 4.804-.612.851-3.642-.656-4.797c-1.508-1.156-3.659-.883-4.804.611M30.312 101.781c-1.146 1.494-.852 3.642.656 4.798s3.659.882 4.804-.612.851-3.642-.656-4.798-3.659-.882-4.804.612M12.341 68.679c-1.145 1.494-.851 3.642.656 4.798s3.659.882 4.804-.612.852-3.642-.656-4.798-3.659-.882-4.804.612M27.515 54.54c-1.146 1.495-.852 3.643.656 4.799s3.659.882 4.804-.612.852-3.642-.656-4.798-3.659-.882-4.804.612"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M20.056 188.611c-.538 5.628 2.971 13.683 8.36 16.624 5.387 2.941 20.83 4.091 25.792 0s3.226-18.943 1.669-22.929-8.237-14.948-22.53-10.938c-14.292 4.01-12.752 11.615-13.29 17.243M63.107 191.979c-.014-5.185.883-11.771 9.755-15.608s14.432-1.527 18.554 2.512c4.121 4.04 11.84 11.605 7.09 19.527-4.748 7.922-9.372 8.326-19.024 8.94-9.651.614-16.362-10.185-16.375-15.371M65.498 208.136c-7.371.087-19.01 2.735-20.522 13.051-1.513 10.317 3.405 20.912 10.261 22.985s21.786.826 24.876-3.804c3.09-4.631 1.22-15.323-1.44-21.133s-5.803-11.186-13.175-11.099"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M63.772 215.195c-5.54.068-9.924 1.94-10.723 7.99s2.632 13.671 7.136 15.671c4.505 2 14.61.736 16.318-3.523s.43-12.612-1.708-15.874-5.483-4.333-11.023-4.264M66.637 183.559c-.07 3.663 2.394 3.628 5.52 3.728 3.127.1 6.213-1.569 9.234-1.332s7.925 4.592 9.164 7.615c1.24 3.023 3.619 6.368 5.488 4.5s2.114-5.889-.892-10.783-8.279-7.887-13.272-8.136-15.172.745-15.242 4.408M44.024 184.478c.082 2.297 1.682 3.475 3.678 3.179s4.352-3.014 3.011-5.099c-1.34-2.085-3.01-2.221-4.697-2.085-1.688.135-2.956-1.698-2.942-2.621s-.752-2.937-3.66-2.613c-2.908.325-3.078 2.498-5.713 2.613s-4.07-1.335-5.821.115c-1.751 1.451-.075 6.517-1.751 6.194s-2.572.26-2.597 2.724c-.026 2.463 1.568 6.002 4.348 4.95s1.162-3.3 1.14-4.95.078-3.871 3.035-3.27c2.956.601 1.789-1.752 4.232-2.049 2.443-.298 1.803 1.489 3.333 1.879s4.32-1.264 4.404 1.033"
                  clip-rule="evenodd"
                ></path>
                <path
                  fill="currentColor"
                  d="M86.797 123.076c1.535.347 3.03.655 4.723 1.041-.111-1.022-.738-1.609-1.446-1.841-2.124-.699-4.287-1.358-6.492-1.821-1.26-.269-1.935.638-1.55 1.855.618 2.041 1.353 4.043 2.05 6.085.038.117.076.275.155.313.274.196.589.312.903.468.12-.275.398-.552.36-.787-.112-.825-.304-1.611-.457-2.397-.076-.432-.191-.824.01-1.454.47.43.98.861 1.45 1.291 9.319 9.317 11.196 23.344 4.772 35.008-.838 1.497-1.832 2.878-2.749 4.336-.318.512-.598 1.025-.916 1.537.078.118.195.196.273.314.356-.12.83-.161 1.068-.437.833-.869 1.667-1.737 2.383-2.723 7.16-9.78 7.526-23.345.817-33.813-1.288-2-2.931-3.762-4.417-5.603-.313-.392-.665-.705-1.018-1.057-.039-.079.002-.197.081-.315"
                ></path>
              </svg>
            </div>
            <div class="text-center __className_2f4fcf twolisttxt">
              Individual Agents: The foundation of our civilization, capable of
              specialized tasks and self-evolution.
            </div>
          </div>
          <div class="flex items-center">
            <div class="twolist">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="144"
                height="283"
                fill="none"
                viewBox="0 0 144 283"
                class="w-full h-auto"
              >
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="1.5"
                  d="m66.114 134-.36 19.795M73.036 145.457l-7.306 9.472-6.32-9.219"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M17.915 220.864c-7.126 3.043-15.228 10.998-13.737 17.658 1.492 6.659 8.582 17.791 19.021 18.648q10.44.857 14.629.857-1.565 10.837 2.74 15.758c4.308 4.922 19.33 8.514 27.14 7.974s19.372-2.264 25.867-13.124c12.888 1.545 28.444 2.703 32.977-4.1 4.532-6.804 4.194-16.367 1.734-20.807 10.563-3.359 13.942-14.72 7.615-29.45q-5.192-12.087-19.027-11.314.799-20.345-15.303-27.566c-16.102-7.221-34.67 3.644-38.182 9.203-7.139-8.86-26.967-13.734-40.19-4.007s-12.35 23.605-10.404 30.76q1.946 7.155 5.12 9.51"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M25.152 199.057c-.5 5.436 2.329 12.909 10.623 12.705 8.295-.204 12.847-6.496 13.637-11.153s-2.35-13.994-10.977-14.128c-8.626-.133-12.783 7.141-13.283 12.576M69.503 211.761c-7.045.223-12.979 4.427-12.755 12.441s4.768 9.39 12.755 9.472 14.368-5.411 14.142-10.957c-.227-5.545-7.097-11.178-14.142-10.956M76.085 194.204c-.092 6.445 5.273 12.09 12.724 12.122 7.452.031 15.379-4.654 14.756-10.903-.623-6.248-4.68-12.875-13.723-12.275s-13.665 4.611-13.757 11.056M100.708 223.597c.146 6.627 6.616 10.992 13.65 11.376s14.1-4.582 13.592-11.376-3.891-11.787-14.841-11.842-12.548 5.214-12.401 11.842M105.048 242.24c-4.766-1.336-9.993-4.133-12.271 1.781s-.406 16.849 9.6 16.745 16.125-1.567 15.918-10.087-8.481-7.104-13.247-8.439M68.023 272.292c-7.084-.37-13.73-4.441-12.978-11.071.752-6.629 3.332-11.396 12.989-10.631s14.227 4.81 13.174 11.139-6.102 10.933-13.186 10.563M32.461 249.087c-6.23-.607-13.05-6.174-12.618-9.735.431-3.561 2.127-12.894 11.551-12.415 9.425.479 14.46 6.408 14.355 11.068-.106 4.661-7.058 11.689-13.288 11.082"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M85.013 194.772c-.206 2.235 1.898 4.396 4.986 4.218s4.956-2.591 5-4.218-1.938-3.888-5-3.767-4.78 1.533-4.986 3.767M110 223.219c-.058 2.495 2.896 3.817 5.921 3.78 3.024-.037 6.04-1.961 6.078-4.287.037-2.325-2.457-3.761-6.078-3.711s-5.863 1.722-5.921 4.218M99.004 252.985c.039 1.403 3.132 3.415 6.683 2.945 3.551-.469 4.712-2.751 4.195-4.441s-2.886-2.903-6.86-2.356c-3.973.547-4.057 2.45-4.018 3.852M63.107 264.912c1.865 3.021 5.723 2.298 7.52.746 1.797-1.551 1.862-6.404 0-8.249-1.863-1.844-5.387-1.913-7.03 0-1.642 1.914-2.355 4.481-.49 7.503M28.664 242.912c1.119 3.021 3.434 2.298 4.512.746 1.078-1.551 1.117-6.404 0-8.249-1.118-1.844-3.233-1.913-4.218 0s-1.413 4.481-.294 7.503M36.585 203.925c-1.322-.16-3.459-4.425-2.206-6.615 1.252-2.19 4.27-3.213 5.68-1.311s1.085 4.428 0 6.292-2.153 1.795-3.474 1.634M68.368 228.722c2.956.603 5.987-.568 6.933-4.551.947-3.983-.99-6.751-3.13-7.096s-6.397.393-6.992 4.392.233 6.652 3.19 7.255M72.178 60.643c-.965-7.398-.952-16.054 8.276-20.564s17.941-1.314 21.949 2.208c4.007 3.522 10.663 12.039 6.504 20.535-4.158 8.495-11.296 11.782-18.036 11.895S73.143 68.04 72.178 60.643M59.082 66.1c-3.147 1.96-9.619 9.172-6.478 13.78s8.109 9.145 15.753 7.898 11.525-7.355 11.063-10.735S72.802 65.476 68.357 64.8c-4.445-.675-6.127-.66-9.275 1.3M59.66 33.691c3.112 2.38 10.866 5.747 18.32 3.338 7.454-2.41 12.938-11.904 12.174-17.756-.764-5.851-5.496-15.117-13.125-17.155S63.93-.107 55.236 9.798c-8.694 9.906 1.31 21.514 4.423 23.893M115.521 38.844c-4.623 3.724-4.258 8.226-2.725 12.713 1.532 4.488 2.947 9.098 9.53 9.793s12.876-2.395 16.057-5.942c3.18-3.546 7.379-9.99.196-16.565s-18.436-3.722-23.058.001M94.364 79.194c5.07.182 10.382 3.531 13.482 8.539s4.178 14.939-3.1 20.922-14.55 9.411-21.282 5.983c-6.733-3.429-12.78-11.202-11.534-17.04 1.245-5.84 4.848-11.63 9.39-15.054 4.543-3.425 7.974-3.532 13.044-3.35M47.776 82.49c1.09-4.602 2.689-9.768-5.196-14.414-7.886-4.646-14.077-4.71-18.988-1.21-4.91 3.502-11.513 10.341-7.514 16.594s8.174 10.003 15.46 10.408c7.285.406 15.147-6.777 16.238-11.379M34.456 36.385c4.048.004 10.068-1.675 12.161-4.502s3.364-9.762 0-13.902-11.803-4.995-16.327-1.656-6.856 7.913-6.06 12.31 6.177 7.747 10.226 7.75"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M71.965 19.16c2.558-1.099 5.125-2.613 4.238-5.02-.888-2.408-6.263-1.056-8.065 0s-3.55 3.456-1.802 5.02c1.75 1.565 3.07 1.1 5.63 0M88.376 55.55c-1.083-2.543-2.242-6.215.323-7.177 2.566-.963 6.338 1.918 7.173 3.427.834 1.508.707 4.11-.835 5.895-1.543 1.785-5.578.397-6.661-2.145M91.463 99.47c3.985-.96 5.25-3.014 4.844-5.389-.408-2.374-4.018-1.662-7.086-1.196s-4.464 2.937-3.068 4.526c1.396 1.59 1.324 3.021 5.31 2.06M67.02 81.931c1.794-.516 3.237-1.951 3.207-3.61-.029-1.66-2.77-2.82-4.422-1.66-1.65 1.159-1.893 2.24-1.65 3.616.242 1.375 1.07 2.17 2.865 1.654M25.926 50.407c2.027-.761 3.413-2.488 2.457-3.879-.955-1.39-3.566-1.888-5.364-.358-1.797 1.53-2.1 2.742-2.003 4.09s2.883.909 4.91.147M53.862 99.815c-1.235-1.18-3.091-2.09-4.52-1.057-1.427 1.032-.212 2.473.744 3.452s2.455 2.891 3.8 1.512 1.21-2.728-.024-3.907M65.621 58.684c2.088-4.16 2.359-12.461-1.229-16.783s-11.471-7.282-17.952-4.324c-6.481 2.957-8.79 8.606-8.494 12.695s1.402 13.235 9.726 13.98c8.324.744 15.862-1.409 17.95-5.568M93.34 24.627c-.442 4.804 3.077 10.81 5.814 11.675 2.737.864 9.986 3.024 13.916 0 3.931-3.024 6.23-9.94 3.931-14.281s-7.066-8.112-12.413-7.724-10.807 5.527-11.248 10.33M113.606 65.212c5.041-1.627 13.925-1 16.22 3.552s3.608 11.945-2.295 16.277-12.881 4-18.034-1.75-.932-16.452 4.109-18.08"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M64.686 94.598c-4.846-4.502-9.015-5.579-14.313-4.988-5.299.591-10.55 4.044-10.844 9.895-.296 5.851.103 12.174 6.167 14.775s15.065 2.64 19.781-2.601 4.055-12.58-.79-17.081M30.191 58.015c2.52-3.713 5.811-12.305-.64-18.485-6.452-6.18-12.248-5.294-18.912-2.356S-.303 45.885 1.358 51.641c1.661 5.755 5.422 10.08 10.723 11.037s15.59-.95 18.11-4.663M35.744 26.9c1.237.934 6.081.823 6.705-.203s-2.16-2.058-5.221-2.106-2.72 1.376-1.484 2.31M102.721 29.714c-.638-3.412.389-4.035 2.218-3.461s2.789 3.013 1.829 4.375c-.96 1.36-3.408 2.498-4.047-.914M124.079 49.52c-.17-4.036 2.085-6.88 3.679-5.338 1.595 1.54.819 4.22 0 6.41-.818 2.191-.856 3.727-2.353 3.453-1.496-.273-1.155-.49-1.326-4.525M118.396 76.175c1.271-.114 4.378-.88 4.122-2.665s-3.12-2.148-5.259-1.314c-2.138.835-2.698 1.128-2.299 2.382.399 1.253 2.165 1.712 3.436 1.597M51.156 53.954c1.88-.49 4.076-2.657 3.627-3.972s-1.285-2.5-4.638-1.315c-3.353 1.184-3.323 2.71-2.605 3.713s1.736 2.064 3.616 1.574M30.5 77.616c-.596-2.165-.264-4.373 1.553-4.373s4.247 1.226 4.205 2.991c-.043 1.765.676 3.674-.922 4.244-1.599.571-4.24-.696-4.836-2.862"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
            <div class="text-center __className_2f4fcf twolisttxt">
              Collaborative Swarms: Intelligent networks that combine Agents to
              handle complex workflows.
            </div>
          </div>
          <div class="flex items-center">
            <div class="twolist">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="213"
                height="251"
                fill="none"
                viewBox="0 0 213 251"
                class="w-full h-auto"
              >
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M52.895 169.209c2.066 1.857 7.32.776 10.504-2.164s6.044-2.275 10.75-3.079c4.704-.803 10.224-5.675 12.207-11.031s5.392-8.197.257-16.053M90.722 134.25c.44 4.346 1.462 8.407 3.439 6.926s6.041-6.52 5.774-9.044M104.758 136.557c-2.529 1.154-10.218 8.581-9.135 10.705 1.083 2.123 7.756-2.673 9.861-6.207M108.437 144.402c-.957.677-5.456 3.166-5.297 5.989s14.304 1.228 10.667 1.787c-3.636.559-10.362 1.185-14.942 2.411-4.581 1.227-9.912 4.013-8.942 10.885s.642 14.588 9.081 16.009 21.508-2.012 28.794-3.325c7.287-1.312 42.726-6.321 46.749-7.407 4.022-1.085 13.293-5.17 11.743-13.303-1.551-8.133-2.233-12.416-4.478-17.48q-2.245-5.064-.058-10.629M185.52 129.36c-.709 1.387-2.913 2.748-.624 8.401q2.29 5.654 9.197-9.149M196.326 132.085c-1.034 1.947-3.113 4.266-3.882 8.275q-.769 4.01 7.643 1.092M198.567 146.031c-1.867.538-6.433-.724-6.666 2.522-.232 3.246 2.792 9.254-.334 12.928s1.605 3.584 12.988 1.382M203.932 168.068c-6.007.465-15.12 1.035-17.789 3.375-2.668 2.341 4.382 7.716 8.881 8.571q4.5.856 11.215 2.348M205.966 188.36c-3.142-.378-12.867-3.155-11.184.116 1.682 3.272 12.336 10.475 15.888 11.72M207.819 202.911c-2.325-.704-8.659-5.483-8.936-2.744-.277 2.74 4.108 12.434 8.475 14.702M205.244 217.91c-2.54-1.665-8.655-5.601-10.373-12.896-1.719-7.295-3.077-16.301-8.319-20.446s-7.527-10.51-12.83-9.682-37.161 6.9-57.735 9.796c-20.575 2.895-27.851 7.983-35.885 13.752-8.035 5.768-7.9 3.893-13.86 11.668q-5.96 7.774-17.36 16.084M46.887 223.156c2.264-2.02 10.579-8.227 7.31-9.371q-3.268-1.144-9.774 6.494"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M42.872 216.279c1.528-1.254 5.406-6.972 10.269-6.563 4.862.408 11.577-3.394 11.369-10.277-.209-6.884-2.5-19.246-11.388-22.294s-16.212-3.424-20.006 5.905M31.404 172.442c4.436-2.118 6.86-2.806 3.874-5.606a330 330 0 0 0-5.61-5.146M30.985 156.202c3.245 3.427 7.233 8.818 10.43 8.103s-2.342-5.706-3.163-8.052q-.822-2.346-6.253-7.956M40.214 144.37c.038 2.947 1.767 10.865 7.178 16.96s5.35 7.663 6.983 8.314"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M68.067 181.363c.811 4.12 3.584 9.454 8.81 9.317s9.95-3.634 9.949-9.155c0-5.522-4.01-8.847-9.38-9.135-5.369-.289-10.19 4.853-9.38 8.973"
                  clip-rule="evenodd"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M17.323 112.463c.293-3.836.845-9.878 6.088-11.173 5.242-1.295 13.633-4.588 19.378-2.678s11.628-1.706 17.462.02 76.369 15.4 84.395 20.348 10.518 15.625 10.655 21.241c.138 5.617.25 22.133 5.051 26.536M165.463 161.698c-2.75-3.443-8.082-14.248-4.75-15.831q3.333-1.584 7.877 5.831M168.382 142.548c-3.785-2.142-8.162-5.637-8.729-10.453-.567-4.817-4.873-8.612-4.419-11.729s5.804-8.535 7.638-4.276q1.834 4.259 6.226 7.649M172.529 115.26c-2.83-1.276-8.186-2.162-8.046-5.103q.141-2.942 7.04-1.136M175.058 102.72c-2.969.459-7.769 2.554-7.544-1.343s2.699-7.234 6.187-7.07q3.488.165 6.74 3.274M180.795 88.388c-1.722.509-6.03 3.45-6.532.823q-.502-2.625 1.97-8.44M172.003 81.453c-1.348 2.964-2.815 8.34-4.608 8.502q-1.792.162-2.993-7.275M161.006 83.594c.541 3.765 3.82 14.856-.25 19.834s-9.214 8.673-16.206 6.935S72.54 97.92 66.388 93.945c-6.151-3.976 3.105-18.675 12.048-17.985 8.944.691 11.517 12.634 16.136 13.437"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M96.405 84.35c-4.192-1.826-9.051-6.377-7.323-7.704 1.728-1.328 2.378-5.827 11.646-7.11M99.93 64.677c-1.425.496-8.404 2.606-6.228-1.102a39 39 0 0 1 4.965-6.728M95.286 52.152c-1.782 2.312-3.89 12.12-6.206 11.372s1.445-9.644 3.474-13.501M86.926 48.673c-1.045 3.321-.31 16.628-9.205 19.159s-15.33 4.604-19.742 3.186-7.175-6.302-10.926-6.454c-3.75-.152-5.053 2.285-9.741.814-4.688-1.47-8.356-7.59-11.82-14.892q-3.463-7.303-8.22-6.535M17.864 49.06c2.357 2.577 8.591 5.962 6.148 8.754q-2.442 2.793-9.628-4.482M12.708 57.7c6.667 4.692 6.442 3.51 9.973 5.691 3.53 2.181 8.524 6.69 11.741 8.848 3.218 2.157 6.733 12.7 2.576 15.962-4.156 3.26-9.54 5.092-15.403 2.485-5.862-2.607-9.204-6.436-15.276-5.49M7.07 89.849c3.837.96 8.965.053 9.51 2.774q.543 2.722-8.391 4.164M11.109 101.241c1.881-1.517 7.445-3.434 7.537-2.43.093 1.004-4.253 5.941-4.44 9.094"
                ></path>
                <path
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M45.73 83.882c.69 4.58 3.781 8.788 8.603 7.849s7.083-5.857 5.87-10.185c-1.212-4.327-4.119-7.708-8.478-6.696-4.358 1.013-6.685 4.451-5.995 9.032"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
            <div class="text-center __className_2f4fcf twolisttxt">
              Decentralized Ecosystems: Governance through DAOs and
              community-driven growth for a sustainable civilization.
            </div>
          </div>
        </div>
        <div class="flex items-center justify-between twoimgs relative">
          <div class="flex flex-col twoimgsleft">
            <div class="flex items-center twoimgl">
              <div class="twoimg">
                <img
                  src="../assets/slider2-1-dark.svg"
                  alt=""
                  style="width: 13.9275rem; scale: 0.8"
                />
              </div>
              <div class="twoimgtxt">Agent DAO</div>
            </div>
            <div class="flex items-center twoimgl">
              <div class="twoimg">
                <img
                  src="../assets/slider2-2-dark.svg"
                  alt=""
                  style="width: 13.3125rem; scale: 0.8"
                />
              </div>
              <div class="twoimgtxt">
                Agent Lego <br />
                World
              </div>
            </div>
            <div class="flex items-center twoimgl">
              <div class="twoimg">
                <img
                  src="../assets/slider2-3-dark.svg"
                  alt=""
                  style="width: 12.625rem; scale: 0.8"
                />
              </div>
              <div class="twoimgtxt">Agent Swarming</div>
            </div>
          </div>
          <div class="flex-1 text-right">
            <img
              src="../assets/slider2-4-dark.png"
              alt=""
              class="twoimgright"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- Ecosystem -->
    <div class="w-full threebox">
      <div class="container text-center flex flex-col items-center">
        <div class="threestit mb-4">Ecosystem</div>
        <div class="threetit mb-12">Meet the AICell On BNB Chain</div>
        <div class="relative threeimg overflow-hidden mb-12">
          <img
            alt=""
            loading="lazy"
            decoding="async"
            data-nimg="fill"
            class="object-contain irelative"
            style="
              position: absolute;
              height: 100%;
              width: 100%;
              left: 0;
              top: 0;
              right: 0;
              bottom: 0;
              color: transparent;
            "
            src="../assets/slider3-1.png"
          />
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
    </div>
    <!-- foot -->
    <div class="w-full flex justify-center footbox">
      <div class="container flex items-center justify-between">
        <img src="../assets/dark-logo.svg" class="footimg" alt="" /><span
          class="foottxt"
          >Connect and build on the Decentralized AI Finance</span
        >
        <div class="flex items-center gap-6">
          <a
            class="cursor-pointer alink"
            href="https://x.com/AICell_World"
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
            href="https://github.com/AIcell-labs"
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
                d="M12 0c6.63 0 12 5.37 12 12a12.02 12.02 0 0 1-8.175 11.385c-.6.12-.825-.255-.825-.57 0-.405.015-1.695.015-3.3 0-1.125-.375-1.845-.81-2.22 2.67-.3 5.475-1.32 5.475-5.925 0-1.32-.465-2.385-1.23-3.225.12-.3.54-1.53-.12-3.18 0 0-1.005-.33-3.3 1.23-.96-.27-1.98-.405-3-.405s-2.04.135-3 .405c-2.295-1.545-3.3-1.23-3.3-1.23-.66 1.65-.24 2.88-.12 3.18-.765.84-1.23 1.92-1.23 3.225 0 4.59 2.79 5.625 5.46 5.925-.345.3-.66.825-.765 1.605-.69.315-2.415.825-3.495-.99-.225-.36-.9-1.245-1.845-1.23-1.005.015-.405.57.015.795.51.285 1.095 1.35 1.23 1.695.24.675 1.02 1.965 4.035 1.41 0 1.005.015 1.95.015 2.235 0 .315-.225.675-.825.57A11.99 11.99 0 0 1 0 12C0 5.37 5.37 0 12 0"
              ></path></svg
          ></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
/* 公共 */
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

/* 父元素 */
.main {
  padding-top: 14rem;
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

/* 首屏 */
.onebox {
  color: white;
  padding-bottom: 8.125rem;
  z-index: 2;
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
  max-height: 72.75rem;
}

.onebimg {
  width: 80%;
  height: auto;
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
  gap: 9.9375rem;
}

.twolist {
  width: 9.75rem;
  flex-shrink: 0;
}

.twolisttxt {
  width: 13.8125rem;
  font-size: 2.25rem;
  line-height: 96%;
}

.twoimgs {
  gap: 9.9375rem;
  padding-top: 7.5rem;
}

.twoimgsleft {
  width: 30%;
  max-width: 100%;
  gap: 8.625rem;
}

.twoimgl {
  gap: 1.75rem;
}

.twoimg {
  width: 12.5rem;
  flex-shrink: 0;
}

.twoimgtxt {
  font-family: "JustMeAgainDownHere";
  font-size: 1.8rem;
  font-weight: 900;
  line-height: 150%;
}

.twoimgright {
  display: inline;
  max-height: 44.125rem;
  max-width: 100%;
  transform: translate(0, 0) rotate(0) skewX(0) skewY(0) scaleX(0.8) scaleY(0.8);
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

.threeimg {
  width: 62.5rem;
  max-width: 100%;
  overflow: hidden;
  border-radius: 2.5rem;
}

.threetxt {
  width: 64.5rem;
  max-width: 100%;
  font-size: 1.375rem;
  font-weight: 400;
  line-height: 157.091%;
  font-family: "JustMeAgainDownHere";
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
/* foot */
.footbox {
  height: 7.5rem;
  border-top: 0.0625rem solid rgba(234, 238, 245, 0.12);
  background-color: #0f0f0f;
  color: #fff;
}

.footimg {
  width: 7.5rem;
}

.foottxt {
  font-size: 1.125rem;
  font-family: "JustMeAgainDownHere";
}
/* 自适应 */
@media (min-width: 640px) {
  .container {
    max-width: 40rem;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 48rem;
  }
}

@media not all and (min-width: 768px) {
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
  }
}

@media (min-width: 1024px) {
  .container {
    max-width: 64rem;
  }
}

@media (min-width: 1280px) {
  .container {
    max-width: 80rem;
  }
}

@media (min-width: 1536px) {
  .container {
    max-width: 96rem;
  }
}
</style>
