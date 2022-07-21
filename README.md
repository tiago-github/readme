<h1 align="center">Hiring Coders #3 - Fase 3</h1>
<h2 align="center">DreamScape - Grupo 05</h2>
<img src="https://dreamscape.vtexassets.com/assets/vtex.file-manager-graphql/images/923aab7b-457b-4a72-90f9-b4641f810fc2___ffe6b2b6cf146ec503007dc90e070d76.png"/>

<p align="center">
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
</p>

# Desafio da Semifinal
## Sumário
:small_blue_diamond: [Cenário](#Cenário)<br>
:small_blue_diamond: [Organização das Tarefas](#Organização-das-Tarefas)<br>
:small_blue_diamond: [Pré-requisitos de Uso](#Pré-requisitos-de-Uso)<br>
:small_blue_diamond: [Instruções de Uso](#Instruções-de-Uso)<br>
:small_blue_diamond: [Agradecimentos](#Agradecimentos)<br>

## Cenário
Maria tem uma loja e quer implementar um modelo de recompensa:
* A cada R$1,00 gasto o sistema deve gerar 1 ponto de recompensa;
* Todo consumidor precisa saber quantos pontos tem em sua carteira virtual;
* Um contador de saldo de pontos deve estar visível para validação do saldo;    
* Ela já possui um sistema no qual o usuário final pode utilizar os pontos gerados;
* O sistema demanda de uma API para consultar o saldo de pontos e de outra para debitar pontos.   
## Organização das Tarefas
- Workspace de Planejamento:
    - Resumos;    
    - Geração e distribuição de tarefas;
    - Check List de Tarefas;
    - Materiais de Referência;
    - Quadro de Dúvidas;
- Fluxo de Desenvolvimento:
    - Desenvolvimento de um Workspace funcional com SKUs e processamento de compras;
    - Construção de um tema próprio;
    - Implementação de um Componente de Carteira de Pontos para exibir o saldo atualizado no Front-End da Loja;
- Banco de Dados:
    - Criação da entidade Wallet no Master Data v2 da VTEX;
    - Relacionamento da entidade Wallet com a entidade Client por meio de uma Trigger que cria um documento na Wallet associando o userId;
- Criação de APIs:
    - API de crédito e atualização de pontos;
    - API de débito e atualização de pontos;
- Implementação de APIs da VTEX:
    - Orders Feed;
- Back-End na AWS:
    - ???;
- Documentação do Projeto;
- Fluxograma do Projeto.

## Pré-Requisitos
- Ter uma conta VTEX;

## Instruções de Teste da Loja
- Instale:
    - Node.js;
    - Yarn;
    - VTEX Toolbelt;
- Use ou Crie um Workspace VTEX;
- Clone o projeto para uma máquina local;
- Abra o Terminal de Comandos de sua preferência:
  - Acesse a pasta FrontEnd e execute o comando `vtex link`;
  - Acesse a pasta BackEnd e execute o comando `vtex link`;
  - Acesse a pasta WalletAPP e execute o comando `vtex link`.
- Faça o login da sua conta VTEX;
- Acesse a página da loja pelo navegador;
- Verifique o saldo inicial no contador de pontos;
- Cadastre uma conta na loja;
- Realize uma compra;
- Verifique o saldo atualizado no contador de pontos;

## Instruções de Teste das APIs
-
-
-

## Agradecimentos
Agradeçemos a toda a rede de colaboração que fez o Hiring Coders #3 acontecer e ser um sucesso:     
- Idealizadores;
- Patrocinadores;
- Time do HC;
- Time da Gama;
- Time da VTEX;    
- Mentores;
- Palestrantes;    
- Alunos.
