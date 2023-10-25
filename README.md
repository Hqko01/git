# Merhaba 👋

**Git** komutları ve kullanımları.
<br>
## Dosya yükleme - klonlama
Deponun olmasını istediğimiz klasörü açıyoruz bir **terminal** çalıştırıyoruz.

    git clone depobağlantıadresi
 bu kodu **terminale** yazıyoruz bu şekilde klasörümüze **bağlantı adresini girdiğimiz depo** klonlanmış oluyor.
  

    git status
   Bu kod ile  **commit durumunu** görüntüleyebiliriz.
  <br>
  Dosyaları **depoya yüklemek** için sırasıyla bu kodları uyguluyoruz.
  

    git add .
    git commit -m "açıklama"
    git push origin main
Bu komut ile ilk başta **klonladığımız depo** güncellenmiş oluyor.
 #
**Commit`i geri çekmek** için **revert** komudunu kullanıyoruz.

    git revert commitID
 <br>
 
 ## Branch Komutları

**Dalları** görüntüleme komudu.

    git branch
    
**Dal** oluşturma komudu.
  

    git branch isim
   **Dallar arası geçiş** yapma
   

    git checkout name
   <br>
   
   ## Dosya çekme - PULL
   

    git pull
   **Depo ile bağlantı** sağladığınıza dikkat edin.
 
<br>

<img src="https://images.app.goo.gl/j7sUmUuQ1iA1pDsY7">