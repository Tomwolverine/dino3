<template>
    <section>
        <form id="application-input">
        <label>Apply Here: </label>
        <textarea id="application-text" rows="8" cols="100"></textarea>
        <input id="submit" type="submit" value="Submit" />
        </form>
    </section>
        <!-- <p id="message">&nbsp;</p>
        <button id="preview-toggle">Show Preview</button>
        <section id="application-preview" class="hidden"></section> -->
</template>

<script>
export default {
    name: "Inputform"
    
    
}
</script>

<style>
main {
    grid-row: 2/3;
    width: 70%;
    margin: 0 auto;
    padding: 10px;
}

main section {
    grid-column: 2/3;
}

small {
    color: black;
    font-size: .5rem;
    margin-left: 10px;
}

a {
    color: #C261CC;
    text-decoration: none;
}
</style>

