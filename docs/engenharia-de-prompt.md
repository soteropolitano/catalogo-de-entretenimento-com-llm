# Engenharia de prompt

As instruções transformam uma conversa aberta em operações previsíveis sobre o catálogo.

## Fluxo de atualização

1. identificar se o usuário está consultando, recomendando ou atualizando;
2. localizar o título e seus aliases;
3. verificar se já existe um registro;
4. separar informação explícita de inferência;
5. normalizar categoria, estado e prioridade;
6. pedir confirmação quando a obra ou o progresso estiverem ambíguos;
7. atualizar a linha existente em vez de criar uma duplicata;
8. registrar origem, confiança e data da atualização.

## Fluxo de recomendação

1. entender o pedido e as restrições da conversa;
2. identificar a energia mental disponível naquele momento;
3. consultar notas, rejeições, energia atribuída e referências do catálogo;
4. retirar títulos já concluídos quando o pedido for por novidade;
5. pesquisar informações temporais em fontes atuais;
6. comparar os candidatos com o histórico e com a energia atual;
7. explicar por que cada sugestão pode funcionar naquele momento.

## Guardrails

- não transformar menção em confirmação;
- não inventar nota, progresso ou plataforma;
- não sobrescrever uma avaliação pessoal com nota externa;
- não criar uma linha nova quando um alias resolve o título;
- não afirmar disponibilidade sem uma fonte atual;
- levar registros ambíguos para a aba de revisão.
- não confundir energia mental com nota, prioridade ou qualidade.

## Aplicação profissional

O mesmo desenho serve para catálogos técnicos: ativos, incidentes, documentos ou solicitações. A LLM interpreta linguagem natural, mas trabalha sobre estados controlados, confiança, origem e próxima ação. Isso torna a resposta rastreável e reduz decisões baseadas somente na memória da conversa.
