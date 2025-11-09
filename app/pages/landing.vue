<template>
  <AuroraBackground>
    <div class="relative z-10 flex flex-col items-center justify-center gap-6 px-4 text-center">
      <h1 class="text-4xl font-bold md:text-7xl dark:text-white">
        Welcome to Blogr
      </h1>
      <p class="max-w-2xl text-lg font-light md:text-2xl dark:text-neutral-200">
        Create beautiful blogs with stunning backgrounds and modern design
      </p>
      <div class="flex gap-4">
        <Button size="lg" class="text-base">
          Get Started
        </Button>
        <Button size="lg" variant="outline" class="text-base">
          Learn More
        </Button>
      </div>
    </div>
  </AuroraBackground>
</template>

<script setup lang="ts">
import { AuroraBackground } from "~/components/ui/aurora-background";
import { Button } from "~/components/ui/button";

definePageMeta({
  layout: "blank",
});
</script>
