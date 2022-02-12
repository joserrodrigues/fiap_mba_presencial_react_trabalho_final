
# FIAP MBA Mobile - Trabalho Final - React JS

Olá, seja bem-vindo a entrega final do Aula Aplicações Web com React.

Você terá de desenvolver um aplicativo Next.js PWA que irá listar os produtos de uma loja.

**Principais instruções**

- Após o login, o usuário poderá visualizar os detalhes de cada produto e saber quais as lojas eles estão disponíveis.
- Também será possível favoritar o produto e ver uma página com os produtos favoritos.
- Ao realizar o refresh do navegador, a aplicação deverá permanecer logada.
> **Dica:** Em todas as APIs você deve usar a URL: **https://fiap-reactjs-presencial.herokuapp.com**.


# Páginas

## Página de Login

- Página em Next.js com e-mail e senha para autenticar o usuário
- Você utilizará a **API Login**
- Utilizar o Yup para realizar a validação

## Página de cadastro

- Página em Next.js com nome, telefone, e-mail e senha para cadastrar o usuário
- Você utilizará a **API Register**
- Utilizar o Yup para realizar a validação

## Header

- Em todas as páginas logadas, deverá aparecer um header com as seguintes funções:

- Lateral esquerda, um menu com as opções:
  - Ir a página Principal (Página de produtos)
  - Ir a página de favoritos (Página de favoritos)
- Lateral direita
  - Nome do usuário
  - Botão de logout

## Página de produtos

- Página em Next.js que exibirá em uma tabela os dados dos produtos
- A tabela deverá mostrar: Nome do Produto, Preço do Produto, Favorito e um botão de visualizar detalhe (Ir a tela **Detalhe do produto**).
- Essa página utilizar a paginação de resultados.
- Você utilizará a **API Buscar Produtos**.
- Essa página deverá buscar a posição do usuário.

## Página de Favoritos

- Página em Next.js que exibirá os produtos determinados como favoritos dos usuários.
- A tabela deverá mostrar: Nome do Produto, Preço do Produto, Favorito e um botão de visualizar detalhe (Ir a tela **Detalhe do produto**).
- Você utilizará a **API Buscar Favoritos**.
- Essa tela deverá buscar a informação pré-carregada do servidor.

## Detalhe do produto

- Página em Next.js que exibirá os detalhes de um produto.
- A tela deverá mostrar:
  - Nome do Produto
  - Preço do Produto
  - Se é Favorito do usuário (e um botão para marcar/desmarcar favorito)
  - Mapa com a posição do usuário e as lojas com o produto disponível
- Você utilizará a **API Buscar Info Produto** e **API Favoritar Produto**
- Essa tela deverá buscar a informação pré-carregada do servidor e os produtos de 1 a 5 já deverão ser previamente carregados na construção do app

# Doc das APIs

A documentação das APIs está disponível em: **https://fiap-reactjs-presencial.herokuapp.com/doc**