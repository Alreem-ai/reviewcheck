# reviewcheck · Real or Fake?

Interactive companion website for our **CS370 Artificial Intelligence** project — *Fake Product Review Detection* (Section 5C2, Princess Nourah bint Abdulrahman University).

Visitors read three product reviews, guess **Real human** or **Fake**, then see what our model predicted and which words gave each review away. A final section shows the twist: reviews written by Gemini slip past the model.

## The model
- **TF-IDF + Multinomial Naive Bayes** (Logistic Regression as the baseline)
- **88.7%** test accuracy on the labelled review dataset
- All probabilities shown on the site are real outputs from our notebook.

## Team
Aryam Aljohani · Alreem Aldossary · Munirah Alsallum · Norah Altaweel

## Run locally
It's a single static page — open `index.html` in a browser.

---
Student project. Not affiliated with any store.
