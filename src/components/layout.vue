<template>
    <div class="container sections-wrapper">
        <div class="row">
            <div class="primary col-md-8 col-sm-12 col-xs-12">
                <AboutMe></AboutMe>
                <LatestProject></LatestProject>
                <WorkExperience></WorkExperience>
                <GithubCalendar></GithubCalendar>
            </div>
        </div>
    </div>
</template>
<style>
</style>
<script>
    import AboutMe from './about-me'
    import LatestProject from './latest-project'
    import WorkExperience from './work-experience'
    import GithubCalendar from './github-calendar'

    export default{
        name: 'Layout',
        data(){
            return{
                msg:'hello vue'
            }
        },
        components:{
            AboutMe, LatestProject, WorkExperience, GithubCalendar
        }
    }
</script>
