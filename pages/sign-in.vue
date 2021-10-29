<template>
    <div class="rs-sign-in">

        <div class="container">
            <v-row>
                <v-col cols=2></v-col>
                <v-col cols="8">
                    <v-form >
                        <h1 class="text-center">LOGIN</h1>
                        <v-text-field v-model="email"  placeholder="E-mail" required></v-text-field>
                        <v-text-field v-model="password" placeholder="Password" required></v-text-field>
                        <v-btn block color="orange"> LOGIN! </v-btn>
                        <v-btn text block href="sign-up">¿Do you need an account? Sign up to continue</v-btn>
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
