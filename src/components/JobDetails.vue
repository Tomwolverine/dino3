<template>
    <main>
        <section>
            <h2>Job Details</h2>
            <h4>Demolitions Manager</h4>
            <p>Please destroy things for us.</p>
        </section>
    </main>
</template>

<script>
export default {
    name: 'JobDetails'
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
