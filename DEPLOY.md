# Publicar na Vercel

Site estático: `index.html` + `assets/` + `sites-incriveis.js/.css`. Sem build.

## Opção 1 — Pelo painel (mais simples)
1. Crie conta em vercel.com (pode entrar com GitHub).
2. Suba esta pasta num repositório no GitHub.
3. Na Vercel: Add New → Project → importe o repositório.
4. Framework Preset: **Other**. Build Command e Output Directory: deixe vazios.
5. Deploy. Em ~30 s você recebe um endereço `.vercel.app`.

## Opção 2 — Pela linha de comando
    npm i -g vercel
    cd site
    vercel          # teste
    vercel --prod   # publicação

## Domínio próprio
Project → Settings → Domains → adicione o domínio e siga as instruções de DNS.

## Antes de divulgar
- Trocar o link do WhatsApp (QR) por wa.me/55DDDNUMERO.
- Incluir CREFITO, formação e anos de atuação no "Sobre".
- Opcional: imagem de compartilhamento (og:image) com a URL final.
