## Sobre

Esta é uma API sobre os personagens de Stranger Things.

Ela lista os personages e mostra sua atual situação na série.
existe apenas um get nesta aplicaçã e sua funcionalidade mais 
legal vem da função hereIsTheUpsideDown, que quando falsa mostra os
dados normais e comumente apresentados, quando true mostra
os dados de cabeça para baixo, representando o mundo invertido.

Para acessar o deply da aplicação basta verificar os links a seguir,
- https://car0l15-up.herokuapp.com   // mostra os dados normais.
- https://car0l15-dw.herokuapp.com   // mostra os dados invertidos.
- https://car0l15-ft.herokuapp.com  // front-end simples feito com as API's acima.

O deploy foi feito no Heroku. O back-end foi buildado a partir do Dockerfile e
o front-end foi buildado com ajuda de um buildpack auxiliar.

## Clone
Para ter este código em sua máquina basta ir ao terminal do seu ambiente e inserir o comando:

- git clone git@github.com:car0l15/Stranger-Things-API.git 
- cd Stranger-Things-API
- npm install
- npm start para iniciar a API.
