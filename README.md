# BayrakQuiz
## Kullanılan Teknolojiler:
1. Activity arası geçişler (Intent) 
2. Sqlite veritabani
3. Hashmap yardımı ile oluşturulan nesnelerin bir list üzerinde dağınık halde tutulması
4. Activityler arası nesne aktarımı

## Özet
Uygulama 3 adet Activityden oluşuyor ve sırasıyla şu şekilde; MainActivity,QuizActivity,ResultActivity. İlk Activity olan MainActivitynin görevi aslında bir karşılama
sayfası oluşturmak ve Quiz başlamadan önce kullanıcının kendini hazırlmasını sağlamak. Başla buttonuna basarak Quiz Activitye gecip Quizin başlamasını sağlayabilirsiniz
ardından Quiz Activity üzerinde kullanıcıyı 5 sorudan oluşan ve 4 şık seçeneğine sahip olan test sistemi karşılıyor ekranın saol üstünden doğru sayısını sağ üstünden ise
yanlış sayısını görebilir. Şıklardaki tercihlerini yaptıktan sonra sorular bittiği zaman otomatik olarak bizi Result Activiye atıyor ve karşımıza iki adet textView ile 
sonuç bilgileri çıkıyor ilk textView üzerinde kaç adet doğru kaç adet yanlış olduğunu bize söylüyor ikinci textView üzerinde ise yüzdelik başarımızı hesaplayıp yeniden 
bize aktarıyor. İsterseniz tekrar dene buttonunu kullanıp yeniden QuizActivity sekmesine dönerek testi yeniden başlatabilirsiniz ya da geri tuşuna basarak Main Activity
üzerine gelebilirsiniz.
