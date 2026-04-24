# Design System - Sistema de Gerenciamneto de uma Adega

## Introdução

* O Design System em questão serve para ajudar o cliente a utilizar o sistema, sendo intuitivo e prático, com cores guias e design simplista.


## Fundamentos

### 🎨Cores:

<div style="background-color:#FFFF; padding:10px; color:black; border-radius:10px;">
  Primary Color - #FFFFFF
</div>

<div style="margin:2px; background-color:#E5E5E5; padding:10px; color:black; border-radius:10px;">
  Secondary Color - #E5E5E5
</div>

<div style="margin:2px; background-color:#A41623; padding:10px; color:white; border-radius:10px;">
  Third Color - #A41623
</div>

### Tipografia: 

* Fonte Principal: Inter, sans-serif
    - Melhor legibilidade;
    - Sensação de modernidade, rapidez e confiança;
    - Performance e responsividade;

* Hierarquia:
    - H1: 32px
    - H2: 24px
    - Texto: 16px
    - Small: 14px

### Componentes:

## 🔘Botão 

<button style="background-color: #A41623; color: #FFFFFF; border: none; padding: 12px 20px; border-radius: 8px;">
  Salvar Produto
</button>

### USO
Usados para adicionar, remover/desativar produtos;
    
## 📝Card 

<div style="width: 250px; border: 1px solid #E5E5E5; border-radius: 10px; overflow: hidden; font-family: sans-serif; background: #FFFFFF;">

  <!-- Imagem -->
  <div style="background: #E5E5E5; height: 140px; display: flex; align-items: center; justify-content: center; color: #999;">
    Imagem
  </div>

  <!-- Conteúdo -->
  <div style="padding: 12px;">
    
<h4 style="margin: 0 0 8px; color: #333;">
      Cerveja Brahma
    </h4>

 <!-- Quantidade -->
<div style="display: flex; align-items: center; justify-content: space-between; margin-bottom: 10px;">

<span style="font-size: 14px; color: #666;">
        Quantidade
      </span>

<div style="display: flex; align-items: center; gap: 6px;">
        
<button style="
          width: 28px;
          height: 28px;
          border: 1px solid #E5E5E5;
          background: #FFFFFF;
          border-radius: 6px;
          cursor: pointer;
        ">
          -
        </button>

<span style="min-width: 20px; text-align: center;">12</span>

<button style="
          width: 28px;
          height: 28px;
          border: none;
          background: #A41623;
          color: #FFFFFF;
          border-radius: 6px;
          cursor: pointer;
        ">
          +
</button>

</div>
</div>

<!-- Valor -->
<p style="margin: 0; font-weight: bold; color: #A41623;">
      R$ 89,90
</p>

  </div>

</div>

### USO
Expor os produtos de forma organizada;

## 🕳️Input  

<div style="font-family: sans-serif; width: 220px;">

  <input type="text" placeholder="Nome" style="width:100%; margin-bottom:6px; padding:6px;">
  
  <input type="number" placeholder="Quantidade" style="width:100%; margin-bottom:6px; padding:6px;">
  
  <input type="text" placeholder="Valor" style="width:100%; margin-bottom:6px; padding:6px;">
  
  <input type="text" placeholder="Fornecedor" style="width:100%; margin-bottom:8px; padding:6px;">

  <button style="width:100%; padding:6px; background:#A41623; color:#fff; border:none;">
    Salvar
  </button>

</div>

### USO
Campos de textos para informar dados do produto;

## ✔️Seletores

<style>
.menu {
  width: 180px;
  background: #FFFFFF; /* fundo principal */
  padding: 10px;
  border-right: 2px solid #E5E5E5;
}

.menu a {
  display: block;
  color: #333;
  padding: 10px;
  text-decoration: none;
  border-radius: 5px;
  margin-bottom: 5px;
}

.menu a:hover {
  background: #E5E5E5; /* leve destaque */
}

.menu a.ativo {
  background: #A41623; /* destaque principal */
  color: #FFFFFF;
}
</style>

<div class="menu">
  <a href="#" class="ativo">🏠 Início</a>
  <a href="#">📦 Produtos</a>
  <a href="#">📊 Relatórios</a>
  <a href="#">⚙️ Configurações</a>
</div>

### USO
Para menus;

## 🚢Navegação 

### USO
Menus laterais para navegar em diferentes campos;

## Princípios

### Responsividade:
    - Elementos funcionais;
    - Responsivos;
    - Para qualquer resolução e aparelho;

    * Para os componentes se comportarem de forma organizada

### Componentes visuais:
    - Imagens intuitivas;
    - Botões chamativos que expressem sua funcionalidade;

    * A paleta combina branco, cinza e vinho para garantir uma interface limpa, organizada e com destaque elegante alinhado ao tema de adega. Junto das imagens e botões que ajudarão o cliente em seu uso 

### Acessebilidade;
    - Foco no Usuário;
    - Tomar decisões baseadas nas prefereências do cliente;

