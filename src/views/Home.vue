<template>
  <div class="home container mt-4">
    <div class="jumbotron text-center">
      <h1 class="display-4">Welcome Everyone!</h1>
      <p class="lead mt-4">We could all use a little more organization.</p>
      <hr class="my-4" />
      <p id="intro">This web app aims to help keep your daily agenda in order. More features to come</p>
    </div>
    <div class="container mt-4 loginOrSignup">
      <div class="row">
        <div class="col-md-6">
          <div class="container text-center loginForm">
            <form action="">
              <h5 class="mt-4">Login</h5>
              <div class="row">
                <div class="col">
                  <label for="loginEmail">Email</label>
                  <br />
                  <input id="loginEmail" type="email" />
                </div>
              </div>
              <div class="row">
                <div class="col">
                  <label id="passwordLabel" for="password">Password</label>
                  <br />
                  <input id="password" type="password" />
                </div>
              </div>
              <button type="submit" class="btn loginBtn">Login</button>
            </form>
          </div>
        </div>
        <div class="col-md-6">
          <div class="container text-center signupForm">
            <form action="">
              <h5 class="mt-4">Signup</h5>
              <div class="row">
                <div class="col">
                  <label for="fName">First Name</label>
                  <br />
                  <input type="text" id="fName" />
                </div>
                <div class="col">
                  <label for="lName">Last Name</label>
                  <br />
                  <input type="text" id="lName" />
                </div>
              </div>
              <div class="row">
                <div class="col">
                  <label for="signupEmail">Email</label>
                  <br />
                  <input type="email" id="signupEmail" >
                </div>
              </div>
              <div class="row">
                <div class="col">
                  <label for="signupPassword">Password</label>
                  <br />
                  <input type="password" id="signupPassword">
                </div>
                <div class="col">
                  <label for="confirmPassword">Confirm Password</label>
                  <br />
                  <input type="password" id="confrimPassword">
                </div>
              </div>
              <button type="submit" class="btn signupBtn">Signup</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'home',
};
</script>

<style scoped>
  .home {
    font-family: "Montserrat";
  }

  h1 {
    font-weight: 900;
  }

  .loginOrSignup {
    background-color: #07456f;
  }

  .loginForm {
    background-color: #0f0a3c;
  }

  .signupForm {
    background-color: #0f0a3c;
  }

  #intro {
    width: 33%;
    margin: 10px auto 0 auto;
  }

  button {
    background-color: #cdffeb;
    margin: 10px auto;
    color: #07456f;
  }

  form {
    /* border: 5px solid black; */
    margin: 20px auto;
  }

  label {
    margin-top: 10px;
  }

</style>
