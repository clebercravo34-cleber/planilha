PWA — PREMIAÇÃO GRUPO NICO

Arquivos:
- index.html: aplicativo original com suporte PWA
- manifest.json: configuração para instalação como aplicativo
- sw.js: cache básico para abertura offline (recursos externos podem exigir internet)
- icons/: ícones do aplicativo

PUBLICAR NO GITHUB:
1. Crie um repositório no GitHub.
2. Envie todos os arquivos e pastas deste ZIP para a raiz do repositório.
3. Ative Settings > Pages > Deploy from a branch > main > /(root).
4. Abra a URL HTTPS gerada e use "Instalar app" ou "Adicionar à tela inicial".

IMPORTANTE SOBRE SINCRONIZAÇÃO:
O PWA, por si só, não sincroniza dados entre aparelhos. O HTML usa armazenamento local e contém integração com Supabase que precisa ser configurada corretamente, com tabelas e permissões adequadas. Não compartilhe sua chave secreta/service_role. Teste a sincronização entre dois aparelhos antes de usar com dados reais.
