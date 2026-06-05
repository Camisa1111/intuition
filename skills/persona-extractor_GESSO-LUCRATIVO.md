# SKILL: PERSONA EXTRACTOR — Gesso Lucrativo v2
**Objetivo:** Analisar materiais de marketing (landing pages, criativos em vídeo, depoimentos, comentários de anúncio) e extrair um relatório de persona estruturado para orientar a criação de novos criativos vencedores em tráfego frio.
**Oferta de referência:** Curso online "Gesso Lucrativo" — artesanato em gesso perfumado para renda extra
**Data de referência:** Junho de 2026
**Versão:** 2.0 — Auditada e otimizada

> **O que mudou na v2:** (1) Prompt de instrução expandido com critério de priorização de evidência; (2) Camada de consciência com protocolo de diagnóstico antes de qualquer copy; (3) Dores reorganizadas por intensidade de conversão, não por ordem de aparição; (4) Nova Camada 8 — Mapa de Objeções com roteiros de dissolução; (5) Nova Camada 9 — Segmentação por Subtipo de Avatar; (6) Seção VOC expandida com classificação de uso por posição no criativo; (7) Jornada emocional detalhada com timing de segundos e critério de corte de atenção; (8) Lacunas críticas elevadas ao topo do documento como prioridade de ação; (9) Templates de dissolução de objeção em formato pronto para copy.

### Par de skills (Claude Work / projeto local)

1. **Esta skill (Persona Extractor)** — roda primeiro: persona, dores, VOC, objeções, hooks priorizados.  
2. **`copy-pattern-analyst_GESSO-LUCRATIVO.md`** — roda depois: padrões do swipe, arquétipos, templates, experimentos A/B.  
**Não pular o Extrator:** sem Camada 2A (consciência) e Painel de Lacunas, o Pattern Analyst tende a replicar só ROI e ignorar dor/identidade.

---

## INSTRUÇÃO GERAL DE USO

Esta skill analisa materiais de marketing da oferta Gesso Lucrativo e devolve um relatório de persona completo, dividido em camadas progressivas de profundidade. **Toda afirmação deve ser ancorada em evidência direta dos materiais.** Inferências são explicitamente marcadas com nível de confiança (ALTA / MÉDIA / BAIXA).

**Regra de priorização de evidência:**
- Evidência que aparece em 3+ materiais distintos → ALTA CONFIANÇA → usar como base de qualquer criativo
- Evidência que aparece em 1–2 materiais → MÉDIA CONFIANÇA → usar como hipótese de teste
- Inferência sem citação direta → BAIXA CONFIANÇA → não usar sem coleta de dados própria
- Ausência consistente de um elemento → **GAP IDENTIFICADO** → tratar como oportunidade de teste, não como falha

**Materiais a receber como input:**
- Transcrições de criativos em vídeo (VSL, Reels, TikToks, Stories)
- Texto completo da landing page
- Depoimentos de alunas (quando disponíveis) — **prioridade máxima: são VOC puro**
- Capturas de comentários em anúncios — **prioridade máxima: revelam objeções reais não filtradas**
- Print de conversas no WhatsApp com pedidos (quando disponível)

> **⚠️ NOTA ANTES DE ESCREVER QUALQUER COPY:** Consultar a Camada 2A (nível de consciência) antes de escolher tipo de hook. Hook errado para o nível de consciência = criativo que não converte mesmo com boa copy.

---

## CLASSIFICAÇÃO DOS MATERIAIS ANALISADOS

Antes de iniciar a análise, montar a seguinte tabela com os materiais recebidos:

| Material | Tipo | Quantidade | Prioridade de VOC |
|---|---|---|---|
| [identificar] | Landing page / Sales page | [N] | Alta — fonte principal de dores e desejos |
| [identificar] | VSL / Transcrição de criativo | [N] | Alta — revela o que já foi testado |
| [identificar] | Depoimentos de alunas | [N] | **Máxima — VOC puro, usar verbatim** |
| [identificar] | Comentários de anúncio | [N] | **Máxima — objeções não filtradas** |
| [identificar] | Prints de WhatsApp / venda | [N] | Alta — prova do canal de venda |
| **Total** | | **[N peças]** | |

> **Nota metodológica:** Frases que aparecem em 3+ materiais são tratadas como validadas pelo produtor e priorizadas nas recomendações. A ausência de um elemento em todos os materiais não significa que não funciona — significa que **nunca foi testado**. Ausências são oportunidades, não confirmações de inadequação.

---

## ⚡ PAINEL DE LACUNAS CRÍTICAS (Ler primeiro — agir antes de escalar)

> Esta seção foi movida para o topo porque são as ações de maior impacto imediato. Resolver estes gaps antes de aumentar budget.

```
LACUNA CRÍTICA #1 — Prova social com rosto + nome + cidade + número real
Impacto: MÁXIMO em tráfego frio
Problema: "centenas de mulheres" é vago. A persona em cold traffic não acredita em
          massa anônima. Ela acredita em "Maria, de Fortaleza, que fez R$340 no primeiro mês."
Ação:     Coletar 3–5 depoimentos com: primeiro nome, cidade, resultado em R$, contexto
          ("era donas de casa / trabalhava de carteira assinada / nunca tinha feito artesanato")
Formato ideal: vídeo vertical 15s OU foto com texto OU print de conversa no WhatsApp

LACUNA CRÍTICA #2 — Demonstração do canal de venda (WhatsApp)
Impacto: ALTO — "pedidos chegam pelo WhatsApp" é a promessa de conversão mais concreta
         da oferta, mas nenhum criativo mostra isso acontecendo
Problema: Prometer que o WhatsApp vai encher de pedidos sem mostrar um pedido real
          é o tipo de afirmação que o público de cold traffic descarta em 2 segundos
Ação:     Criar criativo mostrando (ou simulando) a notificação chegando no WhatsApp
          com pedido real (anonimizado). Ou depoimento em vídeo: "chegou esse pedido aqui..."

LACUNA CRÍTICA #3 — Arquétipo de hook com abertura em dor — NUNCA TESTADO
Impacto: ALTO — nenhum criativo atual abre com a dor "dia 30 sem dinheiro"
         que é a dor #1 mapeada na landing page
Problema: Todos os criativos abrem com resultado ou revelação social.
          A prospect que está no nível de consciência 2 (só sente a dor, não busca solução)
          não para scroll por ROI — ela para por dor nomeada.
Ação:     Criar 1 criativo abrindo com Dor #1 e A/B testar contra os formatos atuais.

LACUNA CRÍTICA #4 — Âncora de ROI total / payback do curso
Impacto: MÉDIO-ALTO — a persona sabe que a peça vale R$30 mas não conecta isso
         ao investimento de R$37,60 no curso
Problema: A aritmética do payback nunca é feita explicitamente:
          "você faz 2 peças, recupera o curso, o resto é lucro puro"
Ação:     Inserir cálculo nos criativos E na landing page
          Exemplo: "em 2 vendas você já pagou o curso. A partir daí, é tudo seu."

LACUNA CRÍTICA #5 — Urgência sem timer visual na landing page
Impacto: MÉDIO — "vai subir sem aviso" é urgência textual fraca
Problema: Urgência sem âncora temporal não cria ação — cria paralisia
Ação:     Adicionar timer de contagem regressiva ou data explícita de reajuste
```

---

## CAMADA 1 — DEMOGRAFIA EVIDENCIADA

