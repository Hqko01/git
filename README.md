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
   <br>![enter image description here](data:image/jpeg;base64,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)
