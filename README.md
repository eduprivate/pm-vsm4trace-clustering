# Modelo de espaço vetorial para trace clustering utilizando Doc2Vec

## Libs e depências
pandas
pm4py
nltk
sklearn 
pandas
gensim
from gensim.models.doc2vec import Doc2Vec, TaggedDocument
from sklearn.preprocessing import Binarizer
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.decomposition import PCA
from sklearn.cluster import DBSCAN


## Este repositório contém todo o código utilizado no trabalho 
## Antes de executar os notebooks você deve descompactar os arquivos de logs que estão no diretório 'logs':
    - sintético: sintetico_completo.xes.zip
    - real: TJSP-BL-event-log.csv.zip


## Os notebooks foram separados para os cenários com log real e sintético:
    - sintético: 
        Discovery, exploração, métricas e estatísticas: discovery_exploracao_sintetico.ipynb 
        Trace clustering: trace_clustering_juris_sintetico.ipynb
    - real: 
        Discovery, exploração, métricas e estatísticas: discovery_exploracao_real.ipynb 
        Trace clustering: trace_clustering_juris_real.ipynb


## Para Experimentos e métricas dos hyperparametros:
    - experiments_results_analysis.ipynb

## Diretório results guarda dados e planilhas resultado dos experimentos
