<h1>AĞ TEMELLERİ ÇALIŞMA REHBERİ</h1>

<div class="section">
<h2>1. BÖLÜM: VERİ HABERLEŞMESİNE GİRİŞ</h2>

<h3>1.1 Ağ (Network) Nedir?</h3>
<p>Ağ, bilgi paylaşımı, iletişim ve kaynak kullanımını sağlamak amacıyla birbirine bağlanmış cihazlar topluluğudur.</p>

<h3>Ağ Kullanım Amaçları</h3>
<ul>
<li>Dosya paylaşımı</li>
<li>Yazıcı gibi donanımların ortak kullanımı</li>
<li>İnternet erişimi</li>
<li>İletişim (e-posta, mesajlaşma)</li>
</ul>

<h3>Veri Akış Yönleri</h3>
<ul>
<li><b>Simpleks (Simplex):</b> Veri tek yönlüdür (Radyo/TV)</li>
<li><b>Yarım Dubleks (Half-Duplex):</b> Veri iki yönlüdür ama aynı anda iletilemez (Telsiz)</li>
<li><b>Tam Dubleks (Full-Duplex):</b> Veri aynı anda iletilebilir (Telefon)</li>
</ul>

<h3>Ağ Performans Terimleri</h3>
<ul>
<li><b>Bant Genişliği:</b> Maksimum veri kapasitesi</li>
<li><b>Throughput:</b> Gerçek iletilen veri miktarı</li>
</ul>

<h3>1.2 Ağ Bileşenleri</h3>

<h4>Uç Cihazlar</h4>
<ul>
<li>Bilgisayar (PC, Laptop)</li>
<li>Akıllı telefon</li>
<li>Tablet</li>
<li>Sunucu (Server)</li>
<li>Yazıcı</li>
</ul>

<p><b>Not:</b> IP adresi bu cihazlara atanır.</p>

<h4>Ara Cihazlar</h4>
<ul>
<li><b>Switch:</b> Aynı ağ içindeki cihazları bağlar, MAC adresi ile çalışır</li>
<li><b>Router:</b> Farklı ağları bağlar, IP ile çalışır</li>
<li><b>Firewall:</b> Güvenlik sağlar</li>
</ul>

<h4>Ağ Ortamı</h4>
<ul>
<li><b>Bakır Kablolar (UTP/STP)</b></li>
<li><b>Fiber Optik</b></li>
<li><b>Kablosuz (Wi-Fi, Bluetooth, 4G/5G)</b></li>
</ul>

<h3>1.3 Ağ Türleri</h3>
<ul>
<li><b>PAN:</b> Kişisel ağ (~1-10m)</li>
<li><b>LAN:</b> Yerel ağ (ev, okul)</li>
<li><b>MAN:</b> Şehir ağı</li>
<li><b>WAN:</b> Geniş ağ (İnternet)</li>
</ul>

<h3>1.4 Özet Tablo</h3>
<table>
<tr><th>Ağ Türü</th><th>Kapsam</th><th>Örnek</th></tr>
<tr><td>PAN</td><td>Kişisel</td><td>Bluetooth</td></tr>
<tr><td>LAN</td><td>Yerel</td><td>Okul ağı</td></tr>
<tr><td>MAN</td><td>Şehir</td><td>Kampüs</td></tr>
<tr><td>WAN</td><td>Global</td><td>İnternet</td></tr>
</table>

</div>

<div class="section">
<h2>2. BÖLÜM: AĞ TOPOLOJİLERİ</h2>

<h3>2.1 Ağ Topolojisi Nedir?</h3>
<p>Cihazların fiziksel veya mantıksal bağlanma şeklidir.</p>

<h3>2.2 Fiziksel ve Mantıksal Topoloji</h3>
<ul>
<li>Fiziksel: Gerçek bağlantı şekli</li>
<li>Mantıksal: Verinin hareketi</li>
</ul>

<h3>2.3 Temel Topolojiler</h3>

<h4>Star (Yıldız)</h4>
<div class="note">
Avantaj: Kolay kurulum, arıza tespiti kolay<br>
Dezavantaj: Switch bozulursa tüm ağ gider
</div>

<h4>Bus (Yol)</h4>
<div class="note">
Avantaj: Ucuz<br>
Dezavantaj: Ana kablo koparsa ağ gider
</div>

<h4>Mesh</h4>
<div class="note">
Avantaj: Çok güvenilir<br>
Dezavantaj: Pahalı ve karmaşık
</div>

<h4>Ring (Halka)</h4>
<div class="note">
Avantaj: Düzenli veri akışı<br>
Dezavantaj: Bir cihaz bozulursa ağ etkilenir
</div>

<h3>2.4 Karşılaştırma</h3>
<table>
<tr><th>Topoloji</th><th>Güvenilirlik</th><th>Maliyet</th><th>Kullanım</th></tr>
<tr><td>Star</td><td>Orta</td><td>Orta</td><td>Yaygın</td></tr>
<tr><td>Bus</td><td>Düşük</td><td>Düşük</td><td>Eski</td></tr>
<tr><td>Mesh</td><td>Çok yüksek</td><td>Çok yüksek</td><td>Özel</td></tr>
<tr><td>Ring</td><td>Orta</td><td>Orta</td><td>Nadir</td></tr>
</table>

</div>

<div class="section">
<h2>3. OSI MODELİ</h2>

<table>
<tr><th>Katman</th><th>Ad</th><th>Görev</th></tr>
<tr><td>7</td><td>Uygulama</td><td>HTTP, FTP</td></tr>
<tr><td>6</td><td>Sunum</td><td>Şifreleme</td></tr>
<tr><td>5</td><td>Oturum</td><td>Bağlantı yönetimi</td></tr>
<tr><td>4</td><td>Taşıma</td><td>TCP/UDP</td></tr>
<tr><td>3</td><td>Ağ</td><td>IP</td></tr>
<tr><td>2</td><td>Veri Bağı</td><td>MAC</td></tr>
<tr><td>1</td><td>Fiziksel</td><td>Bitler</td></tr>
</table>

</div>

<div class="section">
<h2>4. AĞ DONANIMLARI</h2>

<ul>
<li><b>Hub:</b> Tüm portlara gönderir</li>
<li><b>Switch:</b> Hedefe gönderir</li>
<li><b>Router:</b> Ağlar arası bağlantı sağlar</li>
<li><b>Modem:</b> Analog-dijital dönüşüm</li>
</ul>

<h3>MAC vs IP</h3>
<ul>
<li><b>MAC:</b> Fiziksel adres (değişmez)</li>
<li><b>IP:</b> Mantıksal adres (değişir)</li>
</ul>

</div>

<div class="section">
<h2>5. İLETİŞİM PROTOKOLLERİ</h2>

<h3>TCP</h3>
<ul>
<li>Güvenilir</li>
<li>Yavaş</li>
<li>HTTP, FTP, SMTP</li>
</ul>

<h3>UDP</h3>
<ul>
<li>Hızlı</li>
<li>Güvenilmez</li>
<li>Oyun, video, VoIP</li>
</ul>

<h3>Portlar</h3>
<ul>
<li>HTTP → 80</li>
<li>HTTPS → 443</li>
<li>DNS → 53</li>
</ul>

</div>

</body>
</html>
