<template>
  <div class="container">
    <div
      class="d-flex justify-content-center align-items-center"
      style="height: 100vh"
    >
      <div class="text-center">
        <h2>Release surprise!</h2>
        <p class="h4 fw-bold">50% OFF MDB PRO</p>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <img
              src="https://mdbootstrap.com/img/Marketing/campaigns/50off-SJARV.png"
              class="img-fluid"
              alt=""
            />
          </div>
        </div>

        <h5 class="mb-3">
          Use this coupon code before it expires and claim the reward
        </h5>
        <p class="mb-3">
          The coupon code will be valid until the end of the week
        </p>

        <div class="mt-2">
          <!--Coupon code-->
          <code class="h2 border rounded py-1 px-5 flex-item me-2"
            >T9TTVSQB</code
          >
          <br />

          <!--Copy to clipboard-->

          <a
            id="disc-50"
            href="#"
            type="button"
            class="btn-lg btn-info"
            style="background-color: #009fe7"
            >COPY TO CLIPBOARD <i class="far fa-copy ml-2"></i
          ></a>
          <a
            class="btn btn-outline-primary btn-lg mt-3"
            href="https://mdbootstrap.com/docs/standard/getting-started/"
            target="_blank"
            style="border-color: #009fe7; color: #009fe7"
            role="button"
            >Start MDB tutorial</a
          >
        </div>
        <p>See <a href="https://mdbootstrap.com/pro/">prices</a></p>
        <div
          class="my-2 alert alert-success"
          id="code-success"
          style="display: none"
        >
          Copied
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
