<h1 align="center">upfi - Upload de imagens</h1>

<img src=".github\upload-image-capa.jpg" alt="layout upfi" />

# Sobre o projeto

É aplicação onde o principal objetivo é fazer o upload de imagens e adicionar sua descrição usando React Hook Form. A aplicação foi estilizada com Chakra-UI. Ela realiza requisições para sua própria API Next.js que vai retornar os dados do FaunaDB (banco de dados) e do ImgBB (serviço de hospedagem de imagens).

- Infinite Queries e Mutations com React Query;
- Envio de formulário com React Hook Form;
- Exibição de Modal e Toast com Chakra UI;
- Entre outros.

# Tecnologias usadas

- Next.js
- Chakra-ui
- React Query;
- React Hook Form;
- ImgBB;
- FaunaDB;
- API do Next.js;
- Axios;

# Criação do arquivo .env

Para o projeto executar sem erros na hora de trazer uma imagem, é necessário criar conta no [FaunaDB](https://dashboard.fauna.com) e no [ImgBB](https://api.imgbb.com) para que ocorra o armazenamendo de dados no FaunaDB e o armazenamento da image no ImgBB com essas variáveis dentro do arquivo __.env.local__:

``` env
NEXT_PUBLIC_IMGBB_API_KEY=
FAUNA_API_KEY=
```

# Executando o projeto

Execute o seguinte comando para iniciar a aplicação:

`npm run dev`

# Arquivos de test do projeto

O projeto tem a pasta `__test__` que executa os testes com aprovações necessárias baseadas do curso e para ver basta executar este comando:

`npm run test`
