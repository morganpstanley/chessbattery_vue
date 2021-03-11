<template>
  <chessboard />
</template>

<script>
import {chessboard} from 'vue-chessboard'
import 'vue-chessboard/dist/vue-chessboard.css'

export default {
  name: 'ChessArea',
  components: {
    chessboard  
  }
}
</script>