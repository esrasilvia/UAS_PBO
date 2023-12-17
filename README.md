# UAS PEMROGRAMAN BERBASIS OBJEK
|                  Nama Anggota Kelompok                  |         NPM         |
| ------------------------------------------------------- |:-------------------:|
| Esra Silvia Sihite                                      |      G1F022035      |
| Muhammad Rifky Ramadani                                 |      G1F022039      |
| Muhammad Salman Alfarizi                                |      G1F022047      |

## SOAL UJIAN AKHIR SEMESTER

Buatlah game sederhana dengan menggunakan python dan buat laporan bagaimana konsep OOP diterapkan pada pemrograman tersebut.
Dari 12 poin pilihan program yang disediakan, Disini kelompok kami memilih program poin 1 yaitu: 
1. Game Hangman menggunakan python: Saya yakin sebagian besar dari kita pernah
memainkan game klasik yang menggunakan skrip python ini. Kita tahu tujuan utama dari
permainan ini adalah untuk 'menebak kata', yang disebut dengan deretan tanda hubung, dan
kita perlu menebak huruf dari kata tersebut.

## Pendahuluan

#### 1. PBO ( Pemrograman Berorientasi Objek)

Pemrograman Berorientasi Objek (PBO) adalah paradigma pemrograman yang berfokus pada konsep objek sebagai elemen dasar dalam pengembangan perangkat lunak. Dalam PBO, program dikonstruksi menggunakan objek yang merepresentasikan entitas atau konsep dalam dunia nyata. Setiap objek memiliki atribut (data) dan metode (fungsi) yang memanipulasi data tersebut.Salah satu prinsip utama dalam PBO adalah enkapsulasi, di mana data dan metode yang beroperasi pada data tertentu dikemas bersama dalam satu entitas. Hal ini membantu memisahkan implementasi dari penggunaan objek, meningkatkan modularitas, dan memudahkan pemeliharaan kode.

#### 2. Game Hangman
Hangman adalah permainan tebak kata yang populer dan seru. Tujuan dari permainan ini adalah menebak sebuah kata dengan menebak huruf-huruf yang terdapat dalam kata tersebut. Setiap tebakan yang salah akan mengakibatkan gambar gantung terisi sedikit demi sedikit, dan jika gambar gantung tersebut lengkap sebelum kata ditebak, pemain kalah. Game Hangman sering dimainkan untuk menguji kosakata dan kemampuan tebak-tebakan seseorang. Selain itu, game ini juga dapat digunakan untuk melatih pemrograman dan logika pemain dalam menerapkan algoritma pemrosesan kata.

Dalam versi modern, permainan Hangman sering dimainkan dengan seorang pemain yang memilih kata secara acak, sedangkan pemain lain harus menebak kata tersebut dengan menebak huruf-hurufnya. Jika pemain yang menebak gagalmenebak kata dengan benar sebelum gambar gantungan lengkap tergambar, makapemain yang memilih kata akan memenangkan permainan.Game Hangman telah berkembang menjadi permainan komputer dan aplikasi seluler yang populer. Ini adalah permainan yang menyenangkan dan menantang yang tetap menjadi favorit banyak orang untuk mengasah keterampilan kosakata dan menguji daya pikir.


## Solusi Penyelesaian

Game Hangman adalah permainan tebak kata yang seru dan populer. Dalam permainan ini, seorang pemain harus menebak kata yang dipilih secara acak oleh pemain lain atau oleh komputer. Kata tersebut biasanya terdiri dari huruf-huruf yang disembunyikan, dan pemain harus menebak huruf-huruf tersebut satu per satu.Papan permainan Hangman biasanya terdiri dari garis-garis yang mewakili huruf-huruf dalam kata yang harus ditebak. Pemain harus menebak huruf-huruf yang mungkin ada dalam kata tersebut. Jika tebakan pemain benar, huruf tersebut akan diungkapkan dalam kata yang disembunyikan, dan jika tebakan salah, pemain akan mendapatkan bagian tubuh gantungan (hangman) secara bertahap. Tujuan pemain adalah menebak kata sebelum hangman lengkap tergambar. Permainan Hangman biasanya dimainkan dengan kata-kata dalam bahasa Inggris, tetapi dapat diadaptasi untuk menggunakan kata-kata dalam bahasa lain. Ini adalah permainan yang sering dimainkan untuk mengasah keterampilan kosakata, menguji imajinasi, dan melatih strategi menebak kata

