# La Belle Maison – loja (site estático)

HTML + CSS + JS puros, sem build. Na Vercel: Framework Preset "Other", Build Command vazio, Output Directory vazio (raiz).

## Fotos dos produtos
As fotos já carregam do endereço original (campo `img` em `data/produtos.js`). Para usar fotos suas, coloque em `assets/produtos/<handle>.jpg`. O handle é o nome que aparece na URL da página (ex.: `#p-NOME-DO-HANDLE`) e está em `data/produtos.js` (chaves de `P`). Se o arquivo local existir, ele tem prioridade; sem nenhuma foto, aparece um frasco padrão.

## Produtos, preços e coleções
Edite `data/produtos.js` (`P` = produtos, `S` = ordem de cada coleção).

## Checkout
O botão "Finalizar compra" está em `app.js` (`alert(...)`). Troque pelo link/checkout quando estiver pronto.

## Dados da empresa e políticas
Preencha `data/config.js` (razão social, CNPJ, endereço, e-mail, WhatsApp, Instagram, TikTok). Os textos das páginas de política estão em `data/paginas.js` (são modelos: peça para um advogado revisar antes de publicar).
