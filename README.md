# Landing Page Dra. Thalita Assis

Site estático premium para captação de leads via WhatsApp em Direito Bancário.

## Antes de publicar

O domínio público configurado para o site é `https://assisfaria.com.br/`.

- `index.html`: mantenha `canonical`, `og:url`, `og:image` e a URL do JSON-LD alinhados a esse domínio caso ele mude.
- `assets/dra-thalita-assis.png`: foto real da Dra. Thalita.
- `assets/assis-faria-logo-dark.png` e `assets/assis-faria-logo-light.png`: logos da marca.

## Ícone ao instalar

O site inclui favicon SVG, ícone para a tela inicial do iOS e o manifesto PWA para Android e navegadores desktop. Os PNGs em `assets/icons/` são derivados do mesmo desenho de `favicon.svg`; mantenha-os atualizados juntos caso a marca seja alterada.

## Deploy recomendado

1. Suba estes arquivos para um repositório no GitHub.
2. Na Vercel, crie um novo projeto importando o repositório.
3. Como é site estático, a Vercel pode publicar sem comando de build.
4. Adicione o domínio no projeto da Vercel.
5. Na Cloudflare, crie os registros DNS indicados pela Vercel.
6. No Registro.br, aponte os nameservers para os nameservers fornecidos pela Cloudflare.

Para começar com menos risco de conflito de SSL/CDN, deixe os registros da Vercel na Cloudflare como `DNS only`.
