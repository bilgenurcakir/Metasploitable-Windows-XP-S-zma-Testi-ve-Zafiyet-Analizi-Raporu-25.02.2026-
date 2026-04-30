Penetration Testing Lab: Metasploitable & Windows XP
Bu proje, kontrollü bir laboratuvar ortamında gerçekleştirilen uçtan uca sızma testi sürecini ve elde edilen bulguların raporlanmasını içermektedir. Çalışma kapsamında ağ keşfi, zafiyet tespiti, exploit kullanımı ve sistem üzerinde kalıcılık sağlama adımları uygulanmıştır.

🛡️ Uygulanan Senaryolar
1. Metasploitable (Linux) Sızma Testi

Keşif: netdiscover ve nmap araçları ile servis ve port taraması.

İstismar: vsftpd 2.3.4 backdoor zafiyeti ve Samba usermap_script exploitleri ile root erişimi.

Kalıcılık: Sistemde yetkili kullanıcı oluşturma ve Meterpreter oturumuna yükseltme.

2. Windows XP (MS08-067) Sızma Testi

Zafiyet: Uzaktan kod yürütmeye izin veren NetAPI (MS08-067) açığının tetiklenmesi.

CTF/Post-Exploitation: Sistem üzerinde dosya sistemi araması yapılarak gizli bayrağın (flag) ele geçirilmesi.

🛠️ Kullanılan Araçlar
İşletim Sistemi: Kali Linux

Tarama/Keşif: Nmap, Netdiscover

Exploitation Framework: Metasploit (MSFConsole)

Payloads: Meterpreter

📄 Rapor İçeriği
Proje içerisinde yer alan sibervatan_rapor.pdf dosyası, tüm adımların ekran görüntülerini ve teknik açıklamalarını içeren detaylı bir dokümantasyondur.
