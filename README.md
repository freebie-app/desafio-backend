![Logo Freebie](https://github.com/freebie-app/desafio-backend/blob/master/freebie.png "Freebie")

# Desafio Back-End - Freebie

Esse desafio é parte do nosso processo de seleção.
Sua avaliação será dada pelas fases que conseguir entregar e a forma com que foram desenvolvidas.

## Pré-requisitos

- Lógica de programação;
- Conhecimentos sobre Banco de dados;
- Conhecimentos sobre HTTP, API e REST ;
- Conhecimentos sobre Git;

## Requisitos do desafio

- Utilizar PHP(7.4)
- Utilizar Laravel(8)
- Adicionar no README instruções de como executar o projeto.
- A API deve receber e retornar dados no formato JSON.

## Diferenciais

- Código limpo
- Código em Inglês

## Contexto

Você recebeu uma demanda para desenvolver um backend para controle interno dos nossos cupons de desconto, precisamos ter informações e também precisará ser adicionado mídias.

### Fase 1 - Coupons

Nesta fase serão implementados os cupons do aplicativo e seus endpoints:

- Criar um endpoint onde é cadastrado um cupom.
  - Esses cupons devem ter os seguintes dados com as devidas validações:
    - **title** | string, obrigatório, mínimo 10 caracteres e no máximo 20
    - **body** | text, não obrigatório
    - **is_enabled** | boolean, obrigatório
    - **expired_on** | datetime, obrigatório
- Criar um endpoint para listagem desses cupons, ordernados por ordem de cadastro decrescente (mais novo para mais antigo);
- Criar um endpoint para listar um único cupom através do seu id;
- Criar um endpoint para editar um único cupom através do seu id;
- Criar um endpoint para excluir um cupom através do seu id.

### Fase 2 - Midias

Nesta fase serão implementados as midias dos cupons, (um cupom contém várias midias):

- Criar um endpoint onde será possível realizar um upload de um vídeo (.mp4), música (.mp3) ou imagem (.png) com tamanho máximo de 5MB
- Criar um endpoint onde ao passar o id do cupom retorne a url das mídias vinculadas
- Criar um endpoint onde seja possível excluir uma mídia.

## Ao Concluir

- Após isso envie um e-mail para 'tech@freebieapp.com.br', com o assunto 'DESAFIO BACK-END' com link do seu repositório ou faça um pull request do projeto.

## Dúvidas?

mande email para: tech@freebieapp.com.br
