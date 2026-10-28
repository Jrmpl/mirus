# Site Mirus Rastreamento — instruções

Site estático (HTML/CSS/JS), sem dependências. Suba o conteúdo desta pasta na raiz do domínio (mirus.com.br).
- Apache/cPanel: `.htaccess` já inclui HTTPS, redirects, 404 e cache.
- Netlify/Cloudflare Pages: `_redirects` incluso.
- Para regenerar páginas: edite `build.py` e rode `python3 build.py`.

## Antes de publicar
1. Trocar o logotipo SVG provisório pelo logo oficial (função LOGO em build.py).
2. Confirmar a lista de cidades atendidas (CITIES em build.py).
3. Formulário abre WhatsApp (sem backend). Para receber por e-mail, integrar Formspree/PHP.
4. Revisar a Política de Privacidade com o jurídico.
5. Adicionar logos/depoimentos reais em Clientes atendidos.
6. Confirmar "mais de 8 anos" (texto do site atual).

## SEO local (depois de publicar)
- Google Search Console: enviar https://mirus.com.br/sitemap.xml
- Google Meu Negócio: perfil com NAP idêntico ao do site (Rua Bacabal, 140 - Conj. 93, SJC), categoria "Serviço de rastreamento de veículos"
- Pedir avaliações a clientes; publicar 1–2 artigos/mês no blog
- Manter as mesmas URLs do site antigo (mantidas aqui) e redirecionar /mirus-desempenho → /mirus-frota
