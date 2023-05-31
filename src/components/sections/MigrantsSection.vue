<script>

</script>
<template>
    <!-- mobile -->
    <section class="d-block d-md-none">
        <div class="container-fluid section_bg square ps-4">
            <div class="row">
                <div class="col">
                    <button class="theme_btn_section">migranti</button>

                </div>
            </div>
            <div class="row">
                <div class="col">
                    <h3>
                        Roccella Jonica, la Lampedusa che l'Italia ignora
                    </h3>
                </div>
            </div>
            <div class="row pb-3 ">
                <div class="col d-flex">
                    <div class="square">
                        <img class="writer_pic" src="../../assets/img/alessandro_puglia.jpg" alt="Alessandro Puglia">
                    </div>
                    <div class="article_info ps-3">
                        <div class="article_writer">
                            Di Alessandro Puglia
                        </div>
                        <div class="article_date">
                            29 Giugno 2022
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- desktop -->
    <section class="d-none d-md-block">
        <div class="container-fluid d-flex flex-column justify-content-end pb-5 section_bg square ps-4">
            <div class="row">
                <div class="col">
                    <button class="theme_btn_section">migranti</button>

                </div>
            </div>
            <div class="row">
                <div class="col-6">
                    <h3 class="py-3">
                        Roccella Jonica, la Lampedusa che l'Italia ignora
                    </h3>
                </div>
            </div>
            <div class="row">
                <div class="col d-flex">
                    <div class="square">
                        <img class="writer_pic" src="../../assets/img/alessandro_puglia.jpg" alt="Alessandro Puglia">
                    </div>
                    <div class="article_info ps-3">
                        <div class="article_writer">
                            Di Alessandro Puglia
                        </div>
                        <div class="article_date">
                            29 Giugno 2022
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
    .section_bg{
        padding-top: 100px;
        background-image: url(/src/assets/img/migrants_section_bg.jpg);
        background-size: cover;
        height: 350px;
        background-position: center;
    }

    h3, .article_writer, .article_date{
        color: white;
        font-family: 'Anybody';
    }

    h3{
        font-weight: 700;
        font-size: 28px;
        padding: 1rem 0;
        line-height: 42px;
        margin-bottom: 0;
    }

    @media screen and (min-width: 768px){
        .section_bg{
            height:550px;
        }
    }

    
</style>