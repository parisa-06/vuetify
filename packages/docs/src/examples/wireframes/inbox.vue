<template>
    <v-app id="inspire">
        <v-content>
            <v-container class="fill-height  byd-background-image " fluid>
                <v-row align="center" justify="center">
                    <v-col cols="12" sm="8" md="8">
                        <div class="byd-main">
                            <v-row>
                                <v-col cols="12" md="5" >
                                  <div  align="center" justify="center"  >
                                      <v-avatar
                                          class="my-3"
                                          color="grey darken-1"
                                          size="74" >
                                          <v-img
                                              max-height="200"
                                              max-width="73"
                                              src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
                                          ></v-img>

                                      </v-avatar>
                                      <div><h2 class="text-center  teal--text text--accent-3 ">
                                                نام آموزشگاه
                                            </h2></div>
                                      </div>
                                    <v-card-text >
                                        <div class="text-center mt-3">
{{--                                            <v-icon>fa fa-bell-o</v-icon>--}}
                                            <p class="text-center grey--text darken-1" >اطلاعات وارد شده درست نیست. </p>
                                        </div>

                                        <div class="byd-form " >
                                            <v-form>
                                                <v-text-field
                                                    id="user"
                                                    label="نام کاربری"
                                                    name="User"
                                                    type="text"
                                                    color="teal accent-3"
                                                ></v-text-field>

                                                <v-text-field
                                                    id="password"
                                                    label="رمز عبور"
                                                    name="Password"
                                                    type="password"
                                                    color="teal accent-3"
                                                ></v-text-field>
                                            </v-form>
                                        </div>
                                        <p class="text-center  grey--text lighten-1 display-6 mt-5 " >
                                            رمز عبورتان را فراموش کرده‌اید؟‌‌‌‌‌‌‌‌‌
                                            <v-chip
                                            color="white"
                                            filter
                                            link
                                          class="  teal--text accent-3 byd-forget-password"
                                        ><b> کلیک کنید. </b></v-chip></p>
                                    </v-card-text>
                                    <div class="text-center mt-3 mb-12">
                                        <v-btn rounded color="teal accent-4"  dark class="ml-4 px-6"> ورود </v-btn>
                                        <v-btn rounded color="teal accent-3" dark> ثبت نام</v-btn>
                                    </div>
                                </v-col>
                                <v-col cols="12" md="7" class="teal accent-3 byd-advertising">
                                    <v-card-text class="white--text mt-12">
                                        <h2 class="text-center "> سلام دوست من </h2>
                                        <h3
                                            class="text-center"
                                        >
                                            مشخصات شخصی خود را وارد کنید و عضوی از خانواده سهمان شوید.
                                            <br>

                                        </h3>
                                        <p  class="text-center">
                                            در اینجا عکس تبلیغات قرار میگیرد با بک گرند سفید و استفاده از این رنگ :    teal
                                        </p>
                                    </v-card-text>
                                    <div class="text-center">

                                    </div>
                                </v-col>
                            </v-row>
                        </div>
                    </v-col>
                </v-row>
            </v-container>
        </v-content>
    </v-app>
</template>
