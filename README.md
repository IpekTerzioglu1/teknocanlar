# teknocanlar

## ÖZET
Bu araç bütçe düzenlemesi ve bankacılık promosyonlarına erişim kolaylığı sağlayacak. Tüketici alışkanlıklarını harcamalar üzerinden öğrenip kullanıcıya en uygun kampanyaları öneri olarak sıralayacak. Bütçe düzenlemesi kısmında faturalar, mobil ödemeler, kredi kartı ödemeleri tarihleri tutulacak ve de aile planlaması seçeneği olacak. 

## Kullanılacak Teknolojiler
1. ML
2. NLP
   - Kelimeleri anlamına göre değerlendirip buna uygun kampanya bulması sağlanacak.
3. Data Mining
   - Scraper kullanıllarak internetten bilgi alıp işlenecek.
4. Database
   - PostgreSQL
5. C++
6. Proje yönetimi için Git&GitHub kullanılacak.

## RoadMap
1- Database şeması oluşturulacak.(users, payments, campaigns...)
2- Database relationships birbirine bağlı olan verilerin arasındaki ilişkilerin belirlenmesi.-->PostgreSQL-->Bu dataların AES-256 kullanılarak şifrelenmesi.
3- Scraperın geliştirilmesi, çekilen verilerin düzenlenip aktarımı için pipeline kurulması.
4- NLP ile metin analizi yapıldıktan sonra c++ ile yazılan algoritmalardan bu verilerin geçirilmesi. (c++ düşük ram belleği kullanmak için)
5- Mobil bankacılıklara erişim lisansımız olmadığı için mock data oluşturacağız bireyler için.(bu ya kendin bir sanal bankacılık ya da mock datasetler oluşturularak yapılabilir)
6- Kimlik doğrulama ve aile birikim yönetimi sistemlerinin eklenmesi.
