# movie-challenge

Projeto Vue.js criado com a ferramenta Vue.cli

Instalação local:
- Faça o clone do projeto;
- Acesse a pasta "app";
- Execute o comando "npm install";
- Execute o comando "npm run serve";
- Acesso o projeto pelo navegador na porta indicada após o "run serve" 
    O padrão é http://localhost:8080/

Bibliotecas utilizadas:
    bootstrap-vue - https://bootstrap-vue.js.org/
        - Utilizado para trabalhar com o Bootstrap no projeto que facilita o desenvolvimento do layout, além de ter diversos componentes prontos para uso.

    vue-axios - https://www.npmjs.com/package/vue-axios
        - Utilizado para fazer requisições HTTP para a API com o Axios, muito utilizado no Vue.js como também no Node.js.

    vue-moment - https://www.npmjs.com/package/vue-moment
        - Usado para facilitar a formatação e exibição de datas ao usuário.

    vue-lodash - https://www.npmjs.com/package/vue-lodash
        - Utilizado no componente que permite pesquisar os filmes. Com o lodash é possível identificar quando o usuário parou de digitar no campo de busca evitando que o sistema faça requisiçoes desnecessárias para a API.