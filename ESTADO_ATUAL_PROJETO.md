# Resumo e Estado Atual do Funil Rosa Oriental (28/10/2026)

## 🌐 URLs em Produção na Vercel
1. **Advertorial (Link para os Anúncios Meta Ads):**
   - `https://ciencia-longevidade.vercel.app/` (Serve `artigo.html`)
2. **Página de Vendas Oficial (Direto na Raiz `/`, sem `/vendas`):**
   - `https://rosaoriental-oficial.vercel.app/` (Serve `vendas.html` via rewrite de host em `vercel.json`)
3. **Repositório GitHub Conectado:**
   - `https://github.com/rafalaxl/funil-rosa-oriental`

## 🔗 Links de Afiliado Braip Configurados (`vendas.html`)
- **Kit 3 Meses (R$ 347,00):** `https://ev.braip.com/campanhas/cpa/camk7l89d`
- **Kit 5 Meses (R$ 447,00):** `https://ev.braip.com/campanhas/cpa/camj2z8gz`
- **Kit 12 Meses (R$ 897,00):** `https://ev.braip.com/campanhas/cpa/camzvj0mx`

## 🖼️ Criativos Nativos (Método Sabri Suby) Prontos
Localizados em `D:\01_Projetos\Site funil de vendas\funil-rosa-oriental\criativos-anuncio\`:
- `criativo-1-casal-circulo-vermelho.jpg`
- `criativo-2-casal-editorial-safe.jpg`
- `criativo-3-banheiro-cremes-aposentados.jpg`
- `criativo-4-amigas-cafe-bolsa.jpg`

## ✅ Pixel da Meta Configurado (ID: `4262952370623357`)
- **Advertorial (`artigo.html`):** Dispara `PageView` no carregamento + evento customizado `CliqueAdvertorial` ao clicar nos botões de chamada para a página de vendas.
- **Página de Vendas (`vendas.html`):** Dispara `PageView` + `ViewContent` no carregamento + `InitiateCheckout` (com valor exato em BRL de cada kit: R$ 347, R$ 447 ou R$ 897) ao clicar em qualquer um dos 3 botões de compra da Braip.
- **Braip:** Lembre-se de cadastrar também o Pixel ID `4262952370623357` no menu **Ferramentas > Pixel** da Braip para rastrear os eventos de `Purchase` (Boleto/PIX/Cartão).
