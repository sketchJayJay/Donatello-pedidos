# Donatello — prévia para Coolify · versão 2

Pronto para publicar a demonstração por Dockerfile. Não exige login no ChatGPT.

Extraia o ZIP, coloque os arquivos na raiz de um repositório e conecte-o ao Coolify.

| Configuração | Valor |
| --- | --- |
| Build Pack / Build strategy | Dockerfile |
| Base Directory | `/` |
| Dockerfile Location | `/Dockerfile` |
| Ports Exposes | `80` |
| Variáveis de ambiente | Nenhuma |
| Persistent Storage | Não é necessário nesta demonstração |
| Healthcheck opcional na interface | `GET /health`, porta `80` |

O arquivo **LEIA-ME_COOLIFY.txt** contém o passo a passo e um roteiro de apresentação.

## Escopo

Montagem de pizza, cardápio, carrinho, entrega/retirada, troco, pedido simulado e painel demonstrativo. Imagens e fontes estão incluídas; não é necessário executar npm install ou comandos de build do frontend.

Dados salvos somente no navegador usado no teste. Não há banco de dados, autenticação administrativa, sincronização entre aparelhos, recebimento real de pedidos ou pagamentos. Use dados fictícios.

O próximo passo para operação comercial é implementar o backend, o banco persistente, as permissões e as integrações acordadas com a pizzaria.

Veja as origens das imagens em ASSETS.md e a licença da fonte em `dist/assets/fonts/OFL.txt`.

## Melhorias desta versão

- Abertura com foto ampla, contraste forte e identidade mais marcante.
- Destaques com fotos ilustrativas de Donatello, Calabresa e Frango com Catupiry.
- Favoritos salvos no navegador e filtro para consultá-los.
- Ordenação por nome ou menor preço, com expansão do cardápio completo.
- Carrinho lateral no computador e navegação fixa no celular.
- Montagem de pizza com prévia visual e busca de sabores por ingrediente.
- Sugestão opcional de refrigerante no carrinho, sem descontos ou valores inventados.
- Fotos ilustrativas adicionais de Calabresa, Frango e Chocolate com Morango.

Os dados da primeira versão são preservados se o domínio e o navegador continuarem os mesmos.
