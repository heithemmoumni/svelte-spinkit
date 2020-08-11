<script>
  export let name;
  export let color;
  import "./css/global.css";
  import "./css/wave.css";
  import "./css/circle.css";
  import "./css/fading-circle.css";
  import "./css/flow.css";
  import "./css/fold-cube.css";
  import "./css/grid-cube.css";
  import "./css/pulse.css";
  import "./css/swing.css";
  import "./css/wander-cube.css";
  import "./css/double-bounce.css";
  import "./css/rotating-plane.css";
  import "./css/chasing-dots.css";

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
