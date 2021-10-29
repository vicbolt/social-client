<template>
    <div class="rs-popular">
        <RsCard title="Most Popular" icon="mdi-camera-image" class="mt-5" >
            <div class="rs-images-container">
                <v-row class="pa-2">
                    <v-col cols=6 v-for="image in images" :key="image.id"  class="rs-images-container-item">

                        <v-img :src="image.url" width="200px" height="150px"> </v-img>
                    </v-col>
                </v-row>
            </div>
        </RsCard>

    </div>
</template>


<script>
export default{
    data(){
        return{
            images: [
                {
                    id: 1,
                    url: "https://i.picsum.photos/id/1002/4312/2868.jpg?hmac=5LlLE-NY9oMnmIQp7ms6IfdvSUQOzP_O3DPMWmyNxwo"
                },{
                    id: 2,
                    url: "https://i.picsum.photos/id/101/2621/1747.jpg?hmac=cu15YGotS0gIYdBbR1he5NtBLZAAY6aIY5AbORRAngs"
                },{
                    id: 3,
                    url: "https://i.picsum.photos/id/1015/6000/4000.jpg?hmac=aHjb0fRa1t14DTIEBcoC12c5rAXOSwnVlaA5ujxPQ0I"
                },{
                    id: 4,
                    url: "https://i.picsum.photos/id/1018/3914/2935.jpg?hmac=3N43cQcvTE8NItexePvXvYBrAoGbRssNMpuvuWlwMKg"
                },
            ]
        }
    }
}
</script>
