# Kelompok5-Firewall
## Nama Anggota
    1.	Dian Novitasari     (21050974006)
    2.	Adib Bagus Subarkah (21050974039)
    3.	Yurie Enggarnisa    (21050974050)
    4.	Adinda Amelia Putri (21050974056)
    5.	Yoga Rizalda        (21050974068)
    
## Link Website Pendidikan Teknologi Informasi
https://pendidikan-ti.ft.unesa.ac.id/

## Deskripsi Project
<p align="justify"> Implementasi firewall menggunakan Debian di Virtual Mesin ini diharapkan dimana nantinya dapat membantu agar masyarakat terhindar dari kejahatan cyber yang menyusup kedalam jaringan kemudian mengambil data – data rahasia dan melumpuhkan sistem jaringan komputer. Pada implementasi kali ini memerlukan Firewall yang menggunakan debian, Firewall sendiri adalah sebuah sistem atau perangkat yang digunakan untuk mengizinkan lalu lintas jaringan yang dianggap aman untuk melaluinya dan mencegah lalu lintas jaringan yang dianggap tidak aman. Firewall umumnya diimplementasikan dalam sebuah mesin terdedikasi, yang berjalan pada pintu gerbang (gateway) antara jaringan lokal dan jaringan lainnya. Lalu juga membutuhkan Virtual Mesin dan PC Windows XP yangsemuanya di Install di dalam Virtual Mesin. </p>

## Langkah-langkah instal Debian pada VirtualBox
1. Buka VirtualBox, lalu Create Virtual Mechine, Kasih nama sesuai dengan apa yang akan kita buat, Lalu ubah Versi menjadi Debian.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/ff61aa24-3d58-4eac-b351-0d9a1e8c12e2)
2. Untuk ukuran memori kita gunakan 2000 Mb.
3. Buat hard disk virtual sekarang.
4. Pilih tipe berkas hard disk virtual yaitu VDI (virtualbox disk image)
5. Virtual mesin yang akan kita buat akan muncul, setelah itu pilih pengaturan, pilih jaringan adapter 1 NAT & adapter 2 Internal Network
    <img width="539" alt="image" src="https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/b926faf6-32fc-4ba2-a3fc-cad86409a292">
    <img width="548" alt="image" src="https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/50e7c1a8-6969-4ac4-a4d6-539e9e8b6a0e">
6. Setelah selesai mengatur jaringan, klik start dan pilih drive host yaitu file iso debian yang telah kita download.
7. Pilih Install
8. Pilih Bahasa yang akan digunakan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/17049a7b-6fc6-48ce-a628-d9940593e589)
9. Pilih layout keyboard yaitu Inggris Amerika.
10. Konfigurasi jaringan, pilih eth0, klik enter, kita tunggu hingga proses konfigurasi 100%
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/12fefd35-705c-4c1f-bbf4-93dba96e31ed)
11. Masukkan nama host sistem, setelah selesai masukan nama host sistem klik lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/650cb08b-f114-4876-8434-136d5269375b)
12. Masukkan nama domain, setelah selesai masukan nama domain klik lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/6403c120-6ea6-4526-8186-b005c055c2a9)
13. Konfigurasi waktu, setelah selesai konfigurasi klik lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/c0fa5c87-2ccf-45a9-a212-cbc5795cdf8f)
14. Partisi Hardisk, pilih terpandu--gunakan seluruh harddisk, lalu enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/852cb66b-0e98-4cc0-a1d6-b54297536165)
15. Pilih hardisk yang akan dipartisi, lalu enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/ebd1147d-bb1f-44d8-ae4d-053f00393b0d)
16. Pilih pola partisi, pilih "semua berkas di satu partisi (disarankan untuk pemula), lalu enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/d726b9c1-f775-4d7c-98c9-22530454cc72)
17. Pilih "Selesai mempartisi dan tulis perubahan-perubahannya ke hard disk, lalu enter
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/11d0065b-449b-46a0-b3c0-7be551d24fb8)
18. Pilih Ya untuk tuliskan perubahan yang terjadi pada hard disk, lalu enter, tunggu hingga memasang sistem dasar 100%.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/70a7c6b3-252f-4245-82a9-a1efdec212f5)
19. Menata pengguna dan kata sandi, masukkan kata sandi root, setelah selesai mengatur kata sandi pilih lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/a61333ee-6c67-4a3a-a5f8-f312d71fdaf9)
20. Masukkan lagi kata sandi untuk verifikasi.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/9ea26613-031f-49c0-95d8-21a57886a578)
21. Masukkan nama dari pengguna baru, setelah selesai pilih lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/65154fa6-894f-46ed-a160-98a69d20b73c)
22. Masukkan kata sandi untuk pengguna baru, setelah selesai mengatur kata sandi pilih lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/f457b790-ce76-403b-a30d-2f56b4e22c60)
23. Masukkan lagi kata sandi pengguna baru untuk verifikasi.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/09706c6b-ed2c-4bb5-8d27-63d8f93ce3ab)
24. Konfigurasi pengelola paket, pilih cd atau dvd lainnya pilih tidak, lalu enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/7f03e1f8-f864-415f-8354-032df6f04e67)
25. Konfigurasi pengelola paket, gunakan suatu jaringan cermin(mirror) pilih tidak, lalu enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/5ba409fd-216b-489c-b39d-9765f295da65)
26. Konfigurasi Popularity contest, Berpartisi dalam survey paket debian.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/8bad21a4-7da5-4272-8a4a-e131dc16d831)
27. Pemilihan perangkat lunak, tandai (*) hanya di Sistem Standar, pilih lanjutkan lalu enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/f58ac62f-07a6-437a-8bea-fc831a1820cf)
28. Memasang boot loader GRUB pada hard disk, pilih ya
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/39ea929c-6779-4e10-8beb-adb3b962ae3a)
29. Instalasi Selesai, Lalu pilih lanjutkan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/a2083755-8318-41a9-9743-3c5184fbfebc)
30. Proses instalasi debian berhasil dan selesai.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/479d1bfe-6c66-49f4-aa0e-f37f140ef867)

