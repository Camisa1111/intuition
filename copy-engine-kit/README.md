# Copy Engine Kit — Persona Extractor + Copy Pattern Analyst

Templates reutilizáveis para criar skills de **qualquer oferta** no Claude Code / Cowork.

Baseado no framework validado em Gesso Lucrativo (cold traffic, Meta Ads).

---

## Estrutura

```
copy-engine-kit/
├── README.md                          ← você está aqui
├── SETUP-CLAUDE-CODE.md               ← instalação passo a passo
├── OFFER-INTAKE.md                    ← preencher ANTES de gerar skills
├── templates/
│   ├── persona-extractor.TEMPLATE.md
│   ├── copy-pattern-analyst.TEMPLATE.md
│   └── CLAUDE.TEMPLATE.md
└── prompts/
    └── BOOTSTRAP-NOVA-OFERTA.md       ← prompt único para gerar tudo
```

---

## Fluxo rápido (nova oferta)

1. Copie `copy-engine-kit/` para a pasta do seu projeto Claude Code
2. Preencha `OFFER-INTAKE.md`
3. Cole materiais em `inputs/` (LP, transcrições, depoimentos)
4. Execute o prompt em `prompts/BOOTSTRAP-NOVA-OFERTA.md`
5. Salve outputs em `skills/{{slug-oferta}}/`
6. Personalize `CLAUDE.md` a partir do template

---

## Referência Gesso (exemplo preenchido)

- `../skills/persona-extractor_GESSO-LUCRATIVO.md`
- `../skills/copy-pattern-analyst_GESSO-LUCRATIVO.md`
- `../gesso-lucrativo-cowork/` (agente completo)

Use como benchmark de profundidade — não copie conteúdo de outra oferta.
