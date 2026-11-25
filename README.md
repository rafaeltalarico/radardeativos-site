# Radar de Ativos | Landing page

Página estática (`index.html` + `assets/`). Abra o arquivo no navegador ou publique a pasta em qualquer hospedagem estática.

## O que falta preencher
1. `index.html`, bloco `CONFIGURAÇÃO` no final: `GROUP_URL` (convite exclusivo do grupo) e `BOT_URL` (WhatsApp do bot).
2. Textos marcados em amarelo (`.todo`): credencial, dificuldade e resultado do Rafael, razão social e CNPJ.
3. Trocar `assets/print-*.svg` por imagens reais comprimidas (WebP/JPG) e ajustar os `src`.
4. Link da Política de privacidade no rodapé.

## Rastreamento
O GTM (`GTM-KB9M5FPT`) está logo após abrir o `<head>`, uma vez só. GA4 e pixel da Meta devem ser configurados dentro do GTM, sem código avulso. Cada clique em botão envia `cta_click` ao `dataLayer` (`cta_location`: hero, recebe, final, sticky, whatsapp_bot).
