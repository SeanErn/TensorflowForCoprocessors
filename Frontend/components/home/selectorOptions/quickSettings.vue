<template>
    <div class="container place-content-center rounded-md bg-base-200 p-3 xl:h-full h-fit w-full mb-auto">
            <div class="py-2">
                <span class="font-bold text-2xl">Quick Settings</span>
            </div>
            <div class="flex-column space-y-2">
                <HomeSelectorOptionsSelectorCamera/>
                <HomeSelectorOptionsSelectorPipeline/>
                <HomeSelectorOptionsSelectorModel/>
                <HomeSelectorOptionsSelectorMinConfidence/>
            </div>
            <p>{{ $pipelineConfig }}</p>
</div>
</template>

<script lang="ts">
const { $pipelineConfig } = useNuxtApp()
</script>
