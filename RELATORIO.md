**Aluno:** Matheus Henrique Maraschin
**Disciplina:** Desenvolvimento Web I
**Trabalho:** Trabalho Avaliativo 01 – Publicando uma Página Web Estática no GitHub Pages
**Site:** https://matheusmaraschin.github.io/The-Last-of-Us/
**Repositório:** https://github.com/matheusmaraschin/The-Last-of-Us

## 1. Tema escolhido

Escolhi fazer um site sobre **The Last of Us**, com cinco páginas: início, jogos, personagens, história e série. Esse jogo marcou minha infancia, joguei o primeiro com 10 anos e zerei ele cerca de 15 vezes, joguei o segundo e zerei 5 vezes, e ainda assisti a série

## 2. Passo a passo

1. **Planejamento.** Decidi fazer a estrutura multipage para o codigo ficar mais organizado e não somente em um arquivo, por isso deixei o `index.html` fora da pasta html pois é um padrão muito utilizado.
2. **Estrutura de pastas.** Organizei o projeto com `index.html` na raiz, as outras páginas na pasta `html/`, o CSS em `css/style.css` e as imagens em `img/`.
3. **HTML.** Escrevi as cinco páginas com menu de navegação, seções, cards, tabela e listas. Aprendi novas tags para listas(dl,dt e dd): dt é a lista inteira, dt é o termo e dd é a descrição do termo.
4. **CSS.** Criei um arquivo css para todo o site, com cores, layout em grid e estilo do menu e do rodapé. Tive bastante dificuldade para entender: gap, repeat do grid, listas, object-fit(deu erro na hora de colocar a imagem)
5. **Imagens.** Baixei as imagens e coloquei na pasta `img/`. Escolhi as imagens que apresentavam melhor qualidade, tentei evitar imagens pixeladas ou de baixa qualidade
6. **GitHub Pages.** Ativei em Settings → Pages, escolhendo a branch `main` e a pasta raiz. O site ficou publicado no endereço acima. Demorou cerca de dois minutos pra conseguir botar o site no ar, normalmente demora uns 30s.
7. **Teste.** Abri o link em uma aba anônima e conferi o menu, os links e as imagens, deu tudo certo na primeira tentativa.

## 3. Ferramentas usadas e por quê

HTML: Para montar a estrutura e o conteúdo das páginas.
CSS: Para estilizar o site e definir o layout. 
GitHub: Para guardar o repositório público na internet.
GitHub Pages: Para publicar o site estático gratuitamente, com endereço público.
Vs Code : Estou familiarizado com essa plataforma, então escolhi ela.
Usei essencialmente o Claude AI para corrigir falhas e explicar as funções de grid, gap, listas em HTML e também para definir cores e fontes.

## 4. Conceitos novos que aprendi

- **Repositório:** pasta do projeto que o Git acompanha e que fica guardada no GitHub.
- **Commit:** registro de uma mudança no projeto, com uma mensagem explicando o que foi feito.
- **Push:** comando que envia os commits do meu computador para o GitHub.
- **GitHub Pages:** serviço que publica um site estático direto do repositório, com um endereço público.
- **Site estático:** site feito só de arquivos prontos (HTML, CSS e imagens), sem servidor nem banco de dados.
- **Markdown:** forma simples de formatar texto com símbolos, usada no README e nesse relatório.
- **Caminhos relativos:** endereços que partem da página atual. Nas páginas dentro de `html/`, o `../` serve para subir uma pasta.
- **Tags semânticas:** `<nav>`, `<main>`, `<section>`, `<header>` e `<footer>` dão significado a cada parte da página.
- **CSS Grid:** usei para organizar os cards em colunas que se ajustam à tela.

## 5. Dificuldades e como resolvi

No meio do caminho, fui colocar uma imagem, mas não carregava, eu chequei os nomes do src e do arquivo joel.jpg, parecia estar igual, mas na verdade o src tinha img/Joel.jpg, com J maiúsculo, só precisei ajeitar isso e funcionou.

## 6. Conclusão

Gostei bastante desse trabalho, achei que aprendi coisas importantes, e por ser um assunto que gosto, me interessei ainda mais para deixar o melhor possível.