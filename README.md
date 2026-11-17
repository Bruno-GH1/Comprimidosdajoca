# Comprimidos da Joca

Website estático para acompanhar a toma diária de comprimidos.

## GitHub Pages

1. Cria um repositório no GitHub.
2. Coloca estes ficheiros na branch `main`.
3. Em **Settings → Pages**, escolhe **GitHub Actions**.
4. Faz push para `main`; o workflow publica automaticamente o site.

A aplicação não precisa de servidor ou base de dados: o estado é guardado no `localStorage` do navegador.

## Estrutura

- `index.html` — aplicação.
- `assets/logo.svg` — logo principal.
- `assets/favicon.svg` — favicon.
- `.github/workflows/pages.yml` — deploy automático para GitHub Pages.
