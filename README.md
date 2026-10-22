# Premiação Grupo Nico — PWA

## Publicar no GitHub Pages
1. Extraia todos os arquivos deste ZIP.
2. Envie **todos** os arquivos para a raiz de um repositório GitHub.
3. Em **Settings → Pages**, selecione a branch principal e a pasta `/(root)`.
4. Abra a URL HTTPS gerada pelo GitHub Pages no celular.
5. No navegador, escolha **Instalar app** ou **Adicionar à tela inicial**.

## Observações
- O PWA precisa ser servido por HTTPS (GitHub Pages atende isso).
- O service worker armazena em cache os arquivos principais do app. Bibliotecas externas e a sincronização Supabase dependem de internet.
- Os dados locais usam o armazenamento do navegador do dispositivo. Para compartilhar dados entre dispositivos, configure o Supabase dentro do app.
- Troque a senha padrão de administrador após o primeiro acesso.
