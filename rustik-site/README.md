# Rustik Lustres — Landing page

Site estático (HTML + CSS + JS puro), pronto para o GitHub Pages.

## Estrutura
```
index.html
assets/
  css/style.css      cores, fontes e layout
  js/main.js         menu mobile, galeria ampliada, animações
  fonts/             Cinzel e Lora (hospedadas no próprio site)
  img/               fotos otimizadas (.webp), logo, ícones, imagem de compartilhamento
  video/             vídeo do processo (queima e lavagem)
```

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub (ex.: `rustiklustres`).
2. Envie todos os arquivos desta pasta para a raiz do repositório (pelo site: **Add file → Upload files**, arraste tudo e confirme).
3. Vá em **Settings → Pages**, em *Source* escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
4. Em 1–2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/rustiklustres/`.

### Domínio próprio (opcional)
Em **Settings → Pages → Custom domain**, informe o domínio (ex.: `rustiklustres.com.br`) e crie no registro do domínio um CNAME apontando para `SEU-USUARIO.github.io`.

## Editar
- **WhatsApp:** procure por `5531986433260` no `index.html`.
- **Instagram:** procure por `instagram.com/rustiklustres`.
- **Fotos:** troque os arquivos em `assets/img/` mantendo o mesmo nome, ou altere o `src` no `index.html`.
- **Imagem de compartilhamento:** depois de publicar, troque `assets/img/og-image.jpg` no `index.html` pelo endereço completo (ex.: `https://SEU-USUARIO.github.io/rustiklustres/assets/img/og-image.jpg`) para a prévia aparecer no WhatsApp.
