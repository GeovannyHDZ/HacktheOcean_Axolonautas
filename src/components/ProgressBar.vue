<script>

</script>

<template>
    <div class="container">
  <div class="progress-container">
    <div class="progress" id="progress"> </div>
    <div class="circle active">25%</div>
    <div class="circle">50%</div>
    <div class="circle">75%</div>
    <div class="circle">100%</div>
  </div>
</div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');

:root {
  --line-border-fill: #3498db;
  --line-border-empty: #e0e0e0;
}

.container {
  margin-top: 15px;
  text-align: center;
  margin-left: 40px;
}

.progress-container::before {
  content: "";
  background: var(--line-border-empty);
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50%);
  height: 4px;
  width: 100%;
  z-index: -1;
}

.progress-container {
  display: flex;
  justify-content: space-between;
  position: relative;
  margin-bottom: 30px;
  max-width: 100%;
  width: 350px;
}

.progress {
  background: var(--line-border-fill);
  position: absolute;
  top: 50%;
  left: 0;
  transform: translateY(-50%);
  height: 4px;
  width: 0%;
  z-index: -1;
  transition: 0.4s ease;
}

.circle {
  background: #fff;
  color: #999;
  border-radius: 50%;
  height: 50px;
  width: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 3px solid var(--line-border-empty);
  transition: .4s ease;
}

.circle.active {
  border-color: var(--line-border-fill);
}

.btn {
  background-color: var(--line-border-fill);
  color: #fff;
  cursor: pointer;
  font-family: inherit;
  border: 0;
  border-radius: 6px;
  padding: 8px 30px;
  margin: 5px;
  font-size: 14px;
}

.btn:active {
  transform: scale(0.98);
}

.btn:focus {
  outline: 0;
}

.btn:disabled {
  background-color: var(--line-border-empty);
  cursor: not-allowed;
}



</style>