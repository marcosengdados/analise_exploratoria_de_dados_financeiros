## 💰 Análise Exploratória de Dados Financeiros
Este projeto tem como objetivo analisar o comportamento de clientes de uma instituição financeira fictícia. A análise foi desenvolvida no contexto do curso Python para Análise de Dados da EBAC e busca gerar insights úteis sobre perfis de clientes, comportamento financeiro e padrões de inadimplência.

# 📌 Objetivos da Análise

- Identificar o perfil demográfico e educacional dos clientes.
- Analisar o comportamento de transações financeiras e uso de produtos.
- Avaliar a inadimplência e fatores associados, como limite de crédito e valor das transações.
- Gerar visualizações comparativas entre clientes adimplentes e inadimplentes.

# 🔎 Etapas Desenvolvidas

- Importação e inspeção dos dados
- Leitura de dados CSV
- Checagem de schema e dados faltantes
- Limpeza e transformação de dados
- Conversão de colunas numéricas com formatação monetária
- Remoção de valores nulos
- Separação de clientes adimplentes e inadimplentes

**Visualização exploratória**

- Gráficos categóricos e histogramas
- Análises por escolaridade, estado civil, salário anual, valor e quantidade de transações
- Gráficos comparativos entre grupos de clientes
- Geração de insights
- Segmentação por perfil demográfico
- Identificação de faixas de renda e padrão de uso
- Relações entre inatividade, inadimplência e movimentações financeiras

📊 Exemplos de Resultados

- Clientes com doutorado apresentam leve tendência à inadimplência.
- A maior parte dos clientes possui ensino médio completo e salário anual inferior a R$ 60.000.
- Clientes adimplentes tendem a realizar mais transações e de valores maiores.
- A quantidade de transações é mais relevante que o salário ao avaliar a inadimplência.
- Cerca de 500 clientes estavam inativos há 12 meses, sem correlação significativa com salário ou limite de crédito.

# 🛠️ Tecnologias Utilizadas

- Python	Linguagem de programação principal
- Pandas	Manipulação e análise de dados
- Matplotlib e Seaborn	Visualização de dados e gráficos comparativos

# 💡 Recomendações Finais

- Desenvolver campanhas voltadas a mulheres casadas entre 25 e 40 anos.
- Explorar fidelização com base em volume de transações, mais do que apenas limite de crédito.
- Monitorar comportamento transacional como fator de risco mais relevante para inadimplência.
