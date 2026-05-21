# Landing Page Dra. Thalita Assis

Site estático premium para captação de leads via WhatsApp em Direito Bancário.

## Antes de publicar

Troque os dados de placeholder:

- `index.html`: ajuste Instagram, endereço e domínio em `LegalService`.
- `assets/dra-thalita-assis.png`: foto real da Dra. Thalita.
- `assets/assis-faria-logo-dark.png` e `assets/assis-faria-logo-light.png`: logos da marca.

## Deploy recomendado

1. Suba estes arquivos para um repositório no GitHub.
2. Na Vercel, crie um novo projeto importando o repositório.
3. Como é site estático, a Vercel pode publicar sem comando de build.
4. Adicione o domínio no projeto da Vercel.
5. Na Cloudflare, crie os registros DNS indicados pela Vercel.
6. No Registro.br, aponte os nameservers para os nameservers fornecidos pela Cloudflare.

Para começar com menos risco de conflito de SSL/CDN, deixe os registros da Vercel na Cloudflare como `DNS only`.