Permainan Hangman sering digunakan sebagai cara yang menyenangkan untuk meningkatkan kosakata dan pemahaman terhadap kata-kata. Dalam bahasa pemrograman Python, Hangman dapat diimplementasikan dengan memanfaatkan struktur data, pengulangan, dan kondisional. Berikut rancangan solusi yang ingin kami terapkan untuk realisasi dalam program game HangMan yang ingin dibuat:

1. Struktur Program:
- Menggunakan pendekatan berorientasi objek dengan membuat kelas HangmanGame untuk menyimpan data dan logika permainan.

2. Inisialisasi dan Pemilihan Kata:
- Menentukan sebuah kumpulan kata yang akan digunakan dalam permainan. Kumpulan kata ini dapat disimpan sebagai atribut di dalam kelas.
- Mengimplementasikan metode untuk memilih kata secara acak dari kumpulan kata tersebut saat permainan dimulai.

3. Tampilan Kata yang Harus Ditebak:
- Mengimplementasikan metode untuk menampilkan kata yang harus ditebak, dengan mengganti huruf yang belum ditebak dengan karakter pemisah (biasanya underscore _).

4. Input Pengguna:
- Menggunakan fungsi input untuk menerima tebakan huruf dari pengguna.
- Memvalidasi input untuk memastikan bahwa pengguna hanya memasukkan satu huruf yang valid.

5. Pengecekan Tebakan:
- Mengimplementasikan mekanisme untuk memeriksa apakah huruf yang ditebak oleh pengguna ada dalam kata yang harus ditebak.
- Menambahkan huruf yang ditebak ke dalam daftar huruf yang sudah ditebak.
- mengurangi jumlah percobaan jika tebakan salah.

6. Pengecekan Kondisi Permainan:
- Setelah setiap tebakan, memeriksa apakah pemain telah berhasil menebak semua huruf dalam kata atau jika jumlah percobaan telah habis.
- Jika pemain menang, menampilkan pesan kemenangan. Jika pemain kalah, menampilkan kata yang benar.

7. Interaksi dengan Pengguna:
- Menampilkan informasi kepada pengguna, seperti kata yang harus ditebak, huruf yang sudah ditebak, dan sisa percobaan.
- Memberikan umpan balik yang jelas terkait dengan tebakan pengguna.

8. Penanganan Kesalahan:
- memastikan ada penanganan kesalahan untuk situasi seperti input yang tidak valid.
- Memastikan agar pengguna mendapatkan informasi yang cukup untuk memahami kondisi permainan.

9. Struktur Kode yang Bersih dan Moduler:
- Mendesain kode agar mudah dipahami dan dikelola.
- Menggunakan fungsi-fungsi dan metode-metode terpisah untuk melakukan tugas-tugas spesifik.


