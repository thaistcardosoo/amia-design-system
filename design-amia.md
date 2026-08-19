# AMIA — Design System v1

**Academia do Marketing com IA**
*Aprenda a usar IA antes que usar IA vire o mínimo.*

O sistema visual da AMIA: editorial, direto, sem tom de guru. Coral pra ação, preto pra autoridade, branco pra respirar.

Seções: 01 Posição · 02 Cor · 03 Tipografia · 04 Layout · 05 Componentes · 06 Slides · 07 Peças · 08 Ícones · 09 Voz · 10 Kernel IA

---

## 01 — Promessa & posição

### A promessa

> Você entra executando tarefas com IA. Sai desenhando processos de marketing com IA.

Não é escola de ferramenta e não é "300 prompts mágicos". É formação de repertório, processo e aplicação — pra IA virar parte do jeito que você trabalha, não algo que você abre quando está sem ideia.

### A transformação

| Antes | Depois |
| --- | --- |
| "Me dá uma legenda." · "Me dá ideias de post." | "Vamos montar um fluxo de criação de conteúdo." |
| Copia prompt que viu no Instagram. | Cria biblioteca adaptada ao próprio contexto. |
| Pula de ferramenta em ferramenta. | Escolhe ferramenta pelo problema, não pela hype. |
| Depende de inspiração e improviso. | Tem processo que o time consegue seguir. |

### A prova — sai com ativos, não com certificado

- **Sistema rodando** — um fluxo real desenhado, testado e documentado.
- **Playbook interno** — onde usar IA, onde não usar, tom de voz, revisão.
- **Horas devolvidas** — antes × depois em tabela; chefia entende.
- **Portfólio de fluxos** — 3 a 5 aplicações práticas, não exercícios.
- **Apresentação pronta** — "IA no marketing nos próximos 90 dias."
- **Assistentes configurados** — com instruções, base e exemplos de uso.

### O aluno

> "Há um mês atrás eu usava o ChatGPT pra melhorar texto — e achava que estava usando IA."
> — aluna da AMIA

O aluno já usa IA — às vezes mais que qualquer um na empresa. Mas usa no nível mais raso. O que trava é método.

E por baixo tem um medo real: *"se qualquer estagiário com ChatGPT faz um post, o que me torna necessária?"*

- **O inimigo** — curso raso de prompt solto, e o medo de virar dispensável.
- **O Hub está dentro** — Hub de IA = organização e assistentes. AMIA = formação de marketing, e inclui o Hub.
- **Nunca** — prazo prometido (ainda não temos base), renda fácil, tom de guru.

---

## 02 — Cor

### Branco manda. Coral aponta.

Base branca com faixas alternadas em off-white quente. Coral só onde há ação: CTA, setas, números, destaques. Vermelho escuro reservado para urgência real.

| Cor | Hex | Uso |
| --- | --- | --- |
| Branco | `#FFFFFF` | fundo padrão |
| Off-white quente | `#FBFAF7` | faixa alternada |
| Quase-preto | `#0E1420` | texto & bloco forte |
| Coral ★ | `#EF5A3C` | acento & CTA |
| Coral hover | `#D94A2E` | estado hover |
| Urgência | `#D0301A` | escassez, oferta |

### Hierarquia de texto — opacidades sobre `#0E1420`

| Nível | Opacidade |
| --- | --- |
| Título / ênfase | 100% |
| Corpo principal | 85% |
| Prosa longa | 70% |
| Legenda / meta | 60% |
| Desativado | 50% |

Bordas entre seções: `1px rgba(14,20,32,0.06)` (hairline). Cards ativos ganham borda coral 2px.

**Proibido:** verde da marca-mãe, rosa do Segundo Cérebro, lima.

---

## 03 — Tipografia

### Serifa itálica pra emoção. Sans pra clareza.

