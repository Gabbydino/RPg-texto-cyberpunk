# Neo-Kowloon // Terminal de Acesso

RPG estilo terminal cyberpunk, feito em HTML/CSS/JS puro, num único arquivo.

## Como subir no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `neo-kowloon-rpg`).
2. Suba o arquivo `index.html` pra raiz do repositório (o nome precisa ser `index.html` pro GitHub Pages reconhecer automaticamente).
3. Vá em **Settings > Pages** no repositório.
4. Em "Source", selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
5. Salva e espera uns minutinhos — o link vai aparecer ali mesmo em Settings > Pages, algo tipo:
   `https://seu-usuario.github.io/neo-kowloon-rpg/`

Só um detalhe: o jogo carrega as fontes Chakra Petch e Share Tech Mono via Google Fonts, então ele precisa de internet pra ficar com a cara certa (isso não afeta o deploy no Pages, só significa que não funciona 100% offline).

Fora isso, é um único HTML autocontido — sem build, sem dependências pra instalar.