## Source Code

    import random

    class HangmanGame:
    def __init__(self):
        self.words = ["python", "hangman", "programming", "computer", "gaming", "developer"]
        self.word_to_guess = ""
        self.guessed_letters = []
        self.attempts = 6

    def choose_word(self):
        self.word_to_guess = random.choice(self.words)

    def display_word(self):
        display = ""
        for letter in self.word_to_guess:
            if letter in self.guessed_letters:
                display += letter
            else:
                display += "_"
        return display

    def play(self):
        print("Selamat datang di permainan Hangman!")

        self.choose_word()

        while True:
            current_display = self.display_word()
            print("\nKata yang harus ditebak: " + current_display)
            print("Huruf yang sudah ditebak: " + ", ".join(self.guessed_letters))
            print("Sisa percobaan: {}".format(self.attempts))

            if current_display == self.word_to_guess:
                print("\nSelamat! Kamu berhasil menebak kata: {}".format(self.word_to_guess))
                break

            if self.attempts == 0:
                print("\nMaaf, kamu kalah. Kata yang benar adalah: {}".format(self.word_to_guess))
                break

            guess = input("\nTebak satu huruf: ").lower()

            if len(guess) != 1 or not guess.isalpha():
                print("Masukkan hanya satu huruf yang valid.")
                continue

            if guess in self.guessed_letters:
                print("Kamu sudah menebak huruf ini sebelumnya. Coba lagi.")
                continue

            self.guessed_letters.append(guess)

            if guess not in self.word_to_guess:
                print("Huruf {} tidak ada dalam kata. Coba lagi.".format(guess))
                self.attempts -= 1
    if __name__ == "__main__":
      game = HangmanGame()
      game.play()

## Pembahasan Program
Tampilan Source code:

<img width="510" alt="Screenshot 2023-12-17 200530" src="https://github.com/SalmanAlfarizi28/UAS_PBO/assets/150643024/387a899a-dfed-446a-bae8-106d970d1b11">
<img width="503" alt="Screenshot 2023-12-17 200608" src="https://github.com/SalmanAlfarizi28/UAS_PBO/assets/150643024/dbe0a3fd-41ea-4d5c-8203-c78c6c371b24">

Dari gambar di atas kita dapat melihat tampilan dari source code program game HangMan, yang merupakan penerapan dari rancangan solusi yang telah kami rancang. Berikut akan kami jelaskan apa fungsi dari masing-masing kode tersebut:

    import random
Penjelasan: Mengimpor modul random untuk digunakan dalam pemilihan kata acak.

    class HangmanGame:
    def __init__(self):
        self.words = ["python", "hangman", "programming", "computer", "gaming", "developer"]
        self.word_to_guess = ""
        self.guessed_letters = []
        self.attempts = 6
Penjelasan: Membuat kelas HangmanGame yang memiliki atribut seperti words (kumpulan kata), word_to_guess (kata yang harus ditebak), guessed_letters (huruf yang sudah ditebak), dan attempts (jumlah percobaan). 

    def choose_word(self):
        self.word_to_guess = random.choice(self.words)
Penjelasan: Metode choose_word digunakan untuk memilih kata secara acak dari kumpulan kata dan menyimpannya dalam atribut word_to_guess.

    def display_word(self):
        display = ""
        for letter in self.word_to_guess:
            if letter in self.guessed_letters:
                display += letter
            else:
                display += "_"
        return display
Penjelasan: Metode display_word digunakan untuk membuat tampilan kata yang harus ditebak, dengan mengganti huruf yang belum ditebak dengan karakter pemisah (biasanya underscore _ ).

    def play(self):
        print("Selamat datang di permainan Hangman!")

        self.choose_word()

        while True:
            current_display = self.display_word()
            print("\nKata yang harus ditebak: " + current_display)
            print("Huruf yang sudah ditebak: " + ", ".join(self.guessed_letters))
            print("Sisa percobaan: {}".format(self.attempts))
Penjelasan: Metode play adalah inti dari logika permainan Hangman. Mencetak pesan selamat datang, memilih kata acak, dan memulai loop permainan.

            if current_display == self.word_to_guess:
                print("\nSelamat! Kamu berhasil menebak kata: {}".format(self.word_to_guess))
                break
Penejelasan: Memeriksa apakah pemain telah berhasil menebak semua huruf dalam kata. Jika iya, mencetak pesan kemenangan dan mengakhiri permainan.

            if self.attempts == 0:
                print("\nMaaf, kamu kalah. Kata yang benar adalah: {}".format(self.word_to_guess))
                break