- **Instrument Serif — títulos.** Sempre itálico. Títulos de seção, hero, frases de respiro. Leading 1.05, tracking tight.
- **DM Sans — corpo · UI.** 400 pra prosa (leading 1.75), 500/600 pra UI e listas, 700 pra ênfase.

### Escala

| Papel | Tamanho | Exemplo |
| --- | --- | --- |
| Hero | 72px | *Método na ordem certa* |
| Seção | 60px | *Como funciona* |
| Eyebrow | 13px | MÓDULO 02 · AO VIVO |
| Prosa | 18px / 1.75 | Texto de leitura em DM Sans 400, container estreito. |
| Contador | — | número em serif itálico + label micro uppercase (ex.: *14* dias) |

Eyebrow: uppercase, 13px, semibold, tracking `0.14em`, em coral.

---

## 04 — Layout & espaço

### Coluna estreita, ritmo de leitura.

**Container**
- Leitura: `max-width` 520–640px, centralizado, padding lateral 24px.
- Grid 2 colunas: imagens, método.
- Grid 3 colunas: prompts, lotes.

**Ritmo vertical**
- Seção: `py` 56px (mobile) / 80px (desktop).
- Separador: hairline `rgba(14,20,32,.06)`.
- Faixas alternadas: branco → off-white → branco.

**Raios:** 12px card · pill botão · 10px chip.

Sem animação acima da dobra. Imagens com dimensão explícita; lazy abaixo da dobra.

---

## 05 — Componentes

### Botões
Primário ("Quero entrar"), secundário, contorno, e link com seta ("Ver o método →").
Pill, altura 52–56px, coral sólido, **sem sombra**.

### Badges & chips
`Turma 03` · `Ao vivo` · `Últimas vagas` · `28 min`
Badge pill, 11px, uppercase, bold.

### Card de preço (ativo)
Cabeçalho "Turma completa" + selo "Popular". Preço `R$ 1.497` ou 12x. Itens com seta coral:
- → 6 módulos + encontros ao vivo
- → Comunidade da turma

Raio 12px. Estado ativo: borda coral 2px + `shadow 0 10px 30px -12px rgba(239,90,60,.35)`.

### Banner de urgência (sticky)
"Turma 03 · inscrições até 12/08" + CTA "Garantir vaga →" + contador `03 dias · 14 horas · 27 min`.

### Item de módulo
Número + título + meta + seta.
- `01` Diagnóstico: onde você perde tempo — 4 aulas · 42 min →
- `02` O acervo que trabalha por você — 5 aulas · 58 min →

### Depoimento & callout
> "Parei de recomeçar do zero toda segunda." — Ana · analista de marketing

**Na prática:** cada aula termina com uma coisa pra aplicar hoje.

---

## 06 — Slides de aula · 1920×1080

### Catorze moldes pras aulas.

Margem 96px, texto nunca abaixo de 28px. Ritmo: capa → agenda → conteúdo → respiro → aplicar hoje.

> Os moldes do arquivo original são proporcionais a 960×540 — metade de 1920×1080 — e escalam com a largura da tela. Pra chegar no tamanho final, **dobre todo valor** (margem 48→96px, corpo 16→32px).

| # | Molde | Conteúdo de exemplo |
| --- | --- | --- |
| 1 | Capa de aula | "Módulo 02 · Aula 03" + título + monograma AMIA |
| 2 | Agenda | "Nesta aula": 01 Por que o prompt bom desaparece · 02 Como nomear pra achar depois · 03 O ritual de 10 minutos |
| 3 | Passo a passo | "3 passos pra montar o acervo" com itens em seta |
| 4 | Respiro / frase | Bloco coral: "Você não precisa de mais uma ferramenta. Precisa de ordem." |
| 5 | Print / prompt | Explicação + print ao lado (contexto / voz / tarefa) |
| 6 | Tarefa / fechamento | "Aplicar hoje" + ação + botão "Fazer agora" |
| 7 | Diagnóstico / tabela | Tarefa × Hoje × Potencial (ex.: calendário editorial, 6h → 2h) |
| 8 | Antes / depois (split) | "Sem processo" × "Com processo" |
| 9 | Erro comum | O erro + seta + a consequência |
| 10 | Checklist | Tem contexto? Soa como a marca? Dá pra reutilizar? O time consegue seguir? |
| 11 | Framework / fluxo | Briefing → Pesquisa → Ângulos → Peça final |
| 12 | Exercício ao vivo | "Exercício ao vivo · 10 min" + instrução |
| 13 | Números / resultado | 6h antes · 2h depois · 4h devolvidas/semana |
| 14 | Transição de módulo | "Fim do módulo 02 — a seguir: …" |

