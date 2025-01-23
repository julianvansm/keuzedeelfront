<template>
 <div class="image-list ">
   <img class=" object-cover"
        :src="project.image"
        alt="hoi"
   />
   <div class="bg-white h-fit p-2">
     <p>{{project.title}}</p>
     <p>{{project.description}}</p>
   </div>
 </div>
</template>

<script>

export default {


  props: {
    project: Object,
  },

  methods: {

  },
};
</script>

<style scoped>

</style>