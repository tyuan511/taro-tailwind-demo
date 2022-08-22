<template>
  <view class="text-[48px] text-[#ff0000]">
    <text>{{ msg }}</text>
  </view>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import './index.css';

const msg = ref('Hello world');
</script>
