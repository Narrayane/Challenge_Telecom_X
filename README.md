# 📊 Desafio de ETL - Telecom X

Este projeto foi desenvolvido como parte do curso de ETL, com o objetivo de aplicar os conhecimentos adquiridos em um desafio prático. A proposta consistiu em extrair, transformar e carregar dados da empresa fictícia **Telecom X**, a fim de obter insights relevantes sobre o comportamento dos clientes e o desempenho da empresa.

## 📌 Objetivos

- Praticar o processo de **ETL (Extract, Transform, Load)**.
- Utilizar bibliotecas Python para manipulação, análise e visualização de dados.
- Gerar insights e indicadores com base nos dados da empresa Telecom X.

## ⚙️ Tecnologias e Bibliotecas Utilizadas

- [Python 3](https://www.python.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Google Colab](https://colab.research.google.com/)

## 🧪 Etapas do Projeto

### 1. **Extração (Extract)**  
Os dados foram disponibilizados em formato `JSON` e importados para o ambiente do Google Colab utilizando a biblioteca `pandas`.

### 2. **Transformação (Transform)**  
Durante a etapa de transformação, foram realizadas as seguintes ações:
- Limpeza de dados ausentes e duplicados.
- Conversão de tipos de dados.
- Categorização de variáveis.
- Criação de colunas derivadas.
- Padronização de formatos.

### 3. **Carga (Load)**  
Os dados transformados foram armazenados em estruturas de dados otimizadas dentro do notebook. Ao final, os dados prontos para análise foram utilizados para gerar visualizações e conclusões.

## 📊 Análises Realizadas

Com os dados tratados, foram criadas análises e gráficos para responder a perguntas de negócio como:

- Qual o percentual de evasão atual?
- Qual é o perfil dos clientes que cancelaram, incluindo o gênero, o tempo de contrato, o tipo de contrato e o método de pagamento,  cancelamento?
- Qual o tempo de contratos dos clientes que permaneceram e dos clientes que cancelaram?

As análises foram feitas utilizando gráficos de barras, de pizza e histogramas com as bibliotecas `matplotlib` e `seaborn`.


## ✅ Resultados e Conclusões

A análise permitiu identificar padrões de comportamento entre os clientes da Telecom X, auxiliando na criação de estratégias para retenção e melhoria de serviços. Algumas conclusões incluem:
- Clientes nos primeiros meses de contrato são mais propensos a cancelar.
- Planos com mais serviços agregados e contratos de longo prazo tendem a ter maior fidelização.


👨‍💻 Desafio desenvolvido como parte do curso de ETL.  
📫 Para dúvidas ou sugestões, entre em contato!

