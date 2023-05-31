<script>

export default{
  data(){
    return{
      themesList: [
        {
            tag: 'Tutti i temi',
            url: '#',
            active: true
        },
        {
            tag: 'Ambiente',
            url: '#',
            active: false
        },
        {
            tag: 'Economia',
            url: '#',
            active: false
        },
        {
            tag: 'Mondo',
            url: '#',
            active: false
        },
        {
            tag: 'Non Profit',
            url: '#',
            active: false
        },
        {
            tag: 'Politica',
            url: '#',
            active: false
        },
        {
            tag: 'Società',
            url: '#',
            active: false
        },
        {
            tag: 'Welfare',
            url: '#',
            active: false
        }
      ]
    }
  },
  methods: {
    setActive(id){
      this.themesList.forEach(element => {
        element.active = false
      });
      this.themesList[id].active = true;
    }
  }
}

</script>

<template>
    <!-- mobile -->
  <header class="d-block d-md-none">
    <div class="container-fluid text-center">
        <!-- row -->
        <div class="row border-bottom border-dark">
            <div class="col empy_col"></div>
        </div>
        <!-- row -->
        <div class="row border-bottom border-dark second_row">
            <div class="col-6 border-end border-dark d-flex align-items-center justify-content-center">
                <a href="#" class="header_links">
                    Contribuisci
                </a> 
            </div>
            <div class="col-6 d-flex align-items-center justify-content-center">
                <a href="#" class="header_links">
                    Abbonati
                </a> 
            </div>
        </div>
        <!-- row -->
        <div class="row border-bottom border-dark third_row">
            <!-- hamburger menu -->
            <div class="col-2 square burger_container border-end border-dark">
                <ul class="burger_menu">
                    <li class="bars_burger bar_burger_1"></li>
                    <li class="bars_burger bar_burger_2"></li>
                    <li class="bars_burger bar_burger_3"></li>
                </ul>
            </div>
            <!-- empty -->
            <div class="col-8"></div>
            <!-- search  -->
            <div class="col-2 square d-flex align-items-center justify-content-center border-start border-dark">
            <svg class="search_icon" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M7.07691 1.23077C3.84817 1.23077 1.23077 3.84817 1.23077 7.07691C1.23077 10.3056 3.84817 12.9231 7.07691 12.9231C10.3056 12.9231 12.9231 10.3056 12.9231 7.07691C12.9231 3.84817 10.3056 1.23077 7.07691 1.23077ZM0 7.07691C0 3.16844 3.16844 0 7.07691 0C10.9854 0 14.1538 3.16844 14.1538 7.07691C14.1538 10.9854 10.9854 14.1538 7.07691 14.1538C3.16844 14.1538 0 10.9854 0 7.07691Z" fill="#E63036"/><path fill-rule="evenodd" clip-rule="evenodd" d="M11.2109 11.211C11.4512 10.9707 11.8408 10.9707 12.0812 11.211L15.8196 14.9495C16.0599 15.1898 16.0599 15.5794 15.8196 15.8198C15.5793 16.0601 15.1896 16.0601 14.9493 15.8198L11.2109 12.0813C10.9705 11.841 10.9705 11.4513 11.2109 11.211Z" fill="#E63036"/>
            </svg>
            </div>
        </div>
    </div>
  </header>
  <!-- desktop -->
  <header class="d-none d-md-block">
    <div class="container-fluid text-center">
        <!-- row 1 -->
        <div class="row border-bottom border-dark py-3 px-4">
            <div class="col d-flex align-items-center">
                <a href="#" class="header_links pe-4">
                    Contribuisci
                </a> 
                <a href="#" class="header_links">
                    Abbonati
                </a> 
            </div>
            <div class="col d-flex align-items-center justify-content-end">
                <span class="profile_icon">
                    <svg width="15" height="15" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M16.7878 7.12769C16.7878 9.68586 15.5201 11.9367 13.6055 13.2215C14.2985 13.471 14.9697 13.7909 15.6092 14.1786C17.3447 15.2308 18.7852 16.7438 19.7863 18.565C20.0191 18.9885 19.8827 19.5321 19.4747 19.7794C19.0637 20.0285 18.5404 19.8785 18.3062 19.4524C17.4537 17.9016 16.2278 16.6145 14.7521 15.7198C13.2766 14.8252 11.6029 14.3554 9.89967 14.3554C8.19642 14.3554 6.52305 14.8252 5.04748 15.7198C3.57183 16.6145 2.34591 17.9016 1.49342 19.4524C1.25919 19.8785 0.735948 20.0285 0.324901 19.7794C-0.0831056 19.5321 -0.219545 18.9885 0.0132516 18.565C1.01445 16.7438 2.45495 15.2308 4.19041 14.1786C4.82984 13.7909 5.50097 13.471 6.1939 13.2215C4.27924 11.9367 3.01153 9.68588 3.01153 7.12769C3.01153 3.14057 6.09096 -0.0999756 9.89967 -0.0999756C13.7084 -0.0999756 16.7878 3.14057 16.7878 7.12769ZM4.71825 7.12769C4.71825 4.11561 7.04255 1.68219 9.89967 1.68219C12.7568 1.68219 15.0811 4.11561 15.0811 7.12769C15.0811 10.1398 12.7568 12.5732 9.89967 12.5732C7.04255 12.5732 4.71825 10.1398 4.71825 7.12769Z" fill="black"/>
                    </svg>
                </span>
                <span>
                    <a href="#" class="ps-3 header_links">
                        Accedi
                    </a> 
                </span>
            </div>
        </div>
        <!-- row 2 -->
        <div class="row border-bottom border-dark second_row_desktop d-flex justify-content-between">
            <!-- hamburger menu -->
            <div class="col-auto square burger_container_desktop border-end border-dark">
                <button class="burger_btn" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                    <ul class="burger_menu">
                        <li class="bars_burger bar_burger_1"></li>
                        <li class="bars_burger bar_burger_2"></li>
                        <li class="bars_burger bar_burger_3"></li>
                    </ul>
                </button>
                <div class="container-fluid dropdown-menu rounded-0 py-0 my_dropdown">
                    <table class="table table-bordered border-dark my_table">
                        <tbody>
                            <tr class="border-top-0">
                                <td class="ps-4 pb-4 border-start-0" colspan="2">
                                    <div class="height_100 d-flex flex-column justify-content-end align-items-start">

                                        <h2>Articoli</h2>
                                        <div class="subtitle">Trend, dati e novità del Terzo Settore.</div>
                                    </div>
                                </td>
                                <td class="ps-4 pb-4 " colspan="2">
                                    <div class="height_100 d-flex flex-column justify-content-end align-items-start">

                                        <h2>Storie</h2>
                                        <div class="subtitle">Letture ed approfondimenti dei fenomeni complessi.</div>
                                    </div>
                                </td>
                                <td class="ps-4 pb-4 border-end-0" colspan="2">
                                    <div class="height_100 d-flex flex-column justify-content-end align-items-start">

                                        <h2>Interviste</h2>
                                        <div class="subtitle">Racconti reali di persone ed organizzazioni.</div>
                                    </div>
                                </td>
                            </tr>
                            <tr>
                                <td class="ps-4 pb-4 border-start-0" colspan="2">
                                    <div class="height_100 d-flex flex-column justify-content-end align-items-start">

                                        <h2>Opinioni</h2>
                                        <div class="subtitle">Riflessioni e confronti dei nostri opinionisti.</div>
                                    </div>
                                </td>
                                <td class="ps-4 pb-4 " colspan="2">
                                    <div class="height_100 d-flex flex-column justify-content-end align-items-start">

                                        <h2>Podcast</h2>
                                        <div class="subtitle">Un luogo per dare voce ai protagonisti della sostenibilità.</div>
                                    </div>
                                </td>
                                <td class="ps-4 pb-4 border-end-0" colspan="2">
                                    <div class="height_100 d-flex flex-column justify-content-end align-items-start">

                                        <h2>Bookazine</h2>
                                        <div class="subtitle">Una rivista da leggere e un libro da conservare.</div>
                                    </div>
                                </td>
                            </tr>
                            <tr class="border-bottom-0 text-center">
                                <td class=" td_col_2  border-start-0 subtitle py-4">
                                    <div class="height_100 d-flex justify-content-center align-items-center">
                                        <span>Chi siamo</span> 
                                        
                                    </div>
                                </td>
                                <td class=" td_col_2 subtitle py-4">
                                    <div class="height_100 d-flex justify-content-center align-items-center">
                                        <span>Comitato editoriale</span> 
                                        
                                    </div>
                                </td>
                                <td class=" td_col_2 subtitle py-4">
                                    <div class="height_100 d-flex justify-content-center align-items-center">
                                        <span>Servizi</span> 
                                        
                                    </div>
                                </td>
                                <td class=" td_col_2 subtitle py-4">
                                    <div class="height_100 d-flex justify-content-center align-items-center">
                                        <span>Agenda / Eventi</span> 
                                    </div>
                                </td>
                                <td class=" td_col_2 subtitle py-4">
                                    <div class="height_100 d-flex justify-content-center align-items-center">     
                                        <span>Mappa dell'attivismo</span> 
                                    </div>
                                </td>
                                <td class=" td_col_2 border-end-0 subtitle py-4">
                                    <div class="height_100 d-flex justify-content-center align-items-center">                                        
                                        <span>Inchieste crowfounding</span> 
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                        </table>
                </div>
            </div>
            <!-- empty -->
            <div class="col-8"></div>
            <!-- search  -->
            <div class="col-auto square d-flex align-items-center justify-content-center border-start border-dark">
            <svg class="search_icon" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M7.07691 1.23077C3.84817 1.23077 1.23077 3.84817 1.23077 7.07691C1.23077 10.3056 3.84817 12.9231 7.07691 12.9231C10.3056 12.9231 12.9231 10.3056 12.9231 7.07691C12.9231 3.84817 10.3056 1.23077 7.07691 1.23077ZM0 7.07691C0 3.16844 3.16844 0 7.07691 0C10.9854 0 14.1538 3.16844 14.1538 7.07691C14.1538 10.9854 10.9854 14.1538 7.07691 14.1538C3.16844 14.1538 0 10.9854 0 7.07691Z" fill="#E63036"/><path fill-rule="evenodd" clip-rule="evenodd" d="M11.2109 11.211C11.4512 10.9707 11.8408 10.9707 12.0812 11.211L15.8196 14.9495C16.0599 15.1898 16.0599 15.5794 15.8196 15.8198C15.5793 16.0601 15.1896 16.0601 14.9493 15.8198L11.2109 12.0813C10.9705 11.841 10.9705 11.4513 11.2109 11.211Z" fill="#E63036"/>
            </svg>
            </div>
        </div>
        <!-- row 3 -->
        <div class="row border-bottom border-dark px-4 d-flex justify-content-between">
            <div class="col-auto">
                <ul class="filter_themes d-flex align-items-center">
                    <li v-for="(item, index) in themesList" @click="setActive(index)" :class="item.active ? 'activeSection' : ''" class="themes_li me-4" :key="index">
                        <a :href="item.url">
                            {{ item.tag }}
                        </a>
                    </li>
                </ul>
            </div>
            <div class="col-auto d-flex align-items-center">
                <span>Aa</span>
                <span>
                    <button class="theme_btn_section square switch_style">
                            <svg width="20" height="17" viewBox="0 0 20 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M1.14624e-08 1.54545C1.14624e-08 0.691924 0.688793 0 1.53846 0H18.4615C19.3112 0 20 0.691924 20 1.54545V15.4545C20 16.3081 19.3112 17 18.4615 17H1.53846C0.688793 17 1.14624e-08 16.3081 1.14624e-08 15.4545V1.54545ZM18.4615 1.54545H1.53846V15.4545H18.4615V1.54545Z" fill="black"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M5.55967 6.62178C5.74785 6.54263 5.94983 6.50187 6.15385 6.50187C6.35786 6.50187 6.55984 6.54263 6.74803 6.62178C6.93515 6.70049 7.10491 6.81559 7.24756 6.96044L11.5385 11.2709L11.5426 11.2667L13.5217 9.27855C13.6644 9.13373 13.8341 9.01866 14.0212 8.93997C14.2094 8.86081 14.4114 8.82005 14.6154 8.82005C14.8194 8.82005 15.0214 8.86081 15.2096 8.93997C15.3967 9.01866 15.5664 9.13373 15.709 9.27855L19.7747 13.3627C20.0751 13.6645 20.0751 14.1537 19.7747 14.4555C19.4743 14.7573 18.9872 14.7573 18.6868 14.4555L14.6154 10.3655L14.6113 10.3697L12.6346 12.3553L12.6322 12.3577C12.4895 12.5026 12.3198 12.6177 12.1326 12.6964C11.9445 12.7756 11.7425 12.8163 11.5385 12.8163C11.3344 12.8163 11.1325 12.7756 10.9443 12.6964C10.7572 12.6177 10.5874 12.5026 10.4447 12.3577L6.15383 8.04734L6.14971 8.05154L1.31316 12.91C1.01276 13.2118 0.525706 13.2118 0.225302 12.91C-0.0751008 12.6083 -0.0751008 12.119 0.225302 11.8172L5.0601 6.96048C5.20275 6.8156 5.37253 6.70049 5.55967 6.62178Z" fill="black"/>
                            <path d="M12.6923 6.95455C13.3296 6.95455 13.8462 6.4356 13.8462 5.79545C13.8462 5.15531 13.3296 4.63636 12.6923 4.63636C12.0551 4.63636 11.5385 5.15531 11.5385 5.79545C11.5385 6.4356 12.0551 6.95455 12.6923 6.95455Z" fill="black"/>
                            </svg>
                        </button>
                </span>
            </div>
        </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
    @use '../style/variables.scss' as *;

    


    /* first row */
    .empy_col{
        height: 50px;
    }

    

    /* 2nd row */

    .second_row{
        height: 3.5rem;

    }
    
    .header_links{
        font-family: "Anybody";
        font-weight: 500;
        font-size: 14px;
        text-decoration: none;
        color: #000;
        display: block;
    }

    

    /* 3rd_row */

    .third_row{


        /* burger menu */

        .burger_container{
            display: flex;
            align-items: center;
            .burger_menu{
                display: inline-block;
                list-style-type: none;
                height: 30px;
                width: 20px;
                position: relative;
                margin: 0 auto;
                .bars_burger{
                    position: absolute;
                    background-color: $primaryColor;
                    left: 5%;
                    right: 5%;
    
        
                }
                .bar_burger_1{
                    top: 15%;
                    bottom: 75%;
                }
    
                .bar_burger_2{
                    top: 45%;
                    bottom: 45%;
                }
    
                .bar_burger_3{
                    top: 75%;
                    bottom: 15%;
                }
            }
        }

        /* search */

        .search_icon{
            height: 30px;
            width: 30px;
        }
    }



    /* desktop */

    .profile_icon{
        position: relative;
        top: -4px;
    }

    /* burger manu */

    .burger_container_desktop{
            display: flex;
            align-items: center;
            justify-content: center;
            .burger_menu{
                display: inline-block;
                list-style-type: none;
                height: 30px;
                width: 20px;
                position: relative;
                margin: 0;
                .bars_burger{
                    position: absolute;
                    background-color: $primaryColor;
                    left: 5%;
                    right: 5%;
    
        
                }
                .bar_burger_1{
                    top: 15%;
                    bottom: 75%;
                }
    
                .bar_burger_2{
                    top: 45%;
                    bottom: 45%;
                }
    
                .bar_burger_3{
                    top: 75%;
                    bottom: 15%;
                }
            }
        }

        .second_row_desktop{
            height: 100px;
            .col-auto, .col-8{
                max-height: 100%;
            }
            .col-auto{
                width: 99.2px;
            }

            /* search */

            .search_icon{
                height: 30px;
                width: 30px;
            }
        }

        /* themes */

        .filter_themes{
            list-style-type: none;
            padding-left: 0;
            margin-bottom: 0;

            .themes_li{
                padding: 1.75rem 0;
                font-family: 'Anybody';
                font-weight: 600;
                font-size: 16px;
                a{
                    text-decoration: none;
                    color: black;
                }
            }
            .activeSection{
                box-shadow: inset 0px -5px 0px 0px $primaryColor;
                
            }
        }

        .switch_style{
            margin-left: 1rem;
            padding: 1px 6px;
        }
        
        .burger_btn{
            background-color: white;
            border: none;
        }

       


        .dropdown-menu{
            max-width: 100vw !important;
            transform: translateY(157px)!important;
            max-height: calc(100vh - 157px);
        }
        .my_dropdown{
            bottom: 0 !important;
            right: 0 !important;
            width: 100vw;
        }

        .height_100{
            height: 100%;
        }
        .w_100{
            max-width: 100%;
        }

        .my_table{
            height: 100%;
            h2{
            padding-top: 5rem;
            font-family: 'Anybody';
            font-weight: 700;
            font-size: 32px;
            line-height: 46px;
        }

            .subtitle{
                font-size: 14px;
                font-family: 'Anybody';
                font-weight: 500;
                line-height: 100%;
            }
        }

        .td_col_2{
            width: calc(100% / 6);
        }
</style>
