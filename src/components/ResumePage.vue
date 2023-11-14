<template>
    <main class="flex-shrink-0">
        <div class="container px-5 my-5">
            <div class="text-center mb-5">
                <h1 class="display-5 fw-bolder mb-0"><span class="text-gradient d-inline">Resume</span></h1>
            </div>

            <div class="row gx-5 justify-content-center">
                <div class="col-lg-11 col-xl-9 col-xxl-8">

                    <ResumeExperienceCard></ResumeExperienceCard>
                    <ResumeEducationCardVue></ResumeEducationCardVue>
                    <ResumeSkillSectionVue></ResumeSkillSectionVue>
                </div>
            </div>
        </div>
    </main>
</template>

<script setup>
import ResumeExperienceCard from './ResumeExperienceCard.vue';
import ResumeEducationCardVue from './ResumeEducationCard.vue';
import ResumeSkillSectionVue from './ResumeSkillSection.vue';
</script>