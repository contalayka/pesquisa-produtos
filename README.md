# Pesquisa de Produtos

Aplicação interna para pesquisar e registrar equivalentes de produtos.

## Persistência compartilhada

O catálogo e as pesquisas são salvos em um banco Supabase compartilhado. A importação do CSV é feita uma única vez: depois de importado pelo site, o catálogo fica na nuvem e não depende mais do arquivo que estava no computador.

Alterações de nome encontrado, plataforma, preço, link, status, confiança, observações e opções também são gravadas no banco. Ao abrir o site em outro computador ou celular, os mesmos dados são carregados.

O `localStorage` não é usado como banco principal.

## Escopo

- catálogo de produtos
- pesquisa e filtros
- status de pesquisa
- anúncios encontrados e múltiplas opções
- links de pesquisa
- simulador de preço
- exportação e backup
- persistência compartilhada entre dispositivos

Não há conversor de planilhas entre marketplaces.
