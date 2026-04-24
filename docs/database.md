# 🗄️ Modelo de Dados

Este documento apresenta o modelo de dados do sistema, com foco nas entidades e seus relacionamentos.

## 📦 Entidade: Produtos

### 📌 Descrição
Representa os produtos em estoque.

### 📄 Atributos
- id (PK)
- nome
- preco
- qtd(quantidade)
- status
- produtoImagem
- dataVenci
- dataCad

## ## 🪢 Relacionamento: Fornecedores

### 📌 Descrição
Um fornecedor tem varios produtos.

### 📄 Atributos
- id (PK)
- nome
- idProduto (FK)
- fornecedorImagem
- dataCad

## 🧾 Entidade: Venda

### 📌 Descrição
Representa uma transação de compra realizada e a saida de um produto.

### 📄 Atributos
- id (PK)
- idProduto (FK)
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
- valor


