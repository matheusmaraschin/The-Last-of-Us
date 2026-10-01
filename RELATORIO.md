# Relatório de aprendizagem

- **Aluno:** Matheus Henrique Maraschin
- **Disciplina:** Desenvolvimento Web I
- **Trabalho:** Trabalho Avaliativo 01 – Publicando uma Página Web Estática no GitHub Pages
- **Site:** https://matheusmaraschin.github.io/The-Last-of-Us/
- **Repositório:** https://github.com/matheusmaraschin/The-Last-of-Us

## 1. Tema escolhido

Escolhi fazer um site sobre **The Last of Us**, com cinco páginas: início, jogos, personagens, história e série. Esse jogo marcou minha infância: joguei o primeiro aos 10 anos e zerei cerca de 15 vezes, joguei o segundo e zerei 5 vezes, e ainda assisti à série.

## 2. Passo a passo

1. **Planejamento.** Decidi fazer um site com várias páginas, para o código ficar mais organizado e não ficar tudo em um arquivo só. Deixei o `index.html` fora da pasta `html/` porque é um padrão muito usado e é a página que o GitHub Pages abre primeiro.
2. **Estrutura de pastas.** Organizei o projeto com `index.html` na raiz, as outras páginas na pasta `html/`, o CSS em `css/style.css` e as imagens em `img/`.
3. **HTML.** As cinco páginas têm menu de navegação, seções, cards, tabela e listas. Aprendi novas tags para listas de descrição: `dl` é a lista inteira, `dt` é o termo e `dd` é a descrição do termo.
4. **CSS.** Um único arquivo CSS cuida de todo o site, com cores, layout em grid e estilo do menu e do rodapé. Tive bastante dificuldade para entender `gap`, o `repeat` do grid, listas e `object-fit` (que deu erro na hora de colocar a imagem).
5. **Imagens.** Baixei as imagens e coloquei na pasta `img/`. Escolhi as de melhor qualidade e evitei as pixeladas.
6. **Git e GitHub.** Criei o repositório público no GitHub e enviei o código com Git, em commits separados por parte do site.
7. **GitHub Pages.** Ativei em Settings → Pages, escolhendo a branch `main` e a pasta raiz. Demorou cerca de dois minutos para o site entrar no ar, quando normalmente leva uns 30 segundos.
8. **Teste.** Abri o link em uma aba anônima e conferi o menu, os links e as imagens. Deu tudo certo na primeira tentativa.

## 3. Ferramentas usadas e por quê

- **HTML:** para montar a estrutura e o conteúdo das páginas.
- **CSS:** para estilizar o site e definir o layout.
- **Git:** para versionar o código e guardar o histórico de mudanças.
- **GitHub:** para guardar o repositório público na internet.
- **GitHub Pages:** para publicar o site estático gratuitamente, com endereço público.
- **VS Code:** já estou familiarizado com ele, então escolhi esse editor.
- **Claude (IA):** me explicou grid, gap, listas em HTML, e me sugeriu cores e fontes.

## 4. Conceitos novos que aprendi

- **Repositório:** pasta do projeto que o Git acompanha e que fica guardada no GitHub.
- **Commit:** registro de uma mudança no projeto, com uma mensagem explicando o que foi feito.
- **Push:** comando que envia os commits do meu computador para o GitHub.
- **GitHub Pages:** serviço que publica um site estático direto do repositório, com um endereço público.
- **Site estático:** site feito só de arquivos prontos (HTML, CSS e imagens), sem servidor nem banco de dados.
- **Markdown:** forma simples de formatar texto com símbolos, usada no README e neste relatório.
- **Caminhos relativos:** endereços que partem da página atual. Nas páginas dentro de `html/`, o `../` serve para subir uma pasta.
- **Tags semânticas:** `<nav>`, `<main>`, `<section>`, `<header>` e `<footer>` dão significado a cada parte da página.
- **CSS Grid:** usei para organizar os cards em colunas que se ajustam à tela.

## 5. Dificuldades e como resolvi

No meio do caminho, fui colocar uma imagem e ela não carregava. Conferi os nomes do `src` e do arquivo `joel.jpg` e pareciam iguais, mas na verdade o `src` estava `img/Joel.jpg`, com J maiúsculo. Só precisei corrigir isso e funcionou.

## 6. Conclusão

Gostei bastante deste trabalho e achei que aprendi coisas importantes. Por ser um assunto de que gosto, me interessei ainda mais em deixar o site o melhor possível.