<script setup>
import WelcomeItem from './WelcomeItem.vue'
import IconHtml from './icons/IconHtml.vue'
import IconCss from './icons/IconCss.vue'
import IconFigma from './icons/IconFigma.vue'
import IconMysql from './icons/IconMysql.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <IconHtml />
    </template>
    <template #heading>HTML</template>
    <div class="progress">
        <div class="progress-bar" role="progressbar" aria-label="Basic example" style="width: 90%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconCss />
    </template>
    <template #heading>CSS</template>
    <div class="progress">
        <div class="progress-bar" role="progressbar" aria-label="Basic example" style="width: 90%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconFigma />
    </template>
    <template #heading>Figma</template>
    <div class="progress">
        <div class="progress-bar" role="progressbar" aria-label="Basic example" style="width: 80%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconMysql />
    </template>
    <template #heading>MySql</template>
    <div class="progress">
        <div class="progress-bar" role="progressbar" aria-label="Basic example" style="width: 80%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
  </WelcomeItem>
</template>