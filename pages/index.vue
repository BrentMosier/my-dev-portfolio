<template>
    <div class="h-full py-6">
      <div>Profile picture</div>
      <div class="p-8 border-2 border-solid border-red-600">Senior Software Engineer and UI/UX Designer</div>
      <div class="p-8 border-2 border-solid border-red-600">Building simple to use interfaces for complex and efficient solutions</div>
      <div class="p-8 border-2 border-solid border-red-600">I've been a softwre engineer for nearly a decade with experience as a front end web dev, back end engineer, and AR/VR Designer.
        I've worked in the health tech space, behavioral health space, and in graph databases. I love learning about a tech process inside 
        and out to help me design the simplest user interfaces so clients can get the most out of a product.
      </div>
      <TechCard title="Languages Known">
        <IconWithTooltip iconName="vscode-icons:file-type-js-official" tooltipText="Javascript"/>
        <IconWithTooltip iconName="vscode-icons:file-type-typescript-official" tooltipText="Typescript"/>
        <IconWithTooltip iconName="vscode-icons:file-type-html" tooltipText="HTML"/>
        <IconWithTooltip iconName="vscode-icons:file-type-css" tooltipText="CSS"/>
        <IconWithTooltip iconName="vscode-icons:file-type-python" tooltipText="Python"/>
        <IconWithTooltip iconName="vscode-icons:file-type-csharp" tooltipText="C Sharp"/>
      </TechCard>
      <div class="flex flex-row gap-x-8">
      <TechCard title="Front End" class="basis-1/2">
        <IconWithTooltip iconName="vscode-icons:file-type-vue" tooltipText="Vue"/>
        <IconWithTooltip iconName="vscode-icons:file-type-reactjs" tooltipText="React"/>
        <IconWithTooltip iconName="vscode-icons:file-type-nuxt" tooltipText="Nuxt"/>
        <IconWithTooltip iconName="vscode-icons:file-type-next" tooltipText="Next"/>
        <IconWithTooltip iconName="vscode-icons:file-type-tailwind" tooltipText="Tailwind"/>
        <IconWithTooltip iconName="vscode-icons:file-type-graphql" tooltipText="GraphQL"/>
        <IconWithTooltip iconName="vscode-icons:file-type-angular" tooltipText="Angular"/>
      </TechCard>
      <TechCard title="Back End" class="basis-1/2">
        <IconWithTooltip iconName="logos:fastapi-icon" tooltipText="FastAPI"/>
        <UTooltip text="TigerGraph">
          <NuxtImg src="/TigerGraph-logo.png" width="48px" height="48px"/>
        </UTooltip>
        <IconWithTooltip iconName="vscode-icons:file-type-mongo" tooltipText="MongoDB"/>
        <IconWithTooltip iconName="vscode-icons:file-type-mysql" tooltipText="MySQL"/>
        <IconWithTooltip iconName="vscode-icons:file-type-pgsql" tooltipText="PostgreSQL"/>
        <IconWithTooltip iconName="logos:aws" tooltipText="AWS"/>
        <IconWithTooltip iconName="logos:nodejs-icon" tooltipText="Node"/>
        <IconWithTooltip iconName="vscode-icons:file-type-serverless" tooltipText="Serverless"/>
      </TechCard>
    </div>
      <TechCard title="Other Skills">
        <IconWithTooltip iconName="mdi:unity" tooltipText="Unity"/>
        <IconWithTooltip iconName="logos:godot-icon" tooltipText="Godot"/>
      </TechCard>
      <TechCard title="Companies Worked At">
        <UTooltip text="TigerGraph">
          <NuxtImg src="/TigerGraph-logo.png" width="48px" height="48px"/>
        </UTooltip>
        <UTooltip text="Optum">
          <NuxtImg src="/Optum_logo_2021.svg.png" sizes="150px"/>
        </UTooltip>
      </TechCard>
      <TechCard title="Education">
        <UTooltip text="Penn State">
          <NuxtImg src="/Penn-State-Logo.png" sizes="150px"/>
        </UTooltip>
      </TechCard>
    </div>
  </template>
  
  <script setup>
  import {ref} from 'vue'
  
  const count = ref(20)
  </script>
  