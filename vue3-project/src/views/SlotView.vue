<!-- Template -->
<template>
  <div>
    <!-- Sử dụng SlotComponent với khe (slot) có tên "details" -->
    <SlotComponent>
      Đây là nội dung mặc định.
      <template #details>
        Đây là nội dung chi tiết.
      </template>
    </SlotComponent>
  </div>
</template>

<!-- Script -->
<script setup>  
import SlotComponent from '@/components/SlotComponent.vue';
</script>
