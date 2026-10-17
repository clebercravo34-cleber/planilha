# NICO Premiação — PWA para GitHub Pages

## Arquivos
- `index.html`: aplicativo
- `manifest.json`: configuração de instalação PWA
- `service-worker.js`: cache básico para abertura offline da estrutura do app
- `icons/`: ícones do aplicativo

## Publicar no GitHub
1. Crie um repositório no GitHub.
2. Envie todos os arquivos e a pasta `icons` para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, escolha `main` e `/(root)`, e salve.
5. Abra a URL HTTPS do GitHub Pages. No Android/Chrome, use o menu ⋮ → **Instalar app** ou **Adicionar à tela inicial**.

## Importante
- O modo PWA exige HTTPS; GitHub Pages fornece HTTPS.
- O aplicativo usa bibliotecas externas e o Supabase configurado dentro do próprio app. O cache offline não garante sincronização com o Supabase sem internet.
- Antes de publicar, altere a senha padrão `admin / admin123` dentro do aplicativo. Não use credenciais administrativas sensíveis embutidas em HTML público.
