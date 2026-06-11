# Miniguia de Estudos com NotebookLM: Inteligência Artificial na Saúde

> **Status do Projeto:** Concluído

## Contexto e Objetivos

Este repositório foi criado como parte de um desafio prático na **DIO (Digital Innovation One)**, focado no uso da Inteligência Artificial como ferramenta de **aprendizagem ativa**. 

O tema escolhido para este caderno temático foi **"O Impacto da Inteligência Artificial no Diagnóstico Médico por Imagem"**. O objetivo principal é entender como algoritmos de Deep Learning estão sendo integrados à radiologia e oncologia, identificando os benefícios clínicos, os desafios éticos e as limitações atuais da tecnologia.

---

## Curadoria de Fontes

Para alimentar o NotebookLM e garantir respostas precisas e embasadas, foram selecionadas as seguintes fontes abertas (artigos científicos e relatórios de mercado):

1. **Artigo 1:** *Deep Learning para Radiologia: Princípios e Aplicações* (Fictício/Exemplo - Substitua pelo seu) - [Link para o PDF/Fonte]
2. **Artigo 2:** *Desafios Éticos da IA na Medicina Diagnóstica* - [Link para o PDF/Fonte]
3. **Relatório 3:** *O Futuro da Saúde Digital e IA (Organização Mundial da Saúde)* - [Link para o PDF/Fonte]

---

## Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Documentar o processo de comunicação com a IA é fundamental para demonstrar o raciocínio técnico. Abaixo estão os testes, erros e acertos durante a interação com o NotebookLM baseado nas fontes fornecidas.

### Prompt Inicial (Genérico)
> **O que perguntei:** *"Me dá um resumo sobre IA na medicina com base nos textos."*
* **Resultado:** A resposta foi muito superficial e misturou IA na administração hospitalar com diagnóstico, fugindo do foco do meu objetivo.

### Prompt Refinado (Estratégico)
> 🤖 **O que perguntei:** *"Com base exclusivamente nos Artigos 1 e 2, crie uma tabela comparativa listando as 3 principais vantagens do Deep Learning na radiologia e as 3 maiores barreiras éticas citadas pelos autores."*
* **Resultado:** Excelente. O NotebookLM restringiu o escopo, trouxe dados cruzados e gerou uma tabela limpa e factual, citando as páginas de referência.

### Cicatrizes e Aprendizados (Troubleshooting)
* **Dificuldade:** O NotebookLM tende a generalizar se o prompt não for restritivo.
* **Solução:** Aprendi que incluir comandos como *"Com base exclusivamente nas fontes fornecidas"* e *"Cite as fontes específicas"* reduz drasticamente as alucinações e foca o modelo no conteúdo que eu upei.

---

## Miniguia de Estudo (Entrega Final)

### Resumo Estruturado: IA no Diagnóstico por Imagem

A Inteligência Artificial, especificamente através de redes neurais convolucionais (CNNs), revolucionou a análise de exames como tomografias, ressonâncias e raios-X. 

* **Alta Precisão:** Modelos de IA conseguem identificar microcalcificações e nódulos em estágios iniciais com precisão comparável (e às vezes superior) à de radiologistas experientes.
* **Triagem Automatizada:** A IA atua como uma "segunda opinião", organizando a fila de exames por gravidade, garantindo que casos urgentes sejam revisados primeiro pelos médicos.
* **O Gargalo:** A eficácia da IA depende de dados de treino rotulados e diversos. Vieses em dados de treinamento podem fazer a IA falhar em subpopulações específicas.

### Glossário de Conceitos-Chave

* **Deep Learning (Aprendizado Profundo):** Subcampo do Machine Learning que utiliza redes neurais artificiais com múltiplas camadas para aprender representações de dados complexos (como imagens médicas).
* **Falso Positivo:** Quando o algoritmo indica a presença de uma patologia que, na realidade, o paciente não possui.
* **Viés de Dados (Data Bias):** Distorção nos resultados do modelo causada por dados de treinamento que não representam fielmente a realidade da população global.

---

## Prompts Reutilizáveis para Revisão Future

Guarde estes prompts para revisar este tema ou aplicar em novos cadernos de estudo no NotebookLM:

```text
1. "A partir dos documentos fornecidos, crie um questionário de 5 perguntas de múltipla escolha com gabarito comentado para testar meu conhecimento sobre [TEMA]."
