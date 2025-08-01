#  Representações de Gênero em Letras de Música com Aprendizado de Máquina

Este repositório contém um estudo realizado no contexto do Mestrado em Computação Aplicada (UFMS), que investiga **padrões de representação de gênero** em letras de músicas brasileiras. O projeto aplica **técnicas de aprendizado de máquina não supervisionado** para identificar e analisar temas linguísticos recorrentes atribuídos a homens e mulheres.

## Objetivo

Utilizar algoritmos como **LDA**, **BERTopic** e **KMeans** para agrupar frases extraídas de letras de músicas brasileiras, revelando **estereótipos de gênero** e representações simbólicas associadas a cada grupo.

##  Técnicas utilizadas

### Processamento de Linguagem Natural (PLN)

- Extração e limpeza de frases com o **SpaCy Matcher**
- Geração de **embeddings semânticos** com o modelo [**BERTimbau**](https://huggingface.co/neuralmind/bert-base-portuguese-cased)

### Modelagem de Tópicos

- **LDA** (Latent Dirichlet Allocation)
- **BERTopic**
- **KMeans**

### Visualização

- Redução de dimensionalidade com **UMAP**
- Análise qualitativa dos clusters gerados por cada técnica

---

##  Destaques da Análise

- **10.000 frases analisadas** (5.000 associadas a *female*, 5.000 a *male*)
- Detecção de temas como:
  - **Female**: beleza física, erotização, empoderamento, romantização
  - **Male**: força, dominação, vulnerabilidade emocional, ostentação
- Comparação entre modelos quanto à coerência dos tópicos e sensibilidade ao contexto

---

## Contribuição Científica

Este projeto amplia abordagens anteriores ao aplicar métodos **automatizados e comparativos** de PLN em larga escala, contribuindo para a compreensão das construções linguísticas de gênero na cultura musical brasileira.

