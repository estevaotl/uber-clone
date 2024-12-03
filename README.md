# Descrição do Projeto
- Esse projeto foi feito visando o aprofundamento no estudo do front-end.
- Para isso foi escolhido a clonagem do aplicativo Uber, muito utilizado atualmente para transporte, no qual utilizei o video (https://www.youtube.com/watch?v=zXpr8zaK2eA&list=WL&index=3&t=2099s) como referência.
- Além disso, foi realizado a criação do aplicativo via PWA.

## Tecnologias Utilizadas
- NodeJS
- Vue.js 3.x
- Tailwind
- Google Maps
- Pwa
- Javascript

## Como Utilizar

- Abra o terminal na raiz do projeto e digite 
```
npm i
```
- Copie o .env.example da raiz e renomeie para .env, modificando a url do localhost conforme necessidade
- A fim de gerar uma nova key para utilizar o google maps, vá até https://console.cloud.google.com/
- Gere uma Api Key
- Adicione a nova chave aos locais:
  - public/index.html - aonde esta escrito YOUR_KEY
  - server/.env - após renomear o .env.example para .env, modifique aonde está escrito YOUR_KEYY
- Por fim, rodar os comandos:
  - npm i -> raiz do projeto ( instalar dependencias do node )
  - npm run serve -> raiz do projeto ( instanciar o servidor front-end )
  - npm run watch -> dentro da pasta server ( instanciar o back-end para ficar ouvindo as requisições do front-end )
  - npm run pwa -> raiz do projeto ( chamada para a criação do aplicativo pwa )

## Application Images

<p float="left">
  <img width="270" alt="Screenshot 2022-11-23 at 17 10 03" src="https://user-images.githubusercontent.com/108229029/203521356-c0f3956f-2b71-4e53-998a-65d10ffd6f29.png">
  <img width="270" alt="Screenshot 2022-11-23 at 17 11 15" src="https://user-images.githubusercontent.com/108229029/203521447-f9ad69eb-67c1-4bc5-89c2-378d7a2dd27f.png">
  <img width="270" alt="Screenshot 2022-11-23 at 17 12 14" src="https://user-images.githubusercontent.com/108229029/203521544-3b982e89-ad62-4e63-a376-5f614acbb588.png">
</p>