# Limitações e próximos testes

## Limitações atuais

- títulos iguais podem representar obras diferentes;
- traduções e aliases incompletos ainda podem gerar duplicidade;
- disponibilidade e datas ficam desatualizadas rapidamente;
- notas em formatos diferentes precisam de normalização cuidadosa;
- uma recomendação ainda depende da qualidade do histórico registrado;
- a revisão humana continua necessária para estados e títulos ambíguos;
- o MVP ainda não possui uma interface própria.

## Próximos testes

1. identificar duplicatas por título original e tradução;
2. atualizar progresso sem apagar o histórico anterior;
3. distinguir temporada concluída de série concluída;
4. medir quantos registros chegam à fila de revisão;
5. comparar recomendações com e sem notas pessoais;
6. validar disponibilidade em plataformas brasileiras;
7. avaliar o peso correto de itens abandonados e notas baixas;
8. testar jogos, documentários e séries dentro do mesmo modelo;
9. gerar snapshots antes de alterações em massa;
10. criar um processo de importação e exportação reproduzível.

## Critérios para uma próxima versão

Uma aplicação própria passa a fazer sentido quando a planilha limitar a atualização, a revisão ou a consulta. Antes disso, o foco continua na qualidade dos estados, na ausência de duplicidade e na utilidade real das recomendações.
