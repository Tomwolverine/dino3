<template>
  <div id="app">
    <Header />
    <JobDetails />
    <Inputform />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header'
import JobDetails from './components/JobDetails'
import Inputform from './components/Inputform'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    JobDetails,
    Inputform,
    Footer
  }
}
</script>

<style>

</style>
