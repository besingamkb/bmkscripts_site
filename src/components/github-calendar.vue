<template>
    <section class="github section">
        <div class="section-inner">
            <h2 class="heading">My GitHub</h2>
            <!-- Prepare a container for your calendar. -->
            <div class="calendar">
                <!-- Loading stuff -->
                Loading the data just for you.
            </div>
        </div>
        <!--//secton-inner-->
    </section>
</template>
<style>

</style>
<script>

    export default{
        name: 'GithubCalendar',
        data(){

            return{
                msg:'hello vue'
            }
        },
        components:{

        },
        methods: {
            ready() {
                GitHubCalendar(".calendar", "besingamkb");
            }
        }
    }
</script>
