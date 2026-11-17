# Comprimidos da Joca

Site estático pronto para GitHub Pages.

## Publicar no GitHub Pages

1. Cria um repositório no GitHub (recomenda-se torná-lo **Public**).
2. Faz upload destes ficheiros mantendo a estrutura:
   - `index.html`
   - `.nojekyll`
   - `assets/logo.svg`
   - `assets/favicon.svg`
3. No repositório, vai a **Settings → Pages**.
4. Em **Build and deployment**, escolhe **Deploy from a branch**.
5. Seleciona a branch `main` e a pasta `/(root)`.
6. Guarda e espera pelo deployment.

Não é necessário GitHub Actions para esta versão.

### Importante
Os comprimidos, histórico e fotos continuam guardados apenas no `localStorage` do navegador/dispositivo onde a aplicação é usada. O GitHub Pages apenas aloja o site.
