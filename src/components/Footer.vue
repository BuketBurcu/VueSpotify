<template>
  <div class="container container-fluid fixed-bottom footer">
    <div class="row">
      <div class="col-3">
        <div class="card mb-3" style="max-width: 540px">
          <div class="row no-gutters">
            <div class="col-md-4">
              <img
                src="https://picsum.photos/id/25/70/70"
                class="rounded"
                style="text-align: left"
              />
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h5 class="card-title">Sana Değer</h5>
                <p class="card-text">Yıldız Tilbe</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="row play">
          <button class="rounded-circle ms-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
              <path
                d="M73 39c-14.8-9.1-33.4-9.4-48.5-.9S0 62.6 0 80V432c0 17.4 9.4 33.4 24.5 41.9s33.7 8.1 48.5-.9L361 297c14.3-8.7 23-24.2 23-41s-8.7-32.2-23-41L73 39z"
              />
            </svg>
          </button>
          <button class="rounded-circle ms-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
              <path
                d="M52.5 440.6c-9.5 7.9-22.8 9.7-34.1 4.4S0 428.4 0 416V96C0 83.6 7.2 72.3 18.4 67s24.5-3.6 34.1 4.4l192 160L256 241V96c0-17.7 14.3-32 32-32s32 14.3 32 32V416c0 17.7-14.3 32-32 32s-32-14.3-32-32V271l-11.5 9.6-192 160z"
              />
            </svg>
          </button>
          <button class="rounded-circle ms-2">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
              <path
                d="M267.5 440.6c9.5 7.9 22.8 9.7 34.1 4.4s18.4-16.6 18.4-29V96c0-12.4-7.2-23.7-18.4-29s-24.5-3.6-34.1 4.4l-192 160L64 241V96c0-17.7-14.3-32-32-32S0 78.3 0 96V416c0 17.7 14.3 32 32 32s32-14.3 32-32V271l11.5 9.6 192 160z"
              />
            </svg>
          </button>
        </div>
        <div class="row play">
          <div class="progress">
            <div
              class="progress-bar w-75"
              role="progressbar"
              aria-valuenow="75"
              aria-valuemin="0"
              aria-valuemax="100"
            ></div>
          </div>
        </div>
      </div>
      <div class="col-3">
        <button class="rounded-circle ms-2">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
            <path
              d="M301.1 34.8C312.6 40 320 51.4 320 64V448c0 12.6-7.4 24-18.9 29.2s-25 3.1-34.4-5.3L131.8 352H64c-35.3 0-64-28.7-64-64V224c0-35.3 28.7-64 64-64h67.8L266.7 40.1c9.4-8.4 22.9-10.4 34.4-5.3zM412.6 181.5C434.1 199.1 448 225.9 448 256s-13.9 56.9-35.4 74.5c-10.3 8.4-25.4 6.8-33.8-3.5s-6.8-25.4 3.5-33.8C393.1 284.4 400 271 400 256s-6.9-28.4-17.7-37.3c-10.3-8.4-11.8-23.5-3.5-33.8s23.5-11.8 33.8-3.5z"
            />
          </svg>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  background-color: rgb(0, 0, 0);
  width: 100%;
  width: 1345px;
  height: 95px;
  margin-left: 0%;
}
.row {
  background-color: rgb(0, 0, 0);
  width: 1345px;
  height: 95px;
  margin-left: 0%;
}
.card {
  background-color: rgb(41, 40, 40, 0.4);
  margin-left: 2px;
  width: 300px;
  height: 70px;
  text-align: left;
}
.card-img {
  width: 55px;
  height: 55px;
  margin-top: 5px;
}
button.card-button {
  background-color: rgb(41, 40, 40, 0.4);
  margin-left: 2px;
  width: 300px;
  height: 70px;
  text-align: left;
}
div h5 {
  color: white;
}
div p {
  font-size: 13px;
  color: darkgray;
}
.col-md-8 {
  padding: 0;
  margin: 0;
}
.col-md-4 {
  width: 90px;
}
/* button { */
  /* background-color: rgba(232, 232, 232, 0.2);
} */
.play {
  height: 700px;
  width: 50px;
  z-index: 3;
}
</style>
