# LP Formação Render.IA

Landing page de vendas da Formação Render.IA — Montani 3D.

## Deploy

**Domínio:** https://formacaorenderia.montani3d.com.br/
**Repo:** https://github.com/empreendedorartificial/lp-formacao-renderai

Repositório git conectado ao Cloudflare Pages. Build vazio (HTML estático), output `/`. Alteração → `git commit` + `git push` → deploy automático em ~30s.

### Prévia de link (Open Graph)
A imagem que aparece no card de WhatsApp/Instagram/Facebook é definida pelas meta tags `og:image`/`twitter:image` no `<head>`, apontando para `assets/og-formacao-renderia.png` (card 1200×630 com a logo oficial da formação). Sem essas tags, as redes puxam uma imagem qualquer da página.

## Stack

- HTML único, CSS inline, ~92KB
- Imagens otimizadas em WebP, ~4MB total
- Zero dependências externas (sem jQuery, sem WordPress)
- Pixels integrados: Meta, UTMify, GA4, GTM, TikTok, Pinterest

## Estrutura

```
index.html              — página completa
assets/
  modulos/              — capas dos 16 módulos
  manuais/              — 29 capas dos manuais de criativos
  agentes/              — 16 avatares dos agentes IA
  bonus-render10x/      — 16 capas do curso bônus Render 10x
  ...                   — imagens auxiliares (Pessoas, Call, Certificado, etc.)
```

## Links importantes no HTML

- Hotmart checkout: `pay.hotmart.com/W105070047I?off=wspdppzx&checkoutMode=10`
- WhatsApp suporte: `44997234024`
- Meta Pixel: `2428536680685666`
