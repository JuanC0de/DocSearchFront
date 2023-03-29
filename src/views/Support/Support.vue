<script setup>
import FormSupport  from '@/layouts/FormSupport/FormSupport.vue'
import SupportingParagraph from '@/layouts/SupportingParagraph/SupportingParagraph.vue'

</script>

<template>
    <v-container>
      <v-row>
        <v-col cols="6">
            <div class="paragraphSupp">
                <SupportingParagraph/>
            </div>
        </v-col>
        <v-col cols="6">
            <FormSupport/>
        </v-col>
      </v-row>
    </v-container>

    <v-card>
        <v-img
            src="@/assets/images/imgSupport/imgSupport.png"
            height="400"            
        ></v-img>
    </v-card>
</template>

<style>
    .paragraphSupp{
        margin-top: 20%;
        margin-left: 30px;
    }
</style>