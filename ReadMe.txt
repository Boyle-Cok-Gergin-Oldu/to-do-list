



				===============================================
						KULLANIM KILAVUZU
				===============================================

Projede her bir değişiklik yaptığımızda, örneğin arayüz sayfalarından bir kaç tanesini oluşturduktan
sonra bunları sisteme yüklemek için unity projemizi kaydediyoruz. Ardından terminali açıp projemizin olduğu klasörün içerisine
"cd klasör_adı" ile giriş yapmamız lazım.



				=========================================
				 Oluşturduğumuz dosyaları göndermek için
				=========================================

=======  =======================================================================================================================
=UYARI=  Dosya göndermeden önce sistemdeki dosyaları çekmeyi unutmayın. Yoksa yanlışlıkla başkasının çalışmasını silebilirsiniz!
=======  =======================================================================================================================

1) Değişiklikleri git sistemine tanıtmak için;

git add .

komutunu kullanıyoruz. (add kelimesinden sonra "." olduğunu unutmayın. Bu bütün dosyaları seçmenizi sağlar. "." Kullanmayacaksanız direkt değiştirdiğiniz
ya da eklediğiniz dosyanın dizinini yazabilirsiniz.

=========================================================================================================================================================

2) Değişiklik hakkında güncelleme mesajı bırakmak için;

git commit -m "Buraya güncelleme mesajı yazılacak"

bu komut github üzerinde yaptığımız güncellemelerde neyi değiştirdiğimizi diğer ekip üyelerine anlatacak kısaca.
Örneğin "Ana ekran tasarımı eklendi", "Market arayüzü eklendi", "Veri tabanı güncellendi" gibi yaptığımız işi kısaca anlatacak mesajlar yazılacak.

=========================================================================================================================================================

3) Dosyaları github reposuna göndermek için;

git push -u origin main

bu komut dosyaları github reposu

=========================================================================================================================================================
=========================================================================================================================================================

				==============================================
				Repo'ya eklenen dosyaları klasöre eklemek için
				==============================================

1) Repodaki dosyaları indirmek için;

git pull

bu komut ile basitçe bütün eksik ya da güncellenmiş olan dosyaları bilgisayarımıza indirebiliyoruz.

=========================================================================================================================================================
