<script setup lang="ts">
import Deliverables from '@/components/Deliverables.vue';
import OldOverview from '@/components/OldOverview.vue';
import Rubric from '@/components/Rubric.vue';

</script>

<template>
    <div class="flex flex-col m-5 gap-10">
        
        <!-- <OldOverview/> -->

        <div class="border border-gray-600 rounded-xl p-8 flex flex-col gap-5">
            <p class="text-2xl font-bold">
                Assessment Brief
            </p>
            <div class="border border-gray-600 rounded-xl p-4 flex items-center gap-3">
                <p class="border border-green-400 rounded-2xl px-2 bg-green-900 text-green-400">
                    1
                </p>
                <div>
                    <p class="font-bold text-lg">
                        Investigate & Test (Use): 
                    </p>
                    <p class="text-base text-gray-300">
                        Here, students explore three curated multimodal resources (videos, interactive maps, and data visualisations) embedded on the class website to examine a major food-producing biome - such as tropical rainforests, temperate grasslands, or Australian wheat-sheep belts. They complete a structured digital inquiry log to identify environmental characteristics, threats to food yield and human alterations like deforestation, irrigation etc. They can then play and test a pre-built starter Scratch simulation to observe how variables like rainfall or land change and how that affects the crop output.
                    </p>
                </div>
            </div>
            <div class="border border-gray-600 rounded-xl p-4 flex items-center gap-3">
                <p class="border border-cyan-400 rounded-2xl px-2 bg-cyan-900 text-cyan-400">
                    2
                </p>
                <div>
                    <p class="font-bold text-lg">
                        Experiment & Remix (Modify)
                    </p>
                    <p class="text-base text-gray-300">
                        Working inside the starter Scratch project, students open the code editor to alter existing mechanics testing 'what-if' scenarios by modifying whatever variable they want (like introducing new stressors like urbanisation or maybe drought). They can then add strategies for sustainable management and record  the changes in shift in the simulation's food security outcomes.
                    </p>
                </div>
            </div>
            <div class="border border-gray-600 rounded-xl p-4 flex items-center gap-3">
                <p class="border border-yellow-400 rounded-2xl px-2 bg-yellow-900 text-yellow-400">
                    3
                </p>
                <div>
                    <p class="font-bold text-lg">
                        Design Build & Playtest (Create)
                    </p>
                    <p class="text-base text-gray-300">
                        Students focus on a chosen area and food crop and design an original Scratch biome Simulation based on it. It must challenge players to balance food production targets against environmental sustainability overtime. A working prototype can then be playtested by peers in a classroom and the final simulation can be submitted once all issues or feedback mentioned has been addressed.
                    </p>
                </div>
            </div>
        </div>

        <!-- Deliverables -->

        <Deliverables/>

        <!--  -->

        <!-- <Rubric/> -->

        <!--  -->

        <div class="flex flex-col gap-5">
            <p class="text-2xl font-bold">
                Curriculum Mapping & Strategic Foundations
            </p>

            <div class="collapse border border-gray-600">
                <input type="checkbox" />
                <div class="collapse-title font-bold text-xl">SCSA WA Year 9 HASS & Digital Techonoliges Syllabus Codes</div>
                <div class="collapse-content text-base">
                    <div class="flex flex-col gap-3 m-5">
                        <p class="">
                            <span class="font-bold">
                                Geography (ACHGK060 / ACHGK061 / ACHGK064):
                            </span>
                            Biomes produce food, industrial materials, and ecosystem
                            services; human alteration of biomes (e.g., WA Wheatbelt land clearing, soil salinity, water diversion); challenges to food security in Australia and Asian region.
                        </p>
                        <p>
                            <span class="font-bold">
                                Economics & Business (ACHEK038 / ACHEK039):
                            </span>
                            How markets operate to allocate resources; innovation and technological advancements in Australian industries and competitive advantage.
                        </p>
                        <p>
                            <span class="font-bold">
                                Civics & Citizenship (ACHCK075 / ACHCK076):
                            </span>
                            The influence of citizens, interest groups, and media on environmental policies and WA parliamentary decision-making processes.
                        </p>
                        <p>
                            <span class="font-bold">
                                Digital Technologies (ACTDIP038 / ACTDIP040):
                            </span>
                            Design algorithms involving control structures and
                            user interface flows; implement programs using Python/Scratch blocks with physical micro:bit
                            sensors.
                        </p>
                    </div>
                </div>
            </div>

            <div class="collapse border border-gray-600">
                <input type="checkbox" />
                <div class="collapse-title font-bold text-xl">APST Teacher Standards Rational (APST 1.5, 2.6, 6.2)</div>
                <div class="collapse-content text-base">
                    <div class="flex flex-col gap-3 m-5">
                        <p>
                            <span class="font-bold">
                                APST 1.5 (Differentiating Teaching):
                            </span>
                            Implements Digital Curation for Teachers (DC-PLN) frameworks (Dayan & Tsybulsky, 2026). Dual-coded infographics, closed-captioned videos, audio podcasts with transcripts, and structured visual storyboards support EAL/D learners and students experiencing coding anxiety.
                        </p>
                        <p>
                            <span class="font-bold">
                                APST 2.6 (Effective ICT Integration):
                            </span>
                            Integrates physical micro:bit sensor hardware into HASS inquiry, turning abstract geography and economic principles into active, student-led Ag-Tech innovation.
                        </p>
                        <p>
                            <span class="font-bold">
                                APST 6.2 (Professional Engagement):
                            </span>
                            Draws on contemporary STEM and computational thinking meta-syntheses (Graßl & Fraser, 2024; Mills et al., 2025; Maslin et al., 2025) to refine inclusive secondary technologies practice.
                        </p>
                    </div>
                </div>
            </div>

        </div>
    </div>

</template>