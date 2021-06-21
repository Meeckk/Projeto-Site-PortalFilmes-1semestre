# Projeto-Site-PortalFilmes-1semestre

`CURSO` Sistemas de Informação

`DISCIPLINA`DESENVOLVIMENTO DE INTERFACES WEB

`SEMESTRE`1º Semestre

`Para acessar o projeto basta clicar no link:` https://meuebook.github.io/MeuEbook.html

## Sobre / Objetivo

Primeiro trabalho pratico da matéria Desenvolvimento de Interfaces Web, colocando em pratica o que foi estudado durante o primeiro semestre do Curso de Sistemas de Informação. O trabalho foi desenvolvido com duas etapas, sendo a primeira Front-end com HTML e CSS (e também o uso de algumas bibliotecas como Boostrap e Jquery). E a segunda etapa o Back-end com Java Script, JSON e também o uso de uma API (The Movie DB).

Foi desenvolvido um site com a temática de Filmes, mostrando trailers e alguns filmes em cartaz da época da realização do trabalho, comentário sobre os filmes, novidades da época e filmes em cartaz da época, além de uma segunda página com diversos filmes em cartaz com sua sinopse, e ao clicar em ver mais terá a capa do filme e informações sobre o mesmo, além de um link redirecionando para outra pagina com mais informações sobre o filme escolhido.

## Etapas

Para a construção do projeto foi dividido em duas etapas sendo elas:

### Primeira Etapa

Nesta etapa, vamos montar o layout de um site de Portal de Filmes que seja responsivo e se adeque corretamente a telas de diferentes dispositivos. O site a ser criado é estático e você deve preencher cada seção com exemplos reais para marcar os locais onde virão os conteúdos reais. Sugerimos para isso, utilizar imagens de sites reais sobre filmes.

#### Critérios de Avaliação

`CRITÉRIO 1`: Conformidade com o Wireframe:

- O aluno seguiu orientações do wireframe, realizando incrementos ou alterações que melhoraram a estrutura de componentes do portal;

`CRITÉRIO 2:` Conteúdo:

- Conteúdos reais para o site: Utilizou imagens, textos, vídeos que contemplam o cenário real de mercado do site;

`CRITÉRIO 3:` Responsividade do Site:

- Responsividade funcional: O site apresenta adaptação e adequação de conteúdos para a versão mobile. Componentes se adaptam ao tamanho, imagem segue o padrão do grid, conteúdo ajusta a resolução com uso correto de media queries;

### Segunda etapa 

Nesta etapa, vamos dar vida ao layout desenvolvido no trabalho anterior. Vamos apresentar informações reais sobre os filmes obtidas dinamicamente a partir da integração com a API The Movie DB

#### Requisitos do Projeto

O site que você fará deve atender aos seguintes requisitos: 

- o site deve ser publicado em um ambiente da Internet (Repl.it, GitHub Pages, Heroku, Netlify ou outro a sua escolha); 
 
- o site deverá ser responsivo permitindo a visualização em um celular de forma adequada;

- o site deve ter uma Home-Page com a listagem dinâmica de itens obtidos via API The Movie DB à escolha do aluno que pode ser qualquer das alternativas como: (1) filmes populares, (2) filmes no cinema, (3) séries de TV ou outra listagem a ser projetada pelo aluno a partir da mesma API. Nessa página inicial, devem ser obedecidos os seguintes requisitos:
- para cada item da listagem devem ser exibidos um mínimo de três (3) dados textuais obtidos por meio da API que descrevam sucintamente o referido item (Ex: título, data, descrição, categoria, etc)
- para cada item da listagem, deve ser exibida uma imagem ilustrativa do referido item
- para cada item da listagem, deve haver um link que leve o usuário para outra página com mais informações sobre o item, seja no próprio site criado pelo aluno ou em outro site na Internet.

- o site deve apresentar uma Página de pesquisa em página adicional à home-page que permita ao usuário informar um texto e localizar informações providas pela API do The Movie DB que devem ser apresentadas como resultado da pesquisa. Na página de pesquisa, devem ser obedecidos os seguintes requisitos:
- o resultado da pesquisa poderá ser paginado ou não
- o resultado deve mostrar uma lista de itens tal qual a home-page com imagem e textos que descrevam o item retornado
- os itens do resultado devem ter um link que ao ser acionado, leve o usuário para a página original do referido item, cujo link é obtido por meio da API do The Movie DB.

#### Critérios de Avaliação

`CRITÉRIO 1:` Formato e responsividade:
- Responsividade funcional: O site apresenta adaptação e adequação de conteúdos para a versão mobile e desktop. Componentes se adaptam ao tamanho, imagem segue o padrão do grid, conteúdo ajusta a resolução com uso correto de media queries;

`CRITÉRIO 2:` Home-page dinâmica integrada com API:

- Home-page com listagem de itens e páginas adicional para visualizar as informações detalhadas de um item ao ser clicado 
Home-Page dinâmica integrada com a API The Movie DB, apresentando os itens a partir dos dados obtidos da API, com a imagem representativa de cada item e os textos descritivos. Ao clicar no item exibido na Home-Page, o usuário visualiza as informações detalhadas em uma página específica feita pelo aluno para o este projeto;

`CRITÉRIO 3:` Funcionalidade de Pesquisa integrada com API:

- Página de Pesquisa totalmente funcional com link para página externa 
Página de pesquisa que permite ao usuário informar um texto e obter os resultados a partir da API The Movie DB, apresentando os itens com a imagem representativa de cada item e os textos descritivos. Ao clicar em um item dos resultados o usuário é direcionado para uma página externa associada ao item;
