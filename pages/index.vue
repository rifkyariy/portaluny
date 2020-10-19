<template>
    <div class="center grid">
        <Preloader/>
        <Navbar/>
        
        <vs-row justify="center" class="top-margin">
            <vs-col vs-type="flex" vs-justify="center" vs-align="center" w="10">
                <vs-row class="x-padding">
                    <vs-col class="main-text" w="4">
                        <h1>One Simple Portal</h1>
                        <br>
                        <p class="main-desc">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod</p>
                    </vs-col>
                    <vs-col w="8">
                        <img class="main-display" src="@/assets/img/testfoto.png" width="100%"/>
                        <img class="misc-hand" src="@/assets/img/hand.png"/>
                    </vs-col>
                </vs-row>
            </vs-col>
        </vs-row>

        <vs-row class="apps-link-section" justify="center">
            <vs-col vs-type="flex" vs-justify="center" vs-align="center" w="10">
                <vs-row class="x-padding" justify="center">
                    <vs-col w=4>
                        <h1 class="">Explore Our Apps</h1>
                    </vs-col>
                </vs-row>
                <vs-row class="x-padding y-padding">
                    <vs-col class="x-padding" w=3>
                        <vs-card type="5">
                            <template #title>
                            <h3>Pot with a plant</h3>
                            </template>
                            <template #img>
                            <img src="@/assets/img/testfoto.png" alt="">
                            </template>
                            <template #text>
                            <p>
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                            </p>
                            </template>
                            <template #interactions>
                            <vs-button danger icon>
                                <i class='bx bx-heart'></i>
                            </vs-button>
                            <vs-button class="btn-chat" shadow primary>
                                <i class='bx bx-chat' ></i>
                                <span class="span">
                                54
                                </span>
                            </vs-button>
                            </template>
                        </vs-card>
                    </vs-col>
                    <vs-col class="x-padding" w=3>
                        <vs-card type="5">
                            <template #title>
                            <h3>Pot with a plant</h3>
                            </template>
                            <template #img>
                            <img src="@/assets/img/testfoto.png" alt="">
                            </template>
                            <template #text>
                            <p>
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                            </p>
                            </template>
                            <template #interactions>
                            <vs-button danger icon>
                                <i class='bx bx-heart'></i>
                            </vs-button>
                            <vs-button class="btn-chat" shadow primary>
                                <i class='bx bx-chat' ></i>
                                <span class="span">
                                54
                                </span>
                            </vs-button>
                            </template>
                        </vs-card>
                    </vs-col>
                    <vs-col class="x-padding" w=3>
                        <vs-card type="5">
                            <template #title>
                            <h3>Pot with a plant</h3>
                            </template>
                            <template #img>
                            <img src="@/assets/img/testfoto.png" alt="">
                            </template>
                            <template #text>
                            <p>
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                            </p>
                            </template>
                            <template #interactions>
                            <vs-button danger icon>
                                <i class='bx bx-heart'></i>
                            </vs-button>
                            <vs-button class="btn-chat" shadow primary>
                                <i class='bx bx-chat' ></i>
                                <span class="span">
                                54
                                </span>
                            </vs-button>
                            </template>
                        </vs-card>
                    </vs-col>
                    <vs-col class="x-padding" w=3>
                        <vs-card type="5">
                            <template #title>
                            <h3>Pot with a plant</h3>
                            </template>
                            <template #img>
                            <img src="@/assets/img/testfoto.png" alt="">
                            </template>
                            <template #text>
                            <p>
                                Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                            </p>
                            </template>
                            <template #interactions>
                            <vs-button danger icon>
                                <i class='bx bx-heart'></i>
                            </vs-button>
                            <vs-button class="btn-chat" shadow primary>
                                <i class='bx bx-chat' ></i>
                                <span class="span">
                                54
                                </span>
                            </vs-button>
                            </template>
                        </vs-card>
                    </vs-col>
                </vs-row>
            </vs-col>
        </vs-row>
    </div>
</template>

<script>
import Vue from 'vue'
import Vuesax from 'vuesax'
import Navbar from '~/components/Navbar.vue'
import Preloader from '~/components/Preloader.vue'


export default {
}
</script>

<style scoped>
    .top-margin {
        margin-top : 60px;
    }

    .x-padding {
        padding : 0 2%;
    }

    .y-padding {
        padding : 2% 0;
    }
    
    .main-display {
        width : 90%;
        height : 400px;
        padding-left : 2%;
        float : right;
        border-radius : 4pc;
    }

    .misc-hand {
        left : 40%;
        top : 40%;
        width : 120%;
        position : absolute;
    }

    .main-text {
        padding-top : 6%;
    }

    .main-desc {
        color : rgba(50,50,50,0.5);
    }

    .apps-link-section {
        margin-top : 100px;
    }
</style>
