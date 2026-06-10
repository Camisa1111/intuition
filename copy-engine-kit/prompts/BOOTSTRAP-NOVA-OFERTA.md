# Bootstrap — Gerar Persona Extractor + Copy Pattern Analyst (nova oferta)

> Cole este prompt no **Claude Code** com a pasta do projeto aberta e `OFFER-INTAKE.md` preenchido.

---

```
# BOOTSTRAP — COPY ENGINE KIT · NOVA OFERTA

Você é engenheiro de prompt e copy strategist. Sua tarefa é criar o **par completo de skills** para uma nova oferta, usando:

1. `OFFER-INTAKE.md` (preenchido)
2. Todos os arquivos em `inputs/`
3. Templates em `copy-engine-kit/templates/` (estrutura obrigatória)
4. Benchmark de profundidade: skills Gesso Lucrativo em `skills/*GESSO*` (só estrutura, não conteúdo)

---

## FASE 1 — LEITURA E DIAGNÓSTICO

Leia OFFER-INTAKE + inputs/. Salve:

`outputs/{{SLUG}}/00-bootstrap-diagnostico.md`

Conteúdo:
- Resumo da oferta em 5 bullets
- Materiais recebidos vs faltantes
- Hipóteses iniciais de avatar (marcar confiança)
- 5 lacunas prováveis antes da análise profunda
- Restrições de copy confirmadas para esta oferta
- Prefixo de IDs de criativo sugerido (ex: OF-01, MX-01)

**Não escrever skills ainda.**

---

## FASE 2 — PERSONA EXTRACTOR

Crie `skills/persona-extractor-{{SLUG}}/REFERENCE.md`:

- Use estrutura completa de `templates/persona-extractor.TEMPLATE.md`
- Preencha com evidência REAL dos materiais em inputs/
- Todas as 11 camadas obrigatórias
- Painel de lacunas no topo (mínimo 5, baseado em gaps reais desta oferta)
- Dores rankeadas por intensidade de conversão em {{PLATAFORMA}}
- Camada 2A consciência com protocolo de hook
- Camada 8 objeções com scripts de dissolução
- Camada 9 subtipos de avatar (mínimo 3)
- Top 15 VOC verbatim (ou marcar gap se LP incompleta)
- Marcar ALTA/MÉDIA/BAIXA em cada bloco

Crie `skills/persona-extractor-{{SLUG}}/SKILL.md`:

```yaml
---
name: persona-extractor-{{SLUG}}
description: [descrição específica da oferta — quando usar]
---
```

Corpo: quando usar · como executar REFERENCE.md · output path · handoff para Pattern Analyst.

**Execute mentalmente a skill** e salve também:
`outputs/{{SLUG}}/01-relatorio-persona.md` (primeira análise real).

---

## FASE 3 — COPY PATTERN ANALYST

Crie `skills/copy-pattern-analyst-{{SLUG}}/REFERENCE.md`:

- Estrutura de `templates/copy-pattern-analyst.TEMPLATE.md`
- Steps 0–8 completos
- Glossário de hooks adaptado ao nicho
- Critério de criativo alinhado **específico** desta oferta (não genérico)
- Step 0 preenchido com criativos reais de inputs/ (ou nota "swipe vazio")
- Hook Autopsy para cada vídeo disponível
- Matrix 3A com linhas relevantes PARA ESTA OFERTA (não copiar matrix de Gesso)
- Mínimo 4 arquétipos nomeados (A–D) + gaps documentados
- Mínimo 5 experimentos priorizados
- Integrar VOC e lacunas do Extrator

Crie `skills/copy-pattern-analyst-{{SLUG}}/SKILL.md` com YAML.

Salve: `outputs/{{SLUG}}/02-pattern-brief.md` (primeira análise real).

---

## FASE 4 — CLAUDE.md DO PROJETO

Crie ou atualize `CLAUDE.md` na raiz usando `templates/CLAUDE.TEMPLATE.md`:

- Pipeline Fases 0–6
- Nome da oferta, tom, restrições, CTA, duração
- Paths corretos para skills e outputs
- Checklist QA específico

---

## FASE 5 — ENTREGA E HANDOFF

Na conversa, entregar:

1. Árvore de arquivos criados
2. Top 3 lacunas críticas desta oferta
3. Top 3 hooks prioritários para testar (com tipo P/R/T/etc.)
4. Próximo comando sugerido para gerar 3 roteiros:

```
Execute Fase 4 conforme CLAUDE.md. Gere 3 roteiros em outputs/{{SLUG}}/04-roteiros/
incluindo 1 hook do gap #1 prioritário.
```

---

## REGRAS DE QUALIDADE

- Nenhum placeholder {{}} pode permanecer nos arquivos finais
- Nenhuma afirmação de persona sem evidência ou tag de confiança
- Não copiar frases de Gesso Lucrativo ou outras ofertas
- Se inputs/ estiver vazio, documentar gaps e gerar skills como **framework pré-preenchido** com [PREENCHER APÓS COLETA] — não inventar transcrições
- Skills REFERENCE.md devem ter profundidade comparável ao benchmark (não resumir camadas)

SLUG = valor de OFFER-INTAKE seção 1.

EXECUTAR Fases 1 → 5 em ordem. Salvar todos os arquivos no disco.
```

---

## Depois do bootstrap

| Comando | Uso |
|---------|-----|
| `/persona-extractor-{{slug}}` | Atualizar persona com novos materiais |
| `/copy-pattern-analyst-{{slug}}` | Atualizar padrões |
| Ver `COMANDO-RODADA-2.md` do Gesso | Modelo para rodadas de diferenciação (adaptar) |
