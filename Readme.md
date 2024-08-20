# Auxiliar de Jantar Romântico com AWS Step Functions

Este projeto utiliza o AWS Step Functions para criar um fluxo de trabalho que auxilia na organização de um jantar romântico. O fluxo de trabalho faz uso do modelo Amazon Titan Text Express para gerar sugestões de combinações gastronômicas, bebidas e locais para o jantar.

## Descrição dos Estados

- **Pergunta ideias de combinação**: Solicita ao modelo sugestões de combinações gastronômicas para um jantar romântico.
- **Add first result to conversation history**: Adiciona o primeiro resultado ao histórico da conversa.
- **Pergunta ideia de bebidas**: Solicita ao modelo sugestões de bebidas que acompanham um jantar romântico.
- **Add second result to conversation history**: Adiciona o segundo resultado ao histórico da conversa.
- **Pergunta ideia de local para jantar**: Solicita ao modelo sugestões de locais perfeitos para um jantar romântico em Paris.

## Como Executar

1. Configure o AWS Step Functions e o Amazon Bedrock.
2. Importe o JSON fornecido no console do AWS Step Functions.
3. Execute o fluxo de trabalho e acompanhe as sugestões geradas para o seu jantar romântico.

