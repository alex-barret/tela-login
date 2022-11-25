<template>
  <div>
    <div class="primeira">
      <form class="form">
        <h1>Cadastrar</h1>

        <label>
          <span>Seu e-mail:</span>
          <input type="email" name="email" />
        </label>

        <label>
          <span>Senha:</span>
          <input type="password" name="password" />
        </label>

        <button class="submit" type="submit">Cadastrar</button>
      </form>
    </div>

    <div class="segunda">
      <form class="form">
        <h1>Logar</h1>
        <label>
          <span>Seu e-mail:</span>
          <input type="email" name="email" />
        </label>

        <label>
          <span>Senha:</span>
          <input type="password" name="password" />
        </label>

        <button class="submit" type="submit">Logar</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.primeira {
  display: inline-block;
  background: #fff;
  box-shadow: 0 19px 38px black, 0 15px 12px rgba(0, 0, 0, 0.22);
  border-radius: 25px;
  width: 40%;
}

.segunda {
  display: inline-block;
  background: #fff;
  box-shadow: 0 19px 38px black, 0 15px 12px rgba(0, 0, 0, 0.22);
  border-radius: 25px;
  width: 40%;
  margin-left: 30px;
}

input,
bottom {
  border: none;
  outline: none;
  background: none;
}

h1 {
  color: black;
  padding-top: 10px;
  font-size: 30px;
}

.form {
  padding: 50px 30px;
  -webkit-transition: -webkit-transform 1.2s ease-in-out;
  transition: -webkit-transform 1.2s ease-in-out;
  transition: transform 1.2s ease-in-out;
  transition: transform 1.2s ease-in-out, -webkit-transform 1.2s ease-in-out;
}

label {
  display: block;
  width: 260px;
  margin: 25px auto 0;
  text-align: center;
}

label span {
  font-size: 14px;
  font-weight: 600;
  color: #505f75;
  text-transform: uppercase;
}
</style>