<template>
  <view class="index">
    <input v-model="msg" placeholder="请输入">
    <text>{{ msg }}</text>
  </view>
</template>

<script>
import './index.scss'

export default {
  data () {
    return {
      msg: ''
    }
  }
}
</script>
