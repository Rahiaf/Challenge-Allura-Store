Análise de Desempenho – Projeto Alura Store
1. Propósito da Análise
O objetivo deste projeto é realizar uma análise exploratória dos dados de vendas de quatro lojas fictícias da rede "Alura Store". A análise visa identificar a loja com o menor desempenho com base em métricas de faturamento, tendência de vendas e avaliações de clientes, a fim de fornecer uma recomendação embasada sobre qual unidade deveria ser vendida para otimizar os negócios da rede.

2. Estrutura do Projeto
O projeto está organizado da seguinte forma:

AluraStoreBr.ipynb: Este é o notebook principal que contém todo o código Python para a análise. Ele abrange desde a importação e limpeza dos dados até a geração de visualizações e a conclusão final.

Dados: Os dados são carregados diretamente de quatro arquivos .csv hospedados em um repositório público no GitHub. Cada arquivo corresponde aos dados de uma das quatro lojas.

Gráficos (Saídas): Durante a execução do notebook, os seguintes gráficos são gerados e salvos como arquivos .png:

faturamento_por_loja.png

tendencia_faturamento_separado.png

composicao_vendas_pizza.png

avaliacao_media_loja.png

ranking_produtos.png

frete_medio_loja.png

3. Exemplos de Gráficos e Insights Obtidos
A análise gerou diversos insights sobre o desempenho comparativo das lojas. Abaixo estão alguns dos principais gráficos e as conclusões extraídas.

Faturamento Total por Loja
O gráfico de barras mostra que a Loja 4 possui o menor faturamento acumulado entre as quatro unidades, enquanto a Loja 1 lidera em receita.

Tendência do Faturamento Mensal
A análise da tendência de vendas ao longo do tempo é crucial. Os gráficos de linha revelam que, embora todas as lojas apresentem volatilidade, a Loja 4 e a Loja 3 mostram uma clara tendência de queda em seus faturamentos no período mais recente (final de 2022 e início de 2023).

Composição de Vendas por Categoria
Os gráficos de pizza indicam que o mix de produtos vendidos é muito semelhante em todas as lojas. As categorias de "móveis" e "eletrônicos" são as mais representativas em todas as unidades, sugerindo que a baixa performance de uma loja não está relacionada a uma estratégia de produtos diferente.

4. Instruções para Executar o Notebook
Para replicar esta análise, siga os passos abaixo.

Pré-requisitos
Python 3.x instalado.

As seguintes bibliotecas Python: pandas, matplotlib, numpy.

Você pode instalar as dependências com o seguinte comando:

  pip install pandas matplotlib numpy

Faça o download ou clone o arquivo AluraStoreBr.ipynb.

Abra o notebook em um ambiente Jupyter (como Jupyter Notebook, JupyterLab ou Google Colab).

Execute as células de código sequencialmente, de cima para baixo.

O notebook está configurado para baixar os dados diretamente da internet, e todos os gráficos serão salvos no mesmo diretório onde o notebook for executado.
