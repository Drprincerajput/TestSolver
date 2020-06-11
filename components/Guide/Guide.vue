<template>
  <div>
    <b-container fluid class="text-light text-center">
      <b-row class="mb-3">
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/uptet.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>UPTET</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/cbse.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>
                <nuxt-link to="/CBSE">CBSE</nuxt-link>
              </strong>
            </figcaption>
          </figure>
        </b-col>

        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/ctet.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>CTET</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/ibps.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>IBPS</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/lic.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>LIC</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img
              src="@/assets/railway.png"
              v-bind="mainProps"
              rounded="circle"
              alt="Circle image"
            ></b-img>
            <figcaption class="figure-caption">
              <strong>RAILWAY</strong>
            </figcaption>
          </figure>
        </b-col>
      </b-row>
      <b-row class="mb-3">
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/rbi.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>RBI</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/sbi.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>SBI</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/ssc.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>SSC</strong>
            </figcaption>
          </figure>
        </b-col>
        <b-col md="2" class="ml-auto mr-auto p-3">
          <figure class="figure">
            <b-img src="@/assets/upsc.png" v-bind="mainProps" rounded="circle" alt="Circle image"></b-img>
            <figcaption class="figure-caption">
              <strong>UPSC</strong>
            </figcaption>
          </figure>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mainProps: {
        blankColor: "#777",
        width: 100,
        height: 100,
        class: "m1"
      }
    };
  }
};
</script>

<style></style>
