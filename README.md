# 📊 Análise de Salários na Área de Dados

Este projeto foi desenvolvido durante a **Imersão de Dados da Alura** e consiste em um **dashboard interativo** que permite explorar dados salariais de profissionais da área de dados em diferentes níveis de senioridade, tipos de contrato, tamanhos de empresa e localização geográfica.

🔗 [Acesse o dashboard online](https://dashboarddados-vb3tscg7ohgnffkacgepjh.streamlit.app/)

---

## 🚀 Tecnologias Utilizadas
- **Python** 🐍  
- **Pandas** para manipulação de dados  
- **NumPy** para operações numéricas  
- **Matplotlib & Seaborn** para visualizações estáticas  
- **Plotly Express** para gráficos interativos  
- **PyCountry** para conversão de códigos de países (ISO-2 → ISO-3)  
- **Streamlit** para criação do dashboard  

---

## 📌 Etapas do Projeto

1. **Coleta de Dados**
   - Dados salariais foram obtidos do repositório público:  
     `https://raw.githubusercontent.com/guilhermeonrails/data-jobs/main/salaries.csv`

2. **Limpeza e Transformação**
   - Renomeação das colunas para português  
   - Conversão de códigos de senioridade, tipo de contrato, tamanho da empresa e modalidade de trabalho para valores mais legíveis  
   - Tratamento de valores ausentes em salários e cidades  
   - Conversão de anos para tipo inteiro  
   - Criação da coluna `residencia_iso3` para visualizações geográficas  

3. **Análise Exploratória**
   - Distribuição de senioridade  
   - Salário médio por nível de senioridade  
   - Distribuição de salários anuais (histograma e boxplot)  
   - Boxplots por senioridade  
   - Visualizações interativas com Plotly  

4. **Dashboard Interativo**
   - Filtros por ano, senioridade, tipo de contrato e tamanho da empresa  
   - Métricas principais: salário médio, salário máximo, total de registros, cargo mais frequente  
   - Gráficos interativos:
     - Top 10 cargos por salário médio  
     - Distribuição de salários anuais  
     - Proporção dos tipos de trabalho (presencial, remoto, híbrido)  
     - Salário médio de Data Scientists por país  
   - Tabela detalhada dos registros filtrados  

---

5. ## Principais insights da análise de salários na área de dados:

- 💼 Senioridade importa: Executivos e sênior ganham significativamente mais que pleno e júnior.

- 📊 Distribuição desigual: A maioria recebe até 150k USD/ano, mas existem outliers com salários muito altos.

- 🏢 Tipo de contrato e empresa: Contratos integrais e empresas médias predominam, enquanto grandes empresas oferecem salários maiores.

- 🌍 Impacto da localização: Profissionais em países desenvolvidos, como EUA, têm salários médios mais altos.

- 🖥️ Modalidade de trabalho: A maior parte trabalha presencialmente, mas o remoto e híbrido mostram tendências de flexibilidade crescente.
