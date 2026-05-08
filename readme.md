# 🏎️ Projeto Mario Kart


Projeto em **JavaScript** que simula uma corrida inspirada em jogos no estilo Mario Kart. A aplicação usa personagens com atributos diferentes, sorteio de pistas, rolagem de dados e cálculo de pontos para definir o vencedor da corrida.


---


## 📌 Sobre o projeto


Este projeto foi desenvolvido para praticar **lógica de programação** com JavaScript, criando uma pequena engine de corrida executada no terminal. Durante a partida, dois personagens competem por 5 rodadas em blocos aleatórios de pista.


A cada rodada, o sistema sorteia o tipo de desafio, calcula o desempenho dos jogadores e atualiza o placar até chegar ao resultado final.


---


## 🎮 Como funciona


Cada personagem possui atributos próprios:


- **Velocidade**: usada em trechos de reta
- **Manobrabilidade**: usada em curvas
- **Poder**: usado em confrontos
- **Pontos**: representam o placar da corrida


Em cada rodada, um bloco de pista é sorteado:


- **RETA**: dado + velocidade
- **CURVA**: dado + manobrabilidade
- **CONFRONTO**: dado + poder


Ao final de 5 rodadas, vence o personagem que tiver mais pontos.


---


## 🧩 Personagens


| Personagem | Velocidade | Manobrabilidade | Poder |
| --- | ---: | ---: | ---: |
| 🐰 Pernalonga | 4 | 3 | 3 |
| 🐤 Piu-Piu | 3 | 4 | 4 |


---


## 🚀 Funcionalidades


- Sorteio automático de blocos da pista
- Rolagem de dados aleatória
- Comparação de atributos entre personagens
- Sistema de pontuação
- Confrontos entre jogadores
- Placar atualizado a cada rodada
- Resultado final com vencedor ou empate


---


## 🛠️ Tecnologias utilizadas


<div align="center">


![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=node.js&logoColor=339933)
![Git](https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white)


</div>


---


## 📂 Estrutura do projeto


```bash
projeto-mario-kart/
├── docs/
│   ├── coyote.png
│   ├── frajola.jpg
│   ├── images.png
│   ├── pernalonga-baby-looney-tunes-fcm.jpg
│   ├── piu piu.jpeg
│   └── taz.jpg
├── index.js
├── package.json
└── readme.md
```


---


## ▶️ Como executar


Clone o repositório:


```bash
git clone https://github.com/tayllaefg-netizen/projeto-mario-kart.git
```


Acesse a pasta:


```bash
cd projeto-mario-kart
```


Execute o projeto:


```bash
node index.js
```


---


## 💻 Exemplo de saída


```bash
🏎️ CORRIDA MALUCA COMEÇANDO


🐰 Pernalonga 🆚 🐤 Piu-Piu


🏁 RODADA 1
📍 Bloco sorteado: RETA
🎲 Pernalonga rolou um dado
🎲 Piu-Piu rolou um dado


📊 PLACAR:
Pernalonga: 1
Piu-Piu: 0
```


---


## 🧠 Conceitos praticados


- Objetos em JavaScript
- Funções assíncronas
- Sorteio com `Math.random()`
- Estruturas condicionais
- Laços de repetição
- Manipulação de pontuação
- Organização de regras de jogo
- Execução de JavaScript com Node.js


---


## 📊 Status do projeto


✅ Projeto desenvolvido para estudos e prática de lógica com JavaScript.


---


## 👩‍💻 Autora


Feito por **Tayla**.


[![GitHub](https://img.shields.io/badge/GitHub-tayllaefg--netizen-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tayllaefg-netizen)





