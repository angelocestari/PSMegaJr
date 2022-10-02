<template>
  <div id="fundo">
    <header>
      <h3>Megabank</h3>
      <h3 id="title">Dashboard</h3>
      <img id="bell" src="Img/bell.png" alt="Sino" />
      <img id="config" src="Img/config.png" alt="config" />
    </header>
    <hr />
    <div id="container">
      <div id="lateral">
        <div id="vertical-line">
          <img id="dash" src="Img/dashboard.png" alt="dashboard" />
          <br />
          <img class="list" src="Img/line.png" alt="list" />
          <br />
          <img class="list" src="Img/line.png" alt="list" />
          <br />
          <img class="list" src="Img/line.png" alt="list" />
          <br />
          <img class="list" src="Img/line.png" alt="list" />
          <div id="user">
            <div class="ao-lado">
              <img id="icon" src="Img/icon.png" alt="icon" />
              <h5 id="boas-vindas">Bem-Vindo de volta</h5>
            </div>
            <h4 id="username">Usuário</h4>
          </div>
          <router-link to="/" class="log-out">
            <img id="sign-out-img" src="Img/sign-out.png" alt="sign-out" />
            <h5 id="sign-out-text">Sign-out</h5>
          </router-link>
        </div>
      </div>
      <div id="centro">
        <div class="ao-lado">
          <div class="esquerda">
            <div class="ao-lado">
              <div id="saldo">
                <h4 id="saldo-text">Meu saldo</h4>
                <div class="ao-lado">
                  <h2 id="saldo-number">$99,999.99</h2>
                  <p id="moeda">BRL</p>
                </div>
                <div id="historico">
                  <div class="ao-lado">
                    <img src="Img/clock.png" alt="clock" />
                    <p id="historico-text">Histórico</p>
                  </div>
                </div>
              </div>
              <div id="renda/gastos">
                <div class="ao-lado">
                  <h4 id="renda-text">Renda</h4>
                  <h4 id="renda-mensal-text">/ mensal</h4>
                  <img id="seta-baixo" src="Img/seta-baixo.png" alt="seta" />
                </div>
                <h2 id="renda-number">$3,331.22</h2>
                <hr id="hr-renda" />
                <div class="ao-lado">
                  <h4 id="gasto-text">Gastos</h4>
                  <h4 id="gastos-mensal-text">/ mensal</h4>
                  <img
                    id="seta-baixo-gasto"
                    src="Img/seta-baixo.png"
                    alt="seta"
                  />
                </div>
                <h2 id="gasto-number">$1,461.98</h2>
              </div>
            </div>
            <div id="cartao">
              <div class="ao-lado">
                <h4>Meus cartões de crédito</h4>
                <h4 id="transacao-text">Últimas transações</h4>
                <img
                  id="seta-direita"
                  src="Img/seta-direita.png"
                  alt="transacoes"
                />
              </div>
              <div class="ao-lado">
                <div id="meu-cartao">
                  <div class="ao-lado">
                    <h4 id="nome-cartao">Usuário Pereira</h4>
                    <img
                      id="megacard"
                      src="Img/MegaCard.png"
                      alt="bandeira-cartão"
                    />
                  </div>
                  <div class="ao-lado">
                    <h5 id="cartao-number">5283 **** **** 3272</h5>
                    <h5 id="bandeira-cartao">MegaBank</h5>
                  </div>
                </div>
                <div class="transacoes">
                  <div id="passaporte">
                    <div class="ao-lado">
                      <img
                        id="passaporte-icon"
                        src="Img/local.png"
                        alt="local"
                      />
                      <h4 id="passaporte-text">Passaporte</h4>
                      <h4 id="passaporte-price">$3,331.22</h4>
                      <h5 id="passaporte-time">3 horas atrás</h5>
                    </div>
                  </div>
                  <div id="entretenimento">
                    <div class="ao-lado">
                      <img
                        id="entretenimento-icon"
                        src="Img/entretenimento.png"
                        alt="camera"
                      />
                      <h4 id="entretenimento-text">Entretenimento</h4>
                      <h4 id="entretenimento-price">$33.22</h4>
                      <h5 id="entretenimento-time">10 horas atrás</h5>
                    </div>
                  </div>
                  <div id="compras">
                    <div class="ao-lado">
                      <img
                        id="compras-icon"
                        src="Img/compras.png"
                        alt="carrinho"
                      />
                      <h4 id="compras-text">Compras</h4>
                      <h4 id="compras-price">$3.50</h4>
                      <h5 id="compras-time">12 horas atrás</h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="ao-lado">
              <div id="new-cartao">
                <div class="ao-lado">
                  <p id="text-novo-cartao">Novo cartão?</p>
                  <img
                    id="adicionar"
                    src="Img/novo-cartao.png"
                    alt="novo-cartão"
                  />
                </div>
              </div>
              <div id="transfer">
                <div class="ao-lado">
                  <img id="transfer-icon" src="Img/transfer.png" alt="setas" />
                  <h4 id="transfer-text">Transferência</h4>
                  <h4 id="transfer-price">$80.00</h4>
                  <h5 id="transfer-time">19 horas atrás</h5>
                </div>
              </div>
            </div>
          </div>

          <div class="direita">
            <div id="pix">
              <h4 id="pix-text">Minhas chaves</h4>
              <ul id="pix-list">
                <li>CPF: 236.***.***-69</li>
                <li>Celular:</li>
                <li>Email:</li>
              </ul>
            </div>
            <div id="transferencia">
              <div id="faz-transferencia">
                <p id="transferencia-text">Faça uma MegaTransferência.</p>
                <img
                  id="seta-transferencia"
                  src="Img/seta-direita.png"
                  alt="transferencia"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
