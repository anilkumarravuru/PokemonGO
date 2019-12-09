# FinalPokemonGO

PokemonGO Analysis on Twitter Data

1. USE `python3`.
2. Set your java version to 8 (`export JAVA_HOME=$(/usr/libexec/java_home -v 1.8)`)
3. Before running multiprocess, desable fork safety (`export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES`)

# REQUIREMENTS

Conda
jupyter notebook
pandas
progressbar (`pip3 install progressbar2`)
Google Translator (`pip3 install googletrans`)
For Spark clustering in Azure HDInsights, find the detailed instructions in `Cluster Instructions.pdf`
Pygal(`pip install pygal`)
pyLDAvis(`pip install pyldavis`)
Geopy(`pip install geopy`)
Plotly(`pip install plotly`)
NLTK(`pip install nltk`)
`nltk.download('stopwords')`
`nltk.download('wordnet')`
Time Series Packages
`pip install statsmodels`
`pip install datetime`
`pip install ipython`
`pip install ipywidgets`
`pip install strings`
`pip install seaborn`

# SEQUENCE(`Preferably`)

1. SparkAllWords.ipynb
2. pokemon_translator.ipynb
3. PokemonGo_OnTwitter.ipynb
4. parallel_all_words.py
5. parallel_pokemon.py
6. Preprocess_all_words.ipynb
