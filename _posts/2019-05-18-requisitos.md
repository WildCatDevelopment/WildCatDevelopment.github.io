---
layout: post
title: "Requisitos e Estimativas"
author: "WildCat Development"
---

## CRUD de Usuário
---

### Tela de cadastro

<table class="table" id="table-tela-cadastro">
  <tr>
    <th>ID</th>
    <th>Categoria</th>
    <th>Tarefa</th>
    <th>Estimativa</th>
  </tr>
  <tr>
    <td>1</td>
    <td>DESIGN</td>
    <td>Fazer design da tela de cadastro</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2</td>
    <td>FRONTEND</td>
    <td>Criar tela de cadastro do sistema</td>
    <td>13</td>
  </tr>
  <tr>
    <td>3</td>
    <td>FRONTEND</td>
    <td>Criar chamada para o backend para salvar usuário</td>
    <td>8</td>
  </tr>
  <tr>
    <td>4</td>
    <td>BANCO</td>
    <td>Criar tabela de usuário no banco de dados</td>
    <td>5</td>
  </tr>
  <tr>
    <td>5</td>
    <td>BACKEND</td>
    <td>Criar endpoint na API para salvar o usuário</td>
    <td>3</td>
  </tr>
  <tr>
    <td>6</td>
    <td>BACKEND</td>
    <td>Criar query para inserção no banco de dados</td>
    <td>5</td>
  </tr>
  <tr>
    <td>7</td>
    <td>BACKEND</td>
    <td>Criar Model do usuário</td>
    <td>8</td>
  </tr>
</table>

---

### Tela de Login

<table class="table" id="table-tela-login">
  <tr>
    <th>ID</th>
    <th>Caregoria</th>
    <th>Tarefa</th>
    <th>Estimativa</th>
  </tr>
  <tr>
    <td>1</td>
    <td>DESIGN</td>
    <td>Fazer design da tela de login</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2</td>
    <td>FRONTEND</td>
    <td>Criar tela de login do sistema</td>
    <td>8</td>
  </tr>
  <tr>
    <td>3</td>
    <td>FRONTEND</td>
    <td>Criar chamada para o backend para login do usuário</td>
    <td>8</td>
  </tr>
  <tr>
    <td>4</td>
    <td>FRONTEND</td>
    <td>Salvar token do usuário para requisições no backend</td>
    <td>13</td>
  </tr>
  <tr>
    <td>5</td>
    <td>BACKEND</td>
    <td>Criar query para busca no banco de dados</td>
    <td>5</td>
  </tr>
  <tr>
    <td>6</td>
    <td>BACKEND</td>
    <td>Fazer criptografia das senhas</td>
    <td>5</td>
  </tr>
  <tr>
    <td>7</td>
    <td>BACKEND</td>
    <td>Usar JWT para fazer autenticação do usuário</td>
    <td>5</td>
  </tr>
  <tr>
    <td>8</td>
    <td>BACKEND</td>
    <td>Criar endpoint na API para login do usuário</td>
    <td>5</td>
  </tr>
</table>

---

## Criar uma tela para visualizar dados dos docentes
---

<table class="table" id="table-tela-dados-docentes">
  <tr>
    <th>ID</th>
    <th>Caregoria</th>
    <th>Tarefa</th>
    <th>Estimativa</th>
  </tr>
  <tr>
    <td>1</td>
    <td>DESIGN</td>
    <td>Fazer design da tela de listagem</td>
    <td>13</td>
  </tr>
  <tr>
    <td>2</td>
    <td>FRONTEND</td>
    <td>Exibir uma lista de Docentes</td>
    <td>3</td>
  </tr>
  <tr>
    <td>3</td>
    <td>FRONTEND</td>
    <td>Filtrar Docentes</td>
    <td>5</td>
  </tr>
  <tr>
    <td>4</td>
    <td>FRONTEND</td>
    <td>Selecionar professor (ir para tela de edição)</td>
    <td>5</td>
  </tr>
  <tr>
    <td>5</td>
    <td>BACKEND</td>
    <td>Criar endpoint na API para listar docentes</td>
    <td>8</td>
  </tr>
  <tr>
    <td>6</td>
    <td>BACKEND</td>
    <td>Criar query para busca no banco de dados</td>
    <td>5</td>
  </tr>
  <tr>
    <td>7</td>
    <td>BANCO</td>
    <td>Criar tabela de docentes</td>
    <td>8</td>
  </tr>
</table>

---

## Criar uma tela para visualizar dados de afastamento
---

<table class="table" id="table-tela-dados-afastamento">
  <tr>
    <th>ID</th>
    <th>Caregoria</th>
    <th>Tarefa</th>
    <th>Estimativa</th>
  </tr>
  <tr>
    <td>1</td>
    <td>DESIGN</td>
    <td>Fazer design da tela de listagem</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2</td>
    <td>FRONTEND</td>
    <td>Exibir uma lista de docentes afastados</td>
    <td>8</td>
  </tr>
  <tr>
    <td>3</td>
    <td>FRONTEND</td>
    <td>Filtragem dos docentes</td>
    <td>5</td>
  </tr>
  <tr>
    <td>4</td>
    <td>FRONTEND</td>
    <td>Editar informações de afastamento</td>
    <td>8</td>
  </tr>
  <tr>
    <td>5</td>
    <td>BACKEND</td>
    <td>Criar query para busca no banco de dados</td>
    <td>5</td>
  </tr>
</table>

---

## Criar uma tela para visualizar atividades dos docentes
---

<table class="table" id="table-tela-atividades-docentes">
  <tr>
    <th>ID</th>
    <th>Caregoria</th>
    <th>Tarefa</th>
    <th>Estimativa</th>
  </tr>
  <tr>
    <td>1</td>
    <td>DESIGN</td>
    <td>Fazer design da tela de listagem</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2</td>
    <td>FRONTEND</td>
    <td>Exibir uma lista de docentes em atividades</td>
    <td>8</td>
  </tr>
  <tr>
    <td>3</td>
    <td>FRONTEND</td>
    <td>Filtragem dos docentes por atividades</td>
    <td>5</td>
  </tr>
  <tr>
    <td>4</td>
    <td>FRONTEND</td>
    <td>Editar informações das atividades</td>
    <td>8</td>
  </tr>
  <tr>
    <td>5</td>
    <td>BACKEND</td>
    <td>Criar query para busca no banco de dados</td>
    <td>5</td>
  </tr>
</table>

---