## Langkah-langkah konfigurasi Firewall di Debian
1. Login gunakan root dan masukkan kata sandi untuk root yang telah kita setting tadi, jika berhasil akan muncul seperti gambar di bawah ini.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/55ebb8c5-5ccb-451d-bde1-4a2a482a2406)
2. Ketikan perintah nano/etc/network/interfaces untuk setting jaringan.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/bd4450a0-0004-4a62-82ba-e94955fd6f96)
3. Setting jaringan seperti gambar dibawah ini.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/3fe47b7e-36ca-458f-b024-af2a374e9ef2)
4. Setelah selasai melakukan setting jaringan seperti pada gambar, kita simpan setting jaringan tersebut dengan cara ctrl+x+y+Enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/876044b5-74c6-46cb-8346-453c55eec882)
5. Ketikkan perintah nano/etc/sysctl.conf, setelh kita ketikkan perintah tersebut maka akan muncul seperti gambar di bawah ini.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/b92782a3-b978-44d4-805f-eb8ff441838b)
6. Hapus tanda pagar pada net.ipv4.ip_forward=1
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/9245223e-0b06-4d1d-b50e-2ace0fc988b3)
7. Setelah itu, kita simpan setting jaringan tersebut dengan cara ctrl+x+y+Enter dan pilih Ya.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/c5132b82-fe22-4b0d-a520-68789e123826)
8. Setelah tersimpan, Ketikkan perintah nano/etc/rc.local.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/553d07fb-18b7-4385-ba74-73c5087924c9)
9. Ketikkan perintah iptables -t -A POSTROUTING -o eth0 -j MASQUERADE, seperti gambar di bawah ini.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/87ced2b5-0bfa-4afd-ac29-7ed76f8bef4e)
10. Setelah itu, kita simpan setting tersebut, setelah tersimpan ketikkan perintah /etc/init.d/networking restart.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/286f36eb-c372-4e9b-bdbb-7cee0c807cf1)
11. Setelah proses networking restart selesai, kita login lagi dengan root dan kata sandi untuk root yang telah kita setting di awal.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/0a1d45e1-e1ef-4447-b979-aff891466667)
12. Setelah berhasil login, kita tes ping ke google dengan perintah ping ke 8.8.8.8
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/697e5b07-9b3d-4dfe-a26e-56d6dec6a80b)
hasil tes ping yang kita lakukan berhasil
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/d6ba7152-e98a-4afd-a0df-e2fa73b70119)

