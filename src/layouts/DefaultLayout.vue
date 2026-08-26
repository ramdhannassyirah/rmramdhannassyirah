<template>
    <div>
        <header class="p-4 container mx-auto">
            <nav class="max-w-5xl mx-auto py-4 px-6 bg-white shadow-md rounded-xl">
                <div class="flex items-center gap-4 justify-between uppercase">
                    <div>
                        <p class="text-sm font-semibold tracking-widest bg-secondary text-white rounded-md w-12 h-12 inline-flex items-center justify-center">
                            RDN
                        </p>
                    </div>
                    <div class="space-x-6 text-sm text-secondary font-semibold tracking-widest ">
                        <a href="#work">
                            Work
                        </a>
                         <a href="#about">
                            About
                        </a>
                        <a href="#journey">
                            Journey
                        </a>
                       
                    </div>
                    <button class="border rounded-md py-2 px-4 font-semibold">
                        Let's Talk
                    </button>
                </div>
            </nav>
        </header>

        <main class="container mx-auto py-8">
            <RouterView />
        </main>

        <footer>
        </footer>
    </div>
</template>

<script setup lang="ts">
    import {
        RouterView
    } from 'vue-router'
</script>
