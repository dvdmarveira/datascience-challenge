# Projetos de Análise de Dados

Este repositório contém dois projetos de análise de dados implementados em Python usando Jupyter Notebooks.

## Desafio 1: Análise de Vendas e Despesas Regionais

### Descrição

O primeiro projeto (`challenge.ipynb`) consiste em uma análise de dados de vendas e despesas por região. O projeto demonstra várias técnicas de manipulação e análise de dados, incluindo:

- Tratamento de dados ausentes (valores nulos)
- Agrupamento de dados por região e mês
- Análises estatísticas descritivas
- Visualização de dados através de gráficos
- Exportação de dados tratados para Excel

### Principais Funcionalidades

1. **Tratamento de Dados**

   - Preenchimento de valores nulos usando média e mediana
   - Verificação e limpeza de dados inconsistentes

2. **Análises Realizadas**

   - Agrupamento de dados por região e mês
   - Cálculo de estatísticas descritivas (média, mediana, desvio padrão)
   - Combinação horizontal de colunas após tratamento

3. **Visualizações**

   - Gráficos de barras para análise estatística
   - Visualizações comparativas entre variáveis

4. **Exportação de Dados**
   - Geração de arquivo Excel com múltiplas abas contendo:
     - Dados tratados
     - Dados agrupados
     - Sumário estatístico

### Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Desafio 2: Análise Estatística de Grupos

### Descrição

O segundo projeto (`elective.ipynb`) foca na análise estatística comparativa entre dois grupos, realizando:

- Testes de normalidade
- Análises de correlação
- Estatísticas descritivas
- Visualizações de dados

### Principais Análises

1. **Estatísticas Descritivas**

   - Cálculo de média, mediana e desvio padrão para cada grupo
   - Comparação entre grupos A e B

2. **Testes Estatísticos**

   - Teste de Shapiro-Wilk para verificação de normalidade
   - Correlação de Pearson entre os grupos

3. **Visualizações**
   - Gráfico de dispersão entre grupos
   - Visualizações estatísticas comparativas

### Resultados Principais

- Confirmação de normalidade dos dados em ambos os grupos
- Correlação linear perfeita entre os grupos

### Tecnologias Utilizadas

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Como Executar os Projetos

1. Clone o repositório
2. Instale as dependências necessárias:

```bash
pip install pandas numpy matplotlib scipy
```

3. Abra os notebooks no Jupyter:

```bash
jupyter notebook
```

4. Execute as células em ordem sequencial

## Estrutura do Projeto

```
.
├── challenge.ipynb
├── elective.ipynb
└── datasets/
    └── dados_vendas.xlsx
    └── dados_vendas_analise.xlsx
```


