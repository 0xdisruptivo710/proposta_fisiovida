# Proposta AIOS × FisioVida

Landing page de proposta comercial (one-pager) da **AIOS** para a **FisioVida Porto Alegre**.

Site estático: um único `index.html`, sem build, sem dependências (apenas Google Fonts). Estética "Concrete Silence" — off-white quente, acento cobalto, DM Serif Display + DM Sans + JetBrains Mono.

## Deploy na Vercel

Site 100% estático — nenhum passo de build é necessário.

1. Importe este repositório na Vercel (Add New → Project).
2. **Framework Preset:** `Other`.
3. **Build Command:** vazio · **Output Directory:** vazio (raiz) · **Install Command:** vazio.
4. Deploy. A Vercel serve `index.html` na raiz automaticamente.

O `vercel.json` já define `cleanUrls` e headers de segurança.

## Preview local

Abra `index.html` direto no navegador, ou sirva a pasta:

```bash
npx serve .
```

## Antes de enviar ao cliente

- [x] Número de WhatsApp preenchido nos dois CTAs (+351 961 342 444).
- [ ] Conferir cidade/domínio no rodapé.
