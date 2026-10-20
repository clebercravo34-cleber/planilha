PREMIAÇÃO GRUPO NICO — PWA PARA GITHUB PAGES

Arquivos:
- index.html: aplicativo original fornecido, mantido completo.
- manifest.json: configura a instalação como aplicativo.
- sw.js: cache básico para abertura offline dos arquivos locais.
- icons/: ícones do aplicativo.

PUBLICAR NO GITHUB:
1. Crie/abra um repositório no GitHub.
2. Envie todos os arquivos e a pasta icons (não envie apenas o index.html).
3. Em Settings > Pages, escolha Deploy from a branch, selecione a branch principal e a pasta /(root), e salve.
4. Abra o endereço HTTPS gerado pelo GitHub Pages.
5. No Android/Chrome, use o menu ⋮ > Instalar app ou Adicionar à tela inicial.

OBSERVAÇÕES:
- Para o PWA funcionar, publique via HTTPS (GitHub Pages fornece HTTPS).
- O sistema original usa localStorage e inclui integração Supabase configurável. O cache PWA não substitui a configuração do Supabase nem garante sincronização entre dispositivos sem conexão e tabelas/permissões corretas.
- O login padrão indicado na tela do aplicativo é admin / admin123. Troque a senha e configure o acesso antes de usar com dados reais.
