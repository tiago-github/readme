<h1 align="center">Hiring Coders #3 - Fase 3 - Desafio da Semifinal</h1>
<p align="center">
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
  <img src="https://img.shields.io/badge/"/>
</p>

## Sumário:
:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)<br>
:small_blue_diamond: [Principais Objetivos do projeto](#principais-objetivos)<br>
:small_blue_diamond: [Pré-requisitos](#pré-requisitos)<br>
:small_blue_diamond: [Como executar a aplicação](#executando-a-aplicação)<br>
:small_blue_diamond: [Workaround](#workaround)<br>
:small_blue_diamond: [Paleta de cores](#paleta-de-cores)<br>
:small_blue_diamond: [Agradecimentos](#agradecimentos)<br>

## Desafio da Semifinal
### Cenário:
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
    - Desenvolvimento de um Workspace com SKUs e processamento de compras (funcional);
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

## Pré-requisitos de Uso
### Conhecimentos em
- HTML, CSS, JS e TS;
- Node.js;
- React;
- VTEX IO;
- AWS.
### Ter login de acesso ao Workspace da Casa DreamScape

## Instruções de Uso
- Instale:
    - Node.js;
    - Yarn;
    - VTEX Toolbelt;
- Use ou Crie um Workspace de Desenvolvimento;
- Clone o projeto para uma máquina local;
- Execute o comando `vtex link` na raiz do projeto clonado.

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