```
GÊNERO
Sinal:    Feminino — confiança MÁXIMA
Evidência direta da landing page:
          "você não está sozinha" (flexão feminina implícita)
          "sem depender de marido, de chefe, de ninguém"
          "com os filhos em casa ou depois que a casa dorme"
          "para muito mais do que as artesãs conseguem atender"
          "centenas de mulheres"
Evidência dos criativos:
          "o que milhares de mulheres comuns estão fazendo"
          "Elas estão criando peças de gesso perfumado"
          "Elas simplesmente decidiram começar"

FAIXA ETÁRIA
Sinal:    25–50 anos [INFERIDO — confiança MÉDIA]
Razão:    Referências a "filhos em casa", "trabalha o mês inteiro",
          contexto de dupla jornada (emprego + casa), desejo de
          independência financeira do marido — padrão de mulher
          em fase ativa de vida familiar e profissional.
          Nenhum material menciona faixa etária diretamente.
Nota v2:  Ampliar faixa superior para 50 anos — o produto não requer
          habilidade digital avançada e atinge mães mais velhas com
          filhos criados e tempo disponível ("depois que a casa dorme"
          é linguagem de mulher mais velha também).
Gap:      Faixa etária real pode ser validada com dados de audiência
          do Gerenciador de Anúncios — consultar antes de definir
          faixa em campanhas.

GEOGRAFIA
Sinal:    Brasil inteiro — confiança ALTA
Evidência: "fornecedores para qualquer estado"
           "Correios ou transportadora" (abrangência nacional)
           Produto digital sem restrição geográfica.
Gap v2:   Hooks com menção a região específica não foram testados.
          Hipótese: "Mulheres de São Paulo / do Nordeste / do interior
          estão fazendo isso de casa" pode aumentar identificação local.
          Testar com variantes segmentadas por estado nas campanhas.

OCUPAÇÃO
Sinal:    Três perfis identificados — confiança ALTA
  Perfil A — Empregada CLT sobrecarregada:
    Evidência: "você trabalha o mês inteiro, dá duro, não para um segundo"
               "sem pedir licença pra ninguém — de manhã, à noite, no fim de semana"
  Perfil B — Dona de casa sem renda própria:
    Evidência: "você tem tempo em casa, mas sente que deveria estar transformando"
               "a culpa aperta quando não consegue"
               "sem depender de marido"
  Perfil C — Desempregada ou em transição:
    Evidência: "renda que não some quando a empresa demite"
               Premissa de entrada: "2 horas livres por dia" (sem menção a emprego fixo)
[NOTA v2: Cada perfil tem um hook dominante diferente. Ver Camada 9 — Subtipos de Avatar.]

RENDA
Sinal:    Baixa a média-baixa / altamente sensível a preço — confiança ALTA
Evidência: Preço de lançamento R$37,60 (de R$89,90) como elemento central
           "por um valor que qualquer mulher pode pagar"
           "você recupera o investimento nas primeiras vendas"
           ROI de material: R$5 → R$35/R$50/R$80
Gap v2:   O cálculo explícito de payback nunca é feito:
          "em 2 vendas você já pagou o curso" — inserir nos criativos e na LP.
          Esta é a âncora de ROI mais persuasiva para persona sensível a preço.

FAMÍLIA
Sinal:    Mãe ou mulher com responsabilidades domésticas — confiança ALTA
Evidência: "com os filhos em casa ou depois que a casa dorme"
           "cuido dos meus filhos, escolho meu horário"
           "sem pedir licença pra ninguém"
           Horários mencionados: manhã, noite, fim de semana — padrão de mãe
Gap v2:   Resistência familiar não é tratada em nenhum criativo atual.
          "meu marido não acreditava, mas..." é um arquétipo de alto potencial
          não testado — ver Medo Latente #6 e Template de Dissolução de Objeção.

NÃO EVIDENCIADO (lacunas — não inferir sem dados):
- Estado civil definido (menção a "marido" não confirma casamento)
- Nível educacional
- Presença digital anterior / familiaridade com e-commerce
- Cidade ou região específica
- Faixa etária exata
```

---

## CAMADA 2 — PERFIL PSICOGRÁFICO

### 2A — Nível de Consciência (Protocolo de Diagnóstico)

> **⚠️ USAR ANTES DE QUALQUER COPY:** O nível de consciência determina qual tipo de hook usar. Hook errado para o nível = anúncio desperdiçado.

```
NÍVEL DOMINANTE: 3 (Consciente do Problema — sabe que quer renda extra,
                     não sabe que gesso é a solução)

NÍVEL SECUNDÁRIO: 2 (Consciente da Dor — sabe que está mal financeiramente,
                     não formulou o desejo de mudança ainda)

PROTOCOLO DE DIAGNÓSTICO:
  → Prospect nível 2: Abre com DOR NOMEADA (hook P) — ela não busca solução ainda
  → Prospect nível 3: Abre com RESULTADO ou REVELAÇÃO SOCIAL — ela está comparando opções
  → Prospect nível 4: Abre com DIFERENCIAÇÃO DO MÉTODO — ela já conhece o mercado

A landing page trata da persona como nível 3–4, mas os criativos de cold traffic
estão alcançando nível 2–3. Isso é correto para tráfego frio no Meta Ads.

Evidência do nível 3:
— LP justifica o mercado antes de apresentar o curso ("esse mercado está explodindo")
— Criativos usam "você sabia que…?" — pergunta que pressupõe novidade para o avatar
— Seção inteira de objeções na LP = resistência não resolvida = nível pré-decisão
— Hook recorrente: mostrar peça + custo vs. preço = educação sobre viabilidade

Evidência do nível 2 (gap atual — criativos não cobrem este segmento):
— Não existe criativo que abre com dor pura, sem revelar produto
— "Você trabalha o mês inteiro e no dia 30 não é suficiente" nunca foi hook de abertura
— Este segmento de prospect provavelmente representa o maior volume não convertido
```

---

### 2B — DORES DECLARADAS (Reorganizadas por Intensidade de Conversão)

> **v2:** Dores reordenadas por potencial de parada de scroll em cold traffic — não por ordem de aparição na landing page.

```
DOR #1 — Dinheiro insuficiente no fim do mês [INTENSIDADE: MÁXIMA]
Copy direta: "você trabalha o mês inteiro, dá duro, não para um segundo —
              e quando chega no dia 30, o dinheiro ainda não é suficiente"
Registro emocional: Esgotamento + humilhação silenciosa + esforço sem recompensa
Potencial de hook: MÁXIMO — é a dor mais universal e imediata do avatar
Status nos criativos: NUNCA usada como abertura — GAP CRÍTICO

DOR #2 — Dependência financeira (de marido, chefe, outros) [INTENSIDADE: ALTA]
Copy direta: "você quer ter o SEU dinheiro — sem pedir, sem depender de marido,
              de chefe, de ninguém. Mas ninguém nunca te mostrou como chegar lá."
Registro emocional: Impotência + vergonha + desejo profundo de autonomia reprimido
Nota v2: A raiva contida contra a dependência é uma emoção ativadora de clique.
         Nenhum criativo usa raiva como motor. Oportunidade de teste de alto impacto.

DOR #3 — Angústia financeira crônica / insônia financeira [INTENSIDADE: ALTA]
Copy direta: "a ansiedade financeira vai cedendo conforme a conta vai subindo.
              Você dorme diferente quando sabe de onde vem o próximo dinheiro."
              "sei exatamente o que é olhar pro fim do mês com aquela angústia no peito"
Registro emocional: Ansiedade de fundo permanente / incapacidade de relaxar
Nota v2: "Você dorme diferente" é uma das frases mais poderosas da LP —
          SUBUTILIZADA nos criativos. Usar como resultado emocional (não financeiro).

DOR #4 — Culpa por ter tempo em casa e não transformar em renda [INTENSIDADE: ALTA]
Copy direta: "você tem tempo em casa, mas sente que deveria estar transformando
              esse tempo em renda — e a culpa aperta quando não consegue"
Registro emocional: Culpa + sensação de desperdício de potencial + julgamento interno
Status nos criativos: NUNCA usada como abertura — GAP DE ALTO POTENCIAL

DOR #5 — Crença de que "não tem talento" / não é para ela [INTENSIDADE: ALTA]
Copy direta: "lá no fundo, uma voz diz: isso não é pra mim,
              eu não tenho talento pra isso. E você acaba acreditando nela."
Registro emocional: Identidade negativa consolidada + auto-sabotagem + medo de tentar
NOTA CRÍTICA v2: Esta é a BARREIRA DE IDENTIDADE — mais difícil de dissolver do que
                 objeção de preço. Precisa ser atacada ANTES de apresentar ROI ou módulos.
                 Dissolução: "se você consegue seguir uma receita de bolo, consegue fazer isso."
                 Esta analogia é a mais eficiente disponível — usar em todo criativo.

DOR #6 — Paralisia na hora de começar [INTENSIDADE: MÉDIA-ALTA]
Copy direta: "trava na hora de começar: por onde eu começo?
              E se não funcionar pra mim? E se eu não tiver jeito?"
Registro emocional: Insegurança + overthinking + medo de desperdício de recurso
Nota v2: Esta dor é a manifestação comportamental da Dor #5 — são a mesma objeção
         em camadas diferentes. Dissolver a identidade dissolve a paralisia.

DOR #7 — Demissão como ameaça real [INTENSIDADE: MÉDIA]
Copy direta: "começa a ter uma renda 100% SUA — que cresce com você
              e não some quando a empresa demite"
Registro emocional: Medo de perder o único sustento + vulnerabilidade
Nota v2: Esta dor ressoa mais em momentos de instabilidade econômica.
         Testar hook com ancoragem nesta dor em contexto de recessão/demissão em massa.
```

