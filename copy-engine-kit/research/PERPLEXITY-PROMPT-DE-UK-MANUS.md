# Prompt Perplexity → Pacote Manus | Alemanha + Reino Unido

**Objetivo:** Decidir qual mercado (DE ou UK) e qual vertical (sais de banho / gesso aromático / velas) entrar com **vantagem competitiva** para infoproduto low-ticket **€27** — mesmo avatar: mulher, renda extra, ensinar craft em casa.

**Países nesta rodada:** 🇩🇪 Alemanha | 🇬🇧 Reino Unido

> Se quiseres incluir um 3.º país (ex.: PT, ES, IT), duplica a secção 4 com o mesmo formato.

---

## COMO USAR

1. Copia **todo o bloco "PROMPT PERPLEXITY"** abaixo para o Perplexity (modo **Research** / **Pro Search** se disponível).
2. Guarda a resposta completa como `PERPLEXITY-OUTPUT-DE-UK.md`.
3. Cola no **Manus** com a instrução: *"Analisa este pacote e produz recomendação final com score e ordem de teste Meta €27."*
4. Completa manualmente a **Secção 6 (Meta Ad Library)** — o Perplexity não substitui contagem de anúncios ativos.

---

## PROMPT PERPLEXITY (copiar da linha seguinte até ao fim do bloco)

