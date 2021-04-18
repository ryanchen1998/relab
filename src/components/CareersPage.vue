<template>
<div>
    <TitleHeader msg="Join the Relab Crew"/>
    <div class="container">
        <div class="row mb-5">
            <p class="description">
                {{ `We’re passionate about our customers and our people. It’s that simple! 
                We want to make the world better, through data, the way we work and the outcomes our people and our customers experience.
                If you're into SaaS, want to work for a company that allows you to have ownership over your work and your direction and 
                are ready to kick the Kool-Aid to the curb... get in touch.` }}
            </p>
        </div>
        <div class="row mb-5">
            <p class="h3 text-muted">
                {{ "Open roles" }}
            </p>
            <span style="border-bottom: 1px solid #8080806b;"/>
        </div>
        <div class="row mb-3 p-2" 
            v-for="job in jobs"
            v-bind:key="job.id"
        >
            <div class="col">
                <div class="row">
                    <p class="h3 job-title">{{ job.title }}</p>
                </div>
                <div class="row">
                    <p class="text-muted">{{ job.location }}</p>
                </div>
            </div>
            <div class="col">
                <p>{{ job.description }}</p><a href="#">{{ "See more details here" }}</a>
            </div>
        </div>
        <div class="row mb-5 policy">
            <p>{{ `We have a policy around here of always hiring. We are building a world leading product and as such are always on the lookout for passionate people who want to join us.  So, if there’s nothing here that tickles your fancy... get in touch and tell us a little about yourself.` }}</p>
        </div>
    </div>
    <div class="container-fluid d-flex justify-content-center find-out-more mb-5">
        <div>
            <a class="btn btn-primary btn-find">Find out more</a>
        </div>
    </div>
</div>
</template>

<script>
import TitleHeader from './TitleHeader'

export default {
    name: 'CareersPage',
    components: {TitleHeader},
    data() {
        return { 
            jobs: [
                { id:1, title: 'Junior Software Developers', location: "Auckland, New Zealand", description: "We're on the hunt for junior software developers who are passionate about their craft..."},
            ]
        }
    }
}
</script>

<style scoped>
.description {
    font-weight: 500;
}
.job-title {
    color: #23b5af;
}
.policy {
    margin-top: 8rem;
}
.find-out-more {
    height: 30vh;
    background-color: #FFF5F5;
    align-items: center;
}
.btn-find {
    color: #fff;
    background-color: #ff0c7d;
    border-color: #ff0c7d;
}
</style>