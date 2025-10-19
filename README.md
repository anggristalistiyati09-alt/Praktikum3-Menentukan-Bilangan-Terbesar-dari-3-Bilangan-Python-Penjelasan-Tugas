# Praktikum3-Menentukan-Bilangan-Terbesar-dari-3-Bilangan-Python-Penjelasan-Tugas
Tugas ini bertujuan untuk membuat program Python yang dapat menerima tiga buah input bilangan bulat dan menentukan serta mencetak bilangan mana yang memiliki nilai terbesar. 
# Flowchart Program
![flowchard program](https://github.com/user-attachments/assets/f2d479d4-1771-4c5c-bb6b-4a479ee13a45)
Penjelasan Flowchart: Flowchart diawali dengan START, dilanjutkan dengan proses INPUT untuk tiga bilangan (bil1, bil2, bil3). Kemudian, program menggunakan serangkaian keputusan untuk membandingkan nilai-nilai tersebut.
Pertama, membandingkan bil1 dengan bil2 dan bil3. Jika bil1 lebih besar dari keduanya, maka bil1 adalah yang terbesar.
Jika tidak, program membandingkan bil2 dengan bil1 dan bil3. Jika bil2 lebih besar dari keduanya, maka bil2 adalah yang terbesar.
Jika kedua kondisi di atas tidak terpenuhi, secara otomatis bil3 adalah bilangan terbesar. Hasil perbandingan (bilangan terbesar) akan dicetak melalui proses OUTPUT, dan alur program diakhiri dengan END.
# Kode program (terbesar.py)
<img width="507" height="368" alt="Screenshot 2025-10-19 131438" src="https://github.com/user-attachments/assets/0ca5e2e0-8c00-47c2-8ad0-2fea930e6104" />

Penjelasan Kode Program:
Input: Program menggunakan input() dan diubah ke tipe int() untuk menerima tiga bilangan bulat. Blok try-except digunakan untuk menangani kesalahan jika input yang dimasukkan bukan angka.
Percabangan if-elif-else:
if A >= B and A >= C:: Mengecek apakah A lebih besar atau sama dengan kedua bilangan lainnya.
elif B >= A and B >= C:: Jika kondisi pertama salah, cek apakah B lebih besar atau sama dengan A dan C.
else:: Jika kedua kondisi di atas salah, maka otomatis C adalah yang terbesar.
Output: Bilangan terbesar dicetak menggunakan fungsi print().

# Hasil output
<img width="709" height="74" alt="Screenshot 2025-10-19 164458" src="https://github.com/user-attachments/assets/79592fb0-94bf-4d9a-a056-23dae91d8f45" />
