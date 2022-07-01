<template>

  <button @click="addLike">Like</button>
  <button @click="addDislike">Dislike</button>
  <div>Кол-во лайков: {{ likes }} </div>
  <div>Кол-во лайков: {{ dislikes }} </div>
</template>


<script>
export default {
  data() {
    return {
      likes: 0,
      dislikes: 5,
    }
  },
  methods: {
    addLike() {
      this.likes += 1
    },
    addDislike() {
    this.dislikes += 1
  }
  }
  
}

</script>



<style>

</style>
