# 📊 Projeto: Análise Exploratória de Churn em Telecom
## 📌 Sobre o Projeto

Projeto desenvolvido no Módulo 15 – Prática, com foco na Análise Exploratória de Dados (EDA) de uma base de clientes de uma empresa de telecomunicações.

O objetivo principal é compreender os fatores que influenciam o Churn (cancelamento de clientes), utilizando análises univariadas e bivariadas, apoiadas exclusivamente em visualizações gráficas.

## 🎯 Objetivos

- Carregar e explorar a base de dados de churn em formato CSV
- Realizar análise univariada de variáveis numéricas e categóricas
- Identificar e tratar outliers
- Analisar a relação entre variáveis explicativas e a variável alvo (Churn)
- Extrair insights relevantes a partir de gráficos

## 📁 Estrutura
- `notebooks/`: Análise exploratória completa em Jupyter Notebook
- `data/`: CHURN_TELECON_MOD08_TAREFA.csv
- `visualizations/`: Boxplot, Histograma, Gráfico de barras, Gráfico de contagem (countplot), Histograma interativo por Churn, Gráfico de barras interativo (medianas)

# 🛠️ Tecnologias

- Python 3.8+
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Análises Realizadas
### Análise Univariada
- Distribuição de variáveis numéricas
- Frequência de variáveis categóricas

### Tratamento de Outliers
- Identificação visual por boxplots
- Ajustes para melhor interpretação dos dados

### Análise Bivariada
- Relação entre variáveis numéricas e o Churn
- Relação entre variáveis categóricas e variáveis numéricas

## 🔍 Principais Insights

- Quanto maior o tempo como cliente, menores são as chances de churn
- Clientes com menor total pago apresentam maior probabilidade de churn
- Clientes com dependentes tendem a permanecer mais tempo na empresa
- Contratos do tipo mês-a-mês estão associados a:
    - Menor tempo como cliente
    - Menor total pago
    - Maior taxa de churn
- Formas de pagamento automáticas (cartão de crédito e débito automático):

    - Estão associadas a maior tempo como cliente
    - Apresentam maiores valores de total pago

## 📌 Conclusão

As variáveis Tempo_como_Cliente e Total_Pago são fortemente relacionadas ao churn. Quanto maiores esses valores, menor a ocorrência de cancelamentos. Essas variáveis estão diretamente ligadas ao tipo de contrato, forma de pagamento e presença de dependentes, sendo fundamentais para estratégias de retenção de clientes.

### 👩‍💻 Autora
Bruna S. R. Santos

- 🔗 LinkedIn: www.linkedin.com/in/brunasrsantos
- 📧 Email: brunasrsantos@gmail.com

### 📝 Licença

Este projeto está licenciado sob a MIT License.
