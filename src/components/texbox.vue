<template>
  <div>
    <div class="card flex justify-content-center">
    <form @submit="onSubmit" class="flex flex-column gap-2">
        <span class="p-float-label">
            <Textarea id="value" v-model="value" :class="{ 'p-invalid': errorMessage }" rows="getrow()" cols= mycol aria-describedby="text-error" />
            <label for="value">{{mylabel}} {{mycol}} col {{myrows}} row</label>
        </span>
    </form>
    <Toast />
</div>
  </div>
</template>
<script>
  export default{ 
    props:['mycol', 'myrows', 'mylabel'],
    methods:{ 
      getrow(){ 
        return this.myrows
      }
  }
  }
</script>
