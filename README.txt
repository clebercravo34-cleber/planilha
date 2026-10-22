PWA — PREMIAÇÃO GRUPO NICO

ARQUIVOS PARA GITHUB PAGES
- index.html: aplicativo
- manifest.json: configuração instalável e nome do atalho
- sw.js: cache básico do aplicativo
- icons/: ícones 192x192 e 512x512

PUBLICAR
1. Crie/abra um repositório no GitHub.
2. Envie todos os arquivos e a pasta icons, mantendo esta estrutura.
3. No repositório, abra Settings > Pages.
4. Em Build and deployment, selecione Deploy from a branch.
5. Escolha a branch main e a pasta /(root), depois Save.
6. Aguarde a publicação e abra o endereço HTTPS gerado.
7. No Chrome Android, abra o site e use o menu ⋮ > Instalar app ou Adicionar à tela inicial.

OBSERVAÇÕES
- O app usa bibliotecas externas por CDN para alguns recursos (XLSX, PDF e Supabase); esses recursos precisam de internet.
- O service worker guarda o shell básico do app, mas não transforma o Supabase em banco offline.
- Configure a URL e a chave publicável do Supabase dentro de Config, se for usar sincronização entre aparelhos.
- Não use credenciais administrativas ou service_role do Supabase no navegador.
