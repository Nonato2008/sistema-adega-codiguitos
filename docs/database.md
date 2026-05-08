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

## 🪢 Relacionamento: Fornecedores

### 📌 Descrição
Um fornecedor pode ter varios produtos.

### 📄 Atributos
- id (PK)
- nome
- fornecedorImagem
- dataCad

## 🧾 Entidade: Venda

### 📌 Descrição
Representa uma transação de compra realizada e a saida de um produto.

### 📄 Atributos
- id (PK)
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