```
# MISSÃO
És analista de mercado digital especializado em infoprodutos low-ticket (€15–€47) no nicho "renda extra feminina / artesanato em casa" na Europa.

Prepara um PACOTE DE PESQUISA COMPLETO para o agente Manus decidir:
- Em que PAÍS entrar primeiro: Alemanha (DE) ou Reino Unido (UK)
- Em que VERTICAL entrar com vantagem competitiva: (A) sais de banho / bath bombs, (B) gesso aromático / gips gießen / plaster craft decorativo, (C) velas aromáticas / candle making

## CONTEXTO DO NEGÓCIO (não ignorar)
- Produto: CURSO DIGITAL low-ticket ~€27 (não e-commerce físico como foco principal)
- Promessa: ensinar a FAZER e VENDER em casa (side income, hobby → negócio)
- Avatar: mulher 25–55, renda extra, craft, Instagram/TikTok, sem experiência prévia
- Canal de aquisição planeado: Meta Ads (tráfego direto)
- NÃO focar em: compliance fiscal detalhado, poder de compra macro, claims médicos
- FOCAR em: demanda de busca, saturação de oferta de CURSOS/infoprodutos, gap competitivo, linguagem local do mercado

## REGRAS DE OUTPUT
1. Responde em PORTUGUÊS (termos locais entre parênteses: DE/EN)
2. Cada afirmação quantitativa deve ter FONTE com URL ou marcar "DADO AUSENTE — método alternativo sugerido"
3. Não inventar números de Ad Library — deixa checklist para preenchimento manual
4. Estrutura obrigatória abaixo — não omitir secções
5. No final: JSON válido no bloco ```json ... ```

---

## SECÇÃO 1 — RESUMO EXECUTIVO (máx. 15 linhas)
- Ranking provisório: País × Vertical (top 3 combinações)
- Uma frase assertiva: "A oportunidade mais clara é ___ porque ___"
- Principal risco em cada top 3

---

## SECÇÃO 2 — FRAMEWORK DE SCORE

Define e aplica:

| Dimensão | Peso | Escala 1–10 | Como medir |
|----------|------|-------------|------------|
| Demanda de busca | 25% | Trends + volume relativo keywords | Google Trends 36 meses, país alvo |
| Saturação infoproduto | 35% | Contagem ofertas indexadas "curso + vender + casa" | Web search, Udemy, Hotmart-style, landing pages DE/EN |
| Gap de oferta | 25% | Poucos players com ângulo "renda extra + vender" em idioma local | Qualidade do match avatar |
| Fit criativo Meta | 15% | Potencial hooks visuais + prova social craft | Julgamento estruturado |

**Score final** = (Demanda × 0,25) + ((11 − Saturação) × 0,35) + (Gap × 0,25) + (Fit × 0,15)

Tabela obrigatória — 6 linhas (3 verticais × 2 países):

| País | Vertical | Demanda | Saturação | Gap | Fit Meta | Score | Confiança (A/B/C) |

---

## SECÇÃO 3 — DEMANDA (por país × vertical)

Para cada combinação, entrega:

### 3.1 Google Trends (últimos 36 meses, país correto)
Keywords obrigatórias:

**Alemanha (DE):**
- A) Badebomben selber machen, Badesalz selber machen, Badebomben verkaufen
- B) Gips gießen, Duftgips, Gips Deko selber machen, Gips verkaufen
- C) Kerzen selber machen, Duftkerzen, Kerzen verkaufen Nebenverdienst

**Reino Unido (UK):**
- A) bath bombs make at home, bath salts DIY, sell bath bombs from home
- B) plaster craft, gypsum casting, scented plaster, make plaster decor sell
- C) candle making course, make candles at home, candle business from home

Para cada keyword: tendência (↑ estável ↓), pico sazonal, comparação relativa entre verticais no mesmo país.

### 3.2 Sinais de aceitação cultural
- Presença em Etsy/Amazon handmade (qualitativo)
- Workshops presenciais vs online (ex.: Konfetti DE, experience days UK)
- Conteúdo viral TikTok/Reels no idioma local (3 exemplos ou "não encontrado")

---

## SECÇÃO 4 — SATURAÇÃO DE INFOPRODUTO (crítico)

Para cada vertical × país, lista **mínimo 8 e máximo 15** ofertas reais encontradas na web.

Colunas obrigatórias:

| # | Nome oferta | URL | Idioma | Preço | Ângulo (hobby / negócio / técnico) | Inclui "vender"? | Plataforma | Nota |

**Critérios de contagem:**
- INCLUIR: cursos online, workshops gravados, masterclasses, ebooks vendidos como curso, páginas de captura "aprende a vender X"
- EXCLUIR: apenas lojas de materiais sem curso; artigos de blog genéricos; Venetian plastering / gesso de construção (UK trade)

**Métricas derivadas (por célula país×vertical):**
- Total ofertas listadas
- % com ângulo "vender / side income / business"
- % em idioma local (DE ou EN-UK)
- Preço mediano
- Player dominante (se existir)
- Saturação 1–10 (justificar em 2 frases)

---

## SECÇÃO 5 — GAP COMPETITIVO (onde está a oportunidade)

Para cada uma das 6 células, responde:

1. **O que o mercado já tem em excesso?** (ex.: cursos técnicos sem módulo venda; cursos em inglês global ignorando DE)
2. **O que falta para o avatar €27?** (promessa clara, prova, comunidade, templates, pricing, Instagram)
3. **Existe equivalente ao "Gesso Lucrativo" BR?** (nome + URL ou "NÃO ENCONTRADO")
4. **Barreira de entrada para novo player** (baixa/média/alta + porquê)
5. **Hook diferenciador sugerido** (1 frase no idioma local)

---

## SECÇÃO 6 — META AD LIBRARY (CHECKLIST MANUAL — não inventar)

O Perplexity NÃO tem acesso fiável à Ad Library. Produz protocolo:

### 6.1 Keywords de pesquisa Ad Library

**DE — Biblioteca de anúncios Meta (Alemanha):**
- Badebomben Kurs / Badesalz / Geld verdienen Zuhause
- Gips gießen Kurs / Duftgips / Nebenverdienst
- Kerzen Kurs / Kerzen selber machen verkaufen

**UK — Meta Ad Library (United Kingdom):**
- bath bomb course / make money from home craft
- plaster craft course / gypsum craft business
- candle making course / candle business from home

### 6.2 Tabela vazia para o utilizador preencher

| País | Vertical | Keyword usada | Anúncios ativos (est.) | % vídeo | % imagem | Ofertas distintas | LP dominante | Saturação Ads 1–10 |

Instruções passo a passo (5 bullets) para Bruno fazer a contagem em 30 min.

---

## SECÇÃO 7 — ANÁLISE COMPARATIVA CROSS-COUNTRY

### 7.1 Mesma vertical, países diferentes
Compara A-DE vs A-UK, B-DE vs B-UK, C-DE vs C-UK: onde há menos concorrência de infoproduto local?

### 7.2 Mesmo país, verticais diferentes
Para DE e UK separadamente: qual vertical tem melhor ratio demanda/saturação?

### 7.3 Recomendação de sequência de teste
Ordem sugerida para 3 testes Meta €27 (ex.: "1º DE-Gesso, 2º UK-Sais...") com orçamento sugerido por teste (€150–300) e KPI go/no-go (CPA, CTR, hook rate).

---

## SECÇÃO 8 — PACOTE PARA MANUS (síntese estruturada)

### 8.1 Decisão recomendada
- **Mercado #1:** [País + Vertical]
- **Mercado #2 (backup):** [...]
- **Evitar por agora:** [...]

### 8.2 Brief criativo (idioma do mercado escolhido)
- 5 hooks de vídeo (texto na língua local)
- 3 objeções do avatar + respostas
- Nome de produto provisório (3 opções)
- Keywords para Persona Extractor

### 8.3 Lacunas que só o teste pago resolve
Lista 5 hipóteses a validar com €27 + Meta.

---

## SECÇÃO 9 — FONTES
Lista numerada de todas as URLs citadas, agrupadas por secção.

---

## SECÇÃO 10 — JSON PARA MANUS

```json
{
  "research_date": "YYYY-MM-DD",
  "countries": ["DE", "UK"],
  "verticals": ["bath_salts_bombs", "scented_plaster", "candles"],
  "scores": [
    {
      "country": "DE",
      "vertical": "bath_salts_bombs",
      "demand": 0,
      "saturation": 0,
      "gap": 0,
      "meta_fit": 0,
      "total_score": 0,
      "confidence": "A|B|C"
    }
  ],
  "ranking": [
    {"rank": 1, "country": "", "vertical": "", "score": 0, "rationale": ""}
  ],
  "avoid": [{"country": "", "vertical": "", "reason": ""}],
  "ad_library_pending": true,
  "recommended_test_sequence": [
    {"order": 1, "country": "", "vertical": "", "budget_eur": 200}
  ],
  "product_names": [],
  "hooks": []
}
```

---

## INSTRUÇÃO FINAL AO PERPLEXITY
Sê assertivo. Se os dados forem insuficientes, diz qual célula está fraca e o que Bruno deve pesquisar manualmente. O objetivo não é relatório académico — é **decisão de entrada de mercado** para infoproduto €27 com vantagem competitiva.
```

---

## PROMPT MANUS (após colar output Perplexity)

```
Recebes o output completo da pesquisa Perplexity (DE + UK × 3 verticais).

Tarefas:
1. Valida consistência dos scores (recalcula se necessário)
2. Cruza com os dados de Meta Ad Library que eu colar [SE VAZIO: assinala como incerteza alta]
3. Produz RECOMENDAÇÃO FINAL em português:
   - Mercado #1 com justificativa em 3 bullets
   - Riscos e mitigação
   - Plano de teste 7 dias (€27, orçamento, criativos, métricas)
4. Gera 3 variações de nome de produto + 5 hooks no idioma do mercado vencedor
5. Output em markdown + tabela resumo

Não suavizes a recomendação — escolhe UM mercado para testar primeiro.
```

---

## NOTAS

- **"Três países"** na mensagem original: nesta versão são **2 países (DE + UK)**. Terceiro país = duplicar secção 4.
- **"Três produtos"** = sais/bath bombs | gesso aromático | velas.
- Perplexity prepara; Manus decide; Meta Ads valida.
