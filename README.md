# Sorting_Products
Sorting IMDB Movie

![image](https://github.com/furkansukan/Sorting_Products/assets/115731123/b9c7032c-aed1-4e79-ae03-96357878f908)



Ürünleri farklı ölçütlere göre sıralamak için kullanılan işlemleri içermektedir. İki farklı uygulama örneği vardır: "Kurs Sıralama" ve "IMDB Film Puanlama ve Sıralama".

"Kurs Sıralama" uygulamasında, bir kursun sıralamasını belirlemek için çeşitli faktörler kullanılır. İlk olarak, kursları "rating" (puanlama) ölçütüne göre sıralamak için kullanılan kod parçacığı bulunmaktadır. 

Ardından, "purchase_count" (satın alma sayısı) ve "comment_count" (yorum sayısı) ölçütlerine göre sıralama yapılır. 

Son olarak, bu üç faktörü ağırlıklı olarak hesaplayarak "weighted_sorting_score" (ağırlıklı sıralama puanı) oluşturulur ve kurslar bu puanı kullanılarak sıralanır.

"Bayesian Average Rating Score" kısmında, "bar_score" (Bayesian ortalama puanı) hesaplamak için bir fonksiyon kullanılır. 

Bu hesaplama, kullanıcıların puanlama verilerine dayanarak bir ürünün gerçek puanını tahmin etmek için Bayesian yöntemini kullanır.

Bu puanlama yöntemi kullanılarak kurslar sıralanır.

Son olarak, "Hybrid Sorting" bölümünde, "bar_score" ve "weighted_sorting_score" puanları birleştirilerek "hybrid_sorting_score" (karma sıralama puanı) oluşturulur ve kurslar bu puan kullanılarak sıralanır.

"IMDB Movie Scoring & Sorting" uygulamasında ise, IMDB film veri seti kullanılarak filmlerin puanlaması ve sıralaması yapılır.

Önce "vote_average" (ortalama oy) ölçütüne göre sıralama yapılır. Ardından, "vote_count" (oy sayısı) ölçütüne göre sıralama yapılır.

"weighted_rating" (ağırlıklı puanlama) ve "bar_score" (Bayesian ortalama puanı) hesaplamaları yapılır ve filmler bu puanlara göre sıralanır.

Bu kod parçacığı, ürün veya film sıralaması için farklı ölçütleri kullanarak istediğiniz sıralamayı elde etmenizi sağlar.

Ölçütler arasındaki ağırlıklandırmayı ayarlayarak kendi sıralama algoritmalarınızı oluşturabilirsiniz.
