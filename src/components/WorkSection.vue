<template>
    <section id="work" class="py-20  overflow-hidden">

        <!-- Header -->
        <div class="mx-auto flex max-w-7xl items-center justify-between gap-6 px-6 ">
            <div class="space-y-1">
                <p class="text-sm font-semibold uppercase tracking-widest text-gray-500">
                    Selected Work
                </p>

                <h2 class="text-5xl font-bold tracking-tight text-gray-900">
                    Work Gallery
                </h2>

                <p class="text-gray-500">
                    A selection of projects I've worked on.
                </p>
            </div>

            <button
                type="button"
                class="pointer-events-auto rounded-lg bg-black px-5 py-2.5
                       text-sm font-medium text-white transition hover:bg-gray-800"
            >
                View More Projects
            </button>
        </div>


        <div class="relative mt-8  py-16">

            <div
                class="pointer-events-none absolute left-1/2 top-1/2
                       h-px w-[140%] -translate-x-1/2 rotate-[7deg]
                       bg-white/10"
            ></div>

            <div
                class="pointer-events-none absolute left-1/2 top-[35%]
                       h-px w-[140%] -translate-x-1/2 -rotate-[4deg]
                       bg-white/5"
            ></div>


            <div class="relative mx-auto max-w-7xl px-6">

                <div
                    class="relative mx-auto flex h-[320px] max-w-6xl
                           items-center justify-center"
                    style="perspective: 1400px"
                >



                  <div
                        class="pointer-events-none absolute left-[1%] hidden
                               w-[400px] overflow-hidden rounded-xl
                               shadow-2xl
                               opacity-70 md:block"
                       
                    >
                        <img
                            src="/projects/audit.png"
                            alt=""
                            class="aspect-[3/2] w-full object-cover"
                        />
                    </div>


                    <!-- Main -->
                    <div
                        class="pointer-events-none relative z-30 w-[90%]
                               max-w-[560px] overflow-hidden rounded-xl
                                shadow-2xl"
                    >
                        <img
                            src="/projects/swom.png"
                            alt="Smart Water Operation Monitoring"
                            class="block aspect-[16/10] bg-white w-full object-contain"
                        />

                        <div
                            class="pointer-events-none absolute inset-0
                                   bg-gradient-to-t from-black/30 to-transparent"
                        ></div>
                    </div>


                    <!-- Right -->
                    <div
                        class="pointer-events-none absolute right-[1%] hidden
                               w-[400px] overflow-hidden rounded-xl
                               shadow-2xl
                               opacity-70 md:block"
                       
                    >
                        <img
                            src="/projects/cms.png"
                            alt=""
                            class="aspect-[3/2] w-full object-cover"
                        />
                    </div>


                </div>


                <!-- Information -->
                <div
                    class="relative z-40 mx-auto mt-12 max-w-3xl
                           text-center"
                >

                    <h2
                        class="text-2xl font-semibold tracking-tight
                               text-black md:text-3xl"
                    >
                       SWOM - Smart Water Operation Monitoring
                    </h2>

                    <p
                        class="mx-auto mt-3 max-w-2xl text-sm leading-6
                               text-gray-600 md:text-base"
                    >
                        Smart Water Operation Monitoring (SWOM) is an IoT-based monitoring platform designed to monitor water resource conditions in real time. The system integrates AWLR, AWS, and ARR sensors to collect and visualize water level, weather, and rainfall data, providing centralized monitoring, historical analytics, and operational insights for more effective water resource management.
                    </p>

                    <a
                        href="https://swompjt2-uw6.info/"
                        target="_blank"
                        class="pointer-events-auto mt-5 inline-flex
                               items-center text-sm font-medium
                               text-black underline underline-offset-4
                               transition hover:text-gray-500"
                    >
                        View Project
                        <span class="ml-1">→</span>
                    </a>

                </div>

            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
</script>