# Projeto 2

## Sistema de Recomendação de Filmes e Exploração de Dados
* Modelo que cria uma listagem dos Top 5 filmes mais recomendados para qualquer filme presente no dataset.
* Dados coletados do seguinte Dataset do Kaggle: ["Netflix Movies and TV Shows"](https://www.kaggle.com/datasets/shivamb/netflix-shows).
* O dataset apresenta um catálogo do Netflix contendo mais de 8000 produtos, divididos em Filmes e Séries.
* O dataset não possui informações de avaliação de usuários, portanto o sistema de Recomendação utilizado é baseado em conteúdo.
* A Tokenização (artifício de Processamento de Linguagem Natural) foi essencial para criarmos uma coluna única de descrição, unindo informações como atores, diretor, país e sinopse.
* Quanto ao algoritmo de Recomendação, foi escolhido a Similaridade por Cossenos por independer do tamanho ou escala do vetor, possibilitando uma comparação apenas pela angulação dos vetores.
