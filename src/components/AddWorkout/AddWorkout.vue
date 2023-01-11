<template>
  <div class="add-workout-container">
    <div class="add-workout-header">
      <div class="header-content">
        <h1 class="title">New Workout</h1>
        <p class="date">01/10/22</p>
      </div>
      <div class="header-btn">
        <input type="button" class="finish-btn" value="Finish" />
      </div>
    </div>
    <div class="exercises-container">
      <input type="button" class="add-exercise-btn" value="Add Exercise" />
    </div>
    <div class="add-workout-footer">
      <input type="button" class="cancel-btn" value="Cancel Workout" />
    </div>
  </div>
</template>

<script>
export default {
  name: "AddWorkout",
  props: {
    msg: String,
  },
};
</script>

<style>
@import url("./style.css");
</style>
