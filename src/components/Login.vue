<template>
    <div class="outside-box">
      <b-container class="bv-example-row">
        <b-row class="justify-content-md-center">
          <b-col cols="12" id="mainLogin">
            <b-card-group deck class="mb-3">
              <b-card border-variant="dark" header="Login" align="center">
                <b-card-text>
                  <b-container fluid>
                    <b-row class="my-1">
                      <b-form-input name='username' id="username" :state="null" placeholder="Username" autocomplete="false"></b-form-input>
                    </b-row>
                    <b-row class="my-1">
                      <b-form-input name='password' id='password' type="password" placeholder="Password"></b-form-input>
                    </b-row>
                    <b-row class="my-1">
                      <b-form-checkbox>Remmerber Me</b-form-checkbox>
                    </b-row>
                    <b-button variant="outline-primary">Login</b-button>
                  </b-container>
                </b-card-text>
              </b-card>
            </b-card-group>
          </b-col>
        </b-row>
      </b-container>
    </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#app {
  background-color: #f9f9f9;
}
.outside-box {
  padding: 30px;
}
#mainLogin {
  margin: 0 auto;
  width: 300px;
}
</style>
