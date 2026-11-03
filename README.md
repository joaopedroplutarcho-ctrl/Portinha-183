# Portinha 183

Site da cafeteria Portinha 183 (São Paulo, SP): cardápio, carrinho com envio do pedido pelo WhatsApp, assinatura, história e contato.

É um único arquivo `index.html`, sem build e sem dependências (só as fontes do Google Fonts).

## Publicar no GitHub Pages
1. Envie `index.html` e este `README.md` para a raiz do repositório.
2. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
3. Aguarde um minuto. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Trocar informações
Abra `index.html` e procure por:
- `PHONE` para o número do WhatsApp (formato 5511999999999)
- `RAW` para os itens e preços do cardápio (`categoria|nome|descrição|preço`, separados por `~`)
