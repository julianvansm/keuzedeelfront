<template>
 <div class="image-list ">
    <img class=" image-cover"
         :src="project.image"
         alt="hoi"
    />
   <div class="text-cover bg-white h-fit p-2">
     <p>{{project.title}}</p>
     <p>{{project.description}}</p>
   </div>
 </div>
</template>

<script>
export default {
  props: { project: Object }
};
</script>

<style scoped>

</style>