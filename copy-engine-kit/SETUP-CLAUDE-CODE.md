# Setup — Nova oferta no Claude Code Projects

## Passo 1 — Criar pasta do projeto

```
meu-projeto-copy/
├── CLAUDE.md
├── OFFER-INTAKE.md          ← copiar de copy-engine-kit/OFFER-INTAKE.md
├── inputs/
│   ├── landing-page.md
│   ├── criativos-transcricoes.md
│   └── depoimentos.md
├── outputs/
│   └── {{slug}}/
└── skills/
    ├── persona-extractor-{{slug}}/
    │   ├── SKILL.md
    │   └── REFERENCE.md
    └── copy-pattern-analyst-{{slug}}/
        ├── SKILL.md
        └── REFERENCE.md
```

---

## Passo 2 — Preencher OFFER-INTAKE.md

Todos os campos da seção 1–7. Sem isso o bootstrap fica genérico demais.

---

## Passo 3 — Gerar skills com Claude Code

Abra o projeto no Claude Code e cole o prompt de:

`copy-engine-kit/prompts/BOOTSTRAP-NOVA-OFERTA.md`

O agente deve criar:
- `skills/persona-extractor-{{slug}}/REFERENCE.md` (skill completa)
- `skills/copy-pattern-analyst-{{slug}}/REFERENCE.md` (skill completa)
- `skills/*/SKILL.md` (YAML frontmatter)
- `CLAUDE.md` personalizado

---

## Passo 4 — Formato SKILL.md (Claude Code)

Cada skill precisa de:

```yaml
---
name: persona-extractor-{{slug}}
description: Use when analyzing {{NOME_OFERTA}} marketing materials to extract persona, pains, VOC, objections. Run FIRST before copy-pattern-analyst.
---
```

Corpo curto + "Execute REFERENCE.md integralmente".

---

## Passo 5 — Testar

```
/persona-extractor-{{slug}}
```

Depois:

```
/copy-pattern-analyst-{{slug}}
```

Ou:

```
Execute pipeline completo conforme CLAUDE.md. Materiais em inputs/.
```

---

## Passo 6 — Evoluir

| Quando | Ação |
|--------|------|
| Novo criativo validado | Atualizar swipe no Pattern Analyst |
| Métricas chegaram | Adicionar em inputs/metricas.md + re-rodar Fase 2 |
| Nova oferta | Nova pasta `outputs/{{slug}}/` + novo par de skills |

---

## Benchmark de qualidade

Compare profundidade com:
- `skills/persona-extractor_GESSO-LUCRATIVO.md` (11 camadas)
- `skills/copy-pattern-analyst_GESSO-LUCRATIVO.md` (Steps 0–8)

Não copie conteúdo de Gesso — copie a **estrutura**.
