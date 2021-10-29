<template>
    <div class="rs-card">
        <v-card>
            <v-card-title class="rs-card-title">
                <v-icon color="orange" size="32" class="mt-n3"> {{ icon }}</v-icon>
                <p class="headline mx-2 white-text"> {{ title }}</p>
            
            </v-card-title>
            <v-divider class="mt-n4"></v-divider>
            <v-card-text class="pa-1 rs-card-text">
                <div class="rs-card-text-container">
                    <slot/>
                </div>
            </v-card-text>
        </v-card>
    </div>
</template>


<script>

export default {
    props:{
        title:{
            type: String,
            required: true,
        },
        icon: {
            type: String,
            default: undefined,
        }
    }
}


</script>



