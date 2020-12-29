<template>
  <v-flex xs12 md12>
    <v-container>
      <v-card class="pa-4">
        <v-card-title class="font-weight-bold pb-4" >
          新規会員登録フォーム(3分で完了)
        </v-card-title>

        <v-card-text>
          WINDIIキャリアに登録すると、スキルシートを簡単にPDFに出力したり、企業からのオファーが届くようになります！
        </v-card-text>
        <v-btn outlined rounded class=" green--text text--darken-4 ma-2">
          2万円〜
        </v-btn>
        <v-btn outlined rounded class=" green--text text--darken-4 ma-2">
          2.5万円〜
        </v-btn>
        <v-btn outlined rounded class=" green--text text--darken-4 ma-2">
          3万円〜
        </v-btn>
        <v-btn outlined rounded class=" green--text text--darken-4 ma-2">
          3.5万円〜
        </v-btn>
        <v-btn outlined rounded class=" green--text text--darken-4 ma-2">
          4万円〜
        </v-btn>
        <v-btn outlined rounded class=" green--text text--darken-4 ma-2">
          それ以上
        </v-btn>

        <v-card-title>稼働開始可能時間</v-card-title>
        <v-date-picker class="px-2" solo type="date"> </v-date-picker>
        <v-card-title>周囲何時間稼働できそうですか</v-card-title>

        <v-btn outlined rounded class="green--text text--darken-4 ma-2">週2</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">週3</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">週4</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">週5</v-btn>
        <v-card-title>働き方の条件を教えてください</v-card-title>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">常駐</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >一部常駐OK</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >フルリモート</v-btn
        >
        <v-card-title
          >出勤（打ち合わせ）可能エリアを選択してください</v-card-title
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >首都圏</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">関西</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >その他</v-btn
        >
        <v-card-title>職歴について教えてください</v-card-title>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">〜1年</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">1年</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">2年</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >3〜5年</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >それ以上</v-btn
        >
        <v-card-title>実務可能な技術を選択してください</v-card-title>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">JaVa</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">PHP</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >Python</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">C#</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">Ruby</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >React.js</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >Angular</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >Vue.js</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2">AWS</v-btn>
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >Docker</v-btn
        >
        <v-btn outlined rounded class="green--text text--darken-4 ma-2"
          >Laravel</v-btn
        >

        <v-card-title>
          簡単にアピールポイントを教えてくだい
        </v-card-title>
        <v-textarea
          class="mt-0"
          solo
          label="Solo textarea"
          auto-grow
          rows="1"
          value=""
          placeholder="独学で勉強をしてきたので、詰まっても自己解決するのが得意です."
        >
        </v-textarea>
      </v-card>
    </v-container>
  </v-flex>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    // Logo,
    // VuetifyLogo
  }
};
</script>
