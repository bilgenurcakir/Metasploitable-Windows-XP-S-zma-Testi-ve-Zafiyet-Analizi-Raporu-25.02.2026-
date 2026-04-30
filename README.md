
🛡️ Penetration Testing Lab: Metasploitable & Windows XP

Bu proje, kontrollü bir laboratuvar ortamında gerçekleştirilen uçtan uca sızma testi sürecini ve elde edilen bulguların raporlanmasını içermektedir.

Çalışma kapsamında aşağıdaki adımlar uygulanmıştır:

* Ağ keşfi (Reconnaissance)
* Zafiyet tespiti (Vulnerability Analysis)
* Exploit kullanımı (Exploitation)
* Sistem üzerinde kalıcılık sağlama (Persistence)

⸻

📌 Senaryo 1: Metasploitable (Linux) Sızma Testi

🔍 Keşif

* netdiscover ve nmap kullanılarak hedef sistem tespit edildi
* Açık portlar ve servisler analiz edildi

💥 İstismar (Exploitation)

* vsftpd 2.3.4 backdoor zafiyeti kullanıldı
* Samba usermap_script exploit ile sistem ele geçirildi
* Root erişimi sağlandı

🔐 Kalıcılık (Persistence)

* Sisteme yetkili kullanıcı eklendi
* Meterpreter oturumu yükseltilerek erişim sürdürülebilir hale getirildi

⸻

📌 Senaryo 2: Windows XP (MS08-067) Sızma Testi

⚠️ Zafiyet

* MS08-067 (NetAPI) açığı kullanılarak uzaktan kod çalıştırıldı

🏴 Post-Exploitation / CTF

* Dosya sistemi tarandı
* Gizli bayrak (flag) başarıyla ele geçirildi

⸻

🛠️ Kullanılan Araçlar

* İşletim Sistemi: Kali Linux
* Tarama & Keşif:
    * Nmap
    * Netdiscover
* Exploitation Framework:
    * Metasploit (MSFConsole)
* Payload:
    * Meterpreter

⸻

📄 Rapor

Proje kapsamında hazırlanan sibervatan_rapor.pdf dosyası şunları içermektedir:

* Tüm adımların detaylı açıklamaları
* Gerçekleştirilen işlemlerin ekran görüntüleri
* Teknik analiz ve bulgular
