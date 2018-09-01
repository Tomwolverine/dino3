<template>
    <div>
        <p>{{message}}</p>
        <button v-on:click="showPreviewBox" id="preview-toggle">Show Preview</button>
        <section v-if="display" id="application-preview">
            {{applyText}}
        </section>
    </div>
</template>

<script>
export default {
    name: 'Preview',
    data() {
        return {
            display: false
        }
    },
    methods: {
        showPreviewBox: function() {
            this.display = !this.display
        }
        
    },
    props: ['applyText', 'message']
}
</script>

<style>
#application-preview {
    border-radius: 6px;
    box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.3);
    border: 1px solid darkgrey;
    min-height: 100px;
    margin-top: 20px;
    padding: 10px;
}

section {
    font-weight: 500;
}
</style>
