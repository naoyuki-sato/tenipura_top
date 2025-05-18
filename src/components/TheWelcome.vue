<script setup>
import WelcomeItem from './WelcomeItem.vue'
import TennisGameIcon from './icons/IconTennisGame.vue'
import ExplanationIcon from './icons/IconExplanation.vue'
import EmailIcon from './icons/IconEmail.vue'
import HouseIcon from './icons/IconHouse.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <HouseIcon />
    </template>
    <template #heading>テニプラについて</template>
    あなたが運営するテニスサークルをより充実するお手伝いをします。<br />
    興味のある方は連絡または説明会にご参加をお願いします。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <TennisGameIcon />
    </template>
    <template #heading>ダブルス乱数表</template>

    ダブルス組み合わせの乱数表です。<br />
    サークル活動時のダブルス試合時に活用してください。<br /><br />
    <a href="https://naoyuki-sato.github.io/tenipura/index.html" target="_blank" rel="noopener"
      >ダブルスペア乱数表</a
    >
    <br /><br />
    テニプラではサークルで活用出来るアプリなどを提供しています。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ExplanationIcon />
    </template>
    <template #heading>説明会日程</template>
    テニプラが提供する機能について説明します。 Google Formから説明会にお申し込みください。<br /><br />

    6月分は<a
      href="https://docs.google.com/forms/d/e/1FAIpQLSfQHyak6GMTQ3TckJil4_EmRzeTgCbGuunKL3TV9Yvi4_2FHw/viewform?usp=header"
      target="_blank"
      rel="noopener"
      >こちら</a
    ><br />
    7月分は<a href="" target="_blank" rel="noopener">未定</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EmailIcon />
    </template>
    <template #heading>連絡先</template>
    テニプラについてお知りになりたい場合はお気軽にお問い合わせください。<br /><br />

    メール: <a href="mailto:naoyuki.sato@gmail.com?">佐藤直之 naoyuki.sato@gmail.com</a>
  </WelcomeItem>
</template>