---

### 2C — MEDOS LATENTES (Implícitos — ordenados por urgência de tratamento)

```
MEDO LATENTE #1 — "Não tenho jeito / sou desajeitada" [URGÊNCIA: CRÍTICA]
Evidência: "mesmo que nunca tenha tocado em artesanato na vida"
           "se consegue seguir uma receita de bolo, consegue fazer isso"
           "não precisa de talento especial, nem de espaço nem de experiência"
Confiança: ALTA — tratado em múltiplos pontos como objeção central
Instrução: Este medo precisa ser dissolvido no bloco 2–3 de qualquer criativo,
           ANTES do ROI. Persona que ainda acredita "não é pra mim" não processa
           dados de resultado — a identidade bloqueia a lógica.
Melhor dissolução validada: analogia da receita de bolo — simples, reconhecível,
           não técnica, sem promessa exagerada.

MEDO LATENTE #2 — Gastar e não recuperar (risco percebido alto) [URGÊNCIA: ALTA]
Evidência: "você recupera o investimento nas primeiras vendas"
           Garantia de 7 dias "sem perguntas, sem burocracia"
           Argumento de custo de material R$5 → R$35/R$50/R$80
Confiança: ALTA
Instrução: Dissolução via cálculo de payback explícito — nunca feito diretamente.
           "em 2 vendas você já pagou o curso — a partir da terceira, é lucro puro"
           Esta frase não existe em nenhum criativo ou LP atual → inserir.

MEDO LATENTE #3 — Não conseguir vender (saber fazer ≠ saber vender) [URGÊNCIA: ALTA]
Evidência: "pedidos chegando pelo WhatsApp" como canal específico prometido
           "produtos que as pessoas pagam bem, pedem de novo e indicam"
Confiança: ALTA (implícito, não resolvido diretamente nos criativos)
Gap v2: Nenhum criativo mostra o processo de venda pelo WhatsApp.
        Criativo mostrando a notificação de pedido chegando = prova mais poderosa
        disponível para este medo. Custo de produção: zero (só gravar a tela).

MEDO LATENTE #4 — Não ter tempo suficiente para ter sucesso [URGÊNCIA: MÉDIA]
Evidência: "2 horas livres por dia" como premissa de entrada
           "acesso vitalício" (sem pressão de prazo)
           "no seu tempo" (3x na LP — repetição = ponto de ansiedade real)
Confiança: ALTA
Instrução: Não subutilizar "2 horas por dia" — é o antídoto para "não tenho tempo".
           Inserir nos hooks: "tem 2 horas livres por dia? Então você tem tudo."

MEDO LATENTE #5 — Ser mais uma que tentou, não deu certo [URGÊNCIA: MÉDIA]
Evidência: "quero que você pule os anos de tentativa e erro"
           "nossas alunas estavam onde você está. Hoje têm pedidos chegando"
           Narrativa da Mari: inversão de fracasso esperado
Confiança: ALTA
Instrução: Criar Arquétipo C (história de quase-fracasso) para capturar
           especificamente esta prospect. Ver Camada 9 — Subtipo B.

MEDO LATENTE #6 — Marido / família não vai apoiar [URGÊNCIA: MÉDIA]
Evidência: "sem pedir, sem depender de marido" (menção específica)
           "não devo satisfação a ninguém"
Confiança: MÉDIA (inferida por contexto + menção ao marido)
Gap v2: Zero criativos tratam da resistência familiar.
        Arquétipo "meu marido não acreditava, mas..." é de alto potencial e
        cria identificação com a prospect que sente esta pressão específica.
        Cuidado de execução: não fazer o marido de vilão — fazer o resultado
        como prova que silencia a dúvida sem confronto.
```

---

### 2D — DESEJOS (Reorganizados por Profundidade de Motivação)

```
DESEJO SUPERFICIAL (racional — o que ela diz que quer):
  → Renda extra
  → Trabalhar de casa
  → Não depender de emprego fixo

DESEJO PROFUNDO (emocional — o que de fato a move):
  → "Ter o SEU dinheiro" — não a renda, a posse identitária dela
    Copy: "uma renda 100% SUA — que cresce com você e não some quando a empresa demite"
  → Dormir tranquila — alívio de ansiedade crônica, não aumento de renda
    Copy: "você dorme diferente quando sabe de onde vem o próximo dinheiro"
    [NOTA v2: Esta frase deveria estar nos criativos. Nunca apareceu como body ou CTA.]
  → Orgulho pelo que criou com as próprias mãos — identidade positiva nova
    Copy: "olha pra peça que criou e sente um orgulho que nenhum salário de emprego deu"
    [NOTA v2: Este é o resultado emocional mais diferenciado da oferta — conecta trabalho
    manual a identidade positiva, o que nenhuma outra oferta de renda digital faz.]

DESEJO OCULTO (não verbalizado — o que ela não admite):
  → Ser vista como alguém que conseguiu / sair do lugar de "quem só tenta"
    Evidência: "a protagonista é você" — promessa de protagonismo na própria história
               "pular os anos de tentativa e erro" — skip da fase de fracasso pública
  → Ter uma atividade que seja refúgio, não mais trabalho
    Evidência: "é a coisa mais relaxante que existe" (Criativo 1)
               "é prazeroso, terapêutico e muito lucrativo" (LP)
    [NOTA v2: A maioria das ofertas de renda extra vende esforço. O Gesso Lucrativo
    pode vender refúgio + renda. Este é o diferencial competitivo mais inexplorado.]
  → Provar para si mesma (e para os outros) que ela é capaz
    Evidência: toda a narrativa de identidade da LP aponta para esta necessidade
               de autovalidação — "descobri que sou capaz de X"
```

---

### 2E — LINGUAGEM DA PERSONA (Voice of Customer — VOC)

> **v2:** Frases reorganizadas por FUNÇÃO na copy (onde usar), não só por origem.

