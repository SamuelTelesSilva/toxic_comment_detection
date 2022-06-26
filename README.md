# Detection of toxic comments in Brazilian Portuguese

# Projeto 🔥
* Detecção de comentários ou textos preconceituosos com processamento de linguagem natural


Projeto apresentado ao Curso de Especialização Lato sensu de Inteligência Artificial e Aprendizado de Máquina da **Universidade Nove de Julho**.


![](https://i0.wp.com/www.datageeks.com.br/wp-content/uploads/2019/03/An%C3%A1lise-de-Sentimentos.jpg?fit=1336%2C785&ssl=1)

# Dataset 
O conjunto de dados utilizado, foi **ToLD-BR** com 21000 comentários toxicos, contendo algumas labels: homophobia, obscene, insult, racism, misogyny e xenophobia.


João A. Leite, Diego F. Silva, Kalina Bontcheva, Carolina Scarton (2020): Toxic Language Detection in Social Media for Brazilian Portuguese: New Dataset and Multilingual Analysis. Published at AACL-IJCNLP 2020. [arxiv version](https://arxiv.org/abs/2010.04543)


# Conteúdo ✨

* Normalização de texto
  * Tokenização
  * Capitalização
  * Remoção de palavras vazias (*stopwords*)
  * Lematização e/ou Radicalização (*Stemming*)
  * Remoção de emoji que tem nos comentários do Twitter
  * Utilizando a ferramenta enelvo para arrumar as palavras da internet

* Embedding das palavras com Bert e Hugging Face 🤗

* Classificação de texto Multilabel com Spacy e Sklearn
  * Embedding das palavras com Spacy
  * Técnicas de classificação utilizadas
    * Random Forest
    * Naive Bayes Classifier
    * Support Vector Machine (SVM)
    * Logistic Regression
    * Gradient Boosting
  * Técnicas de amostragem
    * undersampling
    * oversampling
    
* Classificação de texto Multilabel com Bert e Hugging Face 🤗
  * Embedding das palavras com Bert
  * Técnicas de classificação utilizadas
    * Random Forest
    * Naive Bayes Classifier
    * Support Vector Machine (SVM)
    * Logistic Regression
    * Gradient Boosting
  * Técnicas de amostragem
    * oversampling - SMOTE
    
* Classificação de texto binária com Bert
  * Embedding das palavras com Bert
  * Técnicas de classificação utilizadas
    * Random Forest
    * Naive Bayes Classifier
    * Support Vector Machine (SVM)
    * Logistic Regression
    * Gradient Boosting
  * Técnicas de amostragem
    * oversampling - SMOTE
  
* Classificação de texto binária com Bert e Keras
  * Embedding das palavras com Bert
  * Deep learning com keras
  * Técnicas de amostragem
    * oversampling - SMOTE

# Notebooks 💻

* Normalização de texto [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dHZXclbrZ9WsPCgHoVcMv0gmF2PgnUw-?usp=sharing)

* Embedding das palavras com Bert [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DT48aU0sTJKO4kj_67q8j0y_bYSRFOU-?usp=sharing)

* Classificação de texto Multilabel com Spacy e Sklearn [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I6QCBJIE961nUtb2xvGMOn3SDBkTZnes?usp=sharing)

* Classificação de texto Multilabel com BERT [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12V9yfCEwI4He1EEYBR0V9zpABALcLtUm?usp=sharing) 

* Classificação de texto binária com BERT 🤗 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RDFvs-NAKCWZ4lN9ftkqA88AXRGDDd5f?usp=sharing)

* Classificação de texto binária com BERT, Keras e Hugging Face 🤗 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/drive/1_RrHcsnQCbyWvOZ1MnvswmCys3WTXH-R?usp=sharing)



# Como usar esse conteúdo❓

* Precisa ter o dataset ToLD-BR
  * Para obter o dataset acesse o link https://github.com/JAugusto97/ToLD-Br#readme


* Precisa ter o modelo BERT pré-treinado
  * Para obter o modelo acesse a pagina do huggingface 🤗 https://huggingface.co/neuralmind/bert-base-portuguese-cased

* Para utilizar os Notebooks
  * No tópico Notebooks tem o botão do colab ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg), clique no botão para abrir o notebook.

  * Bibliotecas e pacotes já estão no colab.
  
  * Como utilizar o google colab? 
    * acesse esse link https://colab.research.google.com/github/anthony-agbay/python-resource-guide/blob/master/notebooks/intro-notebooks.ipynb


# Licença 🚩


The source code for the site is licensed under the MIT license, which you can find in the [LICENSE](https://github.com/SamuelTelesSilva/toxic_comment_detection/blob/main/LICENSE) file.







