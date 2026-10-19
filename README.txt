NICO Premiação — pacote PWA para GitHub Pages

ARQUIVOS
- index.html: aplicativo original completo, com metadados e registro PWA adicionados.
- manifest.json: configuração de instalação do aplicativo.
- sw.js: cache básico do app shell para abertura posterior.
- icons/: ícones do aplicativo.

PUBLICAÇÃO
1. Extraia todos os arquivos deste ZIP.
2. Envie TODOS os arquivos e a pasta icons para a raiz do repositório GitHub.
3. No GitHub, entre em Settings > Pages e publique a branch/pasta correta.
4. Abra a URL HTTPS publicada no Chrome do celular e escolha “Instalar app” ou “Adicionar à tela inicial”.

IMPORTANTE
A sincronização entre dispositivos depende da configuração Supabase dentro do próprio aplicativo (URL, chave pública anon e políticas/tabelas corretas). O PWA, por si só, não cria sincronização nem torna os dados locais compartilhados. Bibliotecas externas (Supabase, XLSX e jsPDF) precisam de internet quando não estiverem em cache.
