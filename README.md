# 🛍️ Alura Store BR - Análise de Vendas

Bem-vindo à **Alura Store BR**, um projeto de análise de dados desenvolvido com Python e pandas, onde exploramos o desempenho de quatro lojas virtuais com foco em insights de vendas, faturamento e comportamento do consumidor.

Este notebook foi criado no contexto de um desafio de Data Science da Alura, e tem como objetivo aplicar boas práticas de análise exploratória de dados (EDA), visualização e storytelling com dados.

---

## 📊 Sobre o Projeto

Este projeto analisa os dados de vendas de **quatro lojas online** diferentes, disponíveis em arquivos CSV hospedados no GitHub. Utilizando a biblioteca `pandas`, os dados são importados, tratados e analisados com foco em perguntas como:

- 💰 Qual loja teve o maior faturamento?
- 📈 Quais categorias geram mais receita?
- 🧠 Há padrões interessantes no comportamento de compras?
- 🛒 Como estão distribuídas as vendas por categoria de produto?

---

## 📁 Estrutura dos Dados

Os dados de cada loja contêm as seguintes colunas:

- `produto`
- `categoria`
- `quantidade_vendida`
- `preco_unitario`
- `data_venda`

Cada linha representa uma venda realizada por um produto específico.

---

## 🔍 Etapas da Análise

O notebook está dividido em etapas bem definidas:

1. **Importação e união dos dados**
   - Coletamos dados de quatro arquivos CSV.
   - Unificamos todas as lojas em um único DataFrame.

2. **Análise de Faturamento**
   - Cálculo do total de receita por loja.
   - Comparações visuais de desempenho.

3. **Vendas por Categoria**
   - Análise da performance por tipo de produto.
   - Identificação de categorias mais vendidas.

4. **(Sugestão de expansão futura)**
   - Análise temporal das vendas.
   - Comportamento de clientes por período.

---

## 🛠️ Tecnologias Utilizadas

- [Python 3.x](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Matplotlib / Seaborn](https://matplotlib.org/) *(caso adicionado para visualizações)*

---

## 💡 Resultados & Insights

🔹 A loja com maior faturamento foi a **[insira resultado aqui após execução completa]**  
🔹 A categoria mais lucrativa foi **[insira categoria]**  
🔹 Há uma distribuição desbalanceada entre categorias — oportunidade de crescimento!

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/alura-store-br.git

2. Instale as dependências:
   ```bash
   pip install pandas jupyter
   
3.Execute o Jupyter Notebook:   
  ```bash
  jupyter notebook AluraStoreBr.ipynb

