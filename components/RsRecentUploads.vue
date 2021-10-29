<template>
    <div class="rs-recent-uploads">

        <RsCard title="Recent uploads" icon="mdi-clock" class="mt-5" >
            <div class="rs-recent-upload-container">
                <v-row class="pa-2">
                    <v-col cols=3 v-for="image in images" :key="image.id"  class="rs-recent-upload-item">

                        <v-img :src="image.url" width="200px" height="200px"> </v-img>
                    </v-col>
                </v-row>
            </div>
        </RsCard>



    </div>
</template>

<script>
export default {
    data(){
        return{
            images: [
                {
                    id:1,
                    url: "https://i.picsum.photos/id/1053/3596/2393.jpg?hmac=shru06Q5TiVeHArvSrQdBwclhorTJwYGnprqLqaH0hk"
                },{
                    id:2,
                    url: "https://i.picsum.photos/id/1044/4032/2268.jpg?hmac=BXmoMkaurlzpTLYQupXLipcmI1sFbgT5sIz98Ob5VZE"
                },{
                    id:3,
                    url: "https://i.picsum.photos/id/1043/5184/3456.jpg?hmac=wsz2e0aFKEI0ij7mauIr2nFz2pzC8xNlgDHWHYi9qbc"
                },{
                    id:4,
                    url: "https://i.picsum.photos/id/1042/3456/5184.jpg?hmac=5xr8Veg2D_kEQQO6rvGj_Yk8s_N4iq3-eZ9_KclSXNQ"
                },{
                    id:5,
                    url: "https://i.picsum.photos/id/1041/5184/2916.jpg?hmac=TW_9o6HeD7H7I7NVo-S1Fa1iAvzQ10uvmJqsXvNoi0M"
                },{
                    id:6,
                    url: "https://i.picsum.photos/id/1039/6945/4635.jpg?hmac=tdgHDygif2JPCTFMM7KcuOAbwEU11aucKJ8eWcGD9_Q"
                },{
                    id:7,
                    url: "https://i.picsum.photos/id/1040/4496/3000.jpg?hmac=kvZONlBpTcZ16PuE_g2RWxlicQ5JKVq2lqqZndfafBY"
                },{
                    id:8,
                    url: "https://i.picsum.photos/id/1036/4608/3072.jpg?hmac=Tn9CS_V7lFSMMgAI5k1M38Mdj-YEJR9dPJCyeXNpnZc"
                },{
                    id:9,
                    url: "https://i.picsum.photos/id/1031/5446/3063.jpg?hmac=Zg0Vd3Bb7byzpvy-vv-fCffBW9EDp1coIbBFdEjeQWE"
                },{
                    id:10,
                    url: "https://i.picsum.photos/id/1035/5854/3903.jpg?hmac=DV0AS2MyjW6ddofvSIU9TVjj1kewfh7J3WEOvflY8TM"
                },{
                    id:11,
                    url: "https://i.picsum.photos/id/1032/2880/1800.jpg?hmac=5SLBdyPZBMyr5IBkIRfffZV10bP87Y7RrxVZX1vCefA"
                },{
                    id:12,
                    url: "https://i.picsum.photos/id/1033/2048/1365.jpg?hmac=zEuPfX7t6U866nzXjWF41bf-uxkKOnf1dDrHXmhcK-Q"
                },

            ]
        }
    }
}
</script>