```
PARA HOOKS DE DOR (abertura — parar o scroll):
  — "Você trabalha o mês inteiro, dá duro, não para um segundo — e no dia 30, não é suficiente."
  — "A culpa aperta quando você sabe que deveria estar transformando o tempo em renda."
  — "Isso não é pra mim, eu não tenho talento pra isso." [auto-sabotagem da persona — espelhar]
  — "Por onde eu começo? E se não funcionar pra mim? E se eu não tiver jeito?"

PARA BODY DE IDENTIFICAÇÃO (bloco 2–3 — criar conexão antes do argumento):
  — "Aquela angústia no peito de olhar pro fim do mês"
  — "Sem pedir, sem depender de marido, de chefe, de ninguém"
  — "Ter o SEU dinheiro — que não some quando a empresa demite"
  — "Com os filhos em casa ou depois que a casa dorme"

PARA BODY DE TRANSFORMAÇÃO (bloco 3–4 — resultado emocional, não financeiro):
  — "Você dorme diferente quando sabe de onde vem o próximo dinheiro."
  — "Olhar pra peça que criou com as próprias mãos e sentir um orgulho
      que nenhum salário de emprego nunca deu."
  — "Não devo satisfação a ninguém."
  — "Eu decido."

PARA CTA E FECHAMENTO (bloco 5 — empurrar para ação):
  — "Simplesmente decidiram começar."
  — "A protagonista é você."
  — "Se você chegou até aqui, é porque algo mudou por dentro."
  — "A mudança acontece no dia em que você decide que é agora — não 'um dia'."

PARA DISSOLUÇÃO DE OBJEÇÃO (usar em qualquer posição):
  — "Se consegue seguir uma receita de bolo, consegue fazer isso." [melhor analogia disponível]
  — "Em 2 vendas você já pagou o curso — a partir da terceira, é lucro puro." [payback direto]
  — "Acesso vitalício — estuda no seu ritmo, sem pressão." [dissolve medo de falta de tempo]

NOTA: Usar estas frases verbatim ou com mínima adaptação. A persona deve se ouvir
falar — não ouvir alguém descrevendo ela de fora.
```

---

## CAMADA 3 — ANÁLISE DOS CRIATIVOS EM VÍDEO

### 3A — Padrões de Hook Identificados

```
TIPO R — Resultado imediato + prova pessoal [VALIDADO — 3 criativos]:
  GL-04: "Tá vendo essa peça aqui? Custou menos de R$5, vendi por até R$30."
  → Sequência: objeto físico → dado numérico → ROI implícito → CTA
  → Funciona porque: prova visual + matemática simples em 2 segundos
  → Recomendação: REPLICAR com variações de produto e dado de tempo
    ("fiz em 20 minutos / numa tarde de sábado")

  GL-05: "Se eu te mostrasse esse estoque e dissesse que saiu da minha casa, você acreditaria?"
  → Antecipa o ceticismo da persona antes que ela pense — técnica de inoculação
  → Potencial ALTO para audiência que já foi exposta a promessas exageradas

  GL-01: "Sabe o que eu faço quando estou estressada? Eu vou lá e faço gesso."
  → Único hook de padrão interrompido — não começa por dinheiro
  → Diferencial máximo de feed — todo anúncio concorrente começa por renda extra

TIPO E — Revelação social / curiosidade [VALIDADO — 2 criativos]:
  GL-02: "Deixa eu te contar o que milhares de mulheres comuns estão fazendo…"
  → Hook de segredo coletivo — funciona por FOMO social
  → Risco: "milhares" sem número concreto é genérico em cold traffic

  GL-03: "Você sabia que o segredo das casas mais perfumadas pode ser a sua nova fonte de renda?"
  → Curiosidade + conexão sensorial — converte prospect que não está no modo de busca de renda

TIPO S — Sensorial puro [1 criativo — testar mais]:
  GL-06: "Você já entrou num ambiente e sentiu aquele cheiro que te fez querer ficar?"
  → Ativa memória emocional antes de qualquer argumento financeiro
  → Potencial ALTO com público feminino — diferenciação máxima de feed de renda extra

TIPO P — Dor como abertura [0 criativos — GAP CRÍTICO]:
  NENHUM criativo atual abre com dor.
  Dor #1 ("dia 30 sem dinheiro") nunca foi testada como hook.
  → Esta é a lacuna de maior impacto potencial identificada nesta análise.
  → Ver Hooks P1–P4 na Camada 6A.
```

---

### 3B — Padrões de Transição Identificados

```
TRANSIÇÃO VALIDADA #1 — Inversão de expectativa / "só que o melhor não é isso":
  Exemplo: "Só que o melhor não é isso. O melhor é que essas peças que eu faço
             para relaxar, eu vendo e vendo bem."
  Técnica: Setup emocional (terapia) → revelação de benefício adicional (renda)
  Instrução: Usar em qualquer criativo com abertura emocional não financeira.
             É a transição que converte o hook de terapia em argumento de renda.

TRANSIÇÃO VALIDADA #2 — Progressão de preço com normalizador:
  Exemplo: "sai por R$10, R$15, até R$20 fácil"
  Técnica: 3 números crescentes + palavra normalizadora ("fácil", "tranquilo")
  Instrução: Usar sempre com 3 valores, não 1. A progressão cria prova de faixa,
             não de valor único. "fácil" remove a resistência antes que se instale.

TRANSIÇÃO VALIDADA #3 — Âncora visual → contraste com emprego → identidade:
  Exemplo: "Hoje produzo tudo isso aqui de dentro de casa, no meu tempo,
             sem depender de chefe nem de horário."
  Técnica: prova visual (estoque) → contraste (sem chefe) → identidade (liberdade)
  Instrução: Sequência mais eficiente para criativos de produto físico na câmera.

TRANSIÇÕES AUSENTES (criar e testar):

  TRANSIÇÃO #4 — Tentativa anterior → método certo:
  "Em vez de ficar errando sozinha vendo vídeo no YouTube, você segue
   um método completo que te pega pela mão desde o início."
  Por que faz falta: nenhum criativo nomeia a tentativa anterior como origem do fracasso.
                     Sem vilão, não há pivô de decisão. Sem pivô, não há conversão do
                     prospect que já tentou alguma coisa antes.

  TRANSIÇÃO #5 — Temporal / espelho de passado:
  "Há 6 meses eu estava exatamente onde você está agora."
  Por que faz falta: cria identificação temporal com a persona que está em dúvida.
                     "ela passou pelo mesmo ponto que eu estou" = prova de que é possível sair.

  TRANSIÇÃO #6 — Payback do curso:
  "Em 2 vendas você já pagou o curso. A partir daí, é tudo lucro."
  Por que faz falta: o medo de gastar sem retorno é medo latente #2 — nunca
                     resolvido explicitamente nos criativos atuais.
```

---

### 3C — Padrões de Body Identificados

