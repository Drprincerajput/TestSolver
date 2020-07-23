<template>
  <div>
    <b-navbar toggleable="lg" class="nav">
      <b-navbar-brand>
        <nuxt-link to="/">
          <strong>TestSolver</strong>
        </nuxt-link>
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item>
            <nuxt-link to="/Mocktest">Mock</nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <nuxt-link to="/Previousyear">Previous Year</nuxt-link>
          </b-nav-item>
          <b-nav-item>
            <article variant="light" v-b-modal.modal-1>Download</article>

            <b-modal id="modal-1" title="Download Options">
              <p class="my-4"></p>
              <ol>
                <li>
                  <h6>
                    Mobile
                    <br />
                    <br />
                    <p>
                      Open In Browser (Chrome/Firefox ETC.)
                      <br />Click On ADD TO HOME SCREEN Pop Up!
                      <br />
                    </p>
                  </h6>
                </li>
                <li>
                  <h6>
                    Laptop/PC
                    <br />
                    <br />
                    <p>
                      In Browser Address Bar
                      <br />Click on Circular Plus Button !
                    </p>
                  </h6>
                </li>
              </ol>
            </b-modal>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style>
.nav {
  background-color: #fff;
}
</style>