---

## 07 — Outras peças

- **Carrossel · capa** — monograma + frase forte ("Você salva 140 e aplica 5.") + "o problema não é conteúdo →"
- **Carrossel · miolo** — número grande + título + exemplo curto.
- **Certificado** — "Certificado de conclusão", nome do aluno, turma e módulos, assinatura "Thaís Maia · jul 2026".
- **Email da turma** — cabeçalho "AMIA · Turma 03 / Semana 2", chamada do encontro ao vivo, CTA "Entrar na sala", rodapé "Academia do Marketing com IA · uma iniciativa de Thaís Maia".
- **Story · 1080×1920** — frase forte + "arrasta ↑".
- **Card de aula · área de membros** — módulo, título, play, duração, "64% concluído".
- **Workbook · PDF A4** — "Workbook · Módulo 02 / Mapa de oportunidades": tarefa que consome mais tempo · onde a IA pode entrar · impacto estimado · primeiro teste.
- **Depoimento · feed 1:1** — aspas grandes + fala da aluna + nome e turma.
- **Anúncio · feed 1:1** — promessa + subtítulo "Formação prática de marketing com IA" + CTA "Ver a AMIA".
- **Badge de conclusão** — número do módulo + "Módulo 02 concluído / Seu acervo já está rodando."

---

## 08 — Ícones & desenhos

### Um traço só, uma cor só.

Grade 24, traço 1.5 com terminação arredondada, sem preenchimento. Corpo em quase-preto e **um único** detalhe em coral.

Ícones do set: Crescimento · Fluxo · Funil · Assistente · Faturamento · Automação. A biblioteca completa (24 ícones, 6 composições, desenhos e prompt de imagem) vive em *Ícones e Ilustrações*.

Ilustração é composição geométrica (círculo, quadrado, pill, arco) ou objeto do trabalho (tela, pilha, relógio) — traço 2.5, máx. 4 formas, ~30% de espaço vazio. **Nunca** personagem, mascote, robô ou cérebro de circuito.

---

## 09 — Voz

### Quem já viveu a mesma coisa.

**✓ Faça**
- Assuma que a pessoa já usa IA — vá direto ao método.
- Nomeie a dor com as palavras dela ("salvo 140, aplico 5").
- Fale de ordem, sequência, "na ordem certa".
- Termine tudo com uma coisa pra aplicar hoje.
- Coral só onde há ação. Uma cor forte por peça.

**✕ Evite**
- "Aprenda IA do zero", "domine a IA", renda fácil.
- Tom de guru, promessa de transformação mágica.
- Verde da marca-mãe, rosa do Segundo Cérebro, lima.
- Sombra em botão, animação acima da dobra.
- Urgência falsa — vermelho escuro só com prazo real.

---

## 10 — Kernel para IA

### A AMIA em um prompt. Cole antes de pedir qualquer peça desta submarca.

