# RiffReview - Plataforma de Avaliação Musical

Este projeto abriga a interface web para o RiffReview, com o objetivo de criar um espaço interativo onde os usuários possam classificar, comentar e descobrir músicas, álbuns e bandas.

## 🎯 Funcionalidades

* **Avaliação de Mídias:** Telas para os usuários atribuírem notas específicas a músicas individuais, álbuns completos e bandas.
* **Média de Classificações:** Sistema que calcula e exibe a nota média de cada música, banda ou álbum de acordo com as avaliações da comunidade.
* **Comentários e Resenhas:** Espaço para os usuários escreverem descrições em texto sobre suas opiniões e lerem o que outras pessoas acharam das faixas.
* O layout e as interações poderão ser divididos entre os atores do sistema, como o **Usuário Comum**, que explora o catálogo, dá notas e escreve resenhas, e possivelmente um **Administrador**, responsável por moderar as opiniões e manter o catálogo de bandas e álbuns atualizado.

## 🗂️ Estrutura do Projeto

A organização de pastas e arquivos está dividida da seguinte forma:

* 📁 `infraestructure/`: Diretório base para recursos de infraestrutura visual e estática.
  * 📁 `assets/`: Contém todos os recursos complementares utilizados nas páginas.
    * 📁 `audio/`: Arquivos de áudio da aplicação (ex: `pianinho_massa.wav`).
    * 📁 `css/`: Folhas de estilo para a customização visual (ex: `style.css`).
    * 📁 `fonts/`: Fontes tipográficas personalizadas.
    * 📁 `icons/`: Ícones utilizados no projeto, incluindo o favicon principal (`iconjuju.ico`).
    * 📁 `images/`: Imagens gerais do layout e do catálogo.
    * 📁 `js/`: Scripts para lógicas de interação.
* 📁 `pages/`: Concentra os documentos e marcações estruturais em HTML.
  * 📁 `tests/`: Diretório reservado para páginas de testes, atividades e rascunhos (ex: `atividade-3.html`, `atividade4.html`, `sandbox.html`).
  * 📄 `index.html`: Arquivo principal e ponto de entrada da aplicação web.
* 📄 `readme.md`: Documentação geral do projeto.

## 🚀 Evolução Futura da Estrutura

A estrutura atual mudará consideravelmente ao longo do desenvolvimento. O repositório será expandido para suportar os requisitos funcionais do sistema, ganhando novas páginas para exibir detalhes de artistas, dashboards de notas e os feeds de opiniões dos usuários.