```
BODY DE ROI DIRETO [5/6 criativos — padrão dominante]:
  "Material custa quase nada. Peças vendidas pelo triplo."
  "Menos de R$5 para produzir, vende por R$30 a R$40."
  → Dado mais eficiente: custo R$5 × preço R$30 = multiplicador 6x
  → UPGRADE v2: adicionar dado de velocidade ("em 20 minutos / numa tarde")
    e dado de payback ("em 2 peças você recupera o investimento no curso")

BODY DE DEMOCRATIZAÇÃO — "qualquer uma consegue" [4/6 criativos]:
  "Não precisa de talento especial, nem de espaço e muito menos de experiência."
  "Se consegue seguir uma receita de bolo, consegue fazer isso."
  → Analogia da receita de bolo é a frase mais eficiente disponível — usar em todo criativo.
  → UPGRADE v2: posicionar ANTES do ROI, não depois. Persona que não acredita
    que "é pra ela" não processa dados de resultado.

BODY DE SENSAÇÃO [2/6 criativos — subutilizado]:
  "Você não vende decoração — você entrega sensações, cheiros e memórias."
  "É exatamente essa sensação que essas peças provocam."
  → Único frame que vende o PRODUTO FINAL (o que a cliente compra) antes do curso.
  → UPGRADE v2: criar criativo inteiro neste frame:
    abertura sensorial → produto provoca sensação → produto vende fácil →
    curso ensina a fazer → CTA. Este é o criativo mais diferenciado possível.

BODY AUSENTE (criar):
  → Body de raiva contida: "você merece ter uma renda que é sua,
    que não some quando te demitem e que não depende de ninguém pra existir."
  → Body de alívio emocional: "você dorme diferente quando sabe de onde
    vem o próximo dinheiro" — frase da LP nunca usada em criativo.
  → Body de payback: "em 2 vendas você já pagou o curso — a partir daí, é tudo seu."
```

---

### 3D — Padrões de CTA Identificados

```
CTAs ATUAIS NOS CRIATIVOS:
  — "Clica em Saiba Mais que eu te explico tudo" — 5/6 criativos
  — "Clica agora no botão ou comenta: Eu quero" — criativo 2 (micro-compromisso)
  — "Toque em Saiba Mais e comece hoje mesmo" — criativo 3

PADRÃO DOMINANTE: CTA suave ("Saiba Mais") — CORRETO para tráfego frio
  → Persona em cold traffic está em nível 2–3 de consciência → pede descoberta, não compra

CTAs AUSENTES (criar e testar — por prioridade):

  CTA DE IDENTIDADE (testar primeiro):
  "Clica aqui e começa a construir uma renda que é só sua."
  Por que testar: ancora o clique em identidade, não em produto.

  CTA COM URGÊNCIA SUAVE (testar junto com link-FOMO):
  "Enquanto o preço de lançamento ainda estiver aqui, clica no Saiba Mais."
  Por que testar: única forma de inserir urgência sem quebrar o tom de amiga.

  CTA DE PAYBACK (testar no Arquétipo de ROI):
  "Clica no Saiba Mais — em 2 vendas você já recupera o investimento."
  Por que testar: dissolve o medo de gastar no próprio CTA, antes do clique.

  CTA DE RETIRADA (testar com budget controlado):
  "Se você ainda está com aquela voz dizendo 'e se der certo?' —
   é esse o sinal. Clica."
  Por que testar: altamente eficaz com prospect que tem medo de tentar.
  Cautela: risco de reduzir volume de cliques; usar só para audiências quentes.
```

---

## CAMADA 4 — ANÁLISE DA LANDING PAGE

### 4A — Estrutura Atual com Diagnóstico

```
SEÇÃO 1 — Hero / Identificação inicial
  Promessa central: 2h por dia + renda em casa + sem experiência
  Força: "2 horas livres por dia" é premissa de barreira mínima — funciona bem
  Fraqueza: "Gesso Lucrativo" como título principal não diz benefício
  Recomendação v2: Testar headline que abre com resultado ou dor antes do nome:
    Opção A (resultado): "Aprenda a criar peças que vendem por R$35 — de casa,
                         em 2 horas, sem precisar de experiência."
    Opção B (dor): "Tem 2 horas livres por dia? Então você já tem tudo que
                   precisa para parar de depender só do salário."

SEÇÃO 2 — "Eu Sei o Que Você Está Sentindo"
  Força: Cobre as principais dores em profundidade com emojis como âncoras visuais
  Fraqueza: Seção longa — persona escaneia e pula
  Recomendação v2: Manter as 5 dores mas adicionar microtítulo negritado
                   antes de cada bloco para facilitar o escaneamento.
                   Exemplo: **"Fim do mês chegou e ainda não é suficiente."**

SEÇÃO 3 — "Por que peças de gesso estão vendendo como nunca"
  Força: Educa sobre demanda — reduz ceticismo de viabilidade. Dado de ROI é poderoso.
  Fraqueza: Mercado apresentado de forma abstrata — sem dado de volume
  Recomendação v2: Adicionar dado de prova de mercado concreto:
                   número de pedidos semanais, volume de busca, ou depoimento
                   de recompra ("clientes que pedem de novo toda semana").

SEÇÃO 4 — "O que muda na sua vida"
  Força: A última frase é uma das mais poderosas da página:
         "você olha pra peça que criou com as próprias mãos e sente um orgulho
          que nenhum salário de emprego nunca deu"
  Fraqueza: Esta frase está enterrada no final da seção.
  Recomendação v2: MOVER para o hero OU para o CTA final — é o resultado emocional
                   mais diferenciado da oferta inteira.

SEÇÃO 5 — História da Mari
  Força: Âncora de primeiro resultado específica ("R$120 pela primeira peça")
  Fraqueza: História muito curta — falta o "fundo do poço" antes da virada
  Recomendação v2: Adicionar uma frase de vulnerabilidade máxima antes do resultado:
                   "Não sabia se ia dar certo. Fiz a primeira peça com aquele frio
                    na barriga de quem não sabe se vai funcionar."
                   — cria empatia com a prospect que ainda está em dúvida.

SEÇÃO 6 — Módulos do curso
  Força: Detalhamento técnico completo — adequado para persona em avaliação
  Fraqueza: Linguagem descritiva, não emotiva — lista o que é, não o que acontece depois
  Recomendação v2: Adicionar micro-resultado esperado após cada módulo:
                   "Ao final deste módulo: você vai saber exatamente quanto lucrar
                    em cada peça antes de produzir."

SEÇÃO 7 — Oferta / Preço / CTA
  Força: Âncora de preço (R$89,90 → R$37,60) presente e funcional. Garantia declarada.
  Fraqueza: Urgência textual ("vai subir sem aviso") sem âncora visual — fraca
  Recomendação v2: Timer de contagem regressiva ou data explícita de reajuste.
                   Adicionar cálculo de payback antes do botão:
                   "Em 2 vendas você recupera o investimento. A partir daí, é tudo seu."
```

---

### 4B — Gaps de Copy da Landing Page (Priorizados)

```
GAP LP #1 — Sem prova social com rosto + nome + cidade + número [IMPACTO: MÁXIMO]
Problema: A persona em cold traffic não acredita em "centenas de mulheres" anônimas.
          Ela acredita em "Juliana, de Feira de Santana, que fez R$340 no primeiro mês."
Ação: Coletar 3–5 depoimentos com: nome, cidade, resultado em R$, contexto de ponto
      de partida ("nunca tinha feito artesanato / estava desempregada / duas filhas")
Formato modelo: foto ou vídeo + frase do resultado + dados contextuais

GAP LP #2 — Demonstração do WhatsApp — canal prometido, não provado [IMPACTO: ALTO]
Problema: "pedidos chegam pelo WhatsApp" é a promessa de conversão mais concreta
          da oferta, mas não existe prova visual disto.
Ação: Print de conversa com pedido real (anonimizado) na LP e em criativos dedicados.

GAP LP #3 — Sem âncora de payback explícito [IMPACTO: ALTO]
Problema: A persona sabe que peça vale R$30 mas não conecta isso ao investimento de R$37,60.
Ação: Inserir cálculo explícito antes do botão de compra:
      "Você produz 2 peças. Vende por R$35 cada. São R$70.
       Você já pagou o curso — e ainda sobrou R$32,40 de lucro.
       O que você fizer a partir daí é 100% seu."

GAP LP #4 — Sem comparação com alternativas de renda extra [IMPACTO: MÉDIO]
Problema: Prospect em cold traffic está comparando internamente com revenda, confeitaria,
          delivery — mas a LP não responde a esta comparação.
Ação: Bloco de comparação implícito (sem citar concorrentes):
      "Você poderia tentar revenda — mas precisa de estoque inicial alto.
       Poderia tentar delivery — mas precisa sair de casa. Com o Gesso Lucrativo,
       você começa com R$20 de material, não sai do lugar e controla seu tempo."

GAP LP #5 — História da Mari sem fundo do poço [IMPACTO: MÉDIO]
Problema: A história pula direto para o resultado — não cria empatia máxima com
          a prospect que ainda está na dúvida e que quer se ver no momento de risco.
Ação: Adicionar uma frase de vulnerabilidade antes da primeira venda.
      Ver Recomendação da Seção 5 acima.
```

