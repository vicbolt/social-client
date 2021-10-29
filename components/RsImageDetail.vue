<template>
    <div class="rs-image-details">
        <v-card>
            <v-card-title class="rs-card-title">
                <v-icon color="white" size="32" class="mt-n3"> mdi-blur-on </v-icon>
                <p class="headline mx-2 white-text"> Image title</p>
                <v-spacer></v-spacer>
                <v-btn color=orange > DELETE </v-btn>
            </v-card-title>
            <v-card-text class="pa-1 rs-card-text">
                <div class="rs-card-container-description">
                    <v-img :src="image.url"></v-img>
                        <p class="mt-5"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam vitae molestias veniam cum deserunt! Fugiat laboriosam ipsum similique error omnis obcaecati natus eos aperiam? Sit ut illum eveniet sapiente rerum?</p>
                
                <div class="rs-card-container-footer">
                    <v-row class="mt-7">
                        <v-col cols="3">
                            <v-btn color=red style="width:80%" > <v-icon>mdi-heart</v-icon> </v-btn>
                        </v-col>
                        <v-col cols="3">
                            <p class="font-weight-black"> <v-icon>mdi-heart</v-icon> 304 </p>
                        </v-col>
                        <v-col cols="3">
                            <p class="font-weight-black"> <v-icon>mdi-eye</v-icon> 456 </p>
                        </v-col>
                        <v-col cols="3">
                            <p class="font-weight-black"> <v-icon>mdi-calendar</v-icon> 25-Oct </p>
                        </v-col>
                    </v-row>
                </div>
                
                </div>
            </v-card-text>
        </v-card>
    </div>
</template>


<script>
export default {
    data(){
        return{
            image:{
                url: "https://i.picsum.photos/id/1002/4312/2868.jpg?hmac=5LlLE-NY9oMnmIQp7ms6IfdvSUQOzP_O3DPMWmyNxwo"
            }
        }
    }
}
</script>