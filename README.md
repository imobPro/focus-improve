# focus-improve

# Foco e Concentração em tempos atuais

> Caderno temático construído com **Google NotebookLM** como parte de um desafio prático de curadoria de fontes, engenharia de prompts e consolidação de conhecimento.

![Tema](https://img.shields.io/badge/Tema-Foco%20e%20Concentra%C3%A7%C3%A3o-blue)
![Ferramenta](https://img.shields.io/badge/Ferramenta-NotebookLM-orange)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![Fontes](https://img.shields.io/badge/Fontes%20consolidadas-45-informational)

[https://notebooklm.google.com/notebook/03c97319-6e83-4196-9844-532d58aacf13](https://notebooklm.google.com/notebook/03c97319-6e83-4196-9844-532d58aacf13)

---

## Sumário

1. [Contexto e Objetivos](#-1-contexto-e-objetivos)
2. [Curadoria de Fontes](#-2-curadoria-de-fontes)
3. [Engenharia de Prompts e "Cicatrizes"](#-3-engenharia-de-prompts-e-cicatrizes)
4. [Miniguia de Estudo (Entrega Final)](#-4-miniguia-de-estudo-entrega-final)
   - [4.1 Resumos estruturados](#41-resumos-estruturados)
   - [4.2 Glossário](#42-glossário-de-conceitos)
   - [4.3 Prompts reutilizáveis](#43-biblioteca-de-prompts-reutilizáveis)
5. [Como este caderno foi construído](#-5-como-este-caderno-foi-construído-fluxo-no-notebooklm)
6. [Estrutura do repositório](#-6-estrutura-do-repositório)
7. [Autor](#-7-autor)

---

## 1. Contexto e Objetivos

### Por que este tema?

Há muito tempo eu me perguntava como concluir estudos e tarefas com mais consistência, estimar o que é possível fazer em um período e, principalmente, como **tratar o desvio de foco**. Aproveitei este desafio para transformar uma dúvida pessoal em um estudo estruturado — usando ferramentas de IA para organizar o conhecimento de forma prática.

> *Observação honesta registrada durante o processo:* até para descrever e salvar os caminhos que segui durante a pesquisa foi difícil manter o foco. Ou seja, o próprio tema se manifestou na prática enquanto eu o estudava.

### Objetivos de estudo

- [x] Entender o que a ciência **realmente** diz sobre "redução da capacidade de atenção" (separando fato de mito).
- [x] Mapear as **técnicas** mais eficazes para manter o foco e reduzir distrações.
- [x] Levantar o papel da **alimentação, sono e ambiente** na concentração.
- [x] Construir uma **rotina prática** e replicável.
- [x] Consolidar tudo em um material reutilizável para revisões futuras.

---

## 2. Curadoria de Fontes

Foram selecionadas fontes abertas em texto, vídeo e artigo acadêmico. A meta inicial eram 5 fontes principais; algumas não puderam ser anexadas diretamente no NotebookLM por restrições de acesso (ver seção de [Cicatrizes](#-3-engenharia-de-prompts-e-cicatrizes)). Para compensar, usei o recurso **"Descobrir fontes na web"** do NotebookLM, chegando a um total de **45 fontes consolidadas**.

| # | Fonte | Tipo | Foco do conteúdo |
|---|-------|------|------------------|
| 1 | [Harvard Health — Concentration / Focus](https://www.health.harvard.edu/topics/concentration-focus) | Artigo (saúde) | Base médica sobre concentração |
| 2 | [National Geographic — Attention spans shrinking, how to regain](https://www.nationalgeographic.com/health/article/attention-spans-shrinking-how-to-regain) | Reportagem | Como recuperar a atenção |
| 3 | [The Guardian — Attention span, focus, screens & social media](https://www.theguardian.com/science/2022/jan/02/attention-span-focus-screens-apps-smartphones-social-media) | Reportagem | Impacto das telas e redes sociais |
| 4 | [YouTube — Vídeo de apoio](https://www.youtube.com/watch?v=SkzjB8AbcJI) | Vídeo | Conteúdo audiovisual sobre foco |
| 5 | [ResearchGate — Focusing attention in working & long-term memory](https://www.researchgate.net/publication/370929440_Focusing_attention_in_human_working_memory_and_long-term_memory_benefits_through_dissociable_processes) | Artigo acadêmico | Memória de trabalho × longo prazo |
| 6 | [BBC Worklife — Surprising tricks to help you focus at work](https://www.bbc.com/worklife/article/20170925-the-surprising-tricks-to-help-you-focus-at-work) | Reportagem | Técnicas práticas no trabalho |

> As 45 fontes finais do notebook ampliam estas seis fontes-âncora com material complementar obtido via busca na web dentro do próprio NotebookLM.

---

## 3. Engenharia de Prompts e "Cicatrizes"

Esta seção documenta o **raciocínio** por trás do uso da IA — as perguntas estratégicas, as variações testadas e, principalmente, as dificuldades reais (o que o mercado chama de *troubleshooting*).

### Prompt #1 — Teste na aba "Conversa"

```text
Eu gostaria de fazer um mapa mental demonstrando uma rotina perfeita
de técnicas e alimentação que me garantem melhora no foco, sem distrações.
```

**Resposta obtida:** um texto bem estruturado com as "dicas" organizadas em tópicos.

**Cicatriz registrada:** a própria IA avisou que *tentou gerar um infográfico visual, mas a ferramenta não estava disponível no momento* — sugerindo que o texto já trazia a estrutura lógica para montar o mapa manualmente. Conclusão do teste: **a aba "Conversa" entrega ótimo conteúdo textual, mas não é a via para gerar artefatos visuais.**

### Prompt #2 — Migração para a aba "Estúdio"

Diante da limitação acima, levei a mesma intenção para a aba **Estúdio**.

```text
Crie um mapa mental visual destrinchando os principais tópicos sobre
foco e concentração, organizados por técnicas, alimentação, ambiente
e armadilhas digitais, com base nas fontes do notebook.
```

**Resultado:** muito satisfatório. O NotebookLM destrinchou graficamente os tópicos considerando as 45 fontes consolidadas — exatamente o artefato visual que a aba "Conversa" não conseguiu gerar.

### Cicatrizes (dificuldades e soluções)

| Dificuldade encontrada | Causa | Solução aplicada |
|------------------------|-------|------------------|
| Algumas fontes não podiam ser anexadas | Bloqueio/restrição de acesso da página | Usei o recurso **"Descobrir fontes na web"** para ampliar a base sem depender só dos uploads |
| Aba "Conversa" não gerou infográfico | Recurso visual indisponível nessa aba | Migrei a tarefa para a aba **Estúdio** |
| Dificuldade de manter o foco até para documentar o processo | O próprio tema do estudo (ironia útil!) | Apliquei *time-blocking* + sessões curtas para registrar os passos |

> **Lição de ouro:** documentar o *caminho* (e não só o resultado) é o que diferencia um trabalho técnico maduro. As "cicatrizes" mostram o raciocínio — e é isso que o mercado valoriza.

---

## 4. Miniguia de Estudo (Entrega Final)

### 4.1 Resumos estruturados

#### Mito vs. Ciência: o caso do "peixe dourado"

Uma das descobertas mais importantes deste estudo foi **separar dado real de mito viral**:

- **Mito:** "o ser humano tem 8 segundos de atenção — menos que um peixe dourado (9s)." Essa estatística virou febre em 2015 atribuída a um relatório da Microsoft Canadá, mas o número **nunca apareceu na pesquisa real da Microsoft** — ele veio de uma fonte de marketing (Statistic Brain) sem base científica verificável. Investigações posteriores (BBC, 2017) desmontaram a alegação. Além disso, peixes dourados têm memória e atenção bem mais longas do que o mito sugere.
- **Dado real:** a pesquisadora **Gloria Mark** (UC Irvine), ao longo de quase duas décadas, mediu objetivamente o tempo médio de atenção em telas: caiu de **~2,5 minutos (150s) em 2004** para cerca de **47 segundos** nos últimos anos (mediana de 40s). Esse dado vem de *logging* objetivo de comportamento, não de marketing.

**Conclusão prática:** nossa atenção não está "biologicamente quebrada". O que mudou é o **padrão de troca de tarefas** induzido pelas telas. A capacidade de foco profundo continua intacta — basta criar as condições certas.

#### Os tipos de atenção

"Atenção" não é uma coisa só. Entender os tipos ajuda a atacar o problema certo:

| Tipo | O que é | Quando falha |
|------|---------|--------------|
| **Seletiva** | Focar no relevante e ignorar distrações | Sobrecarga de estímulos |
| **Sustentada** | Manter o foco por longos períodos | Tarefas longas e monótonas |
| **Alternada** | Trocar entre tarefas de forma controlada | Notificações constantes |
| **Dividida** | Multitarefa real | Quase sempre piora o desempenho |

#### Técnicas de foco que funcionam

- **Monotarefa (single-tasking):** fazer **uma coisa de cada vez**. A multitarefa aumenta erros e o tempo total das tarefas.
- **Pomodoro:** blocos de ~25 min de foco + pausas curtas. Ótimo para tarefas que exigem "aquecimento".
- **Time-blocking:** reservar blocos de agenda para tipos específicos de trabalho.
- **Trabalho profundo (Deep Work):** sessões longas e protegidas para o trabalho cognitivamente exigente. É após ~47s de imersão que o cérebro começa a "cavar fundo".
- **Higiene de notificações:** silenciar alertas, modo "não perturbe", apps fora da vista.
- **Design do ambiente:** mesa limpa, celular em outro cômodo, fones com ruído branco se ajudar.
- **Estado de fluxo (flow):** equilíbrio entre desafio e habilidade — onde o foco vira prazer.

#### Alimentação, sono e corpo a serviço do foco

- **Hidratação:** desidratação leve já reduz concentração.
- **Glicemia estável:** preferir carboidratos complexos a picos de açúcar (evitar a "montanha-russa" de energia).
- **Proteínas e ômega-3:** suporte à função cognitiva.
- **Cafeína com estratégia:** útil, mas com timing (evitar perto do sono).
- **Sono:** é o multiplicador silencioso — dormir mal sabota qualquer técnica de foco.
- **Movimento:** pausas ativas e exercício melhoram a atenção sustentada.

#### Rotina-modelo (síntese aplicável)

```
MANHÃ   → Tarefa mais difícil em bloco de Deep Work (sem notificações)
          + água + café estratégico
MEIO    → Pomodoros para tarefas operacionais + pausas ativas
TARDE   → Time-blocking para reuniões/respostas; agrupar comunicações
NOITE   → Higiene digital (telas longe) + sono regular
SEMPRE  → Uma tarefa por vez. O ambiente decide metade do foco.
```

---

### 4.2 Glossário de conceitos

| Termo | Definição |
|-------|-----------|
| **Atenção seletiva** | Capacidade de focar no que importa e filtrar distrações. |
| **Atenção sustentada** | Manter o foco em uma tarefa por um período prolongado. |
| **Atenção alternada** | Alternar o foco entre tarefas de forma controlada. |
| **Fragmentação da atenção** | Troca constante e involuntária entre tarefas, abas e ferramentas. |
| **Resíduo atencional (*attention residue*)** | Parte da mente que "fica" na tarefa anterior após uma troca, reduzindo o desempenho na nova. |
| **Troca de tarefas (*task-switching*)** | Alternar entre atividades; aumenta erros e o tempo total de execução. |
| **Multitarefa** | Tentar fazer várias coisas ao mesmo tempo; na prática, quase sempre piora o resultado. |
| **Monotarefa** | Fazer uma única coisa por vez — base do foco produtivo. |
| **Deep Work (Trabalho Profundo)** | Sessões longas e protegidas dedicadas a tarefas cognitivamente exigentes. |
| **Estado de fluxo (*flow*)** | Imersão total em uma atividade, no equilíbrio entre desafio e habilidade. |
| **Pomodoro** | Técnica de blocos de foco (~25 min) intercalados com pausas curtas. |
| **Time-blocking** | Reservar blocos de agenda para tipos específicos de trabalho. |
| **Sobrecarga cognitiva** | Excesso de informação/estímulos que esgota a capacidade de processar. |
| **Mito do peixe dourado** | Alegação popular (e falsa) de que humanos têm 8s de atenção, menos que um peixe. |
| **Higiene digital** | Conjunto de hábitos para reduzir a interferência das telas e notificações. |

---

### 4.3 Biblioteca de prompts reutilizáveis

Prompts testados e prontos para **revisões futuras** no NotebookLM (ou em qualquer IA de estudo). Basta copiar e ajustar o `[tema]`.

** Resumo e estrutura**
```text
Resuma as fontes deste notebook em até 10 tópicos, organizados por:
conceito, evidência e aplicação prática. Sinalize quando houver
divergência entre as fontes.
```

** Mapa mental (aba Estúdio)**
```text
Gere um mapa mental visual sobre [tema], ramificando em: definições,
técnicas, fatores físicos (sono/alimentação) e armadilhas a evitar.
```

** Checagem de mito (senso crítico)**
```text
Há alguma afirmação popular sobre [tema] que as fontes deste notebook
contradizem ou não sustentam? Liste o mito, a origem e o que a evidência
realmente diz.
```

** Cartões didáticos (flashcards)**
```text
Crie 15 flashcards de pergunta e resposta sobre [tema], do básico ao
avançado, baseados apenas nas fontes deste notebook.
```

** Teste / quiz**
```text
Monte um quiz de 10 questões de múltipla escolha sobre [tema], com
gabarito e uma explicação curta para cada resposta correta.
```

** Podcast / áudio (aba Estúdio)**
```text
Gere um resumo em áudio focado especificamente em [subtema], direcionando
a conversa para esse ponto e ignorando o restante.
```

** Tabela comparativa para exportar**
```text
Crie uma tabela comparando [opção A] e [opção B] segundo as fontes,
com colunas: critério, evidência e recomendação. Formato pronto para
exportar.
```

** Revisão futura**
```text
Considerando tudo que estudei sobre [tema], me faça 5 perguntas de
revisão ativa para testar se ainda domino o conteúdo.
```

---

##  5. Como este caderno foi construído (fluxo no NotebookLM)

```
1. Curadoria → seleção das fontes-âncora (texto, vídeo, artigo)
2. Upload     → envio ao NotebookLM (+ "Descobrir fontes na web" → 45 fontes)
3. Conversa   → testes de prompt; ótimo para texto, sem geração visual
4. Estúdio    → mapa mental, relatórios e tabelas exportáveis
              → podcast/áudio para direcionar subtemas
              → flashcards e quizzes para fixação
5. Consolidação → este README como entrega final
```

**Recursos do NotebookLM mais úteis para estudo, na prática:**
- **Estúdio → Mapa mental:** melhor recurso para visão geral visual do tema.
- **Relatórios e tabelas:** ótimos para exportar e agregar a estudos externos.
- **Podcast/áudio:** direciona o foco para um subtema específico rapidamente.
- **Cartões didáticos e testes:** fixação prática e gerada com rapidez sobre as fontes.

---

## 6. Estrutura do repositório

Sugestão de organização (opcional — você pode manter tudo só no README):

```
miniguia-estudos-notebooklm/
├── README.md              ← este arquivo (entrega final)
├── /fontes                ← PDFs/links salvos das fontes
│   └── anotacoes.txt      ← suas anotações originais do processo
├── /prints                ← capturas do mapa mental, flashcards etc.
│   └── mapa-mental.png
└── /exports               ← relatórios/tabelas exportados do NotebookLM
```

---

## 7. Autor

**Eu, Arthur** — Niterói, Rio de Janeiro 🇧🇷

Caderno temático desenvolvido como desafio prático de estudo com IA.
Os prompts que eu utilizei estão diponíveis, você pode utilizar se quiser. Parte deles eu usei outra IA para compor.

---

#*Material educativo. As fontes citadas pertencem aos seus respectivos autores e veículos.*#
