# Detection of toxic comments in Brazilian Portuguese

# Projeto
* Detecção de comentários ou textos preconceituosos com processamento de linguagem natural


Projeto apresentado ao Curso de Especialização Lato sensu de Inteligência Artificial e Aprendizado de Máquina da **Universidade Nove de Julho**.


![](https://i0.wp.com/www.datageeks.com.br/wp-content/uploads/2019/03/An%C3%A1lise-de-Sentimentos.jpg?fit=1336%2C785&ssl=1)

# Dataset
O conjunto de dados utilizado, foi **ToLD-BR** com 21000 comentários toxicos, contendo algumas labels: homophobia, obscene, insult, racism, misogyny e xenophobia.


João A. Leite, Diego F. Silva, Kalina Bontcheva, Carolina Scarton (2020): Toxic Language Detection in Social Media for Brazilian Portuguese: New Dataset and Multilingual Analysis. Published at AACL-IJCNLP 2020. [arxiv version](https://arxiv.org/abs/2010.04543)


# Conteúdo

* Normalização de texto
  * Tokenização
  * Capitalização
  * Remoção de palavras vazias (*stopwords*)
  * Lematização e/ou Radicalização (*Stemming*)
  * Remoção de emoji que tem nos comentários do Twitter
  * Utilizando a ferramenta enelvo para arrumar as palavras da internet

* Classificação de texto Multilabel com Spacy e Sklearn
  * Embedding
  * Técnicas de classificação utilizadas
    * Random Forest
    * Naive Bayes Classifier
    * Support Vector Machine (SVM)
    * Logistic Regression
    * Gradient Boosting
  * Técnicas de amostragem
    * undersampling
    * oversampling

* Classificação de texto binária com BERT, Keras e Hugging Face 🤗
  * Modelo BERT pré-treinado para o português do Brasil - [BERTimbau Base](https://huggingface.co/neuralmind/bert-base-portuguese-cased)
    * token das palavras
    * id das palavras
    * Obtendo vetores das palavras
  * BERT e Keras para Classificação de texto binária


# Notebooks

* Normalização de texto [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dHZXclbrZ9WsPCgHoVcMv0gmF2PgnUw-?usp=sharing)

* Classificação de texto Multilabel com Spacy e Sklearn [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I6QCBJIE961nUtb2xvGMOn3SDBkTZnes?usp=sharing)

* Classificação de texto binário com BERT, Keras e Hugging Face 🤗 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/drive/1_RrHcsnQCbyWvOZ1MnvswmCys3WTXH-R?usp=sharing)


# Como usar esse conteúdo?

* Precisa ter o dataset ToLD-BR
  * Para obter o dataset acesse o link https://github.com/JAugusto97/ToLD-Br#readme


* Precisa ter o modelo BERT pré-treinado
  * Para obter o modelo acesse a pagina do huggingface 🤗 https://huggingface.co/neuralmind/bert-base-portuguese-cased

* Para utilizar os Notebooks
  * No tópico Notebooks tem o botão do colab ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg), clique no botão para abrir o notebook.

  * Bibliotecas e pacotes já estão no colab.
  
  * Como utilizar o google colab? 
    * acesse esse link https://colab.research.google.com/github/anthony-agbay/python-resource-guide/blob/master/notebooks/intro-notebooks.ipynb


# Licença

The source code for the site is licensed under the MIT license, which you can find in the [LICENSE](https://github.com/SamuelTelesSilva/toxic_comment_detection/blob/main/LICENSE) file.







