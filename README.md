# Monitor jaringan dengan EtherApe di Ubuntu dan GNU\Linux lainnya

Salah satu aplikasi yang menarik digunakan untuk memonitor jaringan di Ubuntu ataupun GNU\linux lainnya adalah EtherApe yang dapat memperlihatkan detail trafik dan node-node yang terhubung dengan kita dalam jaringan dengan tampilan grafis yang memperliharkan laju trafik dan node-node yang terhubung, tertarik??

Monitor Jaringan Linux dengan EtherApe
Memonitor Jaringan Dengan EtherApe
Install EtherApe, kebetulan saya menggunakan Ubuntu, yang menggunakan distro selain turunan ubuntu dan debian bisa download di http://etherape.sourceforge.net/. Buka terminal ketik.
### `sudo apt-get install etherape`

Aplikasi dapat jalan dalam mode root jadi pada terminal ketik
sudo etherape

Untuk memonitor interface mana yang akan di monitor pada menu Captute–>Interface–>Pilih interface mana misalnya eth0 atau wlan0 atau ppp0 untuk dial-up modem. Atau untuk cepatnya saat membuka aplikasi etherape dan ingin memonitor jaringan woreless melalui terminal ketik.
### `sudo etherape -i wlan0`

dan untuk melihat detail trafik dalam bentuk tabel-tabel angka pilih menu View–>Protokols/Nodes

[Sumber](https://untukkami.wordpress.com/2012/01/20/monitor-jaringan-dengan-etherape-di-ubuntu-dan-gnulinux-lainnya/)
