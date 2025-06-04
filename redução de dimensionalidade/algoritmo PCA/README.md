
# Análise PCA para Expansão Global de Franquias

Este projeto aplica a técnica de Análise de Componentes Principais (PCA) para reduzir a complexidade de um conjunto de dados macroeconômicos de diversos países, com o objetivo de apoiar decisões estratégicas de expansão internacional de uma rede de fast-food.

---

## Objetivo

Transformar um conjunto multidimensional de indicadores socioeconômicos em eixos de decisão claros e visuais, permitindo:

- Identificar agrupamentos de países com perfis semelhantes
- Ranquear países com maior potencial para abertura de franquias
- Reduzir riscos iniciais de expansão com base em dados objetivos

---

## Metodologia

1. **Análise Exploratória (EDA):** identificação de padrões, correlações e escalas.
2. **Normalização:** padronização das variáveis para garantir análise justa.
3. **Aplicação do PCA:** extração dos 3 principais componentes.
4. **Interpretação dos Componentes:**
   - **PC1:** Desenvolvimento Socioeconômico
   - **PC2:** Abertura Econômica (comércio exterior)
   - **PC3:** Inflação vs Infraestrutura de Saúde
5. **Visualização 3D:** análise visual das projeções dos países.
6. **Ranking por Potencial:** países com maiores valores em PC1 foram priorizados.

---

## Principais Insights

- Países com altos scores no **PC1** combinam alto PIB per capita, expectativa de vida elevada e baixa mortalidade infantil.
- O gráfico tridimensional revelou padrões regionais e permitiu separar economias desenvolvidas, emergentes e vulneráveis com clareza.
- O PCA serviu como ferramenta de triagem para avaliar risco/retorno de novos mercados.

---

## Recomendação Estratégica

Priorizar países com maior score no **PC1** para abertura de novas unidades, pois apresentam melhores condições estruturais para consumo, logística e operação de uma rede alimentícia global.

---

## Próximos Passos

Para uma análise de mercado ainda mais precisa, recomenda-se integrar dados setoriais como:

- Consumo de fast-food per capita
- Presença de concorrentes diretos
- Poder de compra local
- Indicadores logísticos e tributários

---

## Estrutura do Projeto

```
pca_paises.ipynb       # Notebook completo com análise e visualizações
README.md              # Este documento
```

---

## Tecnologias

- Python (Pandas, Scikit-learn, Seaborn, Plotly)
- Jupyter Notebook
- PCA (Principal Component Analysis)

---

## Autor

**Herbert C. B.**  
Cientista de Dados em formação | Portfólio orientado por projetos com foco em Business Intelligence, Machine Learning e Storytelling com Dados.  
🔗 [GitHub: @HerbertCBM](https://github.com/HerbertCBM)

---
