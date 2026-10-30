<script setup></script>

<template>
  <h1>You did it!</h1>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>
  <h1>Timer</h1>
  <el-button round>Round</el-button>
  <el-button type="primary" plain>Primary</el-button>

  <button @click="updateTime">Update Time</button>
  <button @click="resetTime">Reset Time</button>
  <button @click="stopTime">Stop Time</button>
  <button @click="startTime">Start Time</button>
  <button @click="pauseTime">Pause Time</button>
  <button @click="resumeTime">Resume Time</button>
  <button @click="resetTime">Reset Time</button>

  <div class="button-row">
    <el-button type="success" dashed>Success</el-button>
  </div>
</template>

<style scoped></style>
