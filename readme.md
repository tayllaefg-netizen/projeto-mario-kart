<h1>Desafio de projeto do Felipão: Pernalonga Kart.JS</h1>

<table>
  <tr>
    <td>
      <img src="docs/pernalonga-baby-looney-tunes-fcm.jpg" alt="Pernalonga" width="200">
    </td>
    <td>
      <b>Objetivo:</b>
      <p>Pernalonga é uma simulação de corrida inspirada em jogos de corrida. Nosso desafio será criar uma lógica de um jogo de vídeo game para simular corridas, levando em consideração as regras e mecânicas abaixo.</p>
    </td>
  </tr>
</table>

<h2>Players</h2>
<table style="border-collapse: collapse; width: 800px; margin: 0 auto;">
  <tr>
    <td style="border: 1px solid black; text-align: center;">
      <p>Pernalonga</p>
      <img src="docs/pernalonga-baby-looney-tunes-fcm.jpg" width="60" height="60">
    </td>
    <td style="border: 1px solid black; text-align: center;">
      <p>Velocidade: 4</p>
      <p>Manobrabilidade: 3</p>
      <p>Poder: 3</p>
    </td>

    <td style="border: 1px solid black; text-align: center;">
      <p>Piu-Piu</p>
      <img src="./docs/piu piu.jpeg" width="60" height="60">
    </td>
    <td style="border: 1px solid black; text-align: center;">
      <p>Velocidade: 3</p>
      <p>Manobrabilidade: 4</p>
      <p>Poder: 2</p>
    </td>

    <td style="border: 1px solid black; text-align: center;">
      <p>Patolino</p>
      <img src="./docs/patolino.gif" width="60" height="60">
    </td>
    <td style="border: 1px solid black; text-align: center;">
      <p>Velocidade: 2</p>
      <p>Manobrabilidade: 4</p>
      <p>Poder: 3</p>
    </td>
  </tr>

  <tr>
    <td style="border: 1px solid black; text-align: center;">
      <p>Taz</p>
      <img src="./docs/taz.jpg" width="60" height="60">
    </td>
    <td style="border: 1px solid black; text-align: center;">
      <p>Velocidade: 5</p>
      <p>Manobrabilidade: 2</p>
      <p>Poder: 5</p>
    </td>

    <td style="border: 1px solid black; text-align: center;">
      <p>Frajola</p>
      <img src="./docs/frajola.jpg" width="60" height="60">
    </td>
    <td style="border: 1px solid black; text-align: center;">
      <p>Velocidade: 3</p>
      <p>Manobrabilidade: 4</p>
      <p>Poder: 4</p>
    </td>

    <td style="border: 1px solid black; text-align: center;">
      <p>Coyote</p>
      <img src="./docs/coyote.png" width="60" height="60">
    </td>
    <td style="border: 1px solid black; text-align: center;">
      <p>Velocidade: 2</p>
      <p>Manobrabilidade: 2</p>
      <p>Poder: 5</p>
    </td>
  </tr>
</table>

<h3>🕹️ Regras & mecânicas:</h3>

<b>Jogadores:</b>

<input type="checkbox" />
<label>O Computador deve receber dois personagens para disputar a corrida em um objeto cada</label>

<b>Pistas:</b>

<ul>
  <li><input type="checkbox" /> Os personagens irão correr em uma pista aleatória de 5 rodadas</li>
  <li><input type="checkbox" /> A cada rodada, será sorteado um bloco da pista que pode ser uma reta, curva ou confronto
    <ul>
      <li><input type="checkbox" /> RETA → dado + VELOCIDADE</li>
      <li><input type="checkbox" /> CURVA → dado + MANOBRABILIDADE</li>
      <li><input type="checkbox" /> CONFRONTO → dado + PODER (perdedor perde ponto)</li>
      <li><input type="checkbox" /> Nenhum jogador pode ter pontuação negativa</li>
    </ul>
  </li>
</ul>

<b>Condição de vitória:</b>

<input type="checkbox" />
<label>Ao final, vence quem acumulou mais pontos</label>