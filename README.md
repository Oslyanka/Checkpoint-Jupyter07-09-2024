---

# Análise Comparativa de Avaliações e Duração de Filmes e Séries

Este repositório contém um projeto de análise de dados que explora a relação entre a duração dos filmes e suas avaliações em diferentes plataformas de avaliação, como IMDb e Rotten Tomatoes. O objetivo é integrar e analisar dados de diferentes fontes para obter uma visão mais completa da qualidade dos filmes e séries.

## Conteúdo do Repositório

- **`notebook.ipynb`**: Notebook Jupyter contendo o código de análise, visualizações e insights.
- **`netflix_titles.csv`**: Dataset contendo informações sobre filmes e séries da Netflix.
- **`rotten_tomatoes_critic_reviews.csv`**: Dataset contendo avaliações críticas de filmes do Rotten Tomatoes.( DATASET MUITO GRANDE PARA SER INCLUSO COLOCAREI O LINK AQUI: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset/data )
- **`final_imdb_dataset.csv`**: Dataset contendo informações de filmes do IMDb.

## Objetivos do Projeto

1. **Carregamento e Pré-processamento de Dados**:
   - Limpeza e conversão de dados dos datasets do Rotten Tomatoes e IMDb.
   - Preparação dos dados para análise e integração.

2. **Integração dos Dados**:
   - Mesclagem dos dados do IMDb e Rotten Tomatoes com base em um identificador comum.

3. **Análise de Dados**:
   - Análise estatística das avaliações convertidas.
   - Investigação da relação entre a duração dos filmes e suas avaliações em diferentes plataformas.

4. **Visualização dos Dados**:
   - Criação de gráficos de dispersão e regressão linear para explorar a relação entre o número de votos e a nota média.
   - Análise da correlação entre a duração dos filmes e suas avaliações.

5. **Questões de Análise**:
   - Impacto da duração dos filmes sobre suas avaliações.
   - Diferenças de avaliação entre plataformas.

## Instruções de Uso

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/Oslyanka/Checkpoint-Jupyter07-09-2024.git
   ```

2. **Instale as Dependências**:
   Certifique-se de ter o Python e os pacotes necessários instalados. Você pode usar o `requirements.txt` para instalar as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute o Notebook**:
   Abra o notebook `notebook.ipynb` no Jupyter Notebook para visualizar e executar o código.

## Estrutura dos Dados

- **Netflix DataFrame**:
  - Colunas: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

- **Rotten Tomatoes DataFrame**:
  - Colunas: `rotten_tomatoes_link`, `critic_name`, `top_critic`, `publisher_name`, `review_type`, `review_score`, `review_date`, `review_content`

- **IMDb DataFrame**:
  - Colunas: `Movie`, `Year`, `Duration`, `Genres`, `Rating`, `Num_of_Votes`, `Five_Year`, `Final_Genre`, `Types_of_Duration`

---
