# AgrupadorSemanticoEmbedded
Código em Python (notebook Jupyter) usando embeddings para criar agrupamentos semânticos de palavras extraídas de uma base de dados contendo avaliações de dispositivos em um site.

Como só as palavras estavam disponíveis, sem seu devido contexto, uma base de dados com palavras já embedded por um algoritmo pré-treinada em páginas da wikipedia e da Gigaword. Sua abrangência se mostrou bastante útil para traduzir a maioria das palavras, mas provoca algumas confusões no algoritmo por conter significados gerais, ao invés de específicos na área da computação.

A base de dados não está inclusa no github devido ao seu tamanho, mas pode ser encontrada neste site: https://nlp.stanford.edu/projects/glove/. Créditos a Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. A versão usada foi a de 6B, 300 vetores.
