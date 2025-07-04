# NLP Sentiment Analysis
## NLP Sentiment Analysis Project
About the Dataset
The dataset used in this project consists of tweets collected from Twitter. Sentiment labels (positive, negative, neutral) were assigned automatically—for example, tweets containing :) were labeled positive, and those with :( were labeled negative. The dataset dates back to 2009 and contains 6 fields: sentiment label, tweet ID, date, query, username, and tweet text, with emoticons removed.

What I Did in This Project
Cleaned the tweet texts: converted to lowercase, expanded contractions, removed URLs and special characters, filtered out stopwords, and lemmatized words to their base forms.

Applied sentiment analysis using the VADER tool to assign numeric sentiment scores (0: negative, 1: neutral, 2: positive) to each tweet.

Performed the same preprocessing steps on both training and test datasets.

Tested several machine learning models—Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting—using TF-IDF and Count Vectorizer methods.

Created a function that automatically selects the best model-vectorizer combination based on accuracy and visualizes the results using a confusion matrix.



## NLP Duygu Analiz Projesi
Veri Seti Hakkında
Bu proje için kullandığım veri seti, Twitter’dan toplanmış tweetleri içeriyor. Tweetlerin pozitif, negatif veya nötr olduğunu belirtmek için otomatik etiketleme yapıldı; örneğin, içinde :) olanlar pozitif, :( olanlar negatif kabul edildi. Veri seti 2009 yılına ait ve ham haliyle emojiler kaldırılmış, 6 alan içeriyor: duygu (sentiment) etiketi, tweet ID, tarih, sorgu kelimesi, kullanıcı adı ve tweet metni.

Projede Yaptıklarım
Tweet metinlerini temizledim: Küçük harfe çevirme, kısaltmaları açma, URL ve özel karakterleri kaldırma, stopword’leri çıkarma ve kelimeleri köklerine indirgeyen (lemmatize eden) işlemler yaptım.

Temizlenmiş metinlere duygu analizi uyguladım ve VADER aracıyla her tweetin duygu skorunu sayısal olarak (0: negatif, 1: nötr, 2: pozitif) belirledim.

Eğitim ve test verileri üzerinde aynı ön işlemleri uyguladım.

Logistic Regression, Decision Tree, Random Forest ve Gradient Boosting gibi çeşitli makine öğrenmesi modellerini, TF-IDF ve Count Vectorizer yöntemleriyle birlikte test ettim.

En iyi doğruluk (accuracy) veren model-vektörleştirici kombinasyonunu otomatik olarak seçen ve sonuçları karışıklık matrisi ile görselleştiren bir fonksiyon yazdım.

