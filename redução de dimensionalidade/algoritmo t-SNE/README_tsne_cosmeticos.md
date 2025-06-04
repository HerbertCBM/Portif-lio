## Segmentação e Recomendação de Produtos Cosméticos com t-SNE

Este projeto explora dados de produtos cosméticos para identificar agrupamentos de itens com características similares, utilizando técnicas de redução de dimensionalidade e clusterização.

Aplicamos o algoritmo t-SNE para visualizar padrões de similaridade entre produtos com base em atributos como tipo, avaliação, preço e público-alvo. Em seguida, usamos KMeans para segmentar o mercado em clusters interpretáveis. Finalizamos com a criação de um sistema de recomendação simples que sugere produtos similares a partir da proximidade vetorial no espaço t-SNE.

### Objetivos

- Identificar padrões não triviais de similaridade entre produtos
- Segmentar o portfólio com base em atributos multidimensionais
- Desenvolver um sistema de recomendação baseado em clusters e distância vetorial

### Principais Resultados

- Segmentação coerente de produtos com base em combinações de atributos
- Clusters com perfis distintos de preço e avaliação
- Recomendação de produtos similares por perfil

### Tecnologias

- Python
- Pandas, Scikit-learn
- t-SNE, KMeans
- Plotly, Seaborn
- Jupyter Notebook

### Próximos Passos

- Incorporar dados reais de comportamento de usuário
- Adicionar dados externos como vendas, busca e concorrência
- Testar UMAP como alternativa ao t-SNE
- Criar interface interativa para exploração e recomendação

---

Este projeto demonstra como técnicas não supervisionadas, aliadas à análise estatística e visual, podem gerar insights acionáveis para tomada de decisão estratégica em mercados competitivos como o de cosméticos.