Penjelasan: Memeriksa apakah jumlah percobaan telah habis. Jika iya, mencetak pesan kekalahan dan mengakhiri permainan.              

            guess = input("\nTebak satu huruf: ").lower()

            if len(guess) != 1 or not guess.isalpha():
                print("Masukkan hanya satu huruf yang valid.")
                continue
Penjelasan: Meminta input dari pengguna untuk menebak satu huruf. Melakukan validasi input untuk memastikan bahwa pengguna hanya memasukkan satu huruf yang valid.

            if guess in self.guessed_letters:
                print("Kamu sudah menebak huruf ini sebelumnya. Coba lagi.")
                continue
Penjelasan: Memeriksa apakah huruf sudah ditebak sebelumnya. Jika iya, memberikan pesan dan melanjutkan loop.

            self.guessed_letters.append(guess)

            if guess not in self.word_to_guess:
                print("Huruf {} tidak ada dalam kata. Coba lagi.".format(guess))
                self.attempts -= 1
Penjelasan: Menambahkan huruf ke dalam daftar huruf yang sudah ditebak. Jika huruf tidak ada dalam kata yang harus ditebak, mengurangi jumlah percobaan.

    if __name__ == "__main__":
      game = HangmanGame()
      game.play()
Penjelasan: Menjalankan permainan Hangman dengan membuat instance dari kelas HangmanGame dan memanggil metode play.

Output:

<img width="550" alt="Screenshot 2023-12-17 200637" src="https://github.com/SalmanAlfarizi28/UAS_PBO/assets/150643024/f54d33c6-9bf8-4e10-9cd1-ce4943716427">
<img width="557" alt="Screenshot 2023-12-17 200655" src="https://github.com/SalmanAlfarizi28/UAS_PBO/assets/150643024/a0cadd36-876c-43ca-bf5a-bb4009da9a2c">

Penjelasan:

Saat permainan dimulai, pengguna disambut dengan pesan selamat datang, dan sebuah kata secara acak dipilih dari kumpulan kata. Pengguna diberikan tampilan kata yang harus ditebak, diwakili oleh garis-garis bawah untuk setiap huruf yang belum ditebak.

Selama permainan, pengguna diminta untuk menebak satu huruf pada setiap langkahnya. Validasi input dilakukan untuk memastikan bahwa yang dimasukkan adalah satu huruf yang valid. Setiap langkah menebak disertai dengan pembaruan tampilan kata yang harus ditebak, daftar huruf yang sudah ditebak, dan sisa percobaan. Jika huruf yang ditebak benar, huruf tersebut ditambahkan ke daftar huruf yang sudah ditebak, dan tampilan kata yang harus ditebak diperbarui. Jika huruf yang ditebak salah, jumlah percobaan dikurangi satu.

Seperti dalam gambar di atas dapat kita lihat, saat menebak huruf "Y" ke dalam permainan, muncul pesan Huruf y tidak ada dalam kata. Coba Lagi. dapat kita lihat juga bahwa setelah kesalahan tersebut sisa percobaan berkurang menjadi 5. Dan saat huruf "v" yang ditebak dimana huruf tersebut benar (ada dalam kata), maka program akan otomatis memasukkan huruf tersebut ke dalam barisan garis-garis bawah untuk huruf yang ditebak.

Program memberikan umpan balik yang jelas kepada pengguna, memberi tahu mereka apakah huruf yang ditebak benar atau salah, dan menyediakan informasi terkait dengan kondisi permainan. Proses ini berlanjut hingga pengguna berhasil menebak seluruh kata atau jumlah percobaan habis.

Contoh output di atas menunjukkan jalannya permainan hingga pengguna berhasil menebak kata "developer". Pesan kemenangan ditampilkan, memberi penghargaan kepada pengguna karena berhasil menebak kata secara lengkap. Selama permainan, pengguna dapat merasa terlibat dan mendapatkan umpan balik yang jelas tentang kemajuan mereka dalam menebak kata
