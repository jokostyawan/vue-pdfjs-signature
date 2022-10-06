
<script>
import PdfEditor from './PdfEditor.vue';
export default {
    props: {
        src: {
            required: true
        }
    },
    components: {
        PdfEditor
    }
}

</script>
<template>
    <PdfEditor :src="src"/>
</template>
