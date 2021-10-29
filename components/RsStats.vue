<template>
    <div class="rs-stats">
        <RsCard title="Statics" icon="mdi-chart-box">
            <v-list>
                <v-list-item>
                    <v-list-icon>
                        <v-icon> mdi-file-image</v-icon>
                    </v-list-icon>
                    <v-list-content> 0 Images </v-list-content>
                </v-list-item>

                <v-list-item>
                    <v-list-icon>
                        <v-icon> mdi-comment</v-icon>
                    </v-list-icon>
                    <v-list-content> 0 Comments </v-list-content>
                </v-list-item>

                <v-list-item>
                    <v-list-icon>
                        <v-icon> mdi-eye</v-icon>
                    </v-list-icon>
                    <v-list-content> 0 Views</v-list-content>
                </v-list-item>

                <v-list-item>
                    <v-list-icon>
                        <v-icon> mdi-thumb-up</v-icon>
                    </v-list-icon>
                    <v-list-content> 0 Likes</v-list-content>
                </v-list-item>

            </v-list>
        </RsCard>
    </div>
</template>

<script>

</script>


<style scoped>

#card-title{
    background-color: rgb(86, 107, 76);
    margin-bottom: 13px;
}

#card-text{
    background-color: rgb(123, 133, 121);
}

#list{
    background-color: rgb(123, 133, 121);
}
</style>