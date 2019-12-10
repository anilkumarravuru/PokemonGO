# FinalPokemonGO

PokemonGO Analysis on Twitter Data

1. USE `python3`.
2. Set your java version to 8 (`export JAVA_HOME=$(/usr/libexec/java_home -v 1.8)`)
3. Before running multiprocess, desable fork safety (`export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES`)

# REQUIREMENTS

1. Conda
2. jupyter notebook
3. pandas
4. progressbar (`pip3 install progressbar2`)
5. Google Translator (`pip3 install googletrans`)
6. For Spark clustering in Azure HDInsights, find the detailed instructions in `Cluster Instructions.pdf`
7. Pygal(`pip install pygal`)
8. pyLDAvis(`pip install pyldavis`)
9. Geopy(`pip install geopy`)
10. Plotly(`pip install plotly`)
11. NLTK(`pip install nltk`)
  `nltk.download('stopwords')`
  `nltk.download('wordnet')`
12. Time Series Packages
  `pip install statsmodels`
  `pip install datetime`
  `pip install ipython`
  `pip install ipywidgets`
  `pip install strings`
  `pip install seaborn`

# SEQUENCE(`Preferably`)

Follow Instructions.pdf to run the following codes sequently. 

1. SparkAllWords.ipynb (`Using HD Insights`)
2. pokemon_translator.ipynb (`Using Jupyter Notebook`)
3. final_code.ipynb (`Using Jupyter Notebook`)
4. parallel_all_words.py (`python3 parallel_all_words.py` and give relative path of dataset)
5. parallel_pokemon.py (`python3 parallel_pokemon.py` and give relative path of dataset)
6. Preprocess_all_words.ipynb (`Using Jupyter Notebook` This will take Approximately 7 Hours)
