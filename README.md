## Solução dos exercícios da quinta aula do curso GeoPY
## Criando mapas no Python

Bibliotecas usadas: gdal-bin ; python-gdal ; python3-gdal ; python3-rtree ; geopandas==0.10.0 ; descartes ; os ; pandas ; matplotlib.pyplot ; re ; contextily ; mapclassify

Funções aprendidas : `numpy.loadtxt()` ; `numpy.mean()` ; `numpy.std()` ; `numpy.round()` ; `numpy.reshape()` ; `numpy.transpose()` ; `matplotlib.pyplot.subplots()` ; `matplotlib.pyplot.imshow()` ; `matplotlib.pyplot.title()` ; `matplotlib.pyplot.colorbar()` ; `matplotlib.pyplot.savefig()` ; `sklearn.preprocessing.StandardScaler()` ; `sklearn.decomposition.PCA()` ; `sklearn.cluster.KMeans()` ; `sklearn.metrics.silhouette_score()`

Conteúdos abordados/ explicação dos exercícios : O código em questão apresenta dois exercícios que envolvem o mapeamento geográfico de informações relacionadas à cidade de São Paulo. 

O exercício 1 (E1) tem como objetivo a visualização da distribuição de domicílios em favelas paulistanas. Para isso, o código importa um shapefile com as informações geográficas das favelas, certifica-se que os dados do sistema de coordenadas estão corretos, reprojeta as informações para o sistema de coordenadas WGS84, cria um mapa utilizando a biblioteca Folium centralizado no município de São Paulo e adiciona o geodataframe representando o número de domicílios em cada favela. Além disso, o mapa é configurado para mostrar o ano de implementação de cada favela quando o mouse passar sobre ela, e é adicionado um controle de camadas ao mapa para permitir a ativação e desativação da visualização dos dados.

O exercício 2 (E2) consiste na criação de um mapa com as informações de cinemas, teatros e shows na cidade de São Paulo. Para isso, o código importa um shapefile com as informações geográficas desses locais, certifica-se que os dados do sistema de coordenadas estão corretos, reprojeta as informações para o sistema de coordenadas WGS84, cria um mapa utilizando a biblioteca Folium centralizado no município de São Paulo e adiciona o geodataframe representando esses locais.
