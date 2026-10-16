# Playboy Fest – convite digital

Página estática (sem build). Arquivos:

- `index.html` – convite com botão "Como chegar" (Google Maps), `noindex` e tags de prévia do WhatsApp
- `og.jpg` – imagem 1200x630 que aparece no cartão do link

## Publicar na Hostinger em /playboyfest

1. hPanel > Git (ou Gerenciador de Arquivos) do site maxxeletricasolar.com.br.
2. Pasta de destino: `public_html/playboyfest`.
3. Conferir: https://maxxeletricasolar.github.io/playboyfest/

Se usar outro endereço, troque `maxxeletricasolar.github.io/playboyfest` nas linhas `og:url` e `og:image` do `index.html`.

## Depois da festa

Apague a pasta `playboyfest` do servidor.

## WhatsApp mostra prévia antiga?

O WhatsApp guarda a prévia em cache. Teste com `?v=2` no final do link.
