# 🍣 Sushi Fresh - Delivery de Sushi

Um site moderno e responsivo para um serviço de delivery de sushi, focado em mostrar o menu com detalhes, depoimentos de clientes e informações de contato/localização.

## ✨ Visão Geral do Projeto

O **Sushi Fresh** é um website de uma empresa fictícia de delivery de culinária japonesa. O projeto foi desenvolvido para demonstrar a excelência do serviço com ênfase em **ingredientes frescos**, **preparo artesanal** e um **sabor inigualável**.

O site apresenta as seguintes seções principais:
* **Home:** Uma introdução chamativa com o lema do serviço.
* **Menu (Delivery):** Catálogo de pratos (sushi, sashimi, poke, etc.) com preços e uma descrição detalhada que aparece ao passar o mouse sobre o item.
* **Nossos Clientes (Review):** Seção com depoimentos e avaliações de clientes para construir confiança.
* **Nosso Endereço (Contato):** Localização do estabelecimento.

## 💻 Tecnologias Utilizadas

Este projeto foi construído utilizando as tecnologias fundamentais da web:

* **HTML5:** Estrutura semântica da página.
* **CSS3:** Estilização, layout responsivo e design moderno.
* **Google Fonts:** Utilização da fonte 'Roboto' para a tipografia.

## 🚀 Como Executar o Projeto Localmente

Siga os passos abaixo para ter uma cópia local do projeto rodando em seu computador.

### Pré-requisitos

Você só precisa de um navegador web moderno (como Chrome, Firefox, Edge, etc.).

### Instalação

1.  **Clone o repositório** para o seu computador:
    ```bash
    git clone https://github.com/natalylribeiro/sushi-fresh.git
    ```
2.  **Navegue até a pasta do projeto**:
    ```bash
    cd sushi-fresh
    ```
    (Substitua `sushi-fresh` pelo nome que você deu ao seu diretório, se for diferente).

3.  **Abra o arquivo `index.html`** no seu navegador de preferência. Você pode fazer isso clicando duas vezes no arquivo ou usando o comando:
    ```bash
    open index.html
    ```

O projeto será aberto e estará pronto para ser visualizado.

## 🎨 Estilização e Design

O design é caracterizado por:

* **Paleta de Cores:** Fundo escuro (`var(--bg): #080808` e `var(--black): #13131a`) combinado com uma cor principal forte (`var(--main-color): #b81b1b` e `var(--border): #790808`), remetendo à culinária e à sofisticação.
* **Layout Flexível:** O menu de itens é um grid que se adapta, e a navegação é fixa no topo.
* **Interatividade no Menu:** Ao passar o mouse sobre um item do menu (`.box`), a caixa muda de cor e uma descrição detalhada do produto (`.detalhes-produto`) é exibida, melhorando a experiência do usuário.