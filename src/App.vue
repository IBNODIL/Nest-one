<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="py-1 px-15 bg-black header d-flex align-center justify-space-between">
    <div class="header-social-media"><v-icon>mdi-twitter</v-icon> <v-icon>mdi-facebook</v-icon> <v-icon>mdi-instagram</v-icon></div>
    <div class=" px-10 header-language"><span class="mx-16">nestone@gmail.com</span> <img src="./assets/img/england.svg" alt=""> <span>English</span></div>
  </div>

  <div class="navbar d-flex align-center justify-space-around pa-5 h-auto">
    <img src="./assets/img/logo.png" alt="logo" class="logo-in-navbar">

    <div id="navbar-links">
      <div>About us</div>
      <div>Our advantage</div>
      <div>Virtual tour</div>
      <div>Entertaiment</div>
      <div>Location</div>
      <div>Contact us</div>
    </div>

    <v-btn class="px-6 bg-black" rounded="xl" size="x-large"><v-icon class="mx-2">mdi-phone-in-talk</v-icon><span>+9987712002288</span></v-btn>
  </div>

  <v-divider></v-divider>

  <div class="my-0 hero d-flex align-center justify-lg-space-between">
    <div class="hero-text pa-3">
      <div class="hero-header text-h3">A brand new style of luxury. Buy your apartment from the tallest building in Central Asia.</div>
      <div class="hero-title text-h6">Pay 25% and move in Ready Apartments & Offices</div>
      <div class="hero-sub-title text-caption">Buy your apartment from the tallest building in Central Asia at affordable prices.</div>
      <div transition="slide-x-transition" class="ma-6 hero-read-more"> <v-btn class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl" size="large">Request and call back</v-btn> <v-btn class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
    </div>
    <img src="./assets/img/hero.png" alt="" class="pa-5 hero-img">
  </div>

  <div class="mt-3 mb-8 position-relative d-flex align-center justify-center">
    <img height="70" class="animation-scroll-down position-absolute" src="./assets/img/rotation.png" alt="">
    <v-icon>mdi-arrow-down-thin</v-icon>
  </div>

  <img id="img-after-scroll-down" src="./assets/img/buildings.png" alt="">

  <div id="about-me" class="pa-16">
    <div id="about-me-text">
      <p class="text-caption">Nest One</p>
      <div class="d-flex">
        <p class="text-h4" style="width: 35%;">About building and benefits investing Nest One</p>
        <p class="text-body-1" style="width: 60%;">After the announcement of the start of construction of the Tashkent City IBC project, Murad Buildings, the developer of Lot 4, has been negotiating with companies from Japan, Singapore, America and other countries for two years. The selection was made in "Ozgüven Mimarlik" company, which previously implemented projects in Turkey and other countries of the world. More than 500 specialists worked in the development of the building project. The design of the skyscraper was developed by the Japanese design organization Nihon Sekkei.</p>
      </div>
    </div>

    <div class="about-me-cards d-flex align-center justify-space-between mt-16">
      <v-sheet
        :elevation="2"
        :height="300"
        :width="300"
        rounded="xl"
        class="about-sheet-hidden bg-blue-grey-lighten-5 d-flex flex-column justify-space-between pa-5"
      >
        <v-icon class="about-sheet-icon-hidden text-h2 "><svg xmlns="http://www.w3.org/2000/svg" width="56" height="56" viewBox="0 0 56 56" fill="none">
  <path d="M48.9997 44.3333H53.6663V49H2.33301V44.3333H6.99967V9.33333C6.99967 8.04468 8.04435 7 9.33301 7H32.6663C33.955 7 34.9997 8.04468 34.9997 9.33333V44.3333H44.333V25.6667H39.6663V21H46.6663C47.955 21 48.9997 22.0447 48.9997 23.3333V44.3333ZM11.6663 11.6667V44.3333H30.333V11.6667H11.6663ZM16.333 25.6667H25.6663V30.3333H16.333V25.6667ZM16.333 16.3333H25.6663V21H16.333V16.3333Z" fill="black"/>
</svg></v-icon>
        <p class="text-h4">The business center of the capital</p>

        <p class="about-card-hidden text-caption">After the announcement of the start of construction of the Tashkent City IBC project, Murad Buildings, the developer of Lot 4, has been negotiating with companies from Japan, Singapore, America and other countries for two years.</p>
      </v-sheet>

      <v-sheet
        :elevation="2"
        :height="300"
        :width="300"
        rounded="xl"
        class="about-sheet-hidden about-sheet-hidden bg-blue-grey-lighten-5 d-flex flex-column justify-space-between pa-5"
      >
        <v-icon class="about-sheet-icon-hidden text-h2 "><svg xmlns="http://www.w3.org/2000/svg" width="56" height="56" viewBox="0 0 56 56" fill="none">
  <path d="M28 55.3652L13.1508 40.5161C4.94975 32.3149 4.94975 19.0185 13.1508 10.8175C21.3518 2.61649 34.6481 2.61649 42.8493 10.8175C51.0503 19.0185 51.0503 32.3149 42.8493 40.5161L28 55.3652ZM39.5493 37.216C45.9279 30.8376 45.9279 20.4959 39.5493 14.1173C33.1709 7.73877 22.8291 7.73877 16.4506 14.1173C10.072 20.4959 10.072 30.8376 16.4506 37.216L28 48.7656L39.5493 37.216ZM28 30.3334C25.4226 30.3334 23.3333 28.2441 23.3333 25.6667C23.3333 23.0894 25.4226 21.0001 28 21.0001C30.5774 21.0001 32.6667 23.0894 32.6667 25.6667C32.6667 28.2441 30.5774 30.3334 28 30.3334Z" fill="black"/>
