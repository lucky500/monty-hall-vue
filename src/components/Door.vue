<template>
  <div class="area">
      <div class="frame">
          <Gift />
      </div>
      <div class="door">
          <div class="number">{{ number }}</div>
          <div class="knob"></div>
      </div>
  </div>
</template>

<script>
import Gift from './Gift';

export default {
    props: {
        number: { type: Number },
        hasGift: { type: Boolean },
    },
    components:  {
        Gift
    }
}
</script>

<style scoped>
.area {
    position: relative;
    width: 200px;
    height: 310px;
    background-color: #8f5201;
    font-size: 3rem;
}

.frame {
    position: absolute;
    height: 300px;
    width: 180px;

    border-left: var(--frame-border);
    border-top: var(--frame-border);
    border-right: var(--frame-border);

    display: flex;
    justify-content: center;
    align-items: flex-end;

}
</style>