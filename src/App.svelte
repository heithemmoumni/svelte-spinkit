<script>
  import Spinner from "./Spinner.svelte";
</script>

<style>
  code {
    padding: 5px 5px;
    margin-bottom: 35px;
    display: block;
    margin-top: 35px;
    background-color: rgba(0, 0, 0, 0.04);
    border-radius: 3px;
    font-family: "Liberation Mono", Courier, monospace;
    width: fit-content;
  }
  main {
    width: 70%;
    margin-bottom: 50px;
    padding: 20px 40px;
  }
  .d-flex {
    display: flex;
    justify-content: space-between;
  }
  .d-flex > div {
    width: 100%;
  }
</style>

<main>
  <h1>Svelte-Spinkit</h1>
  <h2>
    <a href="https://github.com/heithemmoumni/svelte-Spinkit">
      Browser in github
    </a>
  </h2>
  <h3>Spinkit Spinners</h3>

  <div class="d-flex">
    <div>
      <code>&lt;Spinner name="circle" /&gt;</code>
      <Spinner name="circle" />
    </div>
    <div>
      <code>&lt;Spinner name="circle" color="red" /&gt;</code>
      <Spinner name="circle" color="red" />
    </div>
  </div>

  <div class="d-flex">
    <div>
      <code>&lt;Spinner name="pulse" /&gt;</code>
      <Spinner name="pulse" />
    </div>
    <div>
      <code>&lt;Spinner name="pulse" color="blue" /&gt;</code>
      <Spinner name="pulse" color="blue" />
    </div>
  </div>

  <div class="d-flex">

    <div>
      <code>&lt;Spinner name="cube-grid" /&gt;</code>
      <Spinner name="cube-grid" />
    </div>
    <div>
      <code>&lt;Spinner name="cube-grid" color="red" /&gt;</code>
      <Spinner name="cube-grid" color="red" />
    </div>

  </div>

  <div class="d-flex">

    <div>
      <code>&lt;Spinner name="wave" /&gt;</code>
      <Spinner name="wave" />
    </div>
    <div>
      <code>&lt;Spinner name="wave" color="red" /&gt;</code>
      <Spinner name="wave" color="red" />
    </div>

  </div>

  <div class="d-flex">

    <div>
      <code>&lt;Spinner name="folding-cube" /&gt;</code>
      <Spinner name="folding-cube" />
    </div>
    <div>
      <code>&lt;Spinner name="folding-cube" color="red" /&gt;</code>
      <Spinner name="folding-cube" color="red" />
    </div>

  </div>

  <div class="d-flex">

    <div>

      <code>&lt;Spinner name="double-bounce" /&gt;</code>
      <Spinner name="double-bounce" />
    </div>
    <div>

      <code>&lt;Spinner name="double-bounce" color="red" /&gt;</code>
      <Spinner name="double-bounce" color="red" />
    </div>
  </div>

  <div class="d-flex">

    <div>
      <code>&lt;Spinner name="rotating-plane" /&gt;</code>
      <Spinner name="rotating-plane" />
    </div>
    <div>
      <code>&lt;Spinner name="rotating-plane" color="red" /&gt;</code>
      <Spinner name="rotating-plane" color="red" />
    </div>
  </div>

  <div class="d-flex">

    <div>
      <code>&lt;Spinner name="chasing-dots" /&gt;</code>
      <Spinner name="chasing-dots" />
    </div>
    <div>
      <code>&lt;Spinner name="chasing-dots" color="red" /&gt;</code>
      <Spinner name="chasing-dots" color="red" />
    </div>
  </div>

</main>