#fundo {
  background-color: black;
  height: 61.7rem;
  color: white;
}
.ao-lado {
  display: flex;
}

header {
  display: flex;
  padding: 2rem;
}

#title {
  margin-left: 50rem;
}
#bell {
  margin-left: 55rem;
}
#config {
  margin-left: 3rem;
}
#container {
  display: flex;
}
#dash {
  margin-top: 4rem;
  width: 15rem;
}
#lateral {
  margin-left: 5rem;
}
.list {
  margin-top: 1rem;
}
#vertical-line {
  width: 30rem;
  height: 54.5rem;
  border-right: 3px solid #964cad;
}
#user {
  margin-top: 10rem;
  width: 20rem;
  height: 10rem;
  border: 2px solid #f4f7f6;
  border-radius: 35px;
}
#icon {
  margin-top: 2.5rem;
  margin-left: 1.5rem;
}
#boas-vindas {
  margin-top: 2.5rem;
  margin-left: 1rem;
  color: #c9c9c9;
}
#username {
  margin-left: 6.5rem;
  margin-top: -2rem;
}
.log-out {
  margin-top: 2rem;
  width: 20rem;
  height: 4rem;
  background: #2e2e2e;
  border-radius: 10px;
  display: flex;
  text-decoration: none;
}
#sign-out-img {
  width: 3rem;
  margin-top: 0.5rem;
  margin-left: 1.5rem;
}
#sign-out-text {
  margin-left: 3rem;
  margin-top: 0.5rem;
  font-size: 2rem;
  color: #f4f7f6;
}
.esquerda {
  margin-left: 5rem;
  margin-top: 3rem;
  width: 50rem;
  height: 20rem;
  border: 1px solid #f4f7f6;
  border-radius: 50px;
}
#saldo {
  border-radius: 50px;
  width: 25rem;
  height: 20rem;
  background-color: #f4f7f6;
}
#saldo-text {
  color: black;
  padding-top: 3rem;
  margin-left: 4rem;
  padding-bottom: 0;
}
#saldo-number {
  margin-top: 2rem;
  margin-left: 4rem;
  color: black;
}
#moeda {
  color: #964cad;
  margin-top: 3rem;
  font-size: 1.4rem;
  font-weight: bold;
}
#historico {
  margin-top: 2rem;
  margin-left: 4rem;
  width: 13rem;
  height: 3rem;
  background-color: #2d0039;
  border-radius: 10px;
}
#historico-text {
  margin-left: 2rem;
  margin-top: 0.4rem;
}
#renda-text {
  margin-left: 4rem;
  margin-top: 2rem;
  margin-right: 1.5rem;
}

