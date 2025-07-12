# 🏪 Sentiment Analysis su recensioni Amazon Fine Food
Progetto per i corsi di Machine Learning e Sistemi Intelligenti per Internet dell'A.A. 2023/2024.  
  
Il progetto consiste in un notebook Python che implementa un modello di Sentiment Analysis sulle recensioni del dataset Amazon Fine Food Reviews.  
L’obiettivo è classificare automaticamente le recensioni come Positive, Neutral o Negative.

## 🧩 Modellazione
Sono addestrati e confrontati quattro modelli:
- Logistic Regression + BoW
- Multinomial Naive Bayes + BoW
- Logistic Regression + TF‑IDF
- Multinomial Naive Bayes + TF‑IDF  
  
La migliore performance è ottenuta con Logistic Regression (C=1) su TF‑IDF, con circa 76% di accuratezza in training e 72% nel test.  
Una matrice di confusione normalizzata viene visualizzata per analizzare errori di classificazione.
  
## Autori
[Gaglione Giulia](https://github.com/giug2)  
[Marrapesa Sara](https://github.com/saramarrapesa)
