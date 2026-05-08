# 🗄️ Modelo de Dados

Este documento apresenta o modelo de dados do sistema, com foco nas entidades e seus relacionamentos.

## 📦 Entidade: Produtos

### 📌 Descrição
Representa os produtos em estoque.

### 📄 Atributos
- id (PK)
- idForn (idFornecedor)
- nome
- descricao
- preco
- qtd(quantidade)
- status
- produtoImagem
- dataVenci
- dataCad

## 🪢 Relacionamento: Fornecedores x Produtos

### 📌 Descrição
Um fornecedor pode ter varios produtos.

### 📄 Atributos
- id (PK)
- nome
- fornecedorImagem
- dataCad

## 🧾 🪢 Relacionamento: Venda x Proprietaros

### 📌 Descrição
Uma venda pertence a um proprietario e a um vendedor e um proprietario possue varias vendes ou uma

### 📄 Atributos
- id (PK)
- idProprietario (FK)
- idVendedor (FK)
- valor_total
- dataCad

## 🪢 Relacionamento: Venda x Itens_Venda

### 📌 Descrição
Uma venda pode conter vários itens.

### 🧾 Estrutura (Itens_Venda)
- id (PK)
- idProduto(FK)
- idVenda (FK)
- qtd (quantidade)
- valorItem

## 📦 Entidade: Propreitarios

### 📌 Descrição
Reprsenta os proprietarios que podem acessar o sistema .

### 📄 Atributos
- id (PK)
- nome
- email
- senha
- dataCad

## 🪢 Relacionamento: Proprietarios x Vendedores

### 📌 Descrição
Um vendedor possue um proprietario e um proprietario possue um ou varios vendedores

### 🧾 Estrutura (Vendedores)
- id (PK)
- idProprietario(FK)
- nome
- dataFunc

