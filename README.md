<h2 align="center">Instal OpenVPN for Debian</h2>
بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيْم

## Bahan
- VM OS Debian 
- Putty [Putty](https://putty.org/)
- FileZilla [FileZilla](https://filezilla-project.org/)
- OVPN Client [OVPN](https://openvpn.net/)

## Penggunaan 

Pastikan alamat ip, dengan perintah:
```
ip a
```

Instal dulu packet curl, kemudian masukkan alamat berikut:
```
curl -O https://raw.githubusercontent.com/yogaputrarm/openvpn-kons1/main/openvpn-install.sh
```

Kemudian ubah aksesnya

```
chmod +x openvpn-install.sh
```

Kemudian instal dan konfigurasi:

```
./openvpn-install.sh
```
### Step Konfigurasi
- Lakukan Konfigurasi dengan mengganti alamat ip sesuai dengan ip yang server anda dapatkan.
- Konfigurasi Port secara default.
- Konfigurasi protokol menggunakan UDP.
- Gunakankah DNS sesuai keinginan anda. 
- Masukkan nama client sesuai keinginan anda.
- Jika sudah selesai, anda dapat mengunduh file ovpn dari direktori server anda melalui filezilla dengan lokasi `/root/"nama client".ovpn`

### Hubungkan dengan OVPN Client
Masukkan file yang sudah di unduh ke OVPN Client 