</svg></v-icon>
        <p class="text-h4">At the center of the Tashkent city</p>
        <p class="about-card-hidden text-caption">After the announcement of the start of construction of the Tashkent City IBC project, Murad Buildings, the developer of Lot 4, has been negotiating with companies from Japan, Singapore, America and other countries for two years.</p>

      </v-sheet>

      <v-sheet
        :elevation="2"
        :height="300"
        :width="300"
        rounded="xl"
        class="about-sheet-hidden  bg-blue-grey-lighten-5 d-flex flex-column justify-space-between pa-5"
      > 
        <v-icon class="about-sheet-icon-hidden text-h2 "><svg xmlns="http://www.w3.org/2000/svg" width="56" height="56" viewBox="0 0 56 56" fill="none">
  <path d="M49.0003 49H7.00033C5.71167 49 4.66699 47.9554 4.66699 46.6667V29.1359C4.66699 28.4615 4.95868 27.8201 5.46691 27.377L14.0003 19.9368V9.33333C14.0003 8.04468 15.045 7 16.3337 7H49.0003C50.289 7 51.3337 8.04468 51.3337 9.33333V46.6667C51.3337 47.9554 50.289 49 49.0003 49ZM21.0003 44.3333H28.0003V30.1971L18.667 22.0594L9.33366 30.1971V44.3333H16.3337V35H21.0003V44.3333ZM32.667 44.3333H46.667V11.6667H18.667V16.6303C19.214 16.6303 19.761 16.8219 20.2004 17.2049L31.8671 27.377C32.3753 27.8201 32.667 28.4615 32.667 29.1359V44.3333ZM37.3337 25.6667H42.0003V30.3333H37.3337V25.6667ZM37.3337 35H42.0003V39.6667H37.3337V35ZM37.3337 16.3333H42.0003V21H37.3337V16.3333ZM28.0003 16.3333H32.667V21H28.0003V16.3333Z" fill="black"/>
</svg></v-icon>
        <p class="text-h4">Superior coomfort and coziness</p>
        <p class="about-card-hidden text-caption">After the announcement of the start of construction of the Tashkent City IBC project, Murad Buildings, the developer of Lot 4, has been negotiating with companies from Japan, Singapore, America and other countries for two years.</p>

      </v-sheet>

      <v-sheet
        :elevation="2"
        :height="300"
        :width="300"
        rounded="xl"
        class="about-sheet-hidden bg-blue-grey-lighten-5 d-flex flex-column justify-space-between pa-5"
      >
        <v-icon class="about-sheet-icon-hidden text-h2 "><svg xmlns="http://www.w3.org/2000/svg" width="56" height="56" viewBox="0 0 56 56" fill="none">
