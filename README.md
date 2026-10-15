# Farol Geleias — Loja demonstrativa

Site estático em HTML, CSS e JavaScript. Funciona no GitHub Pages sem banco de dados, instalação, terminal ou processo de compilação.

## Publicar no GitHub Pages
1. Extraia o ZIP no computador.
2. Crie um repositório no GitHub (por exemplo `farol-geleias`).
3. Envie **os arquivos de dentro da pasta** (`index.html`, `style.css`, `app.js` e a pasta `assets`) à raiz do repositório. Não envie somente o ZIP.
4. No repositório, vá em **Settings → Pages → Build and deployment**. Escolha **Deploy from a branch**, selecione **main** e **/(root)**, depois **Save**.
5. Aguarde o GitHub mostrar o link de publicação. A página inicial será `index.html`.

## Configurações
- WhatsApp do pedido: constante `WHATSAPP` no início de `app.js` (`5519982480386`).
- Valor por pote: constante `PRICE` no início de `app.js` (`40`).
- Nomes, descrições, imagens e ordem: lista `products` em `app.js`.
- As seis artes em `assets/` são estudos visuais e os sabores são ilustrativos. Confirme produtos, ingredientes, pesos, estoques e informações legais antes de vender de verdade.

## Como funciona
- Carrinho com quantidades, remoção e armazenamento local no navegador.
- Resumo visual de pedido imprimível / salvável como PDF; não é nota fiscal.
- Botão de checkout abre WhatsApp com a mensagem completa do pedido pré-preenchida; o cliente precisa tocar em enviar no WhatsApp.
- O frete não é calculado e deve ser combinado diretamente.
- Não há processamento de pagamento, estoque remoto nem envio automático de dados.
