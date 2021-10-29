<template>
    <div class="rs-latest-comments">
        <RsCard title="Latest Comments" icon="mdi-comment" class="mt-5"> 
            <RsCommentItem v-for="comment in comments" :key="comment.id" :image="comment.image" :email="comment.email" :comment="comment.comment">
            </RsCommentItem>

        </RsCard>
    </div>
</template>


<script>
export default {
    data(){
        return{
            comments: [
                {
                    id: 1,
                    image: "https://i.picsum.photos/id/1028/5184/3456.jpg?hmac=WhttNfn25eTgLTNnhRujSq4IVjx2mMa6wvPG1c6qMVc",
                    email:"victor@gmail.com",
                    comment: "Hey que chula!",
                },{
                    id: 2,
                    image: "https://i.picsum.photos/id/1023/3955/2094.jpg?hmac=AW_7mARdoPWuI7sr6SG8t-2fScyyewuNscwMWtQRawU",
                    email:"raquel@gmail.com",
                    comment: "Mola mucho tu foto",
                },{
                    id: 3,
                    image: "https://i.picsum.photos/id/1020/4288/2848.jpg?hmac=Jo3ofatg0fee3HGOliAIIkcg4KGXC8UOTO1dm5qIIPc",
                    email:"perseo@gmail.com",
                    comment: " Love it!!",
                },{
                    id: 4,
                    image: "https://i.picsum.photos/id/1019/5472/3648.jpg?hmac=2mFzeV1mPbDvR0WmuOWSiW61mf9DDEVPDL0RVvg1HPs",
                    email:"veronica@gmail.com",
                    comment: "wow, I wanna go there!",
                },
            ],
        }
    }
}
</script>