<path d="M46.6667 7.24829C47.9554 7.24829 49 8.29295 49 9.58162V46.9148C49 48.2035 47.9554 49.2482 46.6667 49.2482H9.33333C8.04468 49.2482 7 48.2035 7 46.9148V9.58162C7 8.29295 8.04468 7.24829 9.33333 7.24829H46.6667ZM26.1072 30.9513L11.6667 33.4958V44.5815H28.5087L26.1072 30.9513ZM44.3333 11.915H27.489L33.2477 44.5815H44.3333V11.915ZM22.75 11.915H11.6667V28.7568L25.2968 26.3556L22.75 11.915Z" fill="black"/>
</svg></v-icon>
        <p class="text-h4">Developed infrastructure</p>
        <p class="about-card-hidden text-caption">After the announcement of the start of construction of the Tashkent City IBC project, Murad Buildings, the developer of Lot 4, has been negotiating with companies from Japan, Singapore, America and other countries for two years.</p>

      </v-sheet>
    </div>
  </div>

  <div class="vr-tours d-flex align-center flex-column bg-black pa-5 py-16">
    <p class="text-caption my-3">Virtual tour</p>
    <p class="text-h4 mb-6">Nest One rooms and plans</p>
    <div class="vr-tour-buttons">
      <v-btn rounded="xl" class="ma-2 py-5 d-inline-flex" size="small">Nest+1</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+2</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+2,Comfort</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+3</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+3,Comfort</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+4</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+5</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+5,Comfort</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+6</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+6,Comfort</v-btn>
      <v-btn rounded="xl" variant="tonal" class="ma-2 py-5 d-inline-flex" size="small">Nest+8,Comfort</v-btn>
    </div>
    <div class="vr-tour-img px-14 mt-2 position-relative">
      <img style="width: 100%;" src="./assets/img/vr-bg.png" alt="">
      <div class="text-in-vr-img position-absolute d-flex flex-column align-center">
        <p class="text-subtitle-2 my-5">Use VR headset to see real rooms or use virtual mode</p>
        <svg xmlns="http://www.w3.org/2000/svg" width="804" height="384" viewBox="0 0 804 384" fill="none">
          <mask id="path-1-outside-1_20_1236" maskUnits="userSpaceOnUse" x="0" y="0" width="804" height="384" fill="black">
            <rect fill="white" width="804" height="384"/>
            <path fill-rule="evenodd" clip-rule="evenodd" d="M15 79.8864C15 67.9811 19.2962 56.4756 27.0993 47.484C34.274 39.2166 43.9824 33.5231 54.7499 31.5515C114.877 20.5419 175.89 15 237.04 15H401.835H401.881H566.677C627.827 15 688.839 20.5419 748.967 31.5515C759.734 33.5231 769.443 39.2166 776.617 47.484C784.42 56.4756 788.717 67.9811 788.717 79.8864V313.577C788.717 328.257 782.893 342.337 772.523 352.728C762.126 363.146 748.012 369 733.294 369H564.897C546.526 369 528.908 361.692 515.931 348.689C502.953 335.685 485.336 328.377 466.964 328.377L401.881 328.377L401.835 328.377L336.753 328.377C318.381 328.377 300.764 335.685 287.786 348.689C274.808 361.692 257.191 369 238.819 369H70.4225C55.7043 369 41.5905 363.146 31.1936 352.728C20.8239 342.337 15 328.257 15 313.577V79.8864Z"/>
          </mask>
          <path fill-rule="evenodd" clip-rule="evenodd" d="M15 79.8864C15 67.9811 19.2962 56.4756 27.0993 47.484C34.274 39.2166 43.9824 33.5231 54.7499 31.5515C114.877 20.5419 175.89 15 237.04 15H401.835H401.881H566.677C627.827 15 688.839 20.5419 748.967 31.5515C759.734 33.5231 769.443 39.2166 776.617 47.484C784.42 56.4756 788.717 67.9811 788.717 79.8864V313.577C788.717 328.257 782.893 342.337 772.523 352.728C762.126 363.146 748.012 369 733.294 369H564.897C546.526 369 528.908 361.692 515.931 348.689C502.953 335.685 485.336 328.377 466.964 328.377L401.881 328.377L401.835 328.377L336.753 328.377C318.381 328.377 300.764 335.685 287.786 348.689C274.808 361.692 257.191 369 238.819 369H70.4225C55.7043 369 41.5905 363.146 31.1936 352.728C20.8239 342.337 15 328.257 15 313.577V79.8864Z" fill="white" fill-opacity="0.3"/>
          <path d="M401.881 328.377V313.377H401.871L401.881 328.377ZM401.835 328.377V343.377H401.845L401.835 328.377ZM336.753 328.377V343.377V328.377ZM772.523 352.728L761.906 342.132L772.523 352.728ZM748.967 31.5515L746.265 46.3062L748.967 31.5515ZM776.617 47.484L765.288 57.3155L776.617 47.484ZM515.931 348.689L505.313 359.284L515.931 348.689ZM237.04 0C174.984 0 113.067 5.62403 52.0482 16.7968L57.4515 46.3062C116.688 35.4598 176.796 30 237.04 30V0ZM401.835 0H237.04V30H401.835V0ZM401.835 30H401.881V0H401.835V30ZM401.881 30H566.677V0H401.881V30ZM566.677 30C626.921 30 687.029 35.4597 746.265 46.3062L751.668 16.7968C690.65 5.62402 628.733 0 566.677 0V30ZM773.717 79.8864V313.577H803.717V79.8864H773.717ZM733.294 354H564.897V384H733.294V354ZM466.964 313.377L401.881 313.377V343.377L466.964 343.377L466.964 313.377ZM401.871 313.377L401.825 313.377L401.845 343.377L401.891 343.377L401.871 313.377ZM336.753 343.377L401.835 343.377V313.377L336.753 313.377V343.377ZM70.4225 384H238.819V354H70.4225V384ZM0 79.8864V313.577H30V79.8864H0ZM41.8108 342.132C34.2477 334.553 30 324.284 30 313.577H0C0 332.23 7.4001 350.121 20.5763 363.324L41.8108 342.132ZM70.4225 354C59.6878 354 49.3938 349.73 41.8108 342.132L20.5763 363.324C33.7872 376.561 51.7208 384 70.4225 384V354ZM277.169 338.093C267.005 348.277 253.208 354 238.819 354V384C261.175 384 282.612 375.108 298.403 359.284L277.169 338.093ZM336.753 313.377C314.398 313.377 292.961 322.269 277.169 338.093L298.403 359.284C308.567 349.1 322.365 343.377 336.753 343.377V313.377ZM564.897 354C550.509 354 536.712 348.277 526.548 338.093L505.313 359.284C521.105 375.108 542.542 384 564.897 384V354ZM761.906 342.132C754.323 349.73 744.029 354 733.294 354V384C751.996 384 769.93 376.561 783.14 363.324L761.906 342.132ZM773.717 313.577C773.717 324.284 769.469 334.553 761.906 342.132L783.14 363.324C796.317 350.121 803.717 332.23 803.717 313.577H773.717ZM765.288 57.3155C770.724 63.5788 773.717 71.5934 773.717 79.8864H803.717C803.717 64.3688 798.117 49.3724 787.946 37.6526L765.288 57.3155ZM746.265 46.3062C753.554 47.6408 760.26 51.5217 765.288 57.3155L787.946 37.6526C778.625 26.9115 765.915 19.4054 751.668 16.7968L746.265 46.3062ZM15.7705 37.6526C5.59979 49.3724 0 64.3688 0 79.8864H30C30 71.5934 32.9927 63.5789 38.4282 57.3155L15.7705 37.6526ZM526.548 338.093C510.756 322.269 489.319 313.377 466.964 313.377L466.964 343.377C481.352 343.377 495.149 349.1 505.313 359.284L526.548 338.093ZM38.4282 57.3155C43.4562 51.5217 50.1629 47.6408 57.4515 46.3062L52.0482 16.7968C37.8018 19.4054 25.0918 26.9115 15.7705 37.6526L38.4282 57.3155Z" fill="white" fill-opacity="0.5" mask="url(#path-1-outside-1_20_1236)"/>
        </svg>
        <v-chip prepend-icon="mdi-close"> Close VR </v-chip>
      </div>

      <div class="addons-for-vr-tour">
          <div class="addons-for-vr-tour-part">
            <v-icon class="ma-1">
              <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28" fill="none">
                <path d="M14 2.33325L18.9497 7.283L17.2998 8.93291L14 5.63309L10.7001 8.93291L9.05023 7.283L14 2.33325ZM2.33331 13.9999L7.28306 9.05017L8.93297 10.7001L5.63315 13.9999L8.93297 17.2997L7.28306 18.9496L2.33331 13.9999ZM25.6666 13.9999L20.7169 18.9496L19.0669 17.2997L22.3668 13.9999L19.0669 10.7001L20.7169 9.05017L25.6666 13.9999ZM14 16.3333C12.7113 16.3333 11.6666 15.2886 11.6666 13.9999C11.6666 12.7112 12.7113 11.6666 14 11.6666C15.2887 11.6666 16.3333 12.7112 16.3333 13.9999C16.3333 15.2886 15.2887 16.3333 14 16.3333ZM14 25.6666L9.05023 20.7169L10.7001 19.0669L14 22.3668L17.2998 19.0669L18.9497 20.7169L14 25.6666Z" fill="white"/>
              </svg>
            </v-icon>

            <v-icon class="ma-1">
              <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28" fill="none">
                <path d="M14 25.6666C7.55669 25.6666 2.33334 20.4432 2.33334 13.9999C2.33334 7.55659 7.55669 2.33325 14 2.33325C20.4433 2.33325 25.6667 7.55659 25.6667 13.9999C25.6667 20.4432 20.4433 25.6666 14 25.6666ZM14 23.3333C19.1547 23.3333 23.3333 19.1546 23.3333 13.9999C23.3333 8.84526 19.1547 4.66659 14 4.66659C8.84535 4.66659 4.66668 8.84526 4.66668 13.9999C4.66668 19.1546 8.84535 23.3333 14 23.3333ZM12.3922 9.81694L18.0843 13.6117C18.2987 13.7546 18.3567 14.0444 18.2137 14.2588C18.1795 14.31 18.1355 14.354 18.0843 14.3882L12.3922 18.1829C12.1778 18.3259 11.888 18.2679 11.7451 18.0535C11.694 17.9769 11.6667 17.8868 11.6667 17.7946V10.2052C11.6667 9.94749 11.8756 9.73856 12.1333 9.73856C12.2255 9.73856 12.3156 9.76583 12.3922 9.81694Z" fill="white"/>
              </svg>
            </v-icon>

            <v-icon class="ma-1">
              <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28" fill="none">
                <path d="M11.6667 11.7964V1.16675L24.5 8.16675V24.5001H3.5V8.16675L11.6667 11.7964ZM14 5.09734V15.3868L5.83333 11.7572V22.1667H22.1667V9.5519L14 5.09734Z" fill="white"/>
              </svg>
            </v-icon>
          </div>
          
          <div class="addons-for-vr-tour-part">
            <v-icon class="ma-1">
              <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28" fill="none">
                <path d="M15.3069 19.8599L10.4082 17.1877C9.55655 18.0978 8.34469 18.6666 6.99998 18.6666C4.42265 18.6666 2.33331 16.5772 2.33331 13.9999C2.33331 11.4226 4.42265 9.33325 6.99998 9.33325C8.34462 9.33325 9.55644 9.90196 10.408 10.812L15.3069 8.1399C15.2153 7.77506 15.1666 7.39317 15.1666 6.99992C15.1666 4.42259 17.256 2.33325 19.8333 2.33325C22.4106 2.33325 24.5 4.42259 24.5 6.99992C24.5 9.57725 22.4106 11.6666 19.8333 11.6666C18.4886 11.6666 17.2768 11.0978 16.4251 10.1878L11.5264 12.8599C11.618 13.2247 11.6666 13.6066 11.6666 13.9999C11.6666 14.3932 11.618 14.7751 11.5264 15.1399L16.4252 17.812C17.2768 16.902 18.4886 16.3333 19.8333 16.3333C22.4106 16.3333 24.5 18.4226 24.5 20.9999C24.5 23.5772 22.4106 25.6666 19.8333 25.6666C17.256 25.6666 15.1666 23.5772 15.1666 20.9999C15.1666 20.6066 15.2153 20.2247 15.3069 19.8599ZM6.99998 16.3333C8.28864 16.3333 9.33331 15.2886 9.33331 13.9999C9.33331 12.7112 8.28864 11.6666 6.99998 11.6666C5.71131 11.6666 4.66665 12.7112 4.66665 13.9999C4.66665 15.2886 5.71131 16.3333 6.99998 16.3333ZM19.8333 9.33325C21.122 9.33325 22.1666 8.28858 22.1666 6.99992C22.1666 5.71125 21.122 4.66659 19.8333 4.66659C18.5446 4.66659 17.5 5.71125 17.5 6.99992C17.5 8.28858 18.5446 9.33325 19.8333 9.33325ZM19.8333 23.3333C21.122 23.3333 22.1666 22.2886 22.1666 20.9999C22.1666 19.7112 21.122 18.6666 19.8333 18.6666C18.5446 18.6666 17.5 19.7112 17.5 20.9999C17.5 22.2886 18.5446 23.3333 19.8333 23.3333Z" fill="white"/>
              </svg>
            </v-icon>

            <v-icon class="ma-1">
              mdi-safety-goggles
            </v-icon>

            <v-icon class="ma-1">
              <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 28 28" fill="none">
                <path d="M9.33337 3.5V5.83333H4.66671V10.5H2.33337V3.5H9.33337ZM2.33337 24.5V17.5H4.66671V22.1667H9.33337V24.5H2.33337ZM25.6667 24.5H18.6667V22.1667H23.3334V17.5H25.6667V24.5ZM25.6667 10.5H23.3334V5.83333H18.6667V3.5H25.6667V10.5Z" fill="white"/>
              </svg>
            </v-icon>
          </div>
      </div>

      <div class="text-in-vr-tour d-flex py-10 px-16 flex-column">
        <p class="text-h3 mb-16">If you would like more information about the rooms, please contact us now</p>
        <div transition="slide-x-transition" class="ma-6 hero-read-more"> <v-btn variant="outlined" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl" variant="outlined" size="large">Request and call back</v-btn> <v-btn variant="outlined" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
      </div>
    </div>
  </div>

  <div class="projects d-flex align-center flex-column my-16">
    <div class="text-caption">Beautiful projects</div>
    <div class="text-h4">Our projects</div>

    <div class="d-flex ma-5 align-center">
      <v-card class="d-flex pa-5 align-center rounded-xl mx-16">
        <img src="./assets/img/card-1-logo.png" style="height: 100%;" alt="">
        <v-divider class="mx-10" vertical></v-divider>
        <div class="projects-card-texts">
          <p class="text-h4">Nest One apartments</p>
          <p class="text-body" style="width: 500px;">Corem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. </p>
          
          <v-expand-x-transition>
            <div transition="slide-x-transition" class="hero-read-more mt-5"> <v-btn size="small" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl">Request and call back</v-btn> <v-btn size="small" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        
          </v-expand-x-transition>
        </div>
      </v-card>
      <img style="height: 230px;" src="./assets/img/card-1-photo.png" alt="">
    </div>

    <div class="d-flex ma-5 align-center">
      <v-card class="d-flex pa-5 align-center rounded-xl mx-16">
        <img src="./assets/img/card-2-logo.png" style="height: 100%;" alt="">
        <v-divider class="mx-10" vertical></v-divider>
        <div class="projects-card-texts">
          <p class="text-h4">Gala by Nest One</p>
          <p class="text-body" style="width: 500px;">Corem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. </p>
          <div transition="slide-x-transition" class="hero-read-more mt-5"> <v-btn size="small" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl">Request and call back</v-btn> <v-btn size="small" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>
      </v-card>
      <img style="height: 230px;" src="./assets/img/card-2-photo.png" alt="">
    </div>

    <div class="d-flex ma-5 align-center">
      <v-card class="d-flex pa-5 align-center rounded-xl mx-16">
        <img src="./assets/img/card-3-logo.png" style="height: 100%;" alt="">
        <v-divider class="mx-10" vertical></v-divider>
        <div class="projects-card-texts">
          <p class="text-h4">Nest One Offices</p>
          <p class="text-body" style="width: 500px;">Corem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. </p>
          <div transition="slide-x-transition" class="hero-read-more mt-5"> <v-btn size="small" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl">Request and call back</v-btn> <v-btn size="small" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>
      </v-card>
      <img style="height: 230px;" src="./assets/img/card-3-photo.png" alt="">
    </div>

    <div class="d-flex ma-5 align-center">
      <v-card class="d-flex pa-5 align-center rounded-xl mx-16">
        <img src="./assets/img/card-4-logo.png" style="height: 100%;" alt="">
        <v-divider class="mx-10" vertical></v-divider>
        <div class="projects-card-texts">
          <p class="text-h4">Nest One Teracce</p>
          <p class="text-body" style="width: 500px;">Corem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. </p>
          <div transition="slide-x-transition" class="hero-read-more mt-5"> <v-btn size="small" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl">Request and call back</v-btn> <v-btn size="small" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>
      </v-card>
      <img style="height: 230px;" src="./assets/img/card-4-photo.png" alt="">
    </div>

    <div class="d-flex ma-5 align-center">
      <v-card class="d-flex pa-5 align-center rounded-xl mx-16">
        <img src="./assets/img/card-5-logo.png" style="height: 100%;" alt="">
        <v-divider class="mx-10" vertical></v-divider>
        <div class="projects-card-texts">
          <p class="text-h4">Nest One Smart</p>
          <p class="text-body" style="width: 500px;">Corem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. </p>
          <div transition="slide-x-transition" class="hero-read-more mt-5"> <v-btn size="small" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl">Request and call back</v-btn> <v-btn size="small" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>
      </v-card>
      <img style="height: 230px;" src="./assets/img/card-5-photo.png" alt="">
    </div>
  </div>

  <div class="beautiful-projects bg-black d-flex flex-column align-center pt-8 pb-16 px-16">
    <div class="text-body-2 mt-10">Beautiful projects</div>
    <div class="text-h4 ma-2">Nest One's most cozy places</div>
    <div class="d-flex justify-space-around">
      <div class="text d-flex flex-column justify-space-between pr-10">
        <div>
          <p class="text-h5 my-5">Nest One terraces tour</p>
          <p class="text-body-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu turpis molestie, dictum est a, mattis tellus. Sed dignissim, metus nec fringilla accumsan, risus sem sollicitudin lacus, ut interdum tellus elit sed risus. Maecenas eget condimentum velit, sit amet feugiat lectus.</p> 
          <p class="text-body-2">Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Praesent auctor purus luctusenim egestas, ac scelerisque ante pulvinar. Donec ut rhoncus ex. Suspendisse ac rhoncus nisl, eu tempor urna. </p>
          <p class="text-body-2">Curabitur vel bibendum lorem. </p>
          <p class="text-body-2">Morbi convallis convallis diam sit amet lacinia. </p>
          <p class="text-body-2">Aliquam in elementum tellus.</p>
        </div>

        <div class="d-flex align-center">
          <p class="text-body">01<span class="text-caption">/04</span></p>
          <v-progress-linear color="grey-lighten-1" model-value="25"></v-progress-linear>
          <v-btn class="bg-grey-darken-4" variant="tonal" rounded="xl" icon="mdi-arrow-left"></v-btn>
          <v-btn class="bg-grey-darken-4" rounded="xl" icon="mdi-arrow-right"></v-btn>
        </div>
      </div>

      <div class="video">
        <img style="height: 400px;" src="./assets/img/about-pplace-video.png" alt="">
        <div id="video-in-beautiful-projects">
          <div class="d-flex flex-column">
            <div class="d-flex flex-row justify-space-between">
              <div>
                <v-icon class="mr-2">
                    <svg xmlns="http://www.w3.org/2000/svg" width="14" height="18" viewBox="0 0 14 18" fill="none">
                      <path d="M12.532 9.31173L4.58301 14.6111C4.41069 14.726 4.17786 14.6794 4.06298 14.5071C4.02192 14.4455 4 14.3731 4 14.2991V3.70044C4 3.49333 4.16789 3.32544 4.375 3.32544C4.44903 3.32544 4.52142 3.34735 4.58301 3.38842L12.532 8.68773C12.7043 8.80263 12.7509 9.03543 12.636 9.20778C12.6085 9.24895 12.5732 9.28428 12.532 9.31173Z" fill="white"/>
                    </svg>
                </v-icon>
                <p class="d-inline-block text-caption">0:01 / 0:24</p>
              </div>

              <div>
                <v-icon>
                  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18" fill="none">
                    <path d="M14.5416 2.37088L15.6023 3.43153L13.7456 5.28716L15.6023 7.14385L13.7456 8.99947L15.6023 10.8562L13.7461 12.7123L15.6023 14.5684L14.5416 15.6291L11.6248 12.7123L13.481 10.8562L11.6248 9L13.481 7.14385L11.6248 5.28769L14.5416 2.37088ZM9.74978 14.9587C9.74978 15.1657 9.58185 15.3337 9.37478 15.3337C9.28823 15.3337 9.2043 15.3037 9.13733 15.2489L5.16651 11.9993L2.24976 12C1.83555 12 1.49976 11.6642 1.49976 11.25V6.75C1.49976 6.33579 1.83555 6.00001 2.24976 6.00001L4.18747 5.99821L1.35547 3.16637L2.41613 2.10571L9.74948 9.4392L9.74978 14.9587ZM9.66503 2.80388C9.71978 2.87088 9.74978 2.95478 9.74978 3.04135V7.31787L6.96126 4.53013L9.13733 2.75111C9.2976 2.61996 9.53385 2.64359 9.66503 2.80388Z" fill="white"/>
                  </svg>
                </v-icon>

                <v-icon>
                  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18" fill="none">
                    <path d="M6 2.25V3.75H3V6.75H1.5V2.25H6ZM1.5 15.75V11.25H3V14.25H6V15.75H1.5ZM16.5 15.75H12V14.25H15V11.25H16.5V15.75ZM16.5 6.75H15V3.75H12V2.25H16.5V6.75Z" fill="white"/>
                  </svg>
                </v-icon>

                <v-icon>
                  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18" fill="none">
                    <path d="M9 2.25C8.175 2.25 7.5 2.925 7.5 3.75C7.5 4.575 8.175 5.25 9 5.25C9.825 5.25 10.5 4.575 10.5 3.75C10.5 2.925 9.825 2.25 9 2.25ZM9 12.75C8.175 12.75 7.5 13.425 7.5 14.25C7.5 15.075 8.175 15.75 9 15.75C9.825 15.75 10.5 15.075 10.5 14.25C10.5 13.425 9.825 12.75 9 12.75ZM9 7.5C8.175 7.5 7.5 8.175 7.5 9C7.5 9.825 8.175 10.5 9 10.5C9.825 10.5 10.5 9.825 10.5 9C10.5 8.175 9.825 7.5 9 7.5Z" fill="white"/>
                  </svg>
                </v-icon>
              </div>
            </div>

            <v-progress-linear color="grey-lighten-1" model-value="15"></v-progress-linear>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="partners">
    <div class="part-1 d-flex">
      <img class="d-inline ma-8" src="./assets/img/partenrs-6.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-1.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-2.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-3.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-4.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-5.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-6.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-1.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-2.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-3.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-4.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-5.png" alt="">
      <img class="d-inline ma-8" src="./assets/img/partenrs-6.png" alt="">  
      <img class="d-inline ma-8" src="./assets/img/partenrs-1.png" alt="">
    </div>
  </div>

  <div class="bg-grey-lighten-3 our-advantage py-16 d-flex align-center flex-column">
    <div class="mb-6 d-flex align-center flex-column">
      <p class="text-caption">Our advantage</p>
      <p class="text-h4">Entertaiments</p>

      <div class="cards d-flex align-center justify-space-evenly flex-wrap">

        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-1.png" width="300" alt="">
          <p class="text-h4">Longue Terraces</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>

        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-2.png" width="300" alt="">
          <p class="text-h4">Nest One Cinema</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>
        
        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-3.png" width="300" alt="">
          <p class="text-h4">Metting Room</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>

        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-4.png" width="300" alt="">
          <p class="text-h4">Children's Room</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>

        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-5.png" width="300" alt="">
          <p class="text-h4">Library</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>

        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-6.png" width="300" alt="">
          <p class="text-h4">Hall For Guests</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>
        
        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-7.png" width="300" alt="">
          <p class="text-h4">Sky Walk</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>

        <div class="card ma-8 d-inline-block" style="width: 300px;">
          <img src="./assets/img/room-8.png" width="300" alt="">
          <p class="text-h4">Trainig Hall</p>
          <p class="text-subtitle-1 pa-2 d-inline-block">
            Rorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis. Class aptent taciti sociosqu.
          </p>
          <div transition="slide-x-transition" class="hero-read-more"> <v-btn variant="outline" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <div class="d-inline-block">Read more</div> <v-btn variant="outline" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
        </div>

      </div>
    </div>

    <v-card rounded="xl" class="position-relative mt-16 mb-5 mx-10 d-flex justify-space-between pa-0" style="width: 80%;">
      <div class="d-flex pa-5 flex-column justify-space-between" style="width: 400px; height: 300px;">
      <div class="text-h5">
        To get answers to the questions, contact us now by telegram!
      </div>

      <div class="d-flex align-center">
        <v-icon class="mx-10">
          <img src="./assets/img/operator.svg" alt="">
        </v-icon>
        <div>
          <p class="text-body-1">Anna Alexandra</p>
          <p class="text-caption">Adminstrator</p>
        </div>
      </div>

      <div transition="slide-x-transition" class="ma-6 hero-read-more"> <v-btn size="small" class="callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn rounded="xl" ><v-icon class="mr-2" color="blue"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telegram" viewBox="0 0 16 16">  <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.287 5.906c-.778.324-2.334.994-4.666 2.01-.378.15-.577.298-.595.442-.03.243.275.339.69.47l.175.055c.408.133.958.288 1.243.294.26.006.549-.1.868-.32 2.179-1.471 3.304-2.214 3.374-2.23.05-.012.12-.026.166.016.047.041.042.12.037.141-.03.129-1.227 1.241-1.846 1.817-.193.18-.33.307-.358.336a8.154 8.154 0 0 1-.188.186c-.38.366-.664.64.015 1.088.327.216.589.393.85.571.284.194.568.387.936.629.093.06.183.125.27.187.331.236.63.448.997.414.214-.02.435-.22.547-.82.265-1.417.786-4.486.906-5.751a1.426 1.426 0 0 0-.013-.315.337.337 0 0 0-.114-.217.526.526 0 0 0-.31-.093c-.3.005-.763.166-2.984 1.09z"/></svg></v-icon> Request and call back</v-btn> <v-btn size="small" class="callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
    
      </div>

      <div>
        <img height="300" class="pa-3 position-absolute" src="./assets/img/operators.png" alt="">
      </div>
    </v-card>
  </div>

  <div class="gallery py-16 d-flex flex-column align-center">
    <p class="text-caption">Beautiful projects</p>
    <p class="text-h4 mb-5">Gallery</p>
    <div id="our-advantege">
    <div class="gallery-part-1 gallery-animation d-flex">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-1.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-2.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-3.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-4.png" alt="">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-1.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-2.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-3.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-4.png" alt="">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-1.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-2.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-3.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-4.png" alt="">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-1.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-2.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-3.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-4.png" alt="">
    </div>

    <div class="gallery-part-2 gallery-animation d-flex">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-5.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-6.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-7.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-8.png" alt="">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-5.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-6.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-7.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-8.png" alt="">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-5.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-6.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-7.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-8.png" alt="">
      <img class="d-inline ma-2" style="width: 600px; height: 361px;" src="./assets/img/gallery-img-5.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-6.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-7.png" alt="">
      <img class="d-inline ma-2" src="./assets/img/gallery-img-8.png" alt="">
    </div>
  </div>
  </div>  

  <div class="locatio my-16 px-10 py-5 d-flex align-center flex-column">
    <p class="text-caption">View via map</p>
    <p class="text-h4">Location</p>
    <div class=" mt-10 mb-3 d-flex align-center justify-space-between">
      <v-btn class="mx-2 bg-black" rounded="xl">Nest One mainly building</v-btn>
      <v-btn class="mx-2" rounded="xl">Nest One garden</v-btn>
      <v-btn class="mx-2" rounded="xl">Entrance gate</v-btn>
      <v-btn class="mx-2" rounded="xl">Nearest bank</v-btn>
      <v-btn class="mx-2" rounded="xl">Nearest restaurant</v-btn>
      <v-btn class="mx-2" rounded="xl">Hilton</v-btn>
    </div>

    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2996.8360318298583!2d69.2512813171222!3d41.31243052262696!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38ae8b587a25915d%3A0x6b11bea07f51d72c!2sNEST%20ONE!5e0!3m2!1suz!2s!4v1699165158634!5m2!1suz!2s" width="1200" height="550" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>

  <v-divider></v-divider>

  <div class="my-10 px-15 py-10 contact-with-me d-flex justify-space-between">
    <div class="pa-5 d-flex flex-column justify-space-between">
      <div>
        <p class="text-caption">Feel free to apply</p>
        <p class="text-h4">Request a call back</p>
      </div>

      <div>
        <p class="text-h6">Get a Call Back From the Nest One Specialist</p>

        <v-text-field clearable variant="outlined" label="Full name"></v-text-field>
        <v-text-field clearable variant="outlined" label="Phone number"></v-text-field>
        <v-text-field clearable variant="outlined" label="E-mail adres"></v-text-field>

      <div transition="slide-x-transition" class="ma-6 hero-read-more"> <v-btn variant="outlined" size="small" class="black callbeck-1" icon="mdi-arrow-top-right"></v-btn> <v-btn variant="outlined" rounded="xl">Request and call back</v-btn> <v-btn variant="outlined" size="small" class="black callbeck-2" icon="mdi-arrow-top-right"></v-btn> </div>
      </div>

      <div>
        <v-divider></v-divider>

      <div class="text-body-1">Feel free to contact us with any questions or suggestions, we are always ready to serve you, we appreciate you</div>
    
      </div>
    </div>

    <img src="./assets/img/operator-2.png" style="width: 50%;" alt="">
  </div>

  <div class="bg-black d-flex flex-column pa-10">
    <div class="my-16 d-flex align-center justify-lg-space-evenly">
      <div class="d-inline-flex flex-column pa-5 bg-grey-darken-4 rounded-lg">
        <img width="100" src="./assets/img/logo.png" alt="">
        <p class="my-2 text-caption">A brand new style of luxury. Buy your apartment <br> from the tallest building in Central Asia at <br> affordable prices.</p>
      </div>

      <div>
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">About us</p>
        </div>

        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Projects</p>
        </div>

        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Launches</p>
        </div>
      </div>

      <div>
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Virtual tour</p>
        </div>
      
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Available units</p>
        </div>
      
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Masterplan</p>
        </div>
      </div>

      <div>
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Virtual tour</p>
        </div>
      
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Available units</p>
        </div>
      
        <div class="d-flex flex-row footer-link">
          <span class="footer-links-icon ml-2 mt-2"> <v-icon>mdi-arrow-top-right</v-icon> </span>
          <p class="mt-2 text-body-2">Masterplan</p>
        </div>
      </div>

      <div>
        <div class="d-flex flex-row ma-2">
          <span> 
            <v-icon>
              <svg xmlns="http://www.w3.org/2000/svg" width="13" height="13" viewBox="0 0 13 13" fill="none">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M6.66667 0.5C6.39052 0.5 6.16667 0.723858 6.16667 1C6.16667 1.27614 6.39052 1.5 6.66667 1.5C7.30139 1.5 7.9299 1.62502 8.5163 1.86792C9.10271 2.11081 9.63553 2.46683 10.0843 2.91565C10.5332 3.36447 10.8892 3.89729 11.1321 4.4837C11.375 5.0701 11.5 5.69861 11.5 6.33333C11.5 6.60948 11.7239 6.83333 12 6.83333C12.2761 6.83333 12.5 6.60948 12.5 6.33333C12.5 5.56729 12.3491 4.80875 12.056 4.10101C11.7628 3.39328 11.3331 2.75022 10.7915 2.20854C10.2498 1.66687 9.60672 1.23719 8.89899 0.944036C8.19125 0.650884 7.43271 0.5 6.66667 0.5ZM12 11.6667V10.5694C12 10.0242 11.6681 9.53389 11.1619 9.33141L9.80576 8.78897C9.16191 8.53143 8.42813 8.81041 8.11801 9.43066L8 9.66667C8 9.66667 6.33333 9.33333 5 8C3.66667 6.66667 3.33333 5 3.33333 5L3.56934 4.88199C4.18959 4.57187 4.46857 3.83809 4.21103 3.19424L3.66859 1.83815C3.46611 1.33194 2.97583 1 2.43062 1H1.33333C0.596954 1 0 1.59695 0 2.33333C0 8.22437 4.77563 13 10.6667 13C11.403 13 12 12.403 12 11.6667ZM6.16667 3.66667C6.16667 3.39052 6.39052 3.16667 6.66667 3.16667C7.08252 3.16667 7.4943 3.24857 7.8785 3.40771C8.2627 3.56685 8.61179 3.80011 8.90584 4.09416C9.19989 4.38821 9.43314 4.7373 9.59229 5.1215C9.75142 5.5057 9.83333 5.91748 9.83333 6.33333C9.83333 6.60948 9.60948 6.83333 9.33333 6.83333C9.05719 6.83333 8.83333 6.60948 8.83333 6.33333C8.83333 6.0488 8.77729 5.76706 8.66841 5.50419C8.55952 5.24131 8.39993 5.00246 8.19873 4.80127C7.99754 4.60008 7.75869 4.44048 7.49581 4.33159C7.23294 4.22271 6.9512 4.16667 6.66667 4.16667C6.39052 4.16667 6.16667 3.94281 6.16667 3.66667Z" fill="white"/>
              </svg>
            </v-icon> 
          </span>
          <p class="mt-2 text-body-2">nextone@gmail.com</p>
        </div>
      
        <div class="d-flex flex-row ma-2">
          <span> 
            <v-icon>
              <svg xmlns="http://www.w3.org/2000/svg" width="14" height="12" viewBox="0 0 14 12" fill="none">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M0.339573 3.77432C0.335418 3.84902 0.333313 3.92426 0.333313 4V8C0.333313 10.2091 2.12417 12 4.33331 12H9.66665C11.8758 12 13.6666 10.2091 13.6666 8V4C13.6666 3.92426 13.6645 3.84901 13.6604 3.77432L9.64675 6.69332C8.06882 7.84091 5.93113 7.84091 4.35321 6.69332L0.339573 3.77432ZM0.551964 2.69229L4.94138 5.88459C6.16866 6.77715 7.8313 6.77715 9.05858 5.88459L13.448 2.69228C12.9062 1.12533 11.4178 0 9.66665 0H4.33331C2.58213 0 1.09378 1.12533 0.551964 2.69229Z" fill="white"/>
              </svg>
            </v-icon> 
          </span>
          <p class="mt-2 text-body-2">+971564156565</p>
        </div>

        <div class="d-flex flex-row ma-2">
          <span> 
            <v-icon>
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
                <path d="M13.7467 5.63317C13.0467 2.55317 10.36 1.1665 8 1.1665C8 1.1665 8 1.1665 7.99334 1.1665C5.64 1.1665 2.94667 2.5465 2.24667 5.6265C1.46667 9.0665 3.57334 11.9798 5.48 13.8132C6.18667 14.4932 7.09334 14.8332 8 14.8332C8.90667 14.8332 9.81334 14.4932 10.5133 13.8132C12.42 11.9798 14.5267 9.07317 13.7467 5.63317ZM8 8.97317C6.84 8.97317 5.9 8.03317 5.9 6.87317C5.9 5.71317 6.84 4.77317 8 4.77317C9.16 4.77317 10.1 5.71317 10.1 6.87317C10.1 8.03317 9.16 8.97317 8 8.97317Z" fill="white"/>
              </svg>
            </v-icon> 
          </span>
          <p class="mt-2 text-body-2">Tashkent, Shayxontohur, 15 A</p>
        </div>
      </div>

    </div>

    <div>
      <v-divider></v-divider>

      <div class="d-flex justify-space-between mt-10">
        <p class="text-caption">
          We treat your personal information as confidential and will handle it in accordance with data protection legislation as well as with the terms of this
          <br>statement. It is in principal possible to use our website without providing any personal information.
        </p>

        <p class="text-body-1">
          Avazbek Djumabayev
        </p>
      </div>
    </div>
  </div>

  <div class="black-wall">
    <p class="black-wall-text text-h4">Please enter with bigger device.</p>
  </div>
