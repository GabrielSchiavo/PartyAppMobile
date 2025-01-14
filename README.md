# Party Go (Party App Mobile)
<p align="left">
    <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge"/>
   <!-- <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge"/> -->
</p>

<img src="./src/assets/icons/icon2.png" alt="Ícone Party GO"/>

* `PROJETO NO FIGMA` ----------->> https://www.figma.com/file/tj82IcClr5erxg0lbAZ6L9/Prototyping-in-Figma?node-id=0%3A1

1- `EMPATIA:` Comece com a empatia levantando hipóteses sobre o que as pessoas precisam, pode fazer isso fazendo análise de um grupo específico. (ambiente escolar, mensagens, música, transporte.)

* Sabemos que hoje em dia algo muito importante para o sucesso de vender um produto ou um serviço está diretamente atrelado ao marketing em cima dele. Pensando nisso, qual seria a melhor forma de divulgar eventos se não numa plataforma específica para isso?
* Como jovens e adultos que curtem uma boa festa podem encontrar informações sobre esses eventos na nossa região? Saber quantas pessoas irão comparecer, qual a atração da noite, estilo musical, qual o ambiente…

2- `DEFINIÇÃO:` Depois de analisar, ou fazer uma pesquisa de opinião defina o problema que será resolvido.

* Pensando no marketing, buscaremos elaborar um aplicativo que ajuda empresários que promovem festas a divulgarem seus eventos com local e data de uma forma que chegue até o público consumidor de forma simples e automática, onde o próprio consumidor buscará por isso.
* Também pensando nos jovens e adultos que gostam de uma boa festa, mas geralmente não sabem quando e onde acontecerá e, se realmente mais pessoas irão, tornando em teoria a festa mais “empolgante”.

3- `IDEALIZAR:` Chuva de ideias: depois de definir o problema realize com seu grupo uma chuva de ideias, todas são válidas, um dos membros do grupo pode ficar encarregado de anotá-las.

* O aplicativo será voltado para dois públicos: jovens/adultos e empresas
* Será voltado para realizar marketing e vender ingressos de eventos no caso das empresas (funcionalidade paga)
* Vai ser usado pelas pessoas para procurar por eventos na região.
* Os eventos constarão: localização, data e hora, valor do ingresso (com opção de compra), número de pessoas que compraram ingresso, a atração da noite, estilo musical e contará com fotos do ambiente.

## :hammer: Funcionalidades do projeto
* `Login e cadastro de usuários:` tela de login e tela de cadastro de novos usuários com criptografia de senha.

* `Cadastro de eventos:` cadastro dos eventos com nome, estilo musical, local, data, preço do ingresso e imagem.
<!-- * `Uploads de imagens:` upload de imagem para os eventos. -->
* `Exibição dos eventos cadastrados:` exibição na tela Home de todos os eventos cadastrados no banco de dados.
  
* `Pesquisa de eventos:` opção de pesquisar eventos pelo nome, estilo musical ou local.

<br>
<div display: inline_block align="center">
    <img src="./src/assets/img/screenshots/screenshot01.png" alt="Screenshot tela home"/>
    <img src="./src/assets/img/screenshots/screenshot02.png" alt="Screenshot tela cadastro"/>
    <img src="./src/assets/img/screenshots/screenshot03.png" alt="Screenshot tela pesquisa"/>
</div>

## :hammer_and_wrench: Abrir e rodar o projeto
Após baixar o projeto, você pode abrir com o Visual Studio Code. Para o projeto funcionar você deve ter configurado em seu PC:

* Node.js - Versão >= 16.16.0
* Banco de dados MySQL

Em seguida, abra um terminal e execute:

```bash
npm install --global expo-cli
```

Nos arquivos do projeto abra o arquivo config.json na pasta /config e edite as configurações do banco em "development": para as suas configurações escolhidas durante a instalação do MySQL, e altere a configuração "urlRootNode": para o IP do seu PC.

Após abra um novo terminal na raiz do projeto e execute os seguintes comandos:
```bash
npm install
```
```bash
npm install -g nodemon
```
```bash
npx sequelize-cli db:migrate
```
```bash
expo start
```

Em outro terminal na raiz do projeto execute:
```bash
nodemon Controller
```

Agora o projeto está pronto para uso. 

## :white_check_mark: Tecnologias utilizadas
* `Bcrypt - 5.0.1`
* `Expo - 45.0.0`
* `Express - 4.18.1`
* `JavaScript`
* `MySQL Database`
* `Node.js - 16.16.0`
* `Nodemon - 2.0.19`
* `React Native - 0.68.2`
* `Sequelize - 6.20.1`
