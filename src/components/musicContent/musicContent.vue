<!-- eslint-disable-line no-mixed-spaces-and-tabs -->
<template>
  <section class="musicContent">
    <div class="container-flex">
      <div class="card" style="max-width: 20rem">
        <img
          src="@/assets/img/cbjr.jpeg"
          alt="Image"
          class="card-img-top"
        />
        <div class="card-body">
          <h4 class="card-title">Charlie Brown JR</h4>
        </div>
      </div>

      <div class="card" style="max-width: 20rem">
        <img
          src="@/assets/img/cpi.jpeg"
          alt="Image"
          class="card-img-top"
        />
        <div class="card-body">
          <h4 class="card-title">Capital inicial</h4>
        </div>
      </div>

      <div class="card" style="max-width: 20rem">
        <img
          src="@/assets/img/isa.jpg"
          alt="Image"
          class="card-img-top"
        />
        <div class="card-body">
          <h4 class="card-title">Isadora Pompeo</h4>
        </div>
      </div>

    </div>
  </section>
</template>


<script>
export default {
  name: "MusicContent",

  data() {
    return {
      info: null,
    };
  },
};
</script>

<style scoped>
.musicContent {
  padding: calc(var(--padding-y) + 5rem) var(--padding-x);
}

.card {
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: var(--black-light-color);
  background-clip: border-box;
  border-radius: 1rem;
  margin-bottom: 5px;
}

@media (min-width: 720px) {
  .card {
    margin: 5px;
  }
}

.card .card-img-top {
  border-top-left-radius: 1rem;
  border-top-right-radius: 1rem;
  width: 100%;
  height: 80%;
}

.card .card-body {
  flex: 1 1 auto;
  min-height: 1px;
  padding: 1.25rem;
}

.card .card-body .card-title {
  margin-bottom: 0.75rem;
  font-size: 1.5rem;
  color: var(--primary-color);
}

.container-flex {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
</style>