</template>

<style scoped>
  .black-wall{
    display: none;
    width: 200vw;
    height: 200vh;
    background-color: black;
    position: fixed;
    top: -100px;
    left: -100px;
  }

  .black-wall-text{
    position: fixed;
    top:50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
  }

  #navbar-links
  {
    border:2px solid rgb(184, 184, 184);
    background-color: rgb(255, 255, 255);
    padding: 3px;
    border-radius: 50px;
    overflow: hidden;
  }

  #navbar-links div{
    border-radius: 50px;
    display: inline-block;
    height: 100%;
    margin: 0 10px;
    padding: 5px 10px;
    background-color: rgb(244, 244, 244);
  }

  #navbar-links div:nth-child(1), #navbar-links div:nth-child(6){
    margin: 0;
  }

  #navbar-links div:hover{
    background-color: rgb(27, 27, 27);
    color: white;
    cursor: pointer;
  }

  .hero{
    margin: 50px;
    height: 70vh;
  }

  .hero-img{
    height: 100%;
  }

  .hero-header{
    margin: 20px 0 ;
  }

  .callbeck-1,.hero-read-more:hover .callbeck-2, .about-card-hidden, .about-sheet-hidden:hover .about-sheet-icon-hidden {
    display: none;
  }

  .hero-read-more:hover .callbeck-1, .about-sheet-hidden:hover .about-card-hidden{
    display: inline-block;
  }

  .animation-scroll-down{
    animation-name: scrolldown;
    animation-duration: 9s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
  }

  #img-after-scroll-down{
    max-width: 100vw;
  }

  .about-sheet-hidden{
    transition-property: all;
    transition-duration: 5s;
    transition-timing-function: linear;
  }

  .text-in-vr-img{
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }

  .addons-for-vr-tour{
    display:flex;
    align-items: center;
    justify-content: space-between;
    margin: -80px 40px 50px;
  }

  .addons-for-vr-tour-part{
    background-color: rgba(0, 0, 0, 0.539);
    padding: 10px 20px;
    border-radius: 100px;
  }

  @keyframes scrolldown{
    0%{
      transform: rotate(0deg);
    }

    100%{
      transform: rotate(360deg);
    }
  }

  #video-in-beautiful-projects{
    margin-top: -60px;
    padding: 10px 20px;
  }

  #partners{
    position: relative;
    overflow: hidden;
    height: 100px;
  }

  .part-1{
    position: relative;
    animation-name: part-1;
    animation-duration: 10s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
  }

  @keyframes part-1{
    0%{
      transform: translateX(-100px);
    }

    100%{
      transform: translateX(-1600px);
    }
  }

  .gallery{
    overflow: hidden;
  }

  .gallery-animation{
    position: relative;
    animation-duration: 15s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
  }

  .gallery-part-1{
    animation-name: animate-gallery-1;
  }

  .gallery-part-2{
    animation-name: animate-gallery-2;
  }

  @keyframes animate-gallery-1{
    0%{
      transform: translateX(-100px);
    }

    100%{
      transform: translateX(-2565px);
    }
  }

  @keyframes animate-gallery-2{
    0%{
      transform: translateX(100px);
    }

    100%{
      transform: translateX(2510px);
    }
  }

  .footer-link:hover .footer-links-icon{
    transform: rotate(45deg);
  }

  .footer-link:hover p{
    position: relative;
    left: 10px;
  }

  @media only screen and (max-width: 1230px){
    .black-wall{
      display: block;
    }
  }
</style>