# Clusterização de Clientes PJ para Estratégia de Digitalização

## Contexto e Objetivo

Nosso desafio atual é expandir o uso de soluções digitais entre os clientes PJ. Contudo, o perfil desses clientes é diverso, e nem todos estão igualmente prontos ou interessados em inovação.

### Hipótese de Negócio
> Existem perfis distintos de clientes quanto à abertura à inovação e maturidade digital. Agrupar esses perfis pode direcionar campanhas e produtos com maior aderência e eficiência.

---

## Fontes e Estratégia Analítica

### Base de dados
- 500 clientes PJ
- Variáveis: faturamento, número de funcionários, idade da empresa, localização, setor e score de inovação

### Técnica Utilizada
- Clusterização com **KMeans**
- Definição do melhor **k=3** via **Optuna** com base no **Silhouette Score**
- Dados transformados com:
  - `StandardScaler` para variáveis numéricas
  - `OrdinalEncoder` para inovação
  - `OneHotEncoder` para variáveis categóricas

### Por que KMeans?
- Dados padronizados e sem outliers relevantes
- Clusters esperados com separação clara e formato esférico
- Objetivo: segmentar por similaridade geral, não por densidade ou hierarquia

---

## Perfis Identificados (Clusters)

### Cluster 1 – Premium Inovador
- **Inovação média**: 8.0
- **Faturamento mais alto**
- **Base predominante: Vitória**

**Ação:**
- Ofertar soluções digitais avançadas
- Priorizar para testes de produtos (MVPs)
- Engajar com funcionalidades premium

---

### Cluster 0 – Tradicional Conservador
- **Inovação média**: 1.5
- Faturamento alto
- Predominância no **Rio de Janeiro**

**Ação:**
- Campanhas educativas
- Estudos de caso e valor percebido
- Nutrição gradual e assistida

---

### Cluster 2 – Expansivo Econômico
- **Inovação média**: 5.1
- Perfil intermediário
- Predominância em **São Paulo**

**Ação:**
- Ofertas digitais básicas
- Onboarding com apoio
- Monitorar evolução digital

---

## Conclusão Executiva

> A clusterização permitiu transformar dados dispersos em **perfis estratégicos de cliente**. Com isso, agora sabemos **como** e **para quem** oferecer soluções digitais, maximizando impacto e eficiência.

### Ações Recomendadas
- Criar campanhas direcionadas por cluster
- Monitorar engajamento e adoção digital por grupo
- Atualizar perfis periodicamente com novos dados

