# Pizzaria Sabores em Chamas

Cardápio online da pizzaria. O cliente escolhe as pizzas e bebidas, informa nome, endereço e forma de pagamento, e o pedido é enviado pronto pelo WhatsApp.

É uma página única (`index.html`), sem instalação nem servidor: basta abrir o arquivo no navegador.

## Como alterar

Tudo fica no `<script>` do `index.html`:

- **Número do WhatsApp:** constante `WHATSAPP` (DDI + DDD + número, só dígitos).
- **Sabores, bebidas e preços:** lista `MENU`.
- **Sabores de borda:** lista `BORDAS`.
- **Horário de funcionamento:** constantes `ABRE`, `FECHA` e `FOLGA` (dia da semana em que fecha).

## Publicar no GitHub Pages

No repositório, vá em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`. O cardápio fica disponível em `https://<usuario>.github.io/<repositorio>/`.
