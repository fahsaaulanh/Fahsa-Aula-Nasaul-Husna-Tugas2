# Fahsa-Aula-Nasaul-Husna-Tugas2
Tugas 2 BDI 3 in 1 bug fix flappy_floppy
<br>

Langkah penyelesaian :
<br>
issue 1 1-_score-does-not-exist
<br>
-> mengindentifikasi dan mencari sumber bug atau error
<br>
-> menemukan bug di GameManager.cs line 68 dan 69
<br>
-> Error berasal dari typo atau ketidak sesuaian penulisan variabel
<br>
-> merubah variabel _score menjadi score di line 68 dan 69
<br>

issue 2 cannot-implicitly-convert-type-int-to-string
<br>
-> Menggubah atau memodifikasi line 69, error dikarenakan variabel score yang bertipe data integer belum di convert menjadi string untuk mengisi nilai scoreText.text

<br>
 Issue 3 Nug pada gameplay
 <br>
 -> enable Tap Controller dan checklis rigidbody rimulated di object Plane
 <br>
 -> Merubah syntax di Game Manager dan TapController
 
