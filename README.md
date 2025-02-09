#**Análise e Classificação de Dados Financeiros**

Este projeto visa analisar e classificar dados financeiros utilizando técnicas de pré-processamento de dados, visualização gráfica e modelagem preditiva com Regressão Logística. O objetivo principal é prever a classificação de clientes com base em suas características e comportamento financeiro.

---

## **Estrutura do Projeto**

### **1. Importação de Bibliotecas**
As principais bibliotecas utilizadas incluem:
- `pandas` para manipulação de dados.
- `matplotlib` e `seaborn` para visualizações.
- `scikit-learn` para modelagem, validação cruzada e avaliação de métricas.
- `imblearn` para tratamento de desbalanceamento dos dados.

### **2. Leitura e Limpeza dos Dados**
- Leitura do dataset `DatasetAntigo.csv`.
- Exclusão de valores ausentes e colunas irrelevantes.
- Análise exploratória para entender as variáveis.

### **3. Análise Exploratória**
- Mapeamento de variáveis para identificar tipos, valores nulos e faixas de dados.
- Criação de gráficos de boxplot e histogramas para visualização das variáveis.

### **4. Pré-processamento**
- Criação de variáveis dummy para colunas categóricas.
- Seleção das features numéricas e categóricas relevantes.
- Divisão dos dados em treino e teste.

### **5. Modelagem**
- Implementação de Regressão Logística para previsão da variável alvo (`Classificação`).
- Ajuste do modelo com os dados de treino e cálculo das probabilidades para os dados de teste.

### **6. Avaliação**
- Geração de métricas como *classification report*, matriz de confusão e gráficos para análise de desempenho do modelo.

---

## **Resultados**
- **Classificação**: Previsão de classes (`0`, `1` ou `2`) com base nos dados fornecidos.
- **Métricas**:
  - *Precision*, *Recall* e *F1-Score* para cada classe.
  - Matriz de confusão normalizada para avaliar a performance geral.

---

## **Como Utilizar**
1. **Pré-requisitos**:
   - Python 3.7 ou superior.
   - Bibliotecas listadas no arquivo `requirements.txt`.

2. **Execução**:
   - Clone o repositório:
     ```bash
     git clone https://github.com/seu-usuario/seu-repositorio.git
     ```
   - Instale as dependências:
     ```bash
     pip install -r requirements.txt
     ```
   - Execute o script principal:
     ```bash
     python main.py
     ```

3. **Personalização**:
   - Substitua o dataset `DatasetAntigo.csv` pelo seu próprio dataset, garantindo que as colunas sigam o mesmo padrão.

---

## **Visualizações**
### Boxplots de Variáveis Numéricas:
Análise de outliers e dispersão dos dados.

### Matriz de Confusão:
Desempenho do modelo:
![Matriz de Confusão](path/to/matriz_confusao.png)

---