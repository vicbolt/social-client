<template>
    <div class="rs-layout-default">
        <v-app>
            <RsAppBar /> 
            <v-main>
                <v-container fluid>
                    <v-row>
                        <v-col cols="8"> <Nuxt /> </v-col>
                        <v-col cols="4">
                            <RsStats/>
                            <RsPopular />
                            <RsLatestComments />

                        </v-col>
                    </v-row>
                </v-container>
            </v-main>
        </v-app>
    </div>
</template>