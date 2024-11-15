# AsjaiRobi-PBO2-Tugas5

# Program Hitung Kata
Deskripsi

Program PerhitunganKata adalah aplikasi berbasis Java menggunakan Swing yang dapat menghitung jumlah kata dan kalimat dalam teks yang dimasukkan pengguna. Selain itu, aplikasi ini juga memungkinkan pengguna untuk mencari jumlah kemunculan kata tertentu dalam teks dan menyimpan hasil perhitungan dalam file teks.
Fitur

    Menghitung jumlah kata dan kalimat dalam teks yang dimasukkan.
    Mencari jumlah kemunculan suatu kata dalam teks.
    Menyimpan hasil perhitungan jumlah kata dan kalimat ke dalam file teks.
    Mengulangi (clear) teks yang sudah dimasukkan.

Cara Menjalankan

    Antarmuka Pengguna:
        Program akan menampilkan jendela dengan komponen sebagai berikut:
            Text Area: Untuk memasukkan teks yang ingin dihitung.
            Jumlah Kata: Menampilkan jumlah kata yang ada dalam teks.
            Jumlah Kalimat: Menampilkan jumlah kalimat dalam teks.
            Cari Kata: Memungkinkan pengguna untuk mencari jumlah kemunculan suatu kata dalam teks.
            Tombol Ulang: Untuk membersihkan teks yang sudah dimasukkan.
            Tombol Keluar: Untuk menutup aplikasi.
            Tombol Simpan File: Untuk menyimpan hasil perhitungan ke dalam file teks.

Instruksi Penggunaan

    Masukkan Teks:
        Ketik teks yang ingin Anda hitung jumlah kata dan kalimatnya di area yang disediakan.

    Cari Kata:
        Ketik kata yang ingin dicari di dalam Text Field dan klik Cari. Program akan menampilkan berapa kali kata tersebut muncul dalam teks.

    Hasil Perhitungan:
        Jumlah kata dan jumlah kalimat akan dihitung secara otomatis dan ditampilkan setelah Anda mengetik atau mengubah teks.

    Simpan Hasil:
        Klik Simpan File untuk menyimpan hasil perhitungan jumlah kata dan kalimat ke dalam file .txt. Program akan meminta Anda untuk memilih lokasi dan nama file.

    Ulangi:
        Klik Ulang untuk menghapus semua teks yang ada di Text Area.

    Keluar:
        Klik Keluar untuk menutup aplikasi.

# Kode Program
Struktur Kode

Program ini menggunakan Swing untuk antarmuka grafis, dan memiliki beberapa komponen utama:

    JTextArea untuk menampilkan dan mengedit teks.
    JLabel untuk menampilkan hasil perhitungan jumlah kata dan kalimat.
    JTextField untuk memasukkan kata yang ingin dicari.
    JButton untuk berbagai aksi, seperti Simpan, Ulang, Keluar, dan Cari.

Bagian Utama

    hitungKataDanKalimat(): Fungsi yang menghitung jumlah kata dan kalimat dalam teks.
    jButton5ActionPerformed(): Fungsi untuk mencari dan menghitung kemunculan kata yang dimasukkan di Text Field.
    jButton4ActionPerformed(): Fungsi untuk menyimpan hasil perhitungan dalam file teks.

Contoh Output

Jumlah Kata: 10
Jumlah Kalimat: 2

Cari Kata: "Java" ditemukan sebanyak 3 kali.
