<template></template>

<script>
export default {
  name: "Geral",
};
</script>

<style>
/* IMPORTA DA FONTE NUNITO */
@import url("https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

/* Método de uso: font-family: 'Nunito', sans-serif; */

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

:root {
  --branco: #f4f7f6;
  --preto: #0f0c0f;
  --placeholder: #0f0c0f73;

  --vermelho-primaria: #bf1304;
  --roxo-secundaria: #2d0039;

  --auxiliar: #974cae40;

  --cinza: #c9c9c9;

  font-size: 62.5%; /* 1rem = 10px */
}

body {
  font-family: "Nunito", sans-serif;
  font-size: 1.6rem;

  height: 100%;
  background-image: linear-gradient(
    135deg,
    var(--vermelho-primaria) 14.64%,
    var(--roxo-secundaria) 85.36%
  );
  background-attachment: fixed;
}
</style>
