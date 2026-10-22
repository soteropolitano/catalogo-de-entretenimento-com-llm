# Modelo de dados

## Catálogo

Cada linha representa uma obra ou um jogo.

```text
id,titulo,aliases,categoria,status_consumo,progresso,nota,prioridade,proxima_acao,confirmacao_status,origem,confianca,observacao,nota_num,fonte_avaliacao_prioritaria,url_fonte_prioritaria,fontes_secundarias,ultima_atualizacao,regra_recomendacao,subtipo_original,ordem_prioridade
```

## Campos principais

| Campo | Finalidade |
| --- | --- |
| `id` | Identificador estável do registro |
| `titulo` | Nome usado como referência principal |
| `aliases` | Títulos alternativos e nomes originais |
| `categoria` | Filme, série, anime, jogo ou documentário |
| `status_consumo` | Situação atual do item |
| `progresso` | Episódio, temporada, campanha ou outra etapa |
| `nota` | Avaliação preservada no formato informado |
| `nota_num` | Versão numérica para filtros e indicadores |
| `prioridade` | Ordem pessoal de interesse |
| `proxima_acao` | O que deve acontecer com o registro |
| `confirmacao_status` | Distingue confirmação de inferência |
| `origem` | De onde veio a informação |
| `confianca` | Qualidade da identificação ou interpretação |
| `regra_recomendacao` | Como o item deve influenciar novas sugestões |

## Estados iniciais

- assistindo;
- concluído;
- pausado;
- abandonado;
- quero ver;
- jogando;
- zerado;
- backlog;
- citado;
- citado recomendado;
- precisa confirmar.

Os estados podem ser normalizados para uso técnico, mas a interface deve continuar apresentando termos fáceis de entender.
