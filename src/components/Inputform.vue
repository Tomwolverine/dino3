<template>
    <div>
        <form id="application-input">
            <label>Apply Here: </label>
            <textarea v-model="applyText" id="application-text" rows="8" cols="100"></textarea>
            <input v-on:click.prevent="displayText" id="submit" type="submit" value="Submit" />
        </form>
        <Preview v-bind:applyText="applyText" v-bind:message="message" />
    </div>
</template>

<script>
import Preview from './Preview'
export default {
    name: "Inputform",
    components: {
        Preview
    },
    data() {
        return {
            applyText: "",
            message: "",
        }
    },
    methods: {
    displayText: function(event) {
            this.applyText = "";
            this.message = "Your application was submitted!";
        }
    }
}
</script>

<style>
</style>

