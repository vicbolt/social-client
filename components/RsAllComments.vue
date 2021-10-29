<template>
    <div class="rs-all-comments">
        
        <v-card>
            <v-card-text class="pa-1 rs-card-text">
                <div class="rs-all-comments-container">
                    <v-row v-for="(obj, index) in comments" :key="obj.id" class="mt-5 ml-7" >
                        <v-col cols="2">
                            <v-avatar size="130"> <v-img :src="obj.avatar"/></v-avatar>
                           
                        </v-col>
                        <v-col cols="10">
                            <p class="headline black font-weight-black">{{obj.email}}</p>
                            <p>{{obj.comment}}</p>
                        </v-col>
                        <v-col cols="12" v-if="index != comments.length - 1">
                        <v-divider></v-divider>
                        </v-col>
                    </v-row>

                </div>
            </v-card-text>
        </v-card>
    </div>
</template>

<script>
export default {
    data(){
        return{
            comments: [
                {
                    id:1,
                    email: "Svetlana@gmail.com",
                    avatar: "https://i.picsum.photos/id/1027/2848/4272.jpg?hmac=EAR-f6uEqI1iZJjB6-NzoZTnmaX0oI0th3z8Y78UpKM",
                    comment: "I really like your pic",
                },{
                    id:2,
                    email: "Giovanny@gmail.com",
                    avatar: "https://i.picsum.photos/id/447/1280/853.jpg?hmac=4DUUCOsHRIoYbNrPRYEUHOW7wCjM7TROrTrYFivtdPw",
                    comment: "Awesome! where is that?",
                },{
                    id:3,
                    email: "Peter@gmail.com",
                    avatar: "https://i.picsum.photos/id/177/2515/1830.jpg?hmac=G8-2Q3-YPB2TreOK-4ofcmS-z5F6chIA0GHYAe5yzDY",
                    comment: "Haha seems like my house in the mountains!!",
                }
            ]
        }
    }
}
</script>