<template>
  <main class="flex min-h-screen items-center justify-center">
    <h1 class="text-6xl font-thin text-slate-800">Available Deliveries 🚚</h1>
    <form class="delivery-form" @submit="deliveries">
      <input type="text" placeholder="Delivery" />
      <button type="submit" class="bg-yellow-400 px-2 py-2" @click="deliveries">Deliveries</button>
    </form>
  </main>
</template>
