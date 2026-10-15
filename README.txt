NICO Premiação — PWA para GitHub Pages

Arquivos:
- index.html: aplicativo original com configuração PWA
- manifest.json: identificação e opções de instalação
- sw.js: cache básico para abertura offline após o primeiro carregamento
- icons/: ícones da aplicação

Publicação:
1. Extraia o ZIP.
2. Envie todos os arquivos e a pasta icons para a raiz de um repositório GitHub.
3. No GitHub, abra Settings > Pages.
4. Em Build and deployment, escolha Deploy from a branch, selecione a branch principal e a pasta / (root).
5. Acesse o endereço HTTPS gerado pelo GitHub Pages e instale pelo menu do navegador.

Observações:
- O PWA precisa ser servido por HTTPS (GitHub Pages atende).
- Os dados locais existentes usam o armazenamento do navegador. Para compartilhar dados entre aparelhos, configure o Supabase dentro do app.
- A tela usa bibliotecas externas (SheetJS e Supabase); alguns recursos dependem de internet.
- O login padrão mostrado no próprio aplicativo é admin / admin123. Troque a senha após o primeiro acesso.
