# Miniguia de Estudos: Metodologia de Investimentos de Benjamin Graham (NotebookLM)

Repositório desenvolvido como parte do projeto prático do bootcamp de IA do Bradesco em parceria com a **DIO**, explorando o uso da Inteligência Artificial como ferramenta de aprendizagem ativa e curadoria de conhecimento.

---

## 🎯 Contexto e Objetivos

* **Assunto Escolhido:** O "Segundo Cérebro" focado nos ensinamentos clássicos de Benjamin Graham, considerado o pai do investimento em valor (*Value Investing*).
* **Objetivos de Estudo:**
  * Compreender os pilares da análise fundamentalista e da seleção de ações de valor propostos por Graham.
  * Utilizar o **NotebookLM** para centralizar conteúdos multimídia (vídeos e artigos técnicos) e extrair resumos estruturados.
  * Desenvolver competências de engenharia de prompt para guiar a IA na síntese de conceitos financeiros complexos.

---

## 📚 Curadoria de Fontes

Para alimentar o caderno temático no NotebookLM, foram selecionadas fontes abertas divididas entre videoaulas e artigos especializados:

### Fontes de Vídeo (YouTube)
* [Vídeo 1](https://www.youtube.com/watch?v=aQQZKn03EJY)
* [Vídeo 2](https://www.youtube.com/watch?v=9fZ3H1yHb_E)
* [Vídeo 3](https://www.youtube.com/watch?v=ZxYEKaAeBew)
* [Vídeo 4](https://www.youtube.com/watch?v=fMo_xntieUo)
* [Vídeo 5](https://www.youtube.com/watch?v=cWNqf1gifR8)
* [Vídeo 6](https://www.youtube.com/watch?v=T2kL3ejVGdI)

### Fontes de Texto
* [Investopedia - Benjamin Graham Method](https://www.investopedia.com/terms/b/benjamin-method.asp)
* [Investing Brasil - Fórmula de Benjamin Graham](https://br.investing.com/academy/analysis/formula-benjamin-graham/)

---

## 🧪 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante os testes no NotebookLM, foram aplicadas diferentes técnicas de prompt para avaliar a precisão das respostas:

1. **Prompt de Visão Geral (Zero-shot):**
   * *Comando:* "Explique de forma resumida o conceito central da filosofia de investimentos de Benjamin Graham com base nas fontes."
   * *Desafio / Cicatriz:* Inicialmente, as respostas eram muito genéricas. Foi necessário ajustar o escopo adicionando restrições de tamanho e pedindo foco na distinção entre especulação e investimento.

2. **Prompt de Aplicação Prática (Few-shot):**
   * *Comando:* "Utilizando os parâmetros de margem de segurança apresentados nas fontes, demonstre como avaliar se um ativo está subavaliado."
   * *Resultado:* A IA conseguiu cruzar dados dos artigos e vídeos para detalhar fórmulas clássicas de preço teto.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **Value Investing (Investimento em Valor):** Consiste em comprar ativos por um preço inferior ao seu valor intrínseco. A paciência e a disciplina emocional são os pilares para suportar as flutuações de curto prazo do mercado.
* **Margem de Segurança:** O princípio fundamental de Graham que dita que o investidor só deve comprar ações quando houver uma diferença significativa entre o preço de mercado e o valor real estimado, mitigando riscos de imprevistos.

### 2. Glossário de Conceitos-Chave
* **Valor Intrínseco:** O valor real de uma empresa calculado com base em seus fundamentos financeiros (ativos, lucros, dividendos), independente da cotação atual na bolsa.
* **Mr. Market (Senhor Mercado):** Uma alegoria criada por Benjamin Graham que personifica o mercado financeiro como um parceiro de negócios maníaco-depressivo que todos os dias oferece preços diferentes para comprar ou vender suas ações.
* **Preço Teto:** Limite máximo de preço que se deve pagar por uma ação para garantir uma margem de segurança e um rendimento de dividendos adequado.

### 3. Prompts Reutilizáveis para Futuras Revisões
* *Revisão Rápida:* `"Com base nas fontes do caderno, liste em bullet points os 3 maiores erros que um investidor iniciante comete segundo a ótica de Benjamin Graham."`
* *Fixação de Conceitos:* `"Elabore 3 perguntas discursivas desafiadoras sobre a metáfora do Mr. Market para testar meu conhecimento."`
