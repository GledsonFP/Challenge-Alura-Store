#  Projeto Alura Store — Análise de Vendas

##  1. Propósito da Análise

Este projeto tem como objetivo analisar os dados de vendas de quatro lojas da rede **Alura Store** para auxiliar o Sr. João na decisão de **qual loja deve ser vendida** para investimento em um novo negócio.

A análise é baseada em métricas de desempenho, como:
- Faturamento total por loja
- Vendas por categoria de produtos
- Média de avaliação dos clientes
- Produtos mais e menos vendidos
- Custo médio do frete

A partir dessas métricas, foi possível comparar o desempenho das lojas e identificar aquela com menor performance geral.

---

##  2. Estrutura do Projeto e Organização dos Arquivos

A estrutura do projeto é organizada da seguinte forma:

alura-store/

- AluraStoreBrasil.ipynb # Notebook principal com a análise completa
- loja_1.csv # Base de dados da Loja 1
- loja_2.csv # Base de dados da Loja 2
-  loja_3.csv # Base de dados da Loja 3
- loja_4.csv # Base de dados da Loja 4
- README.md # Documentação do projeto


- O arquivo **AluraStoreBrasil.ipynb** contém todo o código de análise, geração de gráficos e o relatório final.
- Os arquivos **.csv** contêm os dados de vendas de cada loja.

---

##  3. Exemplos de Gráficos e Insights Obtidos

Durante a análise, foram gerados diversos gráficos utilizando a biblioteca **Matplotlib**, entre eles:

-  **Faturamento por Loja (gráfico de barras)**  
  → Permite comparar o desempenho financeiro das quatro lojas.

-  **Média de Avaliação por Loja (gráfico de barras)**  
  → Mostra a satisfação média dos clientes em cada loja.

-  **Vendas por Categoria (gráfico de pizza)**  
  → Exibe a distribuição das vendas entre as categorias de produtos.

-  **Produtos mais e menos vendidos**  
  → Identifica quais itens têm maior e menor saída em cada loja.

###  Principal Insight

A **Loja 4** apresentou o **menor faturamento total** entre as quatro lojas e não se destacou positivamente em outros indicadores, como avaliação média ou volume de vendas.  
Com isso, ela foi identificada como a **melhor candidata para ser vendida**.

---

##  4. Instruções para Executar o Notebook

Para executar este projeto:

1. Faça o download do repositório ou dos arquivos do projeto.
2. Abra o arquivo **AluraStoreBrasil.ipynb** no **Google Colab** ou no **Jupyter Notebook**.
3. Certifique-se de que os arquivos:
   - `loja_1.csv`
   - `loja_2.csv`
   - `loja_3.csv`
   - `loja_4.csv`  
   estão na mesma pasta do notebook (ou ajuste os caminhos no código).
4. No Google Colab, clique em:
   - **Ambiente de execução → Executar tudo**
5. Aguarde a execução das células para visualizar:
   - As análises
   - Os gráficos
   - O relatório final com a conclusão

---

##  Conclusão

Este projeto demonstra como a análise de dados pode apoiar decisões de negócio, utilizando Python, Pandas e Matplotlib para explorar dados, gerar visualizações e extrair insights relevantes.

 **Recomendação final:** A **Loja 4** deve ser vendida por apresentar o pior desempenho geral entre as quatro lojas analisadas.
