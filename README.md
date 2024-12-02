# README

## Descrição do Projeto / Project Description

Este projeto visa visualizar a variação dos valores de Custo por Conversão (CPV) ao longo de diferentes categorias e períodos mensais, utilizando um gráfico animado em R. O objetivo é mostrar como os valores variam em torno de uma média fixa, proporcionando uma análise clara da estabilidade ou dispersão dos dados em cada categoria ao longo do tempo.

This project aims to visualize the variation in Cost per Conversion (CPV) values across different categories and monthly periods using an animated plot in R. The goal is to show how values vary around a fixed average, providing a clear analysis of data stability or dispersion within each category over time.

## Uso da Base de Dados / Using the Dataset

O arquivo de dados utilizado neste projeto é `sample_data.csv`. Essa base de dados contém as informações necessárias para criar o gráfico animado e deve seguir um formato específico para garantir a correta execução do código. Você pode substituir `sample_data.csv` por outro arquivo de dados, contanto que ele respeite o mesmo formato e granularidade.

The dataset used in this project is `sample_data.csv`. This dataset contains the information needed to create the animated plot and must follow a specific format to ensure correct execution of the code. You can replace `sample_data.csv` with another dataset, as long as it respects the same format and level of granularity.

### Estrutura da Base de Dados / Dataset Structure

- **Categoria**: Uma coluna categórica contendo as diferentes categorias analisadas.
- **Mês**: Uma coluna representando o mês, no formato `YYYY-MM`, que posteriormente será convertido para exibição no formato "Fevereiro 2024".
- **Dia**: Uma coluna numérica representando o dia do mês, usada para granularidade adicional na análise.
- **CPV**: Custo por Conversão, que deve ser um valor numérico para análise.

- **Category**: A categorical column containing the different categories being analyzed.
- **Month**: A column representing the month, in the `YYYY-MM` format, which will later be converted for display as "February 2024".
- **Day**: A numeric column representing the day of the month, used for additional granularity in the analysis.
- **CPV**: Cost per Conversion, which should be a numeric value for analysis.

## Como Executar / How to Run

1. Instale os pacotes necessários: `tidyverse`, `gganimate`, `ggtext`, e `lubridate`.
2. Substitua o caminho do arquivo `sample_data.csv` no código, caso esteja utilizando outro arquivo.
3. Execute o script R para gerar a animação e salvar o arquivo GIF.

1. Install the necessary packages: `tidyverse`, `gganimate`, `ggtext`, and `lubridate`.
2. Replace the path to the `sample_data.csv` file in the code if you are using another file.
3. Run the R script to generate the animation and save the GIF file.

## Considerações / Considerations

- Certifique-se de que o novo arquivo de dados tenha colunas e tipos de dados compatíveis para evitar erros durante a execução.
- Se precisar de ajustes específicos no formato dos dados, é recomendável realizar essas alterações antes de carregar os dados no script.

- Ensure that the new dataset has compatible columns and data types to avoid errors during execution.
- If specific adjustments to the data format are needed, it is recommended to make those changes before loading the data into the script.

## Exemplos / Examples

Se você quiser utilizar sua própria base de dados, certifique-se de que ela contenha colunas nomeadas e organizadas como descrito acima. Isso garante que o script consiga gerar as visualizações de forma apropriada.

If you want to use your own dataset, ensure it contains columns named and organized as described above. This ensures the script can generate the visualizations correctly.




