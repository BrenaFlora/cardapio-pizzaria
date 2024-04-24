# Página de Cardápio de Pizzas

Este projeto é uma página web estática que apresenta um cardápio de pizzas salgadas e doces. O design é responsivo e elegante, perfeito para uma pizzaria que deseja mostrar seus pratos deliciosos de uma maneira organizada e atraente.

## Funcionalidades

- **Design Responsivo**: A página se adapta a diferentes tamanhos de tela, garantindo uma navegação fácil em dispositivos móveis e desktops.
- **Layout Flexível**: Utilizamos `display: flex` para criar um layout fluido que acomoda os cards do cardápio em colunas. Isso permite que os itens se ajustem de forma elegante à largura da tela.
- **Animações Suaves**: Para melhorar a interatividade do usuário, aplicamos animações CSS para suavizar a entrada de elementos na página (`fadeIn`) e para adicionar um leve movimento aos cards do cardápio quando o mouse passa sobre eles (`transform`).

### Seções da Página

- **Banner Principal**: Uma imagem de fundo grande e atraente com uma animação de fade-in que dá as boas-vindas aos visitantes do site.
- **Cardápio de Pizzas Salgadas**: Uma grade de cards de pizzas salgadas, cada um contendo uma imagem, o nome da pizza, e uma descrição dos ingredientes.
- **Cardápio de Pizzas Doces**: Similar ao cardápio de pizzas salgadas, mas destacando as opções de pizzas doces.
- **Seção dos Integrantes do Grupo**: Nomes das participantes, apresentadas em uma lista clara e estilizada.

### Tecnologias Utilizadas

- HTML5
- CSS3

### Estilos e Animações

A página utiliza Flexbox para criar um layout responsivo:

- `.menu-section` contém `display: flex` e `flex-wrap: wrap` para acomodar os cards em um formato de grade responsiva.
- `.menu-item` usa `flex: 0 0 calc(50% - 20px);` para controlar a largura dos cards e mantê-los em duas colunas.

Animações CSS são aplicadas para melhorar a experiência do usuário:

- `@keyframes fadeIn` para um efeito de fade suave no carregamento dos elementos.
- `:hover` sobre os `.menu-item` para uma pequena elevação e sombra mais profunda, dando uma sensação de profundidade.

### Integrantes

- Brena Flora Xavier Viana
- Maria Julia Magalhaes
- Maria Luiza Silva Rios



