<template>
    <view>
      <text :style="{ fontSize :40}">
          Texto en H1
      </text>

      <text :style="{ fontSize :30}">
          Texto en H2
      </text>
      <text :style="{ fontSize :20}">
          Texto en H3
      </text>
      <text>
          Texto Comun: A Vue Native component for displaying text. The Text component supports nesting, styling, and touch handling.
      </text>
    </view>
</template>

<style>
.h1 {
   font-size :40
}
.h2 {
   font-size :30
}
.h3 {
   font-size :20
}
</style>