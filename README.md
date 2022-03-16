# Sayı Tahmin Oyunu  

## 1. Seviye 
- Random modülü kullanılarak bilgisayar 1 ile 20 arasında bir tam sayı üretir. 
- Kullanıcının numarayı tahmin etmesi gerekir. Kullanıcı tahmini yazdıktan sonra, program ürettiği  sayıdan daha büyük mü yoksa daha küçük mü, yoksa aynı mı olduğunu söyler. 
- Oyun sadece bir tahminle biter.

## 2. Seviye 
- Kullanıcı birkaç kez tahmin edebilir.  
- Kullanıcı doğru sayıyı tahmin ettiğinde oyun sona erer.  

## 3. Seviye 
- Kullanıcı klavyeden "X-x" karakterine basarsa, sayıyı tahmin etmeden oyundan çıkar. 

## 4. Seviye 
- Kullanıcı klavyeden "S-s" karakterine basarsa, gizli değer gösterilir (hile modu)  

## 5. Seviye 
- Sonunda, her tahminden sonra gizli değerin değiştiği bir seviyeye sahip olacağız. Bu seviyeyi izleyebilmek ve hata ayıklamayı kolaylaştırmak için önce bir “debug mode” a sahip olmak istiyoruz. ∙ Kullanıcı "D-d" karakterine basarsa, oyun “debug mode” geçer: sistem, kullanıcıdan yeni giriş  istemeden hemen önce her seferinde tahmin edilmesi gereken mevcut sayıyı göstermeye başlar. ∙ Kullanıcı "D-d" karakterine tekrar basarsa hata ayıklama modunu kapatır. ("D" üzerine her basıldığında  bu mod açılır yada kapanır.)  

## 6. Seviye 
- "M-m" düğmesi ise başka bir geçiştir. Buna "hareket modu" denir. "Açık" olduğunda, gizli sayı her  adımdan sonra (+/- 2) şeklinde değişir. 
- Tekrar "M-m" karakterine basmak bu özelliği kapatır.  

## 7. Seviye 
- Kullanıcının birkaç oyun oynamasına izin verin. 
- "N-n" karakterine basmak mevcut oyunu atlayacak ve yeni bir oyun başlatacaktır. Tahmin etmek için  yeni bir numara üretir.