---

## CAMADA 5 — MAPA DE RESSONÂNCIA EMOCIONAL

### 5A — Emoções Primárias Ativadas (por intensidade e status de exploração)

```
1. ESPERANÇA ESPECÍFICA — "isso pode ser pra mim" [EXPLORADA — manter]
   Evidência: "mesmo que nunca tenha tocado em artesanato na vida"
              "se consegue seguir uma receita de bolo, consegue fazer isso"
   Status: bem tratada na LP e em vários criativos. Âncora central da oferta.

2. ALÍVIO ANTECIPADO — "vou parar de me preocupar com dinheiro" [SUBEXPLORADA]
   Evidência: "você dorme diferente quando sabe de onde vem o próximo dinheiro"
   Status: frase existe na LP mas nunca apareceu como body ou CTA de criativo.
   Instrução: Esta é a emoção de resultado mais poderosa disponível — usar como
              fechamento emocional antes do CTA.

3. ORGULHO ANTECIPADO — "vou criar algo com as próprias mãos" [SUBEXPLORADA]
   Evidência: "olha pra peça que criou e sente um orgulho que nenhum salário deu"
   Status: frase existe na LP, enterrada. Nunca usada em criativo.
   Instrução: É o resultado identitário mais diferenciado da oferta — usar como
              elemento de fechamento em criativos de produto físico.

4. RAIVA CONTIDA — contra a dependência financeira atual [NÃO EXPLORADA]
   Evidência implícita: "sem pedir, sem depender de marido, de chefe, de ninguém"
   Status: nenhum criativo ativa raiva como motor de clique.
   Instrução: Testar criativo que nomeia a raiva sem dramatizar:
              "Você merece ter uma renda que é sua — que não some
               quando te demitem e que não depende de ninguém pra existir."

5. PRAZER SENSORIAL — diferencial único do produto [SUBUTILIZADA]
   Evidência: "em poucos minutos a sua casa inteira está cheirando bem"
              "é a coisa mais relaxante que existe"
   Status: aparece em 1–2 criativos. Nunca como frame central.
   Instrução: Criar 1 criativo inteiro neste frame (ver Arquétipo D na Camada 9).
              É a emoção que diferencia esta oferta de qualquer outra de renda extra.
```

---

### 5B — Jornada Emocional do Criativo Ideal (com timing e critério de corte)

```
[0–2 SEGUNDOS — Parar o scroll]
Objetivo: criar tensão ou curiosidade imediata
Emoção alvo: identificação / surpresa / dor reconhecida
Técnicas validadas:
  → Dor nomeada com precisão ("você trabalha o mês inteiro e não é suficiente")
  → Objeto físico com ROI explícito ("essa peça custou R$4 e eu vendo por R$35")
  → Pergunta sensorial ("você já entrou num ambiente e sentiu aquele cheiro...")
  → Comportamento inesperado ("sabe o que faço quando estou estressada? gesso.")
Critério de corte: se a persona não se reconhece ou não sente curiosidade até 2s → abandona.

[2–8 SEGUNDOS — Criar tensão / a persona pensa "isso é sobre mim"]
Objetivo: aprofundar dor OU mostrar o objeto de desejo
Emoção alvo: tensão + desejo
Técnicas validadas:
  → Nomear a dor com precisão (não generalizar)
  → Mostrar o objeto físico com dado de ROI imediato
  → Revelar o grupo ("outras mulheres como você estão fazendo isso")
Evitar: explicar o produto neste momento — ainda não.

[8–20 SEGUNDOS — Provar que é possível e fácil]
Objetivo: dissolver barreira de identidade antes da barreira de preço
Emoção alvo: esperança específica → "se ela conseguiu, eu consigo"
Técnicas validadas:
  → "comecei do zero, sem saber nada"
  → Analogia da receita de bolo
  → Prova de grupo ("essas mulheres não tinham nada de diferente de você")
Evitar: lista de módulos, detalhes técnicos do curso — quebra o fluxo emocional.

[20–35 SEGUNDOS — Revelar a transformação]
Objetivo: conectar produto a identidade e liberdade, não só a dinheiro
Emoção alvo: alívio + orgulho antecipado
Técnicas validadas:
  → "hoje eu trabalho de casa, no meu tempo, sem pedir licença pra ninguém"
  → "você dorme diferente quando sabe de onde vem o próximo dinheiro"
  → "olha pra peça que criou e sente orgulho que nenhum emprego deu"
Evitar: exagero de resultado sem prova concreta — gera descrença em cold traffic.

[35–45 SEGUNDOS — CTA suave + micro-urgência]
Objetivo: empurrar para o clique sem criar resistência
Emoção alvo: decisão com segurança / baixo comprometimento
Técnicas validadas:
  → "clica no Saiba Mais que eu te explico tudo"
  → "enquanto o preço de lançamento ainda estiver aqui"
  → "em 2 vendas você já recupera o investimento"
Evitar: CTA de compra direta — persona ainda está em convicção, não em decisão.
```

---

## CAMADA 6 — BANCO DE HOOKS (Organizados por Tipo e Prioridade de Teste)

### 6A — Hooks Tipo P (Dor) — PRIORIDADE MÁXIMA (gap crítico)

```
P1 — Dor de fim de mês [ALTA PRIORIDADE — nunca testado]:
"Você trabalha o mês inteiro, dá duro, não para um segundo —
 e quando chega no dia 30, ainda não é suficiente.
 Existe uma saída — e começa com 2 horas por dia."

P2 — Culpa de tempo desperdiçado:
"A culpa de ter tempo em casa e não transformar em dinheiro é real.
 Eu sei porque eu senti também."

P3 — Paralisia de não saber começar:
"Você quer ter uma renda própria, mas toda vez que pensa em começar, trava.
 Vou te mostrar por onde começar."

P4 — Raiva contida [testar com cuidado]:
"Você merece ter uma renda que é sua — que não some quando te demitem
 e que não depende de ninguém pra existir."
```

### 6B — Hooks Tipo R (Resultado)

```
R1 — Variação validada com dado de velocidade:
"Essa peça custou R$4 de material. Eu vendo ela por R$35.
 E faço em 20 minutos dentro de casa."

R2 — Âncora de resultado de primeiro mês:
"No meu primeiro mês, fiz R$380 vendendo pelo WhatsApp.
 Não sabia nada de artesanato 60 dias antes."
[NOTA: usar número real das alunas — não fictício]

R3 — Resultado emocional, não financeiro:
"Pela primeira vez em anos, cheguei no dia 30 sem aquela angústia.
 Não foi o emprego que mudou — foi essa atividade."

R4 — Payback do curso como gancho:
"Em 2 vendas eu já paguei o curso. A partir daí, cada peça é lucro puro."
```

### 6C — Hooks Tipo S (Sensorial — diferencial máximo de feed)

