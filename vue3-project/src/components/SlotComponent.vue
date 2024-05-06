<template>
    <div>
      <slot></slot>
      <!-- mặc định slot là nội dùng bạn để giữa 2 thẻ mở và đóng , ở đây là <SlotComponent> và <SlotComponent/> . -->
      <div v-if="$slots.details">
        <slot name="details"></slot>
        <!-- khi bạn # tên slot thì sẽ tương ứng vị trí của slot đó  , ở SlotView tôi đặt # details thì nội dung sẽ tương ứng với vị trị slot có name là details -->
      </div>
      
    </div>
  </template>
  
  <script setup>
  </script>
  