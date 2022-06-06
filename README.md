# CSS: dispondo elementos com Flexbox e Grid

Curso da Alura sobre disposição dos elementos utilizando **flexbox** e **grid**.

## Objetivo Final &#x1F3AF;

Construir um site com tema de skate aplicando as tecnologias mais novas do CSS.

URL do curso -> [CSS: dispondo elementos com Flexbox e Grid](https://cursos.alura.com.br/course/css-dispondo-elementos-flexbox-grid)

![CSS: dispondo elementos com Flexbox e Grid](https://www.alura.com.br/assets/api/share/curso-css-dispondo-elementos-flexbox-grid.png)

## Links Úteis &#x1F517;
* [Projeto no Figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid) - Layout base para a criação do projeto.
* [Propriedades Flex](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Para conferir todas as propriedades e valores do Flexbox, você pode conferir o post do CSS-TRICKS. Esse post é bem completo.
* [Flexbox Froggy](https://flexboxfroggy.com/) - Jogo didático para exercitar os conceitos do **flex** do **CSS**.

## 01 - Flexbox &#x1F516;
* O que é um flex-container;
    * Flex container é o elemento que recebe grande parte das propriedades de posicionamento para suas tags filhas;
* As propriedades de posicionamento justify-content e align-items;
    * `justify-content` distribui o espaço restante do flex container entre suas tags filhas e `align-items` alinha verticalmente as tags filhas, ou seja, são propriedades de posicionamento horizontal e vertical respectivamente.

### 01 - O Projeto e as Ferramentas
* Criar o `index.html`.

### 02 - O Flex Container
* Gerar os primeiros elementos do `index.html`.

### 03 - Justify-content e Align-items
* Estilizar o cabeçalho principal da página.
* Aplicar as propriedades do `justify-content`.
* Aplicar as propriedades do `align-items`.

***

## 02 - Mais Funcionalidades do Flexbox &#x1F516;
* Como criar quebra de linha de um flex-container com a propriedade `flex-wrap`;
    * `flex-wrap` é a propriedade que usamos quando não existe mais espaço para comportar todos os elementos horizontalmente/verticalmente e é necessário uma “quebra de linha” para manter a proporção dos elementos.
* Alterar a orientação do flex container com a propriedade flex-direction;
    * Naturalmente a orientação do flex container é na horizontal e para trocar o seu eixo, basta usar a propriedade `flex-direction`.
* Propriedades de posicionamento de um `flex-item` com `justify-self` e `align-self`;
    * As propriedades de posicionamento `justify-content` e `align-items` movimentam todos os flex items, se precisamos de um posicionamento individual, usamos as propriedades `-self` nos flex items específicos.
* Uso de flex para remanejar pseudo-elementos;
    * Existem diversas situações que a propriedade de flex pode ser utilizada. É inclusive um incentivo usar flex no lugar de trocar o display para inline/inline-block.

### 01 - Terminando o Cabeçalho
* Setar uma descrição de um ícone da tela usando o `aria-label`.

### 02 - O flex-wrap e flex-direction
* Desenvolver o menu lateral do site.
* Aplicar o `flex-direction` no menu lateral.
* Aplicar o `align-self` para somente um elemento do container flex.

### 03 - Sem Medo de Usar Flex
* Inserir os ícones no menu.

### 04 - Transição do Menu Lateral
* Criar o recurso de menu lateral clicavel.

***

## 03 - O que o Flex não Consegue Fazer &#x1F516;
* As limitações de trabalhar com flexbox.
    * A principal delas é trabalhar com dois eixos ao mesmo tempo, eixo vertical e horizontal.
* O funcionamento básico do grid.
    * A ideia de grid container é bem parecida com flex container, mas no grid container o fluxo é vertical e também ganhamos acesso a outras propriedades.
* Propriedades para criar linhas e colunas: grid-template-rows e grid-template-columns.
    * Os valores que essas propriedades recebem são os tamanhos das colunas/linhas. Ex: para 3 colunas de 30px a propriedade se escreve: grid-template-columns: 30px 30px 30px.
* Nova unidade de medida fr.
    * É a unidade de medida para trabalhar com proporções de uma maneira mais simples do que porcentagem. Principalmente quando a porcentagem é uma dízima periódica.
* Mescla de linhas e colunas com as propriedades grid-columns: span n e grid-rows: span n.
    * É o conceito de “mescla de células”. Serve para dizer quantas colunas/linhas um elemento ocupa dentro do grid container.

### 01 - Litimações do Flexbox
* Começar a fazer a parte dos cartões.

### 02 - A Solução do Grid
* Utilizar a propriedade **grid**.
* Definir o número de colunas com o `grid-template-columns`.

### 03 - Estilização Básica do Cartão
* Ajeitar os componentes do cartão.

### 04 - Montando o Cartão com Grid
* Utilizar a propriedade `grid-column`.