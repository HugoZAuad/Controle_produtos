# Gerenciador de Produtos

Este projeto é um gerenciador de produtos simples, desenvolvido em HTML, CSS e JavaScript. O objetivo é permitir que os usuários adicionem, visualizem e removam produtos de uma lista.

## Estrutura do Projeto

O projeto é composto por três arquivos principais:

1. **HTML**: Define a estrutura da página.
2. **CSS**: Estiliza a página para uma melhor apresentação.
3. **JavaScript**: Implementa a lógica de adição, remoção e validação dos produtos.

## Funcionalidades

### 1. Adicionar Produto
- O usuário pode inserir o nome e o preço do produto em campos de entrada.
- Ao clicar no botão "Adicionar", o produto é validado e, se os dados estiverem corretos, é adicionado à lista.

### 2. Listar Produtos
- Os produtos adicionados são exibidos em uma tabela, que inclui:
  - ID do produto
  - Nome do produto
  - Preço do produto
  - Um ícone para remover o produto da lista.

### 3. Remover Produto
- Cada produto na lista possui um ícone que, ao ser clicado, remove o produto correspondente da lista.

### 4. Cancelar
- O botão "Cancelar" limpa os campos de entrada, permitindo que o usuário comece a inserir um novo produto sem a necessidade de recarregar a página.

## Estrutura HTML

A estrutura HTML é organizada da seguinte forma:

- **Cabeçalho**: Contém o título "Controle de produtos".
- **Corpo Principal**: Inclui:
  - Um formulário para entrada de dados do produto.
  - Uma tabela que lista os produtos adicionados.

## Estilo CSS

O CSS aplicado ao projeto proporciona uma aparência limpa e moderna. Algumas características incluem:

- **Fonte**: Utiliza a fonte Verdana, Geneva, Tahoma, sans-serif.
- **Cores**: O cabeçalho tem um fundo cinza claro, enquanto os botões têm um fundo escuro que muda ao passar o mouse.
- **Tabela**: A tabela é estilizada com cores contrastantes para cabeçalho e células.

## Lógica JavaScript

A lógica do projeto é encapsulada em uma classe chamada `Produto`, que gerencia as operações relacionadas aos produtos. As principais funções incluem:

- **Adicionar**: Lê os dados do produto, valida e salva na lista.
- **Listar**: Atualiza a tabela com os produtos armazenados.
- **Cancelar**: Limpa os campos de entrada.
- **Deletar**: Remove um produto da lista com base no ID.

## Como Usar

1. Abra o arquivo HTML em um navegador.
2. Insira o nome e o preço do produto nos campos apropriados.
3. Clique em "Adicionar" para incluir o produto na lista.
4. Para remover um produto, clique no ícone correspondente na tabela.
5. Use o botão "Cancelar" para limpar os campos de entrada.

## Conclusão

Este gerenciador de produtos é uma aplicação simples, mas funcional, que demonstra conceitos básicos de manipulação de DOM, validação de dados e interação do usuário. É uma boa base para quem deseja aprender mais sobre desenvolvimento web.