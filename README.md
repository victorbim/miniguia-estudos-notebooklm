# # 📈 Miniguia de Estudos: Teoria de Dow Aplicada à Análise de Mercado com NotebookLM

Repositório criado para o Desafio de Projeto da **DIO (Digital Innovation One)**, com o objetivo de demonstrar o uso da Inteligência Artificial **NotebookLM** como ferramenta de aprendizagem ativa, curadoria de conhecimento e engenharia de prompts.

---

## 🎯 1. Contexto e Objetivos

### 🔍 Contexto
No dinamismo do mercado financeiro, a capacidade de interpretar gráficos e prever tendências é um diferencial estratégico. A **Teoria de Dow**, desenvolvida por Charles Dow, é o pilar fundamental da Análise Técnica moderna. Compreender seus seis princípios básicos (como o movimento do mercado em três tendências, os índices que descontam tudo e o volume que deve confirmar a tendência) é indispensável para qualquer analista ou investidor.

Para este projeto, utilizei o **NotebookLM** do Google como um parceiro de estudos e inteligência de dados, centralizando o ecossistema conceitual da Teoria de Dow em um ambiente fechado e livre de alucinações, otimizando o tempo de consulta e refinamento técnico das análises de mercado.

### 📌 Objetivos de Estudo
* **Dominar os Fundamentos:** Consolidar o entendimento sobre as fases do mercado (Acumulação, Participação Pública e Distribuição) e a relação de médias.
* **Agilidade Analítica:** Utilizar a IA para extrair correlações rápidas entre os conceitos históricos da teoria e cenários gráficos atuais.
* **Mitigação de Alucinações:** Validar o ganho de produtividade ao estudar mercados financeiros utilizando LLMs alimentados exclusivamente por fontes confiáveis e selecionadas.

---

## 📚 2. Curadoria de Fontes
Para garantir a maturidade técnica e o embasamento teórico do caderno interativo, foram selecionadas e carregadas no NotebookLM as seguintes fontes de dados abertas:
.
Gráfico-Bitcoin.pdf (Fontes 8 e 9): Arquivo contendo representações visuais do preço do Bitcoin (BTC/USD) no tempo gráfico diário, exibindo indicadores como médias móveis, volume e Stoch RSI
.
Teoria de Dow – Wikipédia: Verbete enciclopédico que resume a formulação histórica da teoria em 1884 e seus pontos básicos, como o princípio da confirmação
https://pt.wikipedia.org/wiki/Teoria_de_Dow
.
.
Você realmente sabe o que é Teoria de Dow? - André Machado: Vídeo onde o autor discute a aplicação profissional da teoria, o uso de stops técnicos e a utilização de médias móveis como rastreadores de tendência
https://www.youtube.com/watch?v=dy7Pip4c_qM
.
.
the-dow-theory-in-technical-analysis.pdf: Documento em inglês que introduz Charles Dow como o pai da análise técnica ocidental e detalha os seis princípios em um contexto de mercados globais
.
.
Teoria de Dow: saiba o que diz, princípios e como aplicar - CM Capital: Artigo que reforça a importância das três fases da tendência (acumulação, participação e distribuição) e o papel do volume
https://cmcapital.com.br/blog/teoria-de-dow-conceitos-basicos/
---

## 🛠️ 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
O grande valor deste projeto está no refinamento dos comandos para obter respostas analíticas de alta fidelidade. Abaixo estão documentados os testes, iterações e aprendizados do processo.

### 🧠 Prompt 1: Entendimento Conceitual (Abordagem Direta)
* **Prompt Inicial:** `"O que é a Teoria de Dow?"`
* **Resultado:** A IA trouxe uma resposta genérica de dicionário, citando apenas que era a base da análise técnica.
* **Refinamento (Engenharia de Prompt):** `"Com base estritamente nos documentos fornecidos, liste os 6 princípios fundamentais da Teoria de Dow. Formate a resposta em tópicos, destacando em negrito o nome do princípio e fornecendo uma breve explicação prática aplicada a gráficos de ações."`
* **Resultado do Refinamento:** Resposta precisa, estruturada e diretamente conectada às fontes do caderno, ideal para consulta rápida antes de operar no mercado.

### 🩹 Cicatrizes e Dificuldades Encontradas (Troubleshooting)
* **O Desafio do Contexto Temporal:** Ao perguntar sobre a aplicação da Teoria de Dow no preço atual do Bitcoin, a IA indicou corretamente que as fontes fornecidas não continham dados em tempo real (visto que o NotebookLM trabalha com o contexto fechado dos documentos carregados). 
* **Solução:** O prompt foi adaptado para focar na lógica estrutural: *"Como a fase de acumulação da Teoria de Dow explicada no Documento X pode ser identificada visualmente em um ativo de alta volatilidade como as criptomoedas?"*. Isso contornou a falta de dados em tempo real e focou no aprendizado do padrão conceitual.

---

## 🎓 4. Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados do Assunto
A Teoria de Dow baseia-se na premissa de que os preços se movem em tendências previsíveis que refletem toda a psicologia do mercado. 

* **As Três Tendências:** O mercado possui a tendência Primária (longo prazo, a maré), Secundária (médio prazo, as ondas) Terciária (curto prazo, as marolas). Para análises macro, o foco deve estar sempre na tendência primária.
* **As Três Fases da Tendência Primária de Alta:**
  1. *Acumulação:* Investidores institucionais e informados compram o ativo a preços baixos, enquanto o público geral está pessimista.
  2. *Participação Pública (ou Avanço):* O mercado começa a subir rapidamente, os analistas técnicos identificam a tendência e o público geral entra comprando.
  3. *Distribuição:* O topo do mercado. Os investidores astutos que compraram na fase 1 começam a vender suas posições para o público eufórico que está entrando atrasado.

### 📖 Glossário de Conceitos Aprendidos
* **Suporte:** Região de preço onde a força compradora é historicamente maior que a vendedora, interrompendo uma queda.
* **Resistência:** Região de preço onde a força vendedora supera a compradora, impedindo o preço de continuar subindo.
* **Princípio da Confirmação:** Um sinal de alta ou baixa em um índice (ex: Índice Bovespa) deve ser obrigatoriamente confirmado por outro índice correlacionado (ex: Índice de Materiais Básicos ou Small Caps) para validar uma tendência de mercado.
* **O Volume Confirma a Tendência:** Em uma tendência de alta, o volume financeiro deve aumentar nos dias de subida e diminuir nas correções de baixa.

### 🔄 Prompts Reutilizáveis para Revisões Futuras
Copie e cole estes prompts no seu NotebookLM sempre que quiser revisar o material ou aplicar o estudo a novos documentos:

```markdown
1. "Faça um resumo executivo comparando as diferenças comportamentais entre a fase de Acumulação e a fase de Distribuição de acordo com as fontes."
2. "A partir dos textos lidos, crie um questionário de 5 perguntas com respostas (estilo Flashcard) para eu testar meu conhecimento sobre como os índices descontam tudo."
3. "Imagine que sou um trader iniciante. Me explique o conceito de 'o volume deve confirmar a tendência' utilizando uma metáfora simples do dia a dia."
