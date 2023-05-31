<script>
export default {
    
}
</script>
<template>
    <section class="d-block d-md-none">
        <div class="container-fluid px-4 py-5 border_bottom">
            <div class="row mx_0">
                <div class="col img_container">
                    <img class="primary_img" src="../../assets/img/img_ghiacciai.png" alt="Stato di scioglimento dei ghiacciai">
                    <div>
                        <button class="theme_btn_section square image_zoom">
                            <svg width="20" height="17" viewBox="0 0 20 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M1.14624e-08 1.54545C1.14624e-08 0.691924 0.688793 0 1.53846 0H18.4615C19.3112 0 20 0.691924 20 1.54545V15.4545C20 16.3081 19.3112 17 18.4615 17H1.53846C0.688793 17 1.14624e-08 16.3081 1.14624e-08 15.4545V1.54545ZM18.4615 1.54545H1.53846V15.4545H18.4615V1.54545Z" fill="black"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M5.55967 6.62178C5.74785 6.54263 5.94983 6.50187 6.15385 6.50187C6.35786 6.50187 6.55984 6.54263 6.74803 6.62178C6.93515 6.70049 7.10491 6.81559 7.24756 6.96044L11.5385 11.2709L11.5426 11.2667L13.5217 9.27855C13.6644 9.13373 13.8341 9.01866 14.0212 8.93997C14.2094 8.86081 14.4114 8.82005 14.6154 8.82005C14.8194 8.82005 15.0214 8.86081 15.2096 8.93997C15.3967 9.01866 15.5664 9.13373 15.709 9.27855L19.7747 13.3627C20.0751 13.6645 20.0751 14.1537 19.7747 14.4555C19.4743 14.7573 18.9872 14.7573 18.6868 14.4555L14.6154 10.3655L14.6113 10.3697L12.6346 12.3553L12.6322 12.3577C12.4895 12.5026 12.3198 12.6177 12.1326 12.6964C11.9445 12.7756 11.7425 12.8163 11.5385 12.8163C11.3344 12.8163 11.1325 12.7756 10.9443 12.6964C10.7572 12.6177 10.5874 12.5026 10.4447 12.3577L6.15383 8.04734L6.14971 8.05154L1.31316 12.91C1.01276 13.2118 0.525706 13.2118 0.225302 12.91C-0.0751008 12.6083 -0.0751008 12.119 0.225302 11.8172L5.0601 6.96048C5.20275 6.8156 5.37253 6.70049 5.55967 6.62178Z" fill="black"/>
                            <path d="M12.6923 6.95455C13.3296 6.95455 13.8462 6.4356 13.8462 5.79545C13.8462 5.15531 13.3296 4.63636 12.6923 4.63636C12.0551 4.63636 11.5385 5.15531 11.5385 5.79545C11.5385 6.4356 12.0551 6.95455 12.6923 6.95455Z" fill="black"/>
                            </svg>
                        </button>
                    </div>
                    <button class="play_button">
                        <svg class="square p_relative " fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path class=" my_play_icon" fill-rule="evenodd" clip-rule="evenodd" d="M16.1972 14.0002C16.0238 13.9964 15.8524 14.0388 15.7008 14.1231C15.5493 14.2074 15.4229 14.3305 15.3349 14.4798C15.2469 14.6291 15.2004 14.7992 15.2002 14.9724L15.2002 25.0277C15.2004 25.2009 15.2469 25.3709 15.3349 25.5202C15.4229 25.6695 15.5493 25.7926 15.7008 25.8769C15.8524 25.9612 16.0238 26.0036 16.1972 25.9998C16.3702 25.9959 16.5392 25.9462 16.6866 25.8558L16.6876 25.8552L24.3287 20.8302C24.4716 20.7448 24.5901 20.6241 24.6727 20.4796C24.7563 20.3335 24.8002 20.1682 24.8002 20C24.8002 19.8318 24.7563 19.6665 24.6727 19.5204C24.5901 19.3759 24.4716 19.2552 24.3287 19.1698L16.6892 14.1458L16.6867 14.1443C16.5392 14.0538 16.3703 14.0041 16.1972 14.0002Z" fill="black"/>
                        </svg>
                    </button>
                </div>
            </div>
            <div class="row mt-4">
                <div class="col">
                    <button class="theme_btn_section btn_2nd">allarmi</button>
                </div>
            </div>
            <div class="row">
                <div class="col">
                    <h3>
                       Il collasso dei ghiacciai negli scatti del fotografo ambientale Fabiano Ventura 
                    </h3>
                </div>
            </div>
            <div class="row">
                <div class="col d-flex">
                    <div class="square">
                        <img class="writer_pic" src="../../assets/img/gilda_sciortino.jpg" alt="Gilda Sciortino">
                    </div>
                    <div class="article_info ps-3">
                        <div class="article_writer">
                            Di Gilda Sciortino
                        </div>
                        <div class="article_date">
                            14 Luglio 2022
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>

    
    .primary_img{
       border: 2px solid black;
       width: 100%;
    }

    .img_container{
        padding: 0;
        position: relative;
        .image_zoom{
            width: 15%;
            position: absolute;
            right: 0;
            bottom: 35%;
        }

        .play_button{
            background-color: white;
            position: absolute;
            right: 0;
            bottom: 0;
            width: 40px;
            padding: 0;
            .my_play_icon{
                width: 15px;
                height: 15px;


            }
        }
    }


    h3{
        font-family: 'Anybody';
        font-size: 24px;
        font-weight: 700;
        line-height: 30px;
        margin: 2rem 0;
    }


    
</style>