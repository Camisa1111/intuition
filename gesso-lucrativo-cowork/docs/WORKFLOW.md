# Workflow detalhado — Agente Gesso Lucrativo

## Diagrama

```
[inputs/] → Fase 0 Inventário
         → Fase 1 Persona Extractor → outputs/01-relatorio-persona.md
         → Fase 2 Copy Pattern Analyst → outputs/02-pattern-brief.md
         → Fase 3 Síntese → outputs/03-sintese-estrategica.md
         → Fase 4 Roteiros → outputs/04-roteiros/*.md
         → Fase 5 QA → outputs/05-qa-log.md
         → Fase 6 Handoff (resumo ao usuário)
```

## Handoff Extrator → Pattern Analyst

| Do Extrator | Para Pattern Analyst |
|-------------|----------------------|
| Top 15 VOC | Banco Step 4 |
| Painel Lacunas #1–5 | Matrix ausências + Experimentos |
| Camada 2A consciência | Coluna temperatura por arquétipo |
| Hooks P1–P4, E1–E4 | Prioridade testes |
| Subtipos A–D | Match hook × arquétipo |

## Critério de sucesso da sessão

- Persona com lacunas rankeadas
- Pattern brief com ≥1 gap crítico com plano de teste
- ≥3 roteiros com timing + QA aprovado (se pedido produção)

## Atualização contínua

Quando o usuário adicionar:
- **Novo criativo validado** → reclassificar Step 0, atualizar matrix, não apagar histórico em `outputs/archive/`
- **Métricas (CTR, CPA)** → preencher coluna performance na tabela; priorizar replicação do que gasta
