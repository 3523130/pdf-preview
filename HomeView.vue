<template>
    <div class="">
      <PDFView :pdfUrl="jsPdf"></PDFView>
    </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import PDFView from './PdfView.vue'

const jsPdf = ref('CheckRelation.pdf');
</script>

<style scoped>

</style>
