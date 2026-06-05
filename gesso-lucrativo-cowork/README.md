# Gesso Lucrativo — Pacote Agente Claude Cowork

Pacote completo para rodar o agente de **criativos vencedores em cold traffic** com duas skills integradas.

## Estrutura

```
gesso-lucrativo-cowork/
├── CLAUDE.md                 ← Cérebro do agente (Cowork lê automaticamente)
├── PROJECT_INSTRUCTIONS.md   ← Versão curta para colar no painel do Project
├── AGENTS.md                 ← Compatível com outros tools (opcional)
├── docs/
│   ├── OFFER_BRIEF.md
│   └── WORKFLOW.md
├── skills/
│   ├── persona-extractor-gesso/
│   └── copy-pattern-analyst-gesso/
├── inputs/                   ← Coloque LP, transcrições, depoimentos aqui
└── outputs/                  ← Relatórios e roteiros gerados pelo agente
```

## Instalação no Claude Cowork (passo a passo)

### 1. Baixar a pasta
- ZIP da branch no GitHub, ou clone:
  ```bash
  git clone https://github.com/Camisa1111/intuition.git
  cd intuition/gesso-lucrativo-cowork
  ```

### 2. Criar um Project no Cowork
1. Abra **Claude Cowork** (desktop).
2. **New Project** → conecte a pasta `gesso-lucrativo-cowork` como workspace.
3. O Cowork detecta `CLAUDE.md` na raiz — confirme que está ativo.

### 3. Project Instructions (opcional, reforço)
1. Painel direito do Project → **Instructions**.
2. Cole o conteúdo de **`PROJECT_INSTRUCTIONS.md`**.

### 4. Registrar as Skills
**Opção A — Pasta do projeto (recomendado)**  
Com a pasta conectada, as skills em `skills/*/SKILL.md` ficam disponíveis. Teste:
- `/persona-extractor-gesso`
- `/copy-pattern-analyst-gesso`

**Opção B — Upload global**  
Settings → Cowork → Features → Skills → envie cada pasta `persona-extractor-gesso` e `copy-pattern-analyst-gesso` como ZIP (cada uma com `SKILL.md` + `REFERENCE.md`).

### 5. Global Instructions (opcional)
Settings → Cowork → Global Instructions — só se quiser que **todo** Cowork fale PT-BR; o restante fica no Project.

### 6. Popular `inputs/`
Exemplos:
- `inputs/landing-page.md`
- `inputs/criativos-gl-01-a-06.md`
- `inputs/depoimentos.md` (quando tiver)

### 7. Primeiro comando sugerido

```
Rode o pipeline completo: Fase 0 a 6 no CLAUDE.md.
Materiais em inputs/. Entregue persona, pattern brief, síntese e 3 roteiros
(Hook P, Arquétipo E, Terapia v2). Salve tudo em outputs/.
```

## Comandos úteis

| Comando | Efeito |
|---------|--------|
| `Rode o pipeline completo` | Fases 0–6 |
| `Só persona` | Fase 1 |
| `Atualize o swipe com [novo vídeo]` | Reclassifica + matrix |
| `3 roteiros para teste A/B` | Fase 4 com QA |
| `QA nos roteiros em outputs/04-roteiros` | Fase 5 |

## Atualizar skills
Substitua os arquivos em `skills/*/REFERENCE.md` quando houver nova versão no repositório `skills/` na raiz do repo.

## Suporte
Oferta: Gesso Lucrativo · Tráfego frio Meta · Público feminino BR