## Langkah-langkah Instal Windows Xp
1. Create Virtual Mechine, masukkan nama dan ubah version menjadi windows
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/8e2d810a-68d1-40ae-a664-e50313c4e392)
2. Untuk ukuran memori kita gunakan 2000 Mb.
3. Buat hard disk virtual sekarang.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/c7b9d8e5-78c9-40bf-831d-be7d8d492b0d)
4. Pilih tipe berkas hard disk virtual yaitu VDI (virtualbox disk image)
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/7742f966-a697-4630-939b-9c1e40e81349)
5. Storage physical hard disk pilih dynamically allocated
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/b9355cae-6206-4fc6-9da5-821b2fa1d896)
6. Pilih lokasi penyimpanan dan ukuran berkas.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/c23e649c-e1a8-4636-b820-bb61518baa97)
7.  Virtual mesin yang akan kita buat akan muncul, setelah itu pilih pengaturan, pilih jaringan adapter 1 setelah itu pilih Internal Network
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/d660efdb-3f27-4d65-82da-6f41e880e00e)
8. Setelah selesai mengatur jaringan, klik start dan pilih drive host yaitu file iso windows yang telah kita download.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/c73e33d4-00f2-4ab8-9c01-3b078af93e16)
9. Setelah berhasil kita start akan muncul seperti pada gambar di bawah ini, lalu klik enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/ecb38e3f-3353-402a-ba8b-ae0318c48147)
10. Pilih Format the partition using the NTFS file system <Quick> lalu klik enter.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/74869a2d-980d-4a56-a8d5-12ae0d2c7d1f)
11. Tunggu hingga semua proses setup selesai.
12. Lalu setelah itu pilih customize.
    ##  ![8616fa7c-f070-41bf-a65b-d31e37311fe8](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/a6cbf9db-21c4-4c9a-ba1f-9a1d397dea22)
13. Kita ganti English (united States) dengan Indonesian, setelah selesai mengganti klik Ok.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/6e4a792e-629e-4de3-b010-352b565899b2)
14. Kita masukkan name dan organization, klik next jika telah selesai.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/cfdffab9-cc36-4b5a-a16d-381872b58c75)
15. Kita masukkan computer name dan administrator password juga confirm passowrd, klik next jika telah selesai.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/7ce028a1-3e1b-4541-8063-266ed7dd9874)
16. Atur waktu dan tanggal, klik next jika telah selasai.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/ba7fe977-802c-4b40-bc34-1c8b214a4eff)
17. Tulis pada box yang tersedia workgrup dengan huruf kapital seperti gambar di bawah ini, klik next jika selesai.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/a6d32ce0-90fa-4a07-bca8-1cb976dce2fd)
18. Tunggu hingga proses selesai, jika selesai windows xp akan menampilkan tampilan seperti gambar di bawah ini.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/3e505db4-d524-457e-b61f-65153243899d)
19. Protect your pc.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/d4543873-6399-4fa3-8104-acb27ba1b10e)
20. Ready to register with microsoft, kita memilih no, not at this time.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/7b3390c1-f2f1-4255-aa93-1eebd25f226f)
21. Masukkan user
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/18477f44-f087-42ab-80f7-7965f850775f)
22. Proses instalasi windows telah berhasil dan selesai
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/6f5521d4-1d0c-41ee-b302-131558baf7ea)

## Langkah-langkah konfigurasi Firewall
1. Setting Ip addres di client yaitu windows yang telah kita instal, kita ke control panel, pilih network and internet connections, selanjutnya pilih network connections, pilih local area network, lalu pilih properties, pilih Internet Protocol(TCP/IP), Setting IP addres seperti gambar dibawah ini, setelah selesai klik Ok.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/e44ac8ee-80a0-496e-a173-f0eb02820afd)
2. Ke CMD, ping ke server debian yaitu ping 192.168.55.1
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/53d83b4e-f9ae-4d1e-8ae2-ae6543add84a)
Hasilnya ping menunjukkan reply yang artinya berhasil.
3. Konfigurasi firewall di client, kita off kan, setelah itu kita coba ping pc client pada debian dengan cara ping 192.168.55.2 (ip addres pc client (windows))
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/2f3fbc42-9503-42df-a52f-5b33c1c6e021)
Hasilnya menunjukkan connect
4. Konfigurasi firewall di client, kita coba on kan firewallnya, setelah itu kita coba ping pc client pada debian dengan cara ping 192.168.55.2 (ip addres pc client (windows)) dan kita lihat hasilnya.
![image](https://github.com/dianovis/Kelompok5-Firewall/assets/116280719/5cbd0109-d0e0-4fb3-bc5b-0607856c7ddb)
Hasilnya menunjukkan disconnect karena firewallnya di aktifkan. 

## Kesimpulan
<p align="justify">Firewall sendiri adalah sebuah sistem atau perangkat yang digunakan untuk mengizinkan lalu lintas jaringan yang dianggap aman untuk melaluinya dan mencegah lalu lintas jaringan yang dianggap tidak aman. Firewall umumnya diimplementasikan dalam sebuah mesin terdedikasi, yang berjalan pada pintu gerbang (gateway) antara jaringan lokal dan jaringan lainnya. Dalam konteks keamanan jaringan, firewall sangat penting untuk mencegah serangan siber dan melindungi jaringan dari ancaman yang mungkin terjadi. Implementasi firewall menggunakan Debian di Virtual Mesin dapat memberikan alternatif yang efektif dan efisien dalam mengamankan jaringan. </p>
