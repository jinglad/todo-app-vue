<template>
  <div class="container">
    <h1 class="text-center my-5 display-1">Todo App</h1>
    <div class="w-50 mx-auto">
      <div class="d-flex mb-5">
        <div class="input_field w-80">
          <input
            type="text"
            placeholder="Add Todo"
            class="form-control form-control-lg"
          />
        </div>
        <div>
          <button class="btn btn-primary ml-2 mt-1">
            Add Todo
          </button>
        </div>
      </div>
    </div>
  </div>
  <Todo />
</template>

<script>
import Todo from "./Todo.vue"

export default {
  name: "AddTask",
  components: {
    Todo
  },
};
</script>

<style>
.w-80 {
  width:80%;
}
.input_field {
  width: "500px";
}
</style>
