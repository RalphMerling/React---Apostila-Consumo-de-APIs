
# React - Apostila Consumo de APIs

Projeto desenvolvido na disciplina Programação Web II,
utilizando Next.js, React e Tailwind CSS.

## Objetivo

Criar um formulário de cadastro de clientes com
preenchimento automático de endereço por meio da API ViaCEP.

## Tecnologias utilizadas

- Next.js
- React
- JavaScript
- Tailwind CSS
- API ViaCEP

## Funcionalidades

- Cadastro de dados básicos do cliente
- Campos de endereço e contato
- Consulta automática de endereço pelo CEP
- Preenchimento de rua, bairro, estado e município
- Mensagem de erro para CEP inexistente
- Botão para limpar o formulário
- Exibição dos dados cadastrados no console

## Estrutura do projeto

- src/app: páginas e layout principal
- src/components/form: componentes do formulário
- src/components/layout: cabeçalho, rodapé e container
- src/models: estrutura inicial dos dados do cliente
- src/services: comunicação com a API ViaCEP

## Como executar

1. Instale as dependências com npm install.
2. Inicie o projeto com npm run dev.
3. Acesse http://localhost:3000 no navegador.

## Funcionamento da API

Ao digitar um CEP com 8 números, o sistema realiza uma
requisição GET à API ViaCEP.

Se o CEP existir, os campos de endereço são preenchidos
automaticamente.

Se o CEP não for encontrado, uma mensagem de erro será
exibida.

## Observações

O projeto tem finalidade acadêmica.

Os dados do formulário são exibidos no console do navegador,
sem armazenamento em banco de dados.

Para os testes, devem ser utilizados dados fictícios.

## Disciplina

Programação Web II

Professor: Vitor H. V. Reis

Senac RJ - 2026
