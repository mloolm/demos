---
layout: layout.njk
title: Glitch Demo
---

<div class="text-center">
  <h1 class="display-5 mb-4">Glitch Demo</h1>
  <p class="lead mb-4">
    Below is an example of the <strong>glitch-effect</strong> in action.
  </p>

  <!-- Здесь вставь демонстрацию -->
  <div class="my-5">
        <div id="glitch-target"></div>
  </div>

  <p>You can apply the glitch effect to any layer using the <a href="https://www.npmjs.com/package/glitch-effect">glitch-effect</a> package.</p>
</div>

<script src="/demos/assets/glitch-effect.min.js"></script>
<script>
const container = document.getElementById('glitch-target');
const glitch = new GlitchEffect(container, '/demos/assets/demo.jpeg', {
  intensity: 1,
  noise: true
});

</script>
