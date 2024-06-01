
# Página web: Utilizando a responsividade em aplicações com HTML e CSS

## Introdução

Projeto realizado junto ao 2 ano do EM na disciplina de Matemática II baseado no curso "Página web: utilizando a responsividade em aplicações com HTML e CSS - Parte 1" da Alura. 

## Rúbricas

* **Aula 01**
   1. Analisar os protótipos disponíveis para o projeto, entendendo a disposição dos elementos em relação ao tamanho da tela. Comparar os layouts mobile e tablet.
* **Aula 02**
   1. Criar os arquivos do projeto: index.html e style.css;
   2. Adicionar a estrutura HTML básica:
        * tags principais: ```<html>, <head>, <link>, <title>, <body>```;
        * metadados: ```charset, viewport```;
   3.Criar a propriedade ```:root``` no style.css, para variáveis personalizadas;
   4. Criar reset.css para resetar as configurações utilizando exemplo [Reset CSS: O que é, Exemplos, Como Criar e Utilizar](#links);
   5. Criar o cabeçalho da página com os items: menu hamburger, meus favoritos, carrinho de compras, meu perfil.
* **Aula 03**
   1. Usar a tag ```header``` com as informações do cabeçalho;
   2. Usar a tag ```img```;
   3. Criar um novo arquivo ```header.css``` para estilizar o conteúdo da tag ```header```;
   4. Criar dois ```div``` com ```class``` ```conteiner```. Um contendo o menu hamburger, outro contendo os demais items;
   5. Modificar a classe div para flex container com as propriedades display, justify-content e align-items.
* **Aula 04**
   1. Estruturar um menu hambúrguer utilizando tags como ```<input>```, ```<label>```, ```<ul>```, e ```<li>```;
   2. Criar uma lista de opções do menu, definindo suas classes e atributos;
   3. Ocultar a lista inicialmente, definindo a propriedade ```display: none;```;
   4. Exibir a lista quando clicamos no menu, implementando a regra CSS ```:checked```;
   5. Corrigir o posicionamento da lista, utilizando as propriedades ```position``` e ```top```.
* **Aula 05**
   1. Estilizar o menu hambúrguer para melhorar sua aparência e usabilidade;
   2. Personalizar os itens da lista, inserindo um gradiente com a propriedade CSS ```linear-gradient```;
   3. Criar mais variáveis de cor no :root para facilitar a manutenção e modificação do estilo;
   4. Ajustar o espaçamento do menu, utilizando a propriedade ```padding```.
* **Aula 06**
   1. Identificar e comparar diferentes tipografias, observando detalhes como serifa, peso e estilo;
   2. Baixar e incorporar uma fonte externa ao projeto, utilizando o Google Fonts;
   3. Aplicar a nova fonte no projeto, definindo propriedades como ```font-family```, ```font-size``` e ```font-weight```;
* **Aula 07**
   1. Criar a estrutura HTML para um banner, utilizando as tags ```<section>```, ```<h2>```, ```<p>```, e ```<input>```;
   2. Determinar um **padrão de classes** aos elementos, para identificá-los dentro da mesma seção de conteúdo;
   3. Estilizar o banner usando CSS, ajustando propriedades de cor, texto, espaçamentos e fundo da tela;
   4. Adicionar estilos a um campo de texto, utilizando o seletor de pseudo-classe ```::placeholder```.
* **Aula 08**
   1. Adicionar uma seção de carrossel ao projeto para exibir os novos lançamentos;
   2. Inserir estilo ao título da seção, através do novo arquivo ```carrossel.CSS```;
   3. Utilizar a ferramenta SwiperJS para integrar o código de um carrossel responsivo;
   4. Adicionar imagens dos livros ao carrossel para exibição.
* **Aula 09**
   1. Ajustar imagens do carrossel, corrigindo a exibição com a ferramenta SwiperJS;
   2. Corrigir a disposição dos livros no arquivo HTML adicionando o diretório das imagens corretamente;
   3. Remover as setas de navegação do carrossel para uma visualização mais limpa;
   4. Adicionar a paginação, mostrando bolinhas indicadoras da página atual do carrossel;
   5. Remover a barra de rolagem, para uma aparência mais elegante no projeto.
* **Aula 10**
   1. Criar um card no HTML, estruturando-o com tags como ```div```, ```img``` e ```a```;
   2. Organizar cada divisão do HTML por classes e selecioná-las separadamente no arquivo CSS;
   3. Estilizar os textos e botões do card, definindo cores, tamanhos e pesos das fontes com CSS;
   4. Posicionar corretamente os elementos, utilizando propriedades como ```display: flex;``` e ```justify-content```.
* **Aula 11**
   1. Estruturar a seção "Tópicos Visitados Recentemente", utilizando tags como ```h2```, ```ul``` e ```li```;
   2. Adicionar tópicos relevantes, cada um com um link a correspondente;
   3. Desenvolver estilos CSS, incluindo cores de fundo, alinhamento de texto e espaçamento entre elementos;
   4. Determinar uma quebra de texto, utilizando a propriedade CSS ```flex-wrap```.
* **Aula 12**
   1. Criar a seção de contato, adicionando elementos HTML como título, texto e campo de email;
   2. Estilizar a seção de contato, determinando cores de fundo, tamanho de fonte e espaçamento;
   3. Adicionar o rodapé no final da página HTML, utilizando um divisor hr e a tag footer;
   4. Aplicamos estilos CSS ao rodapé, ajustando a cor de fundo e o espaçamento;
   5. Finalizar a implementação do layout mobile, salvando os arquivos no VS Code.



## Links

* Protótipo de alta fidelidade em três versões pode ser encotrando [aqui](https://www.figma.com/community/file/1349471036706928943);
* [O que é o HTML e suas tags? Parte 1: estrutura básica](https://www.alura.com.br/artigos/o-que-e-html-suas-tags-parte-1-estrutura-basica?_gl=1*tf3i4g*_ga*OTg1ODEyMDA0LjE3MTcxODYwMzE.*_ga_1EPWSW3PCS*MTcxNzE4NjAzMi4xLjEuMTcxNzE5MDMyOC4wLjAuMA..*_fplc*bnB5SEF4djVFMFoyOThQOHd4eWYlMkJSbTEya05aMXlRTVJ3VE9ySkRKZk5iTHkwZHNKQm1ESXFMbmtiZnB5b1dCJTJGNGVXRjdsQVNZVzdSTFA5UUpiZWI1V3V2a2FtWHBCeTdOVXlHeHU3OGFnY05MJTJGRWxxTGFxOXJCZFduMFZRJTNEJTNE);
* [Reset CSS: O que é, Exemplos, Como Criar e Utilizar](https://www.alura.com.br/artigos/o-que-e-reset-css?_gl=1*14y0iuy*_ga*OTg1ODEyMDA0LjE3MTcxODYwMzE.*_ga_1EPWSW3PCS*MTcxNzE4NjAzMi4xLjEuMTcxNzE5MDMyOC4wLjAuMA..*_fplc*bnB5SEF4djVFMFoyOThQOHd4eWYlMkJSbTEya05aMXlRTVJ3VE9ySkRKZk5iTHkwZHNKQm1ESXFMbmtiZnB5b1dCJTJGNGVXRjdsQVNZVzdSTFA5UUpiZWI1V3V2a2FtWHBCeTdOVXlHeHU3OGFnY05MJTJGRWxxTGFxOXJCZFduMFZRJTNEJTNE);
* [Flexbox CSS: Guia Completo, Elementos e Exemplos](https://www.alura.com.br/artigos/css-guia-do-flexbox?_gl=1*15je8fx*_ga*OTg1ODEyMDA0LjE3MTcxODYwMzE.*_ga_1EPWSW3PCS*MTcxNzE5NjE0Ni4yLjEuMTcxNzE5NzU1Ny4wLjAuMA..*_fplc*bnB5SEF4djVFMFoyOThQOHd4eWYlMkJSbTEya05aMXlRTVJ3VE9ySkRKZk5iTHkwZHNKQm1ESXFMbmtiZnB5b1dCJTJGNGVXRjdsQVNZVzdSTFA5UUpiZWI1V3V2a2FtWHBCeTdOVXlHeHU3OGFnY05MJTJGRWxxTGFxOXJCZFduMFZRJTNEJTNE)
* [CSS FlexBox: Dicas para começar](https://cursos.alura.com.br/extra/alura-mais/css-flexbox-dicas-para-comecar-c301)
* [Entenda a propriedade position CSS](https://www.alura.com.br/artigos/entenda-a-propriedade-position-css?_gl=1*s6n2pb*_ga*OTg1ODEyMDA0LjE3MTcxODYwMzE.*_ga_1EPWSW3PCS*MTcxNzE5NjE0Ni4yLjEuMTcxNzE5NzU1Ny4wLjAuMA..*_fplc*bnB5SEF4djVFMFoyOThQOHd4eWYlMkJSbTEya05aMXlRTVJ3VE9ySkRKZk5iTHkwZHNKQm1ESXFMbmtiZnB5b1dCJTJGNGVXRjdsQVNZVzdSTFA5UUpiZWI1V3V2a2FtWHBCeTdOVXlHeHU3OGFnY05MJTJGRWxxTGFxOXJCZFduMFZRJTNEJTNE)
* [Elementos block-level]([https://](https://developer.mozilla.org/pt-BR/docs/Glossary/Block-level_content))
* [O que é o HTML e suas tags? Parte 3: elementos block-level](https://www.alura.com.br/artigos/html-tags-elementos-block-level?utm_source=gnarus&utm_medium=timeline&_gl=1*1gx8pkv*_ga*MTIzNDQxOTM3Ny4xNzE3MTc1NzEx*_ga_1EPWSW3PCS*MTcxNzI2ODg4Mi42LjEuMTcxNzI3NDI0OS4wLjAuMA..)
