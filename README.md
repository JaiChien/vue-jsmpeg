# vue-jsmpeg
將 JSMpeg js 轉成Vue.js可以用的模組使用~

Demo
'''
<script>
import JSMpeg from 'vue-jsmpeg';
export default {
  created:function(){
    let url = 'ws://localhost:9991'
    let canvas = document.getElementById("cam1")
    let player1 = new JSMpeg.Player(url, {
        canvas: canvas,
        autoplay: true
    })
  }
}
</script>
'''
