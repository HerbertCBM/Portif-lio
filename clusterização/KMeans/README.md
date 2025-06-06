# Segmentação de Clientes com K-Means

Este projeto utiliza clusterização para identificar grupos de clientes com padrões semelhantes de comportamento, com base em atributos como idade, faturamento e propensão à inovação.

Após explorar os dados com testes estatísticos e análise descritiva, aplicamos pré-processamento com técnicas adequadas de escalonamento e codificação. Em seguida, usamos o algoritmo KMeans combinado com otimização de hiperparâmetros via Optuna para encontrar a segmentação mais coerente.

### Objetivos

- Agrupar clientes com características semelhantes
- Avaliar o impacto da inovação e idade sobre o faturamento
- Descobrir perfis estratégicos para ações de marketing e produto

### Principais Resultados

- Cluster 0: clientes jovens com receita média
- Cluster 1: clientes mais velhos e com baixo consumo
- Cluster 2: grupo inovador e economicamente relevante, com alta receita

Esses perfis foram identificados com base na análise cruzada entre idade, inovação e faturamento, revelando insights relevantes para personalização e estratégias comerciais.

### Tecnologias

- Python
- Pandas, Scikit-learn
- Optuna
- KMeans
- Seaborn, Plotly
- Jupyter Notebook

### Próximos Passos

- Incorporar variáveis de comportamento de compra
- Testar modelos hierárquicos e density-based (DBSCAN, HDBSCAN)
- Criar sistema de recomendação baseado nos clusters
- Explorar UMAP como alternativa de redução de dimensionalidade

---

Este projeto mostra como a clusterização pode revelar padrões valiosos de comportamento, mesmo em datasets simples, apoiando decisões mais estratégicas de negócio.
