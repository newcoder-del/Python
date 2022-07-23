# Global-AI-Hub-Project-1

## Proje Hakkında
 Kullanıcı tarafından verilen öğrencilerin ders notlarını hesaplayan ve sonuçları pandas yardımıyla excel tablosu oluşturan uygulama.
 
## Projede istenenler

Bu projede bir öğrenci not sistemi oluşturacaksınız. Sizden istenilenler:
Kendinize bir ders belirleyiniz. (Matematik,Fizik, Lineer Cebir vb.) Not aralığınızı oluşturunuz (100-80 ⇒ A, 79-70 ⇒ B vb.) Öğrenci Bilgilerini (Ad, Soyad, Okul No, sınav puanı) girebileceğiniz ve bu bilgilerin tutulabileceği bir sistem oluşturunuz. Girilen bilgilerden yola çıkarak öğrencinin dersi geçip geçmediğini göstermesi gerekmektedir. Öğrenci dersi geçti ise öğrencinin bilgilerinin tutulduğu alana “Geçti” yazısı, öğrenci dersi geçemedi ise “kaldı” yazısını göstermesi gerekmektedir. Notları girilen öğrencilerden dersi geçenleri ve geçmeyenleri gösteren bir Dataframe oluşturunuz. Oluşturulan Dataframe’i Excel tablosuna dönüştürünüz.

## Proje içindeki dosyalar
* proje 1


##  Uygulamanın akışı

Kullanıcıdan aldığı inputlarla öğrenci listesi oluşturur.

![image](https://user-images.githubusercontent.com/93267352/180609585-d81ae4a2-6d50-4d23-bc65-7ed20fa4fd2a.png)


for döngüsü içinde compute_grade ile notlar belirlendi ve Grade_file a kaydedildi.

![image](https://user-images.githubusercontent.com/93267352/180609610-34bf7c23-3413-483c-9c51-ed89cdd45e7c.png)


Grade_file (yazılacak txt) dosyası oluşturulur vePandas yardımıyla oluşturalacak excel dosyası için Sütun değerli listesi girilir.
![image](https://user-images.githubusercontent.com/93267352/180609653-6ec566a4-e0a3-4df1-82cb-6466c6959113.png)


