# alura-march-2026
Slides and Labs for the workshop at Alura/Fiap

## Labs

### Lab 1 — Regression and Classification
Introduction to supervised learning through linear and polynomial regression. Covers fitting models of varying complexity (degrees 1–4), visualizing predictions, and understanding the bias-variance tradeoff (overfitting vs. underfitting).

**Key tools:** NumPy, Matplotlib, Scikit-learn (`LinearRegression`, `PolynomialFeatures`)

---

### Lab 2 — Clustering and the Curse of Dimensionality
Unsupervised learning with clustering algorithms. Implements K-Means from scratch with step-by-step animation, uses the elbow method to choose the number of clusters, and compares K-Means with DBSCAN on non-spherical data. Also explores how high-dimensional spaces break distance-based intuitions.

**Key tools:** NumPy, Matplotlib, Scikit-learn (`KMeans`, `DBSCAN`, `make_blobs`, `make_moons`)

---

### Lab 3 — Anomaly Detection and Imbalanced Classification
Covers anomaly detection with Isolation Forest and the challenges of building classifiers on imbalanced datasets (MNIST digit recognition). Introduces precision, recall, and F1-score as alternatives to accuracy, and demonstrates a semi-supervised learning approach using K-Means with label propagation to recover lost labels.

**Key tools:** Scikit-learn (`IsolationForest`, `SGDClassifier`, `KMeans`, `MLPClassifier`, `fetch_openml`)

---

### Lab 4 — Sentiment Analysis with Classical NLP and LLMs
Text sentiment classification pipeline comparing traditional ML with modern LLMs. Preprocesses text with NLTK (tokenization, stopword removal, lemmatization), builds bag-of-words features, tunes SVM and Random Forest classifiers (~57% accuracy), then contrasts with GPT-4o-mini via few-shot prompting (100% accuracy). Highlights where LLMs outperform classical approaches on small datasets.

**Key tools:** NLTK, Scikit-learn (`CountVectorizer`, `SVC`, `RandomForestClassifier`, `GridSearchCV`), OpenAI API (GPT-4o-mini), t-SNE

---

## References

- The Royal Swedish Academy of Sciences. *[They used physics to find patterns in information](https://www.nobelprize.org/uploads/2024/11/popular-physicsprize2024-3.pdf)*. Nobel Prize Popular Science Background, 2024.
- Géron, Aurélien. *Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow* — 3ª Edição: Conceitos, Ferramentas e Técnicas Para a Construção de Sistemas Inteligentes. O'Reilly / Alta Books.
- Alura. *[Fundamentos de IA: explorando a estrutura e abordagens de sistemas inteligentes](https://cursos.alura.com.br/course/fundamentos-ia-explorando-estrutura-abordagens-sistemas-inteligentes)*.
- Alura. *[Fundamentos de IA: investigando algoritmos e abordagens de machine learning](https://cursos.alura.com.br/course/fundamentos-ia-investigando-algoritmos-abordagens-machine-learning)*.
