# Proje 1

##### Oturduğunuz mahallenin muhtarı ikametgah bilgilerinin saklamak ve her yeni vatandaş için hazırlanan dilekçe işini otomatize etmek için sizden küçük bir yazılım istedi.
Yapmanız gerekenler:
- input() fonksiyonu ile kimlik numarası, isim, soyisim, sokak ismi bilgilerini alın ,4 tane input() fonksiyonu
  kullanabilirsiniz.
  
- her bir vatandaşın bilgisi bir listede olacak şekilde tüm listeleri database isimli bir listeye ekleyin, append() fonksiyonu kullanabilirsiniz<br>
	`database=[ [tc1, isim1, soyisim1, sokak1], [tc2, isim2, soyisim2, sokak2],[tc3, isim3, soyisim3, sokak3]]`<br>
	3 vatandaşlı bir mahalle için örnek database yukarıda
  
- f-string yada format() fonksiyonu kullanarak aşağıdaki stringi print() fonksiyonu ile yazdırın <br>
		```dilekçe= """ İçişleri Bakanlığına
	{kimlik numarası} kimlik numaralı {isim} {soyisim} x mahallesi {sokak ismi} sokakda ikamet etmektedir."""```
