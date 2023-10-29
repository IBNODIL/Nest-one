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
</template>

<style scoped>
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
</style>