```
S1 — Cheiro como porta de entrada:
"Você já entrou numa casa e não quis mais sair por causa do cheiro?
 Vou te mostrar como transformar isso em renda."

S2 — Processo manual como sensação:
"Sabe aquela sensação de fazer algo com as próprias mãos e se sentir produtiva?
 Agora imagina ganhar dinheiro com isso."

S3 — Terapia + renda [diferencial único]:
"Achei uma atividade que me acalma quando estou estressada
 e ainda coloca dinheiro no meu bolso. Deixa eu te mostrar."
```

### 6D — Hooks Tipo E (Espelho de fracasso + virada) — ARQUÉTIPO NÃO TESTADO

```
E1 — Tentativas anteriores fracassadas:
"Tentei tudo para ter uma renda extra. Revenda, delivery, confeitaria.
 Nunca deu certo. Até que encontrei isso."

E2 — Identidade bloqueada:
"Eu tinha certeza que não tinha jeito pra artesanato.
 Hoje tenho pedidos chegando toda semana."

E3 — Medo de tentar + ação mesmo assim:
"Eu ficava travada na mesma pergunta: 'e se não funcionar pra mim?'
 Aí eu fiz mesmo com medo. E funcionou."

E4 — Resistência familiar:
"Meu marido achou besteira. Não disse nada.
 Fiz. Vendi. Mostrei o pagamento.
 Agora ele pede pra eu fazer mais."
[NOTA: executar com cuidado — não fazer o marido de vilão, fazer o resultado como resposta]
```

### 6E — Hooks Tipo T (Terapia / Padrão Interrompido)

```
T1 — Validado (replicar com variações):
"Sabe o que eu faço quando estou estressada? Eu vou lá e faço gesso."

T2 — Variação com especificidade sensorial:
"Passei a fazer gesso pra me acalmar. Escolho a essência, misturo a massa —
 em 15 minutos a casa está cheirando bem e eu já esqueci o que me preocupava.
 Só que descobri que ainda ganhava dinheiro com isso."

T3 — Resultado duplo explícito:
"Descobri que minha terapia favorita também paga as contas."
```

---

## CAMADA 7 — PERFIL COMPORTAMENTAL DA PERSONA

```
COMO ELA CONSOME CONTEÚDO
→ Celular, Instagram ou TikTok, provavelmente em momentos de pausa (almoço, antes de dormir)
→ Primeiros 2 segundos são decisivos — o que aparece antes do corte de scroll é tudo
→ Escaneia textos longos — títulos, subtítulos e primeiras frases precisam funcionar sozinhos
→ Credibilidade via identificação: "é igual a mim" > "especialista distante"
→ Não compra de quem parece distante, rico ou técnico — compra de quem passou pelo mesmo

COMO ELA TOMA DECISÕES
→ Emoção abre a porta, lógica fecha a compra — não inverter a ordem
→ A primeira barreira a dissolver é IDENTIDADE ("não é pra mim"), não preço
→ Preço de R$37,60 está dentro do limiar de impulso — é decisão emocional, não racional
→ A garantia de 7 dias remove o risco residual — mencionar próximo ao preço, não antes

TENTATIVAS ANTERIORES INFERIDAS (confiança MÉDIA)
→ Já tentou tutoriais gratuitos no YouTube e não teve resultado estruturado
→ Pode ter tentado revenda, confeitaria, ou cuidado de idosos sem sucesso sustentado
→ Já cogitou artesanato mas travou antes de começar

GATILHO DE PARADA DE SCROLL (em ordem de potencial)
1. Dor nomeada com precisão (hook P) — mais eficaz em cold traffic, gap atual
2. Objeto físico com ROI imediato (hook R) — validado, replicar
3. Sensorial inesperado (hook S ou T) — diferenciação máxima de feed
4. Revelação social (hook E) — funciona, mas "milhares" precisa de número concreto

GATILHOS DE DECISÃO NA LP
→ Âncora de preço: R$89,90 → R$37,60 (58% de desconto) — funcional
→ Remoção de risco: garantia 7 dias, "o risco é todo meu" — funcional
→ Urgência: "vai subir sem aviso" — FRACA sem timer visual
→ Prova social: "centenas de mulheres" — VAGA, substituir por número real
→ Payback: ausente — inserir antes do botão
```

---

## CAMADA 8 — MAPA DE OBJEÇÕES E ROTEIROS DE DISSOLUÇÃO

> **v2 — nova camada.** Objeções identificadas nos materiais com script de dissolução pronto para uso em criativos e LP.

```
OBJEÇÃO #1 — "Não tenho jeito / não tenho talento" [FREQUÊNCIA: MÁXIMA]
Dissolução imediata:
  "Se você consegue seguir uma receita de bolo, você consegue fazer isso.
   Não é talento — é método."
Dissolução por prova social:
  "Essas mulheres não tinham nada de diferente de você.
   Elas simplesmente seguiram o passo a passo."
Dissolução por âncora de barreira mínima:
  "O método começa do zero absoluto — sem pressupor que você sabe qualquer coisa."

OBJEÇÃO #2 — "E se não funcionar pra mim?" [FREQUÊNCIA: ALTA]
Dissolução por garantia:
  "Se em 7 dias você não gostar por qualquer motivo — ou nenhum — eu devolvo 100%.
   Sem perguntas. O risco é meu, não seu."
Dissolução por prova de grupo:
  "[número real] mulheres já aprenderam a técnica. A maioria delas dizia
   a mesma coisa antes de começar."

OBJEÇÃO #3 — "Não tenho dinheiro pra investir agora" [FREQUÊNCIA: ALTA]
Dissolução por payback:
  "Em 2 vendas você já recuperou o investimento inteiro.
   Com R$20 de material, você faz peças que vendem por R$30, R$40.
   A partir daí, o curso já está pago."
Dissolução por comparação implícita:
  "O curso custa menos do que um jantar fora. E continua gerando renda
   meses depois que você pagou."

OBJEÇÃO #4 — "Não tenho tempo" [FREQUÊNCIA: MÉDIA]
Dissolução por premissa de entrada:
  "2 horas livres por dia. É tudo que você precisa.
   De manhã, à noite, no fim de semana — você decide."
Dissolução por acesso vitalício:
  "O acesso não tem prazo. Você não precisa terminar rápido.
   Entra no seu ritmo, revê quantas vezes quiser."

OBJEÇÃO #5 — "Não sei se vou conseguir vender" [FREQUÊNCIA: MÉDIA]
Dissolução por canal específico:
  "Os pedidos chegam pelo WhatsApp. Você não precisa montar loja,
   não precisa de CNPJ, não precisa de delivery. Só do produto e do celular."
Dissolução por demanda de mercado:
  "Difusores de gesso perfumado têm demanda que as artesãs não conseguem atender.
   O problema não é vender — é produzir o suficiente."

OBJEÇÃO #6 — "Meu marido / família não vai apoiar" [FREQUÊNCIA: BAIXA — mas bloqueante]
Dissolução por resultado como resposta:
  "Você não precisa pedir permissão pra começar.
   Você começa, vende, mostra o dinheiro entrando.
   O resultado fala por si."
Dissolução por baixo risco de entrada:
  "O investimento é de R$37,60. Se não funcionar, você pede de volta em 7 dias.
   Não tem o que explicar antes de tentar."
```

---

## CAMADA 9 — SEGMENTAÇÃO POR SUBTIPO DE AVATAR

> **v2 — nova camada.** Cada subtipo tem um hook dominante, um medo primário e um arquétipo de criativo ideal.

