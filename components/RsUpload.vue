<template>
    <div class="rs-upload">
        <RsCard title="UPLOAD" icon="mdi-cloud-upload">
            <div class="rs-upload-container">
                <v-form>
                    <v-file-input outlined placeholder="Search file" prepend-icon=""></v-file-input>
                    <v-text-field outlined name="title" placeholder="Image title"></v-text-field>
                    <v-textarea outlined  name="description" placeholder="Description"></v-textarea>
                    <v-btn color=orange block> POST IN METEOR </v-btn>
                </v-form>


            </div>
        </RsCard>
    </div>
</template>

<script>
export default {
    onEnter(){
        console.log('funciona')
    }
}
</script>