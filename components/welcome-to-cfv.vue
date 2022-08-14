<template>
<div>
    <section class="welcome-container">
        <div class="welcome-header">
            <h1>Welcome to Code For Vegas</h1>
        </div>
    </section>
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
}

.welcome-header {
    color: #fff;
    font-family: 'Roboto Mono', monospace;
    font-weight: 500;
    animation: typing 2s steps(25), blink 1s step-end infinite;
    white-space: nowrap;
    overflow: hidden;
    border-right: 2px solid #fff;
   }

@keyframes typing {
  from {
    width: 0%
  }

  to {
    width: 100%;
  }
}
    
@keyframes blink {
  50% {
    border-color: transparent
  }
}
</style>