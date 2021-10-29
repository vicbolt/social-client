<template>
    <div class="rs-sign-up">
        <div class="container">
            <v-row>
                <v-col cols=2></v-col>
                <v-col cols="8">
                    <v-form >
                        <h1 class="text-center">SIGN UP</h1>
                        <v-text-field v-model="email"  placeholder="E-mail" required></v-text-field>
                        <v-text-field v-model="password1" placeholder="password" required></v-text-field>
                        <v-text-field v-model="password2" placeholder="Repeat password" required></v-text-field>
                        <v-btn block color="orange"> JOIN METEOR NOW! </v-btn>
                        <v-btn text block href="sign-in">¿Already have an account? Log in to continue</v-btn>
                    </v-form> 
                </v-col>
                <v-col cols="2"></v-col>
            </v-row>
        </div>
        
    </div>
</template>


<script>
export default ({
    layout: 'auth'
})
</script>