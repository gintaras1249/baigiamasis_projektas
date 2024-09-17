Naudoti duomenys: https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb - 'train_data.txt' failas. Jis turi būti idėtas į aplankalą initial/.
Taip pat, darbo aplinkoje turėtų būti sukurti aplankalai 'cleaned_data/' (kuris naudojamas apdorotų failų įrašinėjimui) ir 'models/', kuris naudojamas modeliams išsaugoti.

preprocess.ipynb - apdoroja duomenis, pašalina nereikalingus ženklus, nereikšmingus žodžius, paverčia žodžius į mažasias raides, tokenizuoja, 
galiausiai naudojamas stemingas ir lemavimas, kurių abudu variantai įrašomi į failus.

modeling.ipynb - ieškomas geriausias derinys problemai spręsti. Palyginamas Lematizavimas ir Stemingas. Išbandomi skirtingi vektorizavimo būdai kaip Word2Vec, TF-IDF;
Su kiekvienu vektorizacijos būdu pritaikomi įvairūs modeliai palyginimui - CNN (Convoliutonial Neural Networks), SVC (Support Vector Classifiers), LSTM (Long-Short term memory model).
Gauti rezultatai, išvados ir rekomendacijos aprašytos modeling faile.
