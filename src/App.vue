<template>
  <MyBtn
    large
    color="red">
    Just Go
  </MyBtn>
  <MyBtn
    color="black">
    <span style="color : red">I'll Go</span>
  </MyBtn>
  <MyBtn
    :color="color">
    For YOUITOI
  </MyBtn>
  <MyBtn
    large>
    Just I'll Go
  </MyBtn>
</template>

<script>
import MyBtn from '~/components/Mybtn';

export default {
  components: {
    MyBtn
  },
  data(){
    return{
      color : '#000'
    }
  }
}
</script>

