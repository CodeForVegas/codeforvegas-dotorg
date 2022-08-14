<template>
<div>
    <b-container class="welcome-container">
        <div class="welcome-header">
            <h1>Welcome to Code For Vegas</h1>
        </div>
    </b-container>
</div>
</template>

<script>
export default {

}
</script>

<style>
.welcome-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 30rem;
    width: 50%;
}

.welcome-header {
    color: #fff;
    font-family: 'Roboto Mono', monospace;
    font-weight: 500;
    overflow: hidden;
    line-height: 1;
    white-space: nowrap;
    border-right: 3px solid #fff;
    animation: text 3.5s steps(35, end), cursor 1s step-end infinite;
   }

@keyframes text {
  from { width: 0; }
  to { width: 100%; }
}
@keyframes cursor {
  from, to { border-color: transparent; }
  50% { border-color: #fff; }
}
</style>