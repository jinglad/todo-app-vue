<template>
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h3 class="text-center">Todo List</h3>
          <div class="todo_list">
            <div class="d-flex justify-content-between">
              <p>Todo list 1</p>
              <div>
                <button class="btn btn-primary btn-sm mr-2">Edit</button>
                <button class="btn btn-success btn-sm mr-2">Done</button>
                <button class="btn btn-danger btn-sm">Remove</button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <h3 class="text-center">Completed List</h3>
          <div class="todo_list">
            <div class="d-flex justify-content-between">
              <p>Todo Task List 1</p>
              <div>
                <button class="btn btn-danger btn-sm">Remove</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: "Todo"
};
</script>

<style scoped>
  .todo_list {
  padding: 20px;
  background-color: lightgray;
  color: black;
  font-size: 18px;
  border-radius: 10px;
  font-weight: 600;
}
</style>