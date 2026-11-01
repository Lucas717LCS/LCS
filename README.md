# Portfólio pessoal

Autor: Lucas da Conceição

Site estático (HTML, CSS e JavaScript), sem build. A sala 3D usa Three.js, carregado por CDN.

## O que tem no site

- Cenário original de sala de aula ao entardecer, com pétalas de sakura, estrelas e janelas que piscam
- Animação de entrada no título e leve paralaxe com o mouse
- Sala de aula 3D: arraste para girar, clique na carteira que brilha para pontuar
- Cadastro simples, sem login, que gera um cartão de aluno
- Sua foto no topo da página (arquivo `foto.jpg`; para trocar, substitua o arquivo mantendo o nome)
- Projetos, tecnologias, trajetória e contato

## Antes de publicar

1. Abra `script.js` e confira o bloco `CONFIG`. Falta o link do seu LinkedIn.
2. Troque `cisiaCode` e `portfolioCode` pelos links dos repositórios, quando existirem.
3. Configure o destino do cadastro (próxima seção).

## Receber os cadastros

Um site estático não guarda dados sozinho. Sem configuração, o formulário só funciona como demonstração e nada chega até você. O jeito mais simples:

1. Crie uma conta grátis em formspree.io e crie um formulário.
2. Copie o endereço que ele gera (algo como `https://formspree.io/f/xxxxxxxx`).
3. Cole em `formEndpoint` no `CONFIG` do `script.js`.

Os cadastros chegam no seu e-mail. Como o formulário coleta nome e e-mail de visitantes, mantenha o aviso de consentimento e use os dados só para o que foi informado (LGPD).

## Testar no computador

Abra `index.html` no navegador, ou use a extensão Live Server do VS Code.

## Publicar na Vercel

1. Crie um repositório no GitHub (por exemplo, `portfolio`) e suba estes arquivos.
2. Em vercel.com, entre com sua conta do GitHub e clique em **Add New > Project**.
3. Escolha o repositório. Em *Framework Preset* deixe **Other**. Não precisa de build command.
4. Clique em **Deploy**.

A partir daí, cada `git push` gera um novo deploy automaticamente.

## Depois de publicar

- Coloque o link do site no seu perfil do LinkedIn e na seção **Destaques**.
- Grave um vídeo curto da sala 3D e do título animado para o post. Funciona bem no LinkedIn.
