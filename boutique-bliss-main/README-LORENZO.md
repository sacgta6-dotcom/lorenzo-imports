# Lorenzo Imports — alterações

- Marca e logo atualizadas em `src/config/store.ts` e `public/logo-lorenzo-imports.webp`.
- Banner substituído por seção responsiva.
- Paleta preta/cinza/dourada.
- Busca por nome, marca, categoria, SKU e descrição; ignora acentos e pontuação.
- A pesquisa agora não é limitada por filtros de categoria/marca/preço previamente selecionados e rola até o catálogo.
- Produtos continuam em `src/data/products.json` (catálogo estático, sem sincronização automática com banco de dados).
- Para incluir/alterar produtos, atualize esse JSON e publique uma nova versão.
- Antes de publicar, confira WhatsApp, frete e informações de contato em `src/config/store.ts`.
- Produtos e preços existentes não foram modificados.
