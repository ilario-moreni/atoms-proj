<script>

export default{
  components: {
    
  },
  data(){
    return{
      
    }
  }
}

</script>

<template>
    <!-- mobile -->
  <section class="d-block d-md-none">
    <div class="container-fluid pt-4 px-3 pb-3  themes_bg">
        <div class="row">
            <div class="col">
                <h2>Tutti i temi 
                    <svg class="themes_toggler" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M0.213013 0.213013C0.497031 -0.0710044 0.957515 -0.0710044 1.24153 0.213013L8 6.97148L14.7585 0.213013C15.0425 -0.0710044 15.503 -0.0710044 15.787 0.213013C16.071 0.497031 16.071 0.957515 15.787 1.24153L8.51426 8.51426C8.23024 8.79828 7.76976 8.79828 7.48574 8.51426L0.213013 1.24153C-0.0710044 0.957515 -0.0710044 0.497031 0.213013 0.213013Z" fill="black"/>
                    </svg>
                </h2>
                <ul class="themes_list">
                    <li class="themes_li">
                        <button class="theme_btn">ambiente</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">economia</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">mondo</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">non profit</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">politica</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">società</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">welfare</button>
                    </li>
                </ul>
            </div>
        </div>
    </div>
  </section>
  <!-- desktop -->
  <section class="d-none d-md-block">
    <div class="container-fluid py-4 px-3   themes_bg">
        <div class="row">
            <div class="col d-flex justify-content-between">
                <h2 class="desktop_h2">Tutti i temi
                </h2>
                <ul class="themes_list">
                    <li class="themes_li">
                        <button class="theme_btn btn_2nd">ambiente</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">economia</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn btn_3nd">mondo</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">non profit</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn btn_4th">politica</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">società</button>
                    </li>
                    <li class="themes_li">
                        <button class="theme_btn">welfare</button>
                    </li>
                </ul>
            </div>
        </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

    .themes_bg{
        background-color: #f4f4f4;
    }

    h2{
        font-size: 40px;
        font-family: 'Anybody';
        font-weight: 700;
        .themes_toggler{
            font-weight: bold;
            width: 25px;
        }
    }
    .desktop_h2{
        font-size: 32px;
        line-height: 60px;
    }

    .themes_list{
        padding-left: 0rem;
        list-style-type: none;
        display: flex;
        flex-wrap: wrap;
        row-gap: 0.75rem;
        .theme_btn{
            height: 3rem;
            background-color: white;
            border: 2px solid black;
            border-radius: 5px;
            margin-right: 0.75rem;
            box-shadow: -3px 2px 1px 1px black;
            text-transform: uppercase;
            font-size: 13px;
            font-weight: 700;
        }
    }
</style>
