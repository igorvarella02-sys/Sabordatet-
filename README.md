# Sabor da Teté — cardápio digital

Esta pasta é a versão estática pronta para publicar no GitHub Pages.

## Publicar no GitHub

1. Crie um repositório novo no GitHub.
2. Envie **todo o conteúdo desta pasta** para a raiz do repositório: `index.html`, `assets/` e `.nojekyll`.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch principal e a pasta `/ (root)`.
5. Salve e aguarde o endereço da página aparecer.

Os preços estão propositalmente como “Consulte o valor”. Para alterar textos, pratos ou valores, edite a versão-fonte em `client/src/pages/Home.tsx` e gere novamente a pasta `github-pages` com `pnpm build`.
