# Prática - Clusterização

Na base Iris, vamos tentar agrupar as flores por informações do tamanho de suas pétalas.

## 1. k-Means e Métricas:
   
* Carregue a base e visualize algumas informações sobre a mesma
* Selecione apenas as características relacionadas às pétalas 'petal length (cm)', 'petal width (cm)'
* Plote a dispersão dessas características
* Padronize os dados (não é recomendado utilizar técnicas não-lineares)
* Plote novamente a dispersão
* Crie e treine modelos KMeans com valores de k que achar válido (de acordo com a visualização)
* Plote a dispersão juntamente com os kmeans.cluster_centers_ e cores correspondentes aos grupos kmeans.labels_ pode ser utilizado como cores
* Analise o melhor valor de K utilizando o método Elbow baseado na inércia - kmeans.inertia_
* Analise o melhor valor de K utilizando o Silhouette Score - silhouette_score
* Baseando-se no melhor k encontrado:
    1. compare o resultado obtido com as espécies reais visualmente
    2. descreva os representantes dos grupos (centróides) e cada um dos clusters encontrados com base em suas características
    3. qual(is) técnica(s) poderiam ser utilizadas caso fosse necessário encontrar outliers?
    4. Implemente e demonstre visualmente.

\
## 2. Clustering Hierárquico:

A partir da prática anterior:

* Faça um experimento com Clustering Hierárquico. Experimente diferentes distâncias. Visualize o dendograma utilizando, pelo menos, duas distâncias diferentes
* [Extra] Experimente, pelo menos, mais uma forma de clustering a seu critério
Compare os grupos criados através de visualizações e métricas vistas
