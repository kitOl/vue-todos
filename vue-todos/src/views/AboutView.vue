<template>
  <div class="about">
    <h1>Vue Todos</h1>
    <p>
      Vue Todos is a CRUD Todo tracking application created for a Vue 3 Crash
      Course by John Komarnicki.
    </p>
    <p>
      Track your daily task's using this todo tracker with abilities tos save,
      complete, edit & delete todo.
    </p>
    <p>
      Feel free to add on to this applications with functionalitites such as the
      ability to drag and reorder todos, animate creation/deletion of todos or
      even create this into a full stack application with the ability to have
      different lists for different days of tracking todos!
    </p>
  </div>
</template>

<style>
p {
  margin-top: 15px;
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
