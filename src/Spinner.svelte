<script>
  export let name;
  export let color;

  require("./css/global.css");
  require("./css/wave.css");
  require("./css/circle.css");
  require("./css/fading-circle.css");
  require("./css/flow.css");
  require("./css/fold-cube.css");
  require("./css/grid-cube.css");
  require("./css/pulse.css");
  require("./css/swing.css");
  require("./css/wander-cube.css");
  require("./css/double-bounce.css");
  require("./css/rotating-plane.css");
  require("./css/chasing-dots.css");

  const spinkitSpinners = {
    circle: { className: "sk-circle", divCount: 12 },
    "cube-grid": { className: "sk-grid-cube", divCount: 9 },
    wave: { className: "sk-wave", divCount: 5 },
    "folding-cube": { className: "sk-folding-cube", divCount: 4 },
    "three-bounce": { className: "sk-three-bounce", divCount: 3 },
    "double-bounce": { className: "sk-double-bounce", divCount: 2 },
    "wandering-cubes": { className: "sk-wandering-cubes", divCount: 2 },
    "chasing-dots": { className: "sk-chasing-dots", divCount: 2 },
    "rotating-plane": { className: "sk-rotating-plane", divCount: 1 },
    pulse: { className: "sk-pulse", divCount: 1 }
  };

  const spinnerInfo = spinkitSpinners[name] || spinkitSpinners["three-bounce"];
  console.log(spinnerInfo);
</script>

<style>

</style>

<div
  class="sk-fade-in sk-fade-in {spinnerInfo['className']}"
  style="color: {color || '#000'};">
  {#each Array(spinnerInfo.divCount) as _, i}
    <div />
  {/each}
</div>
