# Central de Operações & Riscos — Deploy

Pacote pronto para publicar a Central no **Cloudflare Pages** (upload de assets) e no **GitHub Pages**.

> Gerado em: 2025-11-12T17:03:02.161356Z

## Cloudflare Pages (upload do ZIP)
1. Acesse **Cloudflare Dashboard** → **Pages** → **Create a project** → **Upload assets**.
2. Arraste e solte este arquivo ZIP.
3. O arquivo principal é `index.html` (seu *Central de Ajuda.html* renomeado).

## GitHub Pages
1. Crie um repositório.
2. Suba estes arquivos (`index.html`, `_headers`, `README.md`, `LICENSE`).
3. Em **Settings → Pages**, selecione *Deploy from a branch* → `main` → `/ (root)`.
4. Acesse a URL do Pages depois do publish.

## Observações
- Se desejar headers diferentes, edite o arquivo `_headers`.
- Para colaboração em equipe, use o GitHub (PRs e reviews).
