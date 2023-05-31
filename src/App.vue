<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default{
  components: {
    AppHeader,
    AppMain
  },
  data(){
    return{
      
    }
  }
}

</script>

<template>
  <AppHeader />
  <AppMain />
</template>

<style lang="scss">
    .theme_btn_section{
            padding: 0.3rem 1rem;
            background-color: white;
            border: 2px solid black;
            border-radius: 5px;
            box-shadow: -3px 2px 1px 1px black;
            text-transform: uppercase;
            font-size: 13px;
            font-weight: 700;
    }

    .btn_2nd{
      background-color: #E2F1E8 !important;   
    }

    .btn_3nd{
      background-color: #F1DADA !important;
    }

    .btn_4th{
      background-color: #F1F1E2 !important;
    }

    .square{
        aspect-ratio: 1 / 1;
    }

    .mx_0{
      margin-right: 0;
      margin-left: 0;
    }

    .absolute_center{
      position: absolute;
      right: 0;
      bottom: 0;
      transform: translate(-50%, -50%);
    }

    .p_relative{
      position: relative;
    }

    .writer_pic{
        max-height: 100%;
        border-radius: 100%;
        container-type: inline-size;
    }

    .article_writer{
        font-size: 20px;
    }
    .article_date{
        font-size: 14px;
    }

    .border_bottom{
        border-bottom: 2px solid black;
    }

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
