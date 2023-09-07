<template>
    <DynTpl :html="html as string" />
</template>

<script setup lang="ts">
import DynTpl from "~/components/dyn-tpl.vue";

const html = ref<string>(`
<div>
    <div style="background-color: aquamarine;">
        <p>AAAAAAAAA</p>
    </div>
    <div style="background-color: yellow;">
        <p>BBBBBBBBBBB</p>
    </div>
    <!-- Comment -->
    <div style="background-color: orange;">
        <div>CCCCCCCCCC</div>
    </div>
    <div style="background-color: aquamarine;">
        <p>AAAAAAAAA</p>
    </div>
    <div style="background-color: yellow;">
        <p>BBBBBBBBBBB</p>
    </div>
    <!-- Comment 2 -->
    <div style="background-color: orange;">
        <div>CCCCCCCCCC</div>
    </div>
</div>
`);
</script>
