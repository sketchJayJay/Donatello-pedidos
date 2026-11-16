# Donatello — prévia para Coolify

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
