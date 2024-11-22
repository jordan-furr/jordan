<template>
    <div class="h-100">
        <div class="h-100 home-cont">
            <div class="h-100 star-cont flex flex-col">
                <div class="flex flex-row space-between h-50 align-center">
                    <div class="star-word-cont">
                        <div class="star-word essays">
                            <nuxt-link to="/" exact-active-class="active">
                                <p>essays</p>
                            </nuxt-link>
                        </div>
                    </div>
                    <div class="star-word-cont">
                        <div class="star-word web">
                            <nuxt-link to="/" exact-active-class="active">
                                <p>web dev</p>
                            </nuxt-link>
                        </div>
                    </div>
                </div>
                <div class="flex flex-row space-between h-25 align-center">
                    <div class="star-word-cont">
                        <div class="star-word projects">
                            <nuxt-link to="/" exact-active-class="active">
                                <p>projects</p>
                            </nuxt-link>
                        </div>
                    </div>
                    <div class="star-word-cont">
                        <div class="star-word news">
                            <nuxt-link to="/" exact-active-class="active">
                                <p>news</p>
                            </nuxt-link>
                        </div>
                    </div>

                </div>
                <div class="flex margin-a h-20 align-center">
                    <div class="star-word">
                        <nuxt-link to="/" exact-active-class="active">
                            <p>database</p>
                        </nuxt-link>
                    </div>
                </div>
            </div>
        </div>
        <div class="about-btn">
            <p>about</p>
        </div>
    </div>
</template>