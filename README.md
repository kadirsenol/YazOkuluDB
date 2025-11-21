## SQL Server Ayarları ve Veritabanı Oluşturma - README

- Repoya gönderilen `YazOkuluDbScript.sql` dosyası SQL Server Management Studio (SSMS) içerisinden çalıştırılarak script uygulanır. Bu işlem sonrası kullanıcılar, tablo şemaları ve datalar ile veritabanı oluşturulacaktır.

- NOT!= Backend projesi Docker ile çalıştırıldığında, Docker içerisinden local makinadaki veritabanına erişim sağlanabilmesi için TCP/IP ayarının etkinleştirilmesi gerekir. Aşamalar şu şekildedir:
1. `C:\Windows\SysWOW64\SQLServerManager16.msc` adresinde bulunan **SQLServerManager16** çalıştırılır.
2. **SQL Server Network Configuration → Protocols for MSSQLSERVER → TCP/IP** ayarı `Enable` olarak değiştirilir.
3. **SQL Server Services → SQL Server (MSSQLSERVER)** seçeneğine sağ tıklayıp `Restart` edilir.
