<template>
  <div class="flex-center">
    <div class="login-card">
      <form class="login-form">
        <h1>Sign in</h1>

        <div class="form-group">
          <label for="email">Your E-mail</label>
          <input type="email" id="email" />
        </div>
        <div class="form-group">
          <label for="password">Password</label>
          <input type="password" id="password" />
        </div>
        <button type="submit">Sign in</button>
      </form>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.login {
  &-card {
    width: 500px;
    background: white;
    padding: 3rem;
    text-align: left;
    h1 {
      margin-top: 0;
      margin-bottom: 1em;
      font-size: 4em;
      letter-spacing: -2px;
      text-align: center;
    }
    button {
      padding: 20px;
      background-color: #4dbd33;
      border: none;
      border-radius: 4px;
      display: block;
      width: 100%;
      color: white;
      font-weight: 600;
      cursor: pointer;
      &:hover {
        background-color: #4ac948;
      }
    }
  }
}
.form-group {
  display: flex;
  flex-direction: column;
  margin-bottom: 2rem;
  input {
    padding: 10px 5px;
  }
  label {
    margin-bottom: 5px;
    color: #afafaf;
    font-size: 0.7rem;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
}
</style>
