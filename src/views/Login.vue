<template>
  <div id="wrapper">
    <!--Card de Login-->
    <div class="side-a">
      <div class="card">
        <div class="card-header">
          <span>Bem-vindo ao MegaBank!</span>
        </div>
        <form>
          <input
            id="cpf-receive"
            type="text"
            placeholder="Insira o seu CPF"
            autocomplete="off"
          />
          <input type="password" placeholder="Insira a sua senha" />
          <router-link to="/home">
            <input id="button" type="submit" value="Login" />
          </router-link>
        </form>
      </div>
      <div class="footer">
        <p>Ainda não possui uma conta?</p>
        <router-link to="/cadastro">Crie uma conta</router-link>
      </div>
    </div>

    <!--Logo-->
    <div class="side-b">
      <div>
        <img id="logo" src="Img/logo.png" alt="logo" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  nome: "LoginForm",
};
</script>

<style scoped>
#wrapper {
  display: grid;

  grid-template-columns: 1fr 1.5fr;
  grid-template-areas: "A B";
}

.side-a {
  grid-area: A;

  display: flex;
  flex-direction: column;

  align-items: center;

  margin-top: 7rem;
}

.side-b {
  grid-area: B;
}

.side-b div {
  position: fixed;
  width: 120.7rem;
  height: 83.8rem;

  top: 10rem;

  background: rgba(15, 12, 15, 0.3);
  transform: rotate(-80deg);
}

.card {
  background-color: var(--branco);

  height: 35rem;
  width: 39rem;
  border-radius: 2rem;

  box-shadow: 1rem 1rem 0.5rem rgba(0, 0, 0, 0.25);

  margin: 0rem 2rem;
}

.card-header {
  background-color: var(--branco);

  height: 6rem;
  width: 39rem;
  border-radius: 1.9rem 1.9rem 0rem 0rem;

  box-shadow: 0rem 0.6rem 0.5rem rgba(0, 0, 0, 0.25);

  display: flex;
  justify-content: center;
  align-items: center;
}

.card-header span {
  font-style: normal;
  font-weight: 800;
  font-size: 2.2rem;

  background: linear-gradient(
    135deg,
    var(--vermelho-primaria) 14.64%,
    var(--roxo-secundaria) 85.36%
  );
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

form {
  display: flex;
  flex-direction: column;

  gap: 3rem;

  align-items: center;

  margin-top: 4rem;
}

form input {
  padding-left: 2rem;

  width: 30rem;
  height: 5rem;

  background: var(--auxiliar);

  border-radius: 0.7rem;

  border: none;
}

form input::placeholder {
  color: var(--placeholder);
}

#button {
  width: 30rem;
  height: 5rem;

  background: var(--preto);
  border-radius: 0.5rem;

  font-family: "Nunito", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 2rem;
  line-height: 2.7rem;
  text-align: center;

  color: var(--branco);

  border: none;
}

.footer {
  display: flex;
  flex-direction: column;

  gap: 2rem;
  margin-top: 6rem;

  align-items: center;
}

.footer p {
  color: var(--branco);

  font-family: "Nunito", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 1.8rem;
  line-height: 2.5rem;
}

.footer a {
  font-family: "Nunito", sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 2.2rem;
  line-height: 3rem;
  text-decoration-line: underline;

  color: var(--cinza);
}

#logo {
  transform: rotate(80deg);
  margin-left: 70rem;
  width: 20rem;
  margin-top: 10rem;
}
</style>
