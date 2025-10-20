Applied Natural Language Processing (NLP) to classify tweet sentiment (Positive, Negative, Neutral)

Handled noisy, informal tweet text using light preprocessing:
Lowercasing, removing links/mentions/hashtags

Preserved important words (e.g., "not", "never", "I", "you") to retain sentiment meaning

Transformed text into numerical features using TF-IDF vectorization

Trained a Logistic Regression classifier for multiclass sentiment prediction

Compared performance against TextBlob’s polarity-based sentiment tool

Achieved higher accuracy and better handling of negation, sarcasm, and subtle sentiment than TextBlob

Exported trained model and vectorizer using joblib for future predictions or deployment