#renda-mensal-text {
  margin-top: 2rem;
  color: #c9c9c9;
}
#seta-baixo {
  width: 1.5rem;
  height: 1.5rem;
  margin-top: 2.3rem;
  margin-left: 0.5rem;
}
#renda-number {
  margin-left: 5rem;
  margin-top: 1rem;
  margin-bottom: 1rem;
}
#hr-renda {
  margin-left: 6rem;
  margin-right: 3rem;
}
#gasto-text {
  margin-left: 4rem;
  margin-top: 1rem;
  margin-right: 1.5rem;
}
#gastos-mensal-text {
  margin-top: 1rem;
  color: #c9c9c9;
}
#seta-baixo-gasto {
  width: 1.5rem;
  height: 1.5rem;
  margin-top: 1.3rem;
  margin-left: 0.5rem;
}
#gasto-number {
  margin-left: 5rem;
  margin-top: 1rem;
  margin-bottom: 1rem;
}
#cartao {
  margin-top: 4rem;
}
#meu-cartao {
  margin-top: 2rem;
  width: 26rem;
  height: 15rem;
  background: linear-gradient(135deg, #bf1205 14.64%, #2e0038 85.36%);
  border-radius: 15px;
}
#nome-cartao {
  padding-top: 2rem;
  margin-left: 2rem;
}
#megacard {
  margin-left: 5rem;
  margin-top: 1.5rem;
  width: 6rem;
}
#cartao-number {
  margin-left: 1.8rem;
  margin-top: 5rem;
}
#bandeira-cartao {
  margin-left: 3rem;
  margin-top: 4.8rem;
}
#new-cartao {
  margin-top: 3rem;
  height: 4rem;
  width: 26rem;
  border: 2px dashed #c9c9c9;
  border-radius: 41px;
}
#text-novo-cartao {
  margin-left: 8rem;
  margin-top: 0.7rem;
}
#adicionar {
  background-color: #964cad;
  width: 2.5rem;
  margin-top: 0.5rem;
  margin-left: 2rem;
  border-radius: 10px;
}
#transacao-text {
  margin-left: 12rem;
}
#seta-direita {
  margin-left: 2rem;

  background-color: #2e2e2e;
  border-radius: 10px;
}
.transacoes {
  margin-left: 3rem;
  margin-top: 2rem;
}
#passaporte-icon {
  background-color: #ad955e;
  width: 3.5rem;
  border-radius: 12px;
}
#passaporte-text {
  margin-left: 0.5rem;
}
#passaporte-price {
  margin-left: 1rem;
  margin-top: 0.6rem;
}
#passaporte-time {
  margin-top: 2rem;
  margin-left: -16.7rem;
  font-size: 1.3rem;
  color: #c9c9c9;
}
#entretenimento-icon {
  margin-top: 2rem;
  background-color: #26614a;
  width: 3.5rem;
  border-radius: 12px;
}
#entretenimento-text {
  margin-left: 0.5rem;
  margin-top: 2rem;
  font-size: 1.4rem;
}
#entretenimento-price {
  margin-left: 1.5rem;
  margin-top: 2.6rem;
}
#entretenimento-time {
  margin-top: 4rem;
  margin-left: -16.7rem;
  font-size: 1.3rem;
  color: #c9c9c9;
}
#compras-icon {
  margin-top: 2rem;
  width: 4rem;
  background-color: #522161;
  border-radius: 12px;
}
#compras-text {
  margin-top: 2rem;
  font-size: 1.4rem;
  margin-left: 0.5rem;
}
#compras-price {
  margin-left: 6.5rem;
  margin-top: 2.6rem;
}
#compras-time {
  margin-top: 4rem;
  margin-left: -16.5rem;
  font-size: 1.2rem;
  color: #c9c9c9;
}
#transfer-icon {
  margin-top: 3.5rem;
  width: 3.5rem;
  height: 3.5rem;
  margin-left: 3rem;
  background-color: #3bad80;
  border-radius: 12px;
}
#transfer-text {
  margin-left: 0.5rem;
  margin-top: 3rem;
}
#transfer-price {
  margin-left: 2rem;
  margin-top: 4rem;
}
#transfer-time {
  margin-top: 5.5rem;
  margin-left: -17rem;
  font-size: 1.3rem;
  color: #c9c9c9;
}

#pix {
  margin-left: 10rem;
  margin-top: 3rem;
  background-color: #f4f7f6;
  width: 30rem;
  height: 20rem;
  border-radius: 50px;
}
#pix-text {
  color: #0f0c0f;
  margin-left: 3rem;
  padding-top: 3rem;
}
#pix-list {
  color: #0f0c0f;
  margin-top: 1.5rem;
  margin-left: 5rem;
  font-weight: bold;
}

#transferencia {
  margin-left: 10rem;
  margin-top: 7rem;
  background-color: #d9d9d9;
  width: 30rem;
  height: 20rem;
  border-radius: 50px;
}
#faz-transferencia {
  width: 15rem;
  height: 11rem;
  margin-left: 15rem;
  background-color: #964cad;
  border-radius: 50px;
}
#transferencia-text {
  font-size: 1.5rem;
  margin-left: 1.5rem;
  padding-top: 1.5rem;
}
#seta-transferencia {
  margin-left: 10rem;
  margin-top: 1rem;
  width: 2.8rem;
  height: 2.5rem;
  background-color: #0f0c0f;
  border-radius: 10px;
}
</style>
