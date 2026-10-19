# Premiação Grupo NICO — PWA

## Publicar no GitHub Pages
1. Envie os quatro arquivos (`index.html`, `manifest.json`, `service-worker.js`, `icon.svg`) para a raiz do repositório GitHub.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/ (root)` e salve.
4. Abra o endereço GitHub Pages pelo Chrome no celular. Use o menu do navegador e escolha **Instalar app** ou **Adicionar à tela inicial**.

## Observações
- O PWA precisa ser servido por HTTPS (GitHub Pages atende).
- O HTML original foi mantido e preparado com manifesto e service worker.
- A sincronização com Supabase e bibliotecas externas precisam de internet; o service worker guarda os arquivos locais do app para abrir a interface offline.
- Antes de usar em produção, troque a senha padrão `admin / admin123` e configure corretamente as permissões e as políticas de segurança do Supabase.
