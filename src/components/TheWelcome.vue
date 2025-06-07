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
      <ExplanationIcon />
    </template>
    <template #heading>テニプラ無料説明会日程</template>
    テニプラがあなたの運営するテニスサークルをどのようにお手伝いするか説明します。<br />
    Google Formから無料オンライン説明会にお申し込みください。<br /><br />

    6/7月分は<a href="https://forms.gle/B8kZs1mEYxzGfRYw5" target="_blank" rel="noopener">こちら</a
    ><br />
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <TennisGameIcon />
    </template>
    <template #heading>お手伝い出来る内容について</template>
    以下、テニプラがお手伝い出来る内容の一例です。<br /><br />
    <li :style="{ fontWeight: 'bold' }">ダブルスペア乱数表</li>
    <a href="https://naoyuki-sato.github.io/tenipura/index.html" target="_blank" rel="noopener"
      >ダブルスペアの組み合わせ乱数表</a
    >です。
    <p>サークル活動時のダブルス試合時に活用してください。</p>
    <p>番号をサークルメンバーのお名前にすることも可能です。</p>
    <br />

    <li :style="{ fontWeight: 'bold' }">サークルスケジュールアプリ</li>
    サークルメンバーとのスケジュール共有アプリを提供します。<br />
    <br />

    <li :style="{ fontWeight: 'bold' }">サークル会計アプリ</li>
    サークルメンバーとのサークル会計を共有アプリを提供します。<br />
    <br />

    <li :style="{ fontWeight: 'bold' }">練習メニュー</li>
    サークルの練習メニューを提供します。<br />
    ストローク、ボレー、ダブルスなどご希望があればお伝えください。<br />
    <br />

    <li :style="{ fontWeight: 'bold' }">ビデオ撮影・分析</li>
    サークル活動、サークルメンバーのフォーム撮影のお手伝い、ビデオ分析を行います。<br />
    <a href="https://www.youtube.com/watch?v=j4c0iPHjj0c" target="_blank" rel="noopener"
      >ビデオ分析の一例(音声なし) </a
    >です。 <br /><br />

    <li :style="{ fontWeight: 'bold' }">トレーニングメニュー</li>
    サークルのトレーニングメニューを提供します。<br />
    メンバーの体力アップにお役立て下さい。<br /><br />

    <li :style="{ fontWeight: 'bold' }">教え方指南</li>
    教え方でサークルメンバーの上達が変わります。<br />
    あなたのテニス指導を指南します。<br /><br />

    <li :style="{ fontWeight: 'bold' }">球出しお手伝い</li>
    サークル練習のお手伝いも出来ます。<br />
    ストローク練習のための球出しなど。<br /><br />

    <li :style="{ fontWeight: 'bold' }">戦術立案</li>
    あなたのサークルが試合に勝つためのお手伝いをします。<br />
    試合に勝つための戦術立案のお手伝いをします。<br /><br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EmailIcon />
    </template>
    <template #heading>連絡先</template>
    テニプラについてお知りになりたい場合はお気軽にお問い合わせください。<br />
    メール: <a href="mailto:naoyuki.sato@gmail.com?">佐藤直之 naoyuki.sato@gmail.com</a>
  </WelcomeItem>
</template>
