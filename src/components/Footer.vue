<template>
  <section>
    <div class="row at-row flex-center flex-middle">
      <div class="col-lg-24">
        <hr class="footspace">
      </div>
    </div>
    <div class="row at-row flex-center flex-middle">
      <div class="col-lg-24">
        <img src="/static/img/msft_logo.png">
        <img src="/static/img/rh_logo.png">

      </div>
    </div>
    <div class="row at-row flex-center flex-middle">
      <div class="col-lg-6">
      </div>
      <div class="col-lg-12 credits">
        Azure Red Hat OpenShift workshop - Something added by Jay
      </div>
      <div class="col-lg-6">
      </div>
    </div>
    <div class="row at-row flex-center flex-middle credits-tag">
      <div class="col-lg-6">
      </div>
      <div class="col-lg-6">
      </div>
    </div>
    <div class="row at-row flex-center flex-middle credits-other">
      <div class="col-lg-6">
      </div>
      <div class="col-lg-12">
      </div>
      <div class="col-lg-6">
      </div>
    </div>
    <div class="row at-row flex-center flex-middle credits-other">
      <div class="col-lg-6">
      </div>
      <div class="col-lg-12">
      </div>
      <div class="col-lg-6">
      </div>
    </div>
   <div class="row at-row flex-center flex-middle">
      <div class="col-lg-24">
        <h1>
          <!-- modifying code here -->
          </h1>
      </div>
   </div>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        k8sNodeName: process.env.KUBE_NODE_NAME,
        k8sPodName: process.env.KUBE_POD_NAME,
        k8sPodIp: process.env.KUBE_POD_IP
      };
    }
  };
</script>
