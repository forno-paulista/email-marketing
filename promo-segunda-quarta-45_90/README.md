# Forno Paulista – E-mail marketing

Repositório para hospedar as imagens do e-mail (GitHub Pages) e guardar o template.

## Estrutura

- `2026-09-promo/` – imagens usadas no e-mail (NÃO renomeie nem apague depois do envio)
- `template/email-forno-paulista.html` – template para o disparo (com placeholders `{{...}}`)
- `template/email-forno-paulista-PREVIEW.html` – só para visualizar; imagens embutidas (não use para enviar)
- `n8n/codigo-no-code.js` – código do nó Code do n8n, com o HTML já dentro

## Passo a passo

1. Crie um repositório **público** no GitHub (ex.: `forno-paulista-email`).
2. Envie o conteúdo desta pasta (Add file > Upload files; arraste as pastas e o arquivo `.nojekyll`).
3. Em **Settings > Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Espere 1 a 2 minutos e teste em janela anônima:
   `https://SEUUSUARIO.github.io/forno-paulista-email/2026-09-promo/hero-pizzas.png`
5. No `n8n/codigo-no-code.js`, troque `SEUUSUARIO` e preencha o `CONFIG`; cole no nó Code do n8n.

## Próximas campanhas

Crie uma pasta nova (ex.: `2026-10-promo`) com as imagens novas. Nunca altere a pasta de uma campanha já enviada.
