<template>
  <div>

   <AppHeader/>

    <NuxtPage/>
   
   <AppFooter/>

  </div>
</template>

<script setup>


useHead({
    title: 'trial3',
    link: [
    {
      href:"https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css", rel:"stylesheet"
    }
    ],
    script : [
      {src: "https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
  }]
  })
</script>