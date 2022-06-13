<template>
    <div>
        <Navbar></Navbar>
            <section class="m-0 section_bg ">
                     <div class="grid-container careers_cars">
                         <div class="small-12 cell">
                         <h2 class="banner-top__subtitle">Bizning platforma sizga yordam beradi</h2>
                        </div>
                        <div class="row">
                            <div class="col-xl-4" v-for="item in 6" :key="item">
                            <NuxtLink to="/">
                            <div class="card card--careers cell my-3 auto fading-block-enter-done">
                                <div>
                                <div class="card__image" style="background-image: url(&quot;https://www.careerhunter.io/uploads/images/544/small-Archaeologist.jpg&quot;);"></div>
                                <div class="card__section card__section--careers">
                                    <p class="card__name disable-fade-in">Shifokor</p>
                                    </div>
                                    <div class="match-tank pulse_8">
                                    <div class="inner">
                                        <div class="fill fillAction_8" style="transform: translate(0px, 12.92px);">
                                            <svg version="1.1" x="0px" y="0px" width="88px" height="88px" viewBox="0 0 88 88" enable-background="new 0 0 88 88"><path class="wave-shape" d="M300,300V2.5c0,0-0.6-0.1-1.1-0.1c0,0-25.5-2.3-40.5-2.4c-15,0-40.6,2.4-40.6,2.4
                                                c-12.3,1.1-30.3,1.8-31.9,1.9c-2-0.1-19.7-0.8-32-1.9c0,0-25.8-2.3-40.8-2.4c-15,0-40.8,2.4-40.8,2.4c-12.3,1.1-30.4,1.8-32,1.9
                                                c-2-0.1-20-0.8-32.2-1.9c0,0-3.1-0.3-8.1-0.7V300H300z"></path>
                                            </svg>
                                        </div>
                                        </div>
                                    <div class="match-percent hidden ">
                                        <div class="qm">?</div>
                                        Ball
                                        </div>
                                    </div>
                                    </div>
                                </div>
                            </NuxtLink>
                            </div>
                        </div>
                        </div>
            </section>
        <Footer class="m-0"></Footer>
    </div>
</template>
<style scoped>
    .careers_cars{
        padding-top: 100px;
    }
</style>