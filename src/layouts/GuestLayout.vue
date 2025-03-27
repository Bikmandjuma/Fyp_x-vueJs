<template>
    <div>

      <nav class="bg-blue-700 shadow-xl p-4">

        <div class="flex text-center items-center justify-center">
                <!-- <img
                  aria-hidden="true"
                  class="object-cover dark:hidden"
                  src="../assets/Homepage_images/sobre.jpg"
                  width="40"
                  height="40"
                />
               -->
                &nbsp;&nbsp;<router-link to="#" class="inline-block mt-1 text-2xl font-bold tracking-wider bg-gradient-to-b from-white to-white bg-clip-text text-transparent" style="font-family: sa;font-style: italic;">Predictive Maintenance Using IoT and Machine Learning in the Milk 
                  Industry</router-link>
        </div>
      </nav>

      <main>
        <slot></slot>
      </main>
  
    </div>
</template>
  
  <script>
  export default {
    name: 'GuestLayout'
  }
  </script>
  
  <style scoped>
    a{
      text-decoration: none;
    }
  </style>
  