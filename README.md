# zum_nlp
ZUM NLP - Przetwarzanie języka naturalnego

Celem projektu jest stworzenie analizatora sentymentu do analizy polaryzacji społeczeństwa w Polsce na podstawie tweetów na temat COVID-19

Dane wejściowe znajdują w formacie json pod adresem http://77.55.209.58/zum2/tweets.json

Do odszumiania wykorzystano spacy i listę dla polskiego języka pl_core_news_md

Na początku do analizy sentymentu została wykorzystana została biblioteka TextBlob 
Do tokenizacji nltk.tokenize
Do klasyfikacji użyto narzędzi z pakietu sklearn m.in naiwny klasyfikator Bayesa BernoulliNB 
