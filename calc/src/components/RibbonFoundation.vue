
<template>
  <!-- <div class="row text-h6">Онлайн калькулятор расчета размеров, арматуры и количества бетона монолитного ленточного фундамента</div> -->
  <div class="row full-width">
    <div class="col-5 text-subtitle1">
      Тип фундамента
    </div>
    <div class="col-7">
      <q-select outlined :options="options" label="Outlined"></q-select>
    </div>
  </div>
    <div class="row full-width">
    <div class="col-5 text-subtitle1">
      Тип фундамента
    </div>
    <div class="col-7">
      <q-input
        type="number"
        filled
      ></q-input>
    </div>
  </div>
    <div class="row full-width">
    <div class="col-5 text-subtitle1">
      Тип фундамента
    </div>
    <div class="col-7">
      <q-input
        type="number"
        filled
      ></q-input>
    </div>
  </div>
    <div class="row full-width">
    <div class="col-5 text-subtitle1">
      Тип фундамента
    </div>
    <div class="col-7">
      <q-input
        type="number"
        filled
      ></q-input>
    </div>
  </div>
</template>

<script lang="ts">
/* eslint-disable semi */
import { Vue } from 'vue-class-component'
export default class RibbonFoundation extends Vue {
  private options:string[] = ['Google', 'Facebook', 'Twitter', 'Apple', 'Oracle'];
}
</script>
