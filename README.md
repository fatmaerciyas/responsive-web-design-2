# web-design-2

## Responsive web sitesi tasarımı

Responsive tasarım: Duyarlı web tasarımı, web sayfalarının çeşitli cihazlarda ve pencere veya ekran boyutlarında iyi görüntülenmesini sağlayan
web tasarımına bir yaklaşımdır. Hazırladığım web sitesi bilgisayar, tablet ve telefon uyumludur.

* Flex yapısı kullanıldı.
* Ekranın max genişliği 980px'in altına düşünce tablet uyumluluğu,
* max genişlik 600px'in altına düşünce telefon uyumluluğunu yakalayacaktır.

* İçerikteki yazılar latincedir. Amacım responsive web sitesi yapmak olduğu için yazılara özenmedim.
* iconlar fontawesome.com'dan alınmıştır.

* Site başta banner sonra 3 section ve son olarak footer bölümü olmak üzere toplam 5 bölümden oluşmaktadır.
* Bu bölümlerin hepsi bir wrapper'ın içinde bulunmaktadır.

### 1.bölüm
* Bu bölümde header, menu, h2, p ve butonumuz bulunmaktadır.
* Tablet ve bilgisayarlarda header(title yazan kısım) görünürken telefonlarda menü ile birbirlerine karışmaması için görünmemektedir.
* 1.Bölümün bilgisayar görüntüsü;




![Ekran Görüntüsü (15)](https://user-images.githubusercontent.com/55760365/89786873-4cfad000-db25-11ea-9fe8-b8953993964c.png)




* 1 bölümün tablet görüntüsü;




![Ekran Görüntüsü (16)](https://user-images.githubusercontent.com/55760365/89787605-6b150000-db26-11ea-85cd-d6289d9f6534.png)




* 1 bölümün telefon görüntüsü;




![Ekran Görüntüsü (17)](https://user-images.githubusercontent.com/55760365/89787614-70724a80-db26-11ea-8b65-5b93272befa4.png)




### 2.bölüm

* Bu bölümde h2, p tagı, kutular divi ve kutular divinin içinde 3 tane kutu bulunmaktadır.
* Her kutunun içinde 1 resim 1 h3 başlık ve p tagı bulunmaktadır.

* 2.Bölümün bilgisayar görüntüsü;



![Ekran Görüntüsü (18)](https://user-images.githubusercontent.com/55760365/89788825-67827880-db28-11ea-8ee7-ee1765957b92.png)



* 2.Bölümün tablet görüntüsü;

![Ekran Görüntüsü (19)](https://user-images.githubusercontent.com/55760365/89788906-82ed8380-db28-11ea-998c-ee3d12e49347.png)

![Ekran Görüntüsü (20)](https://user-images.githubusercontent.com/55760365/89788913-85e87400-db28-11ea-90e7-647de4feac5d.png)

* 2.Bölümün telefon görüntüsü;

![Ekran Görüntüsü (21)](https://user-images.githubusercontent.com/55760365/89789114-d6f86800-db28-11ea-817c-fbe3831e8406.png)

![Ekran Görüntüsü (22)](https://user-images.githubusercontent.com/55760365/89789145-e24b9380-db28-11ea-9586-f72b8431f9fb.png)



### 3.bölüm

* Bu section 2. bölümle neredeyse aynı mantıktır. "kisiler" adlı divin içinde 4 adet "kisi" adında div bulunmakta ve divlerin içi yazı ve resimle doldurulmaktadır.
* Her bir "kisi" divinin tabletlerde ikişerli, telefonlarda tekli olarak yukarıdan aşağıya hizalanması için flex-wrap yapısı wrap yapılmıştır.


* 3.Bölümün bilgisayar görüntüsü;

![Ekran Görüntüsü (23)](https://user-images.githubusercontent.com/55760365/89789210-f7282700-db28-11ea-9364-847b5d77ea0b.png)



* 3.Bölümün tablet görüntüsü;


![Ekran Görüntüsü (24)](https://user-images.githubusercontent.com/55760365/89789262-09a26080-db29-11ea-8fe3-9cef7d7aa650.png)



* 3.Bölümün telefon görüntüsü;

![Ekran Görüntüsü (25)](https://user-images.githubusercontent.com/55760365/89789323-19ba4000-db29-11ea-8267-0362b06ff74c.png)

![Ekran Görüntüsü (26)](https://user-images.githubusercontent.com/55760365/89789329-1b840380-db29-11ea-85d5-835a5b7056bc.png)


### 4. bölüm

* 2 text, 1 textarea ve 1 butondan oluşmaktadır.
* Mobil görünümünde hepsi alt alta hizalanacak ve ekranın %80 ini kaplayacaktır.



* 4.Bölümün bilgisayar görüntüsü;


![Ekran Görüntüsü (27)](https://user-images.githubusercontent.com/55760365/89789363-2c347980-db29-11ea-86e7-dbe45d1a71d6.png)


* 4.Bölümün tablet görüntüsü;


![Ekran Görüntüsü (28)](https://user-images.githubusercontent.com/55760365/89789370-2e96d380-db29-11ea-805a-e30f29daf282.png)



* 4.Bölümün telefon görüntüsü;


![Ekran Görüntüsü (29)](https://user-images.githubusercontent.com/55760365/89789378-30609700-db29-11ea-9376-06e99fdeae7d.png)




### 5.bölüm(footer)

* Bölüm 4 başlık ve her başlığın altında 4'er link olmak üzere 16 linkten ve 3 icondan oluşmaktadır.
* Normalde sitelerde önceki yazılar veya kullanıcının dikkatini çekebilecek sayfaların linkleri verilir.
* Tablet görünümünde ikişer başlık yan yana görünürken telefon görünümünde tekli olarak başlıklar, linkler ve iconlar yukarıdan aşağıya hizalanır. 


* 5.Bölümün bilgisayar görüntüsü;


![Ekran Görüntüsü (30)](https://user-images.githubusercontent.com/55760365/89789464-4e2dfc00-db29-11ea-86cd-b192834e27a0.png)



* 5.Bölümün tablet görüntüsü;


![Ekran Görüntüsü (31)](https://user-images.githubusercontent.com/55760365/89789493-54bc7380-db29-11ea-8340-e6803de0a1a1.png)

* 5.Bölümün telefon görüntüsü;


![Ekran Görüntüsü (32)](https://user-images.githubusercontent.com/55760365/89789562-6dc52480-db29-11ea-8953-c8dcbdb63691.png)

![Ekran Görüntüsü (33)](https://user-images.githubusercontent.com/55760365/89789565-6f8ee800-db29-11ea-94e2-f322dd852a47.png)
