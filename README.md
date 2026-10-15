# NICO Premiação — PWA

## Publicar no GitHub Pages
1. Extraia os arquivos deste ZIP.
2. Crie/abra um repositório no GitHub.
3. Envie `index.html`, `manifest.json`, `service-worker.js` e `icon.svg` para a raiz do repositório.
4. Em **Settings → Pages**, selecione a branch principal e a pasta `/ (root)`.
5. Abra o endereço HTTPS publicado. No Android/Chrome, use **Adicionar à tela inicial** ou **Instalar app**.

## Observações
- O aplicativo mantém os dados locais no navegador usando `localStorage`; os dados locais não são automaticamente compartilhados entre aparelhos.
- A sincronização Supabase depende de configurar URL, chave e tabelas corretamente em Configurações.
- O service worker armazena a página e os arquivos do app para ajudar a abrir sem conexão. Recursos externos (como bibliotecas carregadas por CDN e sincronização Supabase) precisam de internet.
- Este pacote preserva a tela de login e o conteúdo do HTML fornecido. Antes de publicar para uso real, altere a senha padrão e configure corretamente a segurança do banco. Não use uma chave secreta/service-role no navegador.