```
SUBMARCA: AMIA — Academia do Marketing com IA, curso + comunidade de Thaís Maia. PT-BR. Assinatura da Thaís discreta só no rodapé.

PROMESSA: você entra executando tarefas com IA e sai desenhando processos de marketing com IA. Não é escola de ferramenta nem "300 prompts mágicos" — é repertório, processo e aplicação. Marketing potencializado por IA, não IA pela IA.

TRANSFORMAÇÃO: de operadora de prompts a arquiteta de processos. Antes: "me dá uma legenda", copia prompt do Instagram, pula de ferramenta. Depois: monta fluxo de conteúdo/campanha, cria biblioteca própria, escolhe ferramenta pelo problema, tem processo que o time segue.

PROVA (usar sempre — é o diferencial): sai com ATIVOS, não certificado. Sistema/fluxo rodando · playbook interno de IA · horas devolvidas (antes × depois) · portfólio de 3–5 fluxos · apresentação "IA no marketing em 90 dias" · assistentes configurados · biblioteca de prompts do próprio contexto.

ALUNO: já usa IA todo dia (não é iniciante, não precisa ser convencido) mas no nível mais raso. Trava no método. Frase real de aluna: "há um mês eu usava o ChatGPT pra melhorar texto e achava que estava usando IA." Medo por baixo: "se um estagiário com ChatGPT faz um post, o que me torna necessária?"

INIMIGO: curso raso que ensina prompt solto + o medo de virar dispensável.

ARQUITETURA: o Hub de IA (Segundo Cérebro) é organização/assistentes no Notion e está DENTRO da AMIA. AMIA é a formação de marketing.

ESTRUTURA: híbrida — conteúdo aberto + encontros ao vivo, organizada em turmas (Turma 03). Fase inicial: NÃO prometer prazo nem número de alunos.

TOM: turma/comunidade + carreira. Como quem viveu a mesma coisa e tem um caminho na ordem certa. PROIBIDO: "aprenda IA do zero", "domine a IA", renda fácil, tom de guru, promessa mágica, prazo inventado.

COR: branco #FFFFFF (fundo) · off-white quente #FBFAF7 (faixa alternada) · quase-preto #0E1420 (texto e bloco forte) · coral #EF5A3C (acento, CTA, setas →, números) · hover #D94A2E · vermelho #D0301A (só urgência com prazo real). Hierarquia por opacidade do #0E1420: 100/85/70/60/50. Bordas hairline rgba(14,20,32,0.06). NADA de verde (marca-mãe), rosa (Segundo Cérebro) ou lima.

TIPOGRAFIA: títulos Instrument Serif SEMPRE itálico (leading 1.05, tracking tight); corpo DM Sans 400 (leading 1.75), UI 500/600; eyebrow uppercase 13px semibold tracking 0.14em em coral; contadores = número em serif itálico + label micro uppercase.

LAYOUT: coluna de leitura 520–640px centralizada, padding lateral 24px. Seções py 56–80px separadas por hairline, faixas alternando branco/off-white. Grid 2 col em imagem/método, 3 col em prompts/lotes.

COMPONENTES: CTA pill h52-56 coral sólido SEM sombra. Card de preço raio 12px, ativo = borda coral 2px + shadow 0 10px 30px -12px rgba(239,90,60,.35). Badge pill 11px uppercase bold. Sem animação acima da dobra.

SLIDE 1920×1080: margem 96px, texto nunca abaixo de 28px. Layouts: capa · agenda · passo a passo · respiro (bloco coral) · print/prompt · aplicar hoje.

ÍCONES: grade 24, traço 1.5 round cap/join, sem preenchimento. Corpo #0E1420 + UM detalhe #EF5A3C. Ilustração = composição geométrica (círculo, quadrado, pill, arco) ou objeto do trabalho (tela, pilha, relógio), traço 2.5, máx. 4 formas, ~30% de espaço vazio. PROIBIDO em arte: pessoas, rostos, mascotes, robôs, cérebro de circuito, néon, gradiente, sombra, 3D/isométrico.

FOTO: overlay gradiente rgba(14,20,32,.1) → .8 de cima pra baixo; luz natural e ambiente real; coral só no texto sobre a foto, nunca como filtro.

ASSINATURA: monograma "a" em serif itálico dentro de quadrado arredondado (preto com "a" coral, ou coral com "a" branca).
```

---

*Academia do Marketing com IA — Design system · v1 · 2026*
