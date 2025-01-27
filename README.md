# Configurasi Arduino-ESP8266 agar bisa di gunakan saat terhubung ke wifi arduino
<details open>
  <summary><strong><h2>How to Install</h2></strong></summary>
  <img src="https://github.com/haniefautophile-official/Arduino-ESP8266-WifiDeauther/blob/main/SS/20250127_141038.jpg"/>
  <li>langkah ke Nol install Driver CH340 lalu sambungkan module ESP8266 ke PC/Laptop. Dan lihat di device manager bagian PORT.</li>
  <li>langkah pertama Unduh file zip di github ini, klik code dan download zip.</li>
  <li>langkah kedua ekstrak file zip yg sudah di download tadi.</li>
  <li>langkah ketiga buka file yg sudah di ekstrak bernama esp8266_deauther dan cari file esp8266_deauther.ino lalu buka klik 2x pada file tersebut maka akan terbuka aplikasi esp8266_deauther.</li>
  <li>langkah kempat pilih nama file di aplikasi > preferences > Additional board manager url > pilih icon copy dan paste kode di bawah ini semuanya:
</li>

``` bash
https://arduino.esp8266.com/stable/package_esp8266com_index.json
https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
```
<li> Klik Ok dan klik ok lagi.</li>
  <li>langkah kelima pilih tools > Board Generic ESP8266 > Deauther ESP866 Board > Generic ESP8266.</code></li>
  <li>Langkah keenam masih di tools > Port > Pilih Port Yg sesuai yg ada ada di device manager.</li>
  <li>Langkah ketujuh klik upload dengan mengklik icon panah arah ke kanan, dan tunggu sampai selesai dan perhatikan indexing yg ada di pojok bawah kiri yg sedang berjalan. Jika selesai indexing maka close saja semuanya dan pindai wifi maka akan ada nama wifi pawned. Password wifi (deauther).</li>
  <li>Coba buka browser dan masukan alamat ip 192.168.4.1 dan akan di arahkan ke tampilan web arduino.</li>
  </details>
