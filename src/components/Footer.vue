
<template>
  <!-- <nav text-xl mt-6>
    <RouterLink class="icon-btn mx-2" to="/" :title="'button.home'">
      <div i-carbon-campsite />
    </RouterLink>

    <button class="icon-btn mx-2 !outline-none" :title="'button.toggle_dark'" @click="toggleDark()">
      <div i="carbon-sun dark:carbon-moon" />
    </button>


    <RouterLink class="icon-btn mx-2" to="/about" :title="'button.about'">
      <div i-carbon-dicom-overlay />
    </RouterLink>

    <a class="icon-btn mx-2" rel="noreferrer" href="https://github.com/antfu/vitesse" target="_blank" title="GitHub">
      <div i-carbon-logo-github />
    </a>
  </nav> -->
  <nav flex flex-col items-center>
    <div>
      <button class="icon-btn mx-2 !outline-none" @click="toggleDark()">
        <div i="carbon-sun dark:carbon-moon" />
      </button>
    </div>
    <div icon-btn flex>
      <span i="carbon-license-third-party"></span>
      <a href="https://beian.miit.gov.cn" target="_blank">
        <span>闽ICP备20013211号-1</span>
      </a>
    </div>
  </nav>
</template>
