# Nereye Gidelim? – Seyahat Tercihi Tahmini (Content-Based Travel Recommendation)

## Proje Tanımı / Project Description

Bu proje, TripAdvisor otel yorumları üzerinden kullanıcıların tercihlerini anlamak ve benzer otel yorumlarını önererek kişiselleştirilmiş seyahat tavsiyeleri sunmak amacıyla geliştirilmiştir.  
TF-IDF metin vektörleştirme ve kosinüs benzerliği kullanılarak içerik-temelli öneri sistemi oluşturulmuştur. Ayrıca, kullanıcının birden fazla beğendiği yoruma göre profil çıkarılarak öneri doğruluğu artırılmıştır.

This project is developed to understand user preferences from TripAdvisor hotel reviews and provide personalized travel recommendations by suggesting similar hotel reviews.  
A content-based recommendation system is built using TF-IDF text vectorization and cosine similarity. Moreover, user profiles are created from multiple liked reviews to improve recommendation accuracy.

## Kullanılan Teknolojiler / Technologies

- Python 3  
- Pandas & NumPy  
- Scikit-learn (TF-IDF, Cosine Similarity)  

## Projede Yapılanlar / What Has Been Done

- Veri yükleme, ön inceleme ve görselleştirme  
- Otel yorumlarının TF-IDF ile sayısal vektörlere dönüştürülmesi  
- Cosine similarity matrisi ile yorum benzerliklerinin hesaplanması  
- Tek bir yoruma benzer en iyi önerilerin sunulması  
- Kullanıcı beğenilerine göre profil oluşturulması ve kişiselleştirilmiş öneriler  
- Sonuçların kolay yorumlanabilmesi için tablo ve grafiklerle desteklenmesi

- Data loading, exploratory analysis, and visualization  
- Converting hotel reviews into numerical vectors using TF-IDF  
- Calculating review similarities with cosine similarity matrix  
- Recommending top similar reviews for a single review  
- Creating user profiles from liked reviews for personalized suggestions  
- Supporting results with tables and plots for easy interpretation

  ---
  
