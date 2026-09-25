# Como atualizar o K-Beauty Guide

## Estrutura
- `index.html` → página inicial
- `metodologia.html`, `transparencia.html`, `referencias.html` → páginas fixas
- `comparacoes/index.html` → lista de todas as comparações
- `comparacoes/exemplo.html` → modelo de comparação (5 produtos)
- `imagens/` → fotos (produto1.png, produto2.png... e hero.png)
- `style.css` → visual de todas as páginas

## Criar uma comparação nova
1. Abra `comparacoes/exemplo.html`, copie todo o conteúdo.
2. Add file → Create new file → nome: `comparacoes/acne.html` (por exemplo) → cole → commit.
3. Troque tudo que está entre [colchetes] e os "Nome do produto".
4. Em `comparacoes/index.html`, transforme o card "Em breve" em link para o arquivo novo.

## Adicionar um produto numa comparação
Copie um bloco `<article class="analise-produto">` inteiro e mude o `id="produto-X"`.
Adicione também uma linha na tabela "Resumo rápido".

## Link de afiliado
Troque `https://www.amazon.com.br/` pelo seu link. Não apague o `rel="sponsored nofollow noopener"`.
