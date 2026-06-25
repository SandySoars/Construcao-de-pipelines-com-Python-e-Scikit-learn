# Pipeline de Aprendizado de Máquina com Scikit-learn

Este projeto apresenta uma implementação prática de um **Pipeline de Machine Learning** utilizando **Python** e **Scikit-learn**. O objetivo é demonstrar como organizar todas as etapas de um fluxo de aprendizado de máquina, desde a preparação dos dados até a avaliação do modelo, utilizando boas práticas de desenvolvimento.

O projeto foi desenvolvido como atividade prática para auxiliar estudantes na compreensão da construção de pipelines em Machine Learning.

---

## Objetivos

- Compreender o funcionamento de um Pipeline no Scikit-learn;
- Organizar as etapas de pré-processamento e treinamento;
- Separar dados de treino e teste;
- Padronizar variáveis de entrada;
- Treinar um modelo de Regressão Linear;
- Realizar previsões;
- Avaliar o desempenho do modelo utilizando métricas estatísticas.

---

## Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Estrutura do Projeto

```
.
├── Aula06_Pratica_Pipelines_ML.ipynb
├── README.md
```

---

## Fluxo do Projeto

O notebook segue as seguintes etapas:

1. Importação das bibliotecas
2. Criação do conjunto de dados
3. Exploração dos dados
4. Visualização gráfica
5. Separação entre variáveis de entrada e saída
6. Divisão entre dados de treino e teste
7. Construção do Pipeline
8. Treinamento do modelo
9. Realização de previsões
10. Avaliação do modelo
11. Previsão para novos dados

---

## Pipeline Utilizado

O Pipeline é composto por duas etapas principais:

- **StandardScaler**
  - Responsável pela padronização das variáveis numéricas.

- **LinearRegression**
  - Modelo de regressão linear utilizado para realizar as previsões.

Exemplo:

```python
pipeline = Pipeline([
    ("padronizacao", StandardScaler()),
    ("modelo", LinearRegression())
])
```

---

## Métricas Avaliadas

O desempenho do modelo é analisado utilizando:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score (Coeficiente de Determinação)

Essas métricas permitem verificar a qualidade das previsões realizadas pelo modelo.

---

## Exercícios Propostos

O notebook também contém exercícios para fixação dos conceitos, incluindo:

- Exploração do dataset;
- Criação de gráficos;
- Separação das variáveis;
- Interpretação da divisão entre treino e teste;
- Análise dos erros de previsão;
- Interpretação das métricas de avaliação.

---

## Como Executar

### 1. Clone este repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Acesse a pasta

```bash
cd seu-repositorio
```

### 3. Instale as dependências

```bash
pip install pandas numpy matplotlib scikit-learn notebook
```

### 4. Execute o Jupyter Notebook

```bash
jupyter notebook
```

Abra o arquivo:

```
Aula06_Pratica_Pipelines_ML.ipynb
```

---

## Conceitos Abordados

- Machine Learning
- Pipeline
- Pré-processamento de dados
- Padronização
- Regressão Linear
- Treinamento de modelos
- Avaliação de modelos
- Predição

---

## Público-alvo

Este material é indicado para:

- Estudantes de Ciência da Computação;
- Estudantes de Sistemas de Informação;
- Cursos de Inteligência Artificial;
- Disciplinas de Aprendizado de Máquina;
- Iniciantes em Scikit-learn.

---

## Autor

Desenvolvido por **Sandyella Silva Soares** como material didático para práticas de Aprendizado de Máquina utilizando Python e Scikit-learn.

---

## Licença

Este projeto é destinado a fins acadêmicos e educacionais.