```
SUBTIPO A — "A Sobrecarregada" (empregada + mãe + dupla jornada)
Medo primário:    Não ter tempo / ser mais uma despesa sem retorno
Desejo primário:  Renda que entra SEM sair de casa SEM chefe
Hook ideal:       Tipo P ("você trabalha o mês inteiro e no dia 30...")
                  ou Tipo T ("sabe o que faço quando estou estressada?")
Arquétipo ideal:  Produto → Liberdade (GL-04 / GL-05)
Dissolução chave: "2 horas por dia. No seu horário. Acesso vitalício."
Tom:              Empático + aliviado — ela está cansada de ser cobrada

SUBTIPO B — "A Que Já Tentou" (renda extra tentada, não funcionou)
Medo primário:    Ser mais uma que tentou e falhou / vergonha de tentar de novo
Desejo primário:  Validação de que desta vez vai ser diferente
Hook ideal:       Tipo E ("tentei tudo — revenda, delivery, confeitaria — até encontrar isso")
Arquétipo ideal:  Quase-fracasso + vilão (Arquétipo C — não testado ainda)
Dissolução chave: Vilão nomeado ("sem método certo, qualquer tentativa falha")
                  + pivô de decisão ("desta vez é diferente porque...")
Tom:              Espelho de experiência — "ela passou pelo mesmo que eu passei"

SUBTIPO C — "A Dependente" (dona de casa sem renda própria)
Medo primário:    Dependência de marido + vergonha de não contribuir financeiramente
Desejo primário:  Ter O SEU dinheiro — não a renda, a autonomia
Hook ideal:       Tipo P (dor de dependência) ou Tipo E (resistência familiar)
Arquétipo ideal:  Revelação Social + Identidade
Dissolução chave: "você não precisa pedir permissão pra começar"
Tom:              Encorajador + identitário — "você merece ter o seu"

SUBTIPO D — "A Exausta" (qualquer ocupação — está no limite emocional)
Medo primário:    Mais uma obrigação / mais uma coisa pra dar errado
Desejo primário:  Uma atividade que descanse, não que cobre
Hook ideal:       Tipo T ("achei uma atividade que me acalma E ainda paga as contas")
                  ou Tipo S (sensorial — ativa sensação antes de argumento)
Arquétipo ideal:  Terapia + Renda (GL-01 — único representante)
Dissolução chave: Prazer sensorial do processo ANTES do argumento financeiro
Tom:              Suave + sensorial + sem pressão — "não é mais uma obrigação"
```

---

## CAMADA 10 — ANÁLISE DE POSIÇÃO NO FUNIL

```
TOPO — Criativos em vídeo (tráfego frio — Meta Ads)
Nível de consciência: 2–3
Objetivo: Parar scroll → criar identificação → CTA de Saiba Mais
Subtipos a capturar: A, B, C, D (via arquétipos distintos)
Frases-chave: dor cotidiana, objeto físico + ROI, "não precisa de experiência"
Tom: pessoal, coloquial, igual a ela — não superior, não técnico
Temperatura: FRIA a MORNA
Gap atual: nenhum criativo cobre subtipo B (a que já tentou) — criar Arquétipo C

MEIO — Landing page
Nível de consciência: 3–4
Objetivo: Dissolver objeções → construir confiança → empurrar para oferta
Frases-chave: módulos, prova social (precisam de melhoria), história da Mari, ROI
Tom: empático + didático + aspiracional
Gap atual: sem prova social com rosto e número real, sem timer de urgência

FUNDO — Oferta + CTA final
Nível de consciência: 1–2 (consciente do produto, avaliando risco)
Objetivo: Fechar → remover risco → criar urgência real
Frases-chave: R$37,60, garantia 7 dias, acesso imediato, payback explícito
Tom: direto + seguro + urgente
Gap atual: sem timer visual, sem cálculo de payback antes do botão
```

---

## CAMADA 11 — NÍVEL DE CONFIANÇA DA EVIDÊNCIA

```
ALTA CONFIANÇA (múltiplas fontes — usar com segurança em qualquer criativo):
  — Gênero feminino
  — Dupla jornada (emprego/casa + filhos)
  — Renda limitada / sensível a preço
  — Barreira de identidade ("não é pra mim") como objeção #1
  — ROI de material como argumento de viabilidade
  — Desejo de renda própria / independência financeira
  — "Trabalhar em casa no próprio horário" como benefício central
  — CTA suave adequado para cold traffic
  — Analogia da receita de bolo como melhor dissolução de identidade disponível

MÉDIA CONFIANÇA (fonte única ou inferência lógica — testar antes de usar como base):
  — Frame de "terapia + renda" como diferencial único
  — Resistência familiar (marido) como barreira latente
  — Tentativas anteriores com outras formas de renda extra
  — Faixa etária 25–50 anos

BAIXA CONFIANÇA / INFERIDO (não usar sem coleta de dados própria):
  — Estado civil específico
  — Canal de venda preferido pela persona
  — Experiência com e-commerce ou redes sociais
  — Motivação religiosa ou cultural por tipo de peça
  — Plataforma de vídeo principal de consumo

SEM EVIDÊNCIA — LACUNAS DE DADOS (resolver antes de escalar):
  — Resultado financeiro médio das alunas (número real para substituir "centenas")
  — Volume total de alunas verificado
  — Faixa etária real (validar com Gerenciador de Anúncios)
  — Print de WhatsApp com pedido real (para o gap de prova de canal de venda)
  — Depoimentos com nome + cidade + resultado (prioridade máxima de coleta)
```

---

## TOP 15 FRASES VOC (para uso verbatim — organizadas por posição no criativo)

```
HOOKS (abertura — usar para parar o scroll):
1. "Você trabalha o mês inteiro, dá duro — e quando chega no dia 30, ainda não é suficiente."
2. "Sabe o que eu faço quando estou estressada? Eu vou lá e faço gesso."
3. "Tentei revenda, delivery, confeitaria. Nunca deu certo. Até encontrar isso."
4. "A culpa de ter tempo em casa e não transformar em dinheiro é real."
5. "Eu tinha certeza que artesanato não era pra mim. Hoje tenho pedidos toda semana."

BODY (meio — criar conexão e provar viabilidade):
6. "Por onde eu começo? E se não funcionar pra mim? E se eu não tiver jeito?" (espelhar a dúvida)
7. "Uma peça que você produz com menos de R$5 pode ser vendida por R$35, R$50, R$80."
8. "Se consegue seguir uma receita de bolo, consegue fazer isso." (melhor analogia disponível)
9. "Eu comecei do zero, sem saber nada de gesso."
10. "Em 2 vendas você já pagou o curso — a partir daí, é tudo seu." (inserir nos criativos)

FECHAMENTO (resultado emocional — antes do CTA):
11. "Você dorme diferente quando sabe de onde vem o próximo dinheiro." (subexplorada)
12. "Você olha pra peça que criou com as próprias mãos e sente um orgulho
     que nenhum salário de emprego nunca deu."
13. "Sem depender de marido, de chefe, de ninguém."
14. "Quando minha primeira cliente transferiu R$120, entendi: isso era liberdade."

CTA (fechamento — empurrar para ação):
15. "A mudança acontece no dia em que você decide que é agora — não 'um dia'."
```

---

*Skill v2 gerada com base em análise da landing page completa do Gesso Lucrativo + transcrições de 6 criativos em vídeo.*
*Todas as afirmações de alta confiança estão ancoradas em citações diretas dos materiais.*
*Afirmações de média/baixa confiança e inferências estão explicitamente marcadas.*
*Lacunas identificadas são oportunidades de teste — não são falhas da oferta.*
*Novidades da v2: Painel de Lacunas Críticas movido para o topo, Camada 8 (Mapa de Objeções com dissolução), Camada 9 (Subtipos de Avatar), dores reordenadas por intensidade de conversão, VOC reorganizado por posição no criativo, transições ausentes mapeadas, CTA ausentes classificados por prioridade.*
