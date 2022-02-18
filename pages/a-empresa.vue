<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto h-10 flex items-center space-x-4 mb-10">
        <NuxtLink :to="{ name: 'a-empresa' }">
          A empresa
        </NuxtLink>
        <NuxtLink :to="{ name: 'servicos' }">
          Serviços
        </NuxtLink>
      </div>
    </div>

    <div>
      <div class="container mx-auto">
        <h1 class="text-lg font-bold">
          A Empresa
        </h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero minima quaerat quibusdam non quidem pariatur nam omnis, eos assumenda! Velit dignissimos tenetur veritatis natus molestias minus quisquam sed mollitia. Ab!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AEmpresaPage',

  data () {
    return {
    }
  },

  mounted () {
  },

  methods: {
  }
}
</script>
