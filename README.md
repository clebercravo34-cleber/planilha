# Premiação Grupo NICO — PWA

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste ZIP.
2. Envie `index.html`, `manifest.json`, `sw.js` e a pasta `icons` para a raiz do repositório GitHub.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch principal e a pasta `/ (root)`, e salve.
5. Aguarde a publicação e abra o endereço HTTPS do GitHub Pages.
6. No Android, abra o site no Chrome e escolha **Instalar app** ou **Adicionar à tela inicial**.

## Observações
- O arquivo HTML original foi mantido e preparado como `index.html`; foram adicionados o manifesto, o service worker e ícones.
- O aplicativo usa bibliotecas externas via CDN e o Supabase configurado dentro do próprio app. Algumas funções dependem de internet.
- Os dados locais ficam no armazenamento do navegador daquele aparelho. Para sincronizar entre aparelhos, configure corretamente o Supabase e suas políticas/tabelas.
- Troque a senha padrão `admin / admin123` depois do primeiro acesso.
- O service worker só funciona em HTTPS (como GitHub Pages) ou localhost.
