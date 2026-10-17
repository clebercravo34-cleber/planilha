# PWA — NICO Premiação

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste ZIP.
2. Envie `index.html`, `manifest.json`, `service-worker.js` e a pasta `icons` para a raiz do repositório GitHub.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, escolha a branch `main` e a pasta `/ (root)`, depois salve.
5. Aguarde a publicação e abra o endereço HTTPS do GitHub Pages.

## Instalar
- Android/Chrome: abra o endereço publicado e use o menu do navegador → **Instalar app** ou **Adicionar à tela inicial**.
- iPhone/Safari: abra o endereço publicado → **Compartilhar** → **Adicionar à Tela de Início**.

## Observações importantes
- O PWA precisa estar publicado em HTTPS para instalar e usar o service worker.
- O modo offline mantém a estrutura do aplicativo disponível, mas recursos externos (como bibliotecas CDN e conexão com Supabase) exigem internet.
- Os dados já existentes neste HTML usam armazenamento local do navegador. Para compartilhar dados entre aparelhos, configure corretamente o Supabase dentro do aplicativo.
- Troque a senha padrão de administrador antes de usar em produção.
