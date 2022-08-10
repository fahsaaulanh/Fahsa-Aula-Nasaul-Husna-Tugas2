# Fahsa-Aula-Nasaul-Husna-Tugas2
Tugas 2 BDI 3 in 1 bug fix flappy_floppy
============================================================

Langkah penyelesaian :
============================================================
issue 1 1-_score-does-not-exist
============================================================
-> mengindentifikasi dan mencari sumber bug atau error
-> menemukan bug di GameManager.cs line 68 dan 69
-> Error berasal dari typo atau ketidak sesuaian penulisan variabel
-> merubah variabel _score menjadi score di line 68 dan 69
============================================================
issue 2 cannot-implicitly-convert-type-int-to-string
============================================================
-> Menggubah atau memodifikasi line 69, error dikarenakan variabel score yang bertipe data integer belum di convert menjadi string untuk mengisi nilai scoreText.text
