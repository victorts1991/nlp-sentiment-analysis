# nlp-sentiment-analysis

1. Após executar o git clone execute os comandos abaixo na raiz do projeto:

```
python3 -m venv venv

source venv/bin/activate  # Unix/macOS
# ou
venv\Scripts\activate  # Windows

pip install -r requirements.txt

python3 -m ipykernel install --user --name=nlp_sentiment_analysis_venv

```

2. Abra o arquivo analise_sentimentos.ipynb no Visual Studio Code e selecione o Kernel nlp_sentiment_analysis_venv;


Obs: Após instalar uma dependência nova, para atualizar o arquivo requirements.txt execute o comando abaixo:

```
pip freeze > requirements.txt
```