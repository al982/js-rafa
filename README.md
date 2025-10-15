<h1>CATATAN PEMROGRAMAN</h1>

<h4>1. HELLO WORLD</h4>
<p>Program dasar untuk memastikan lingkungan kerja berjalan baik. Biasanya digunakan untuk menampilkan teks “Hello World” di layar menggunakan beberapa metode JavaScript seperti console.log(), alert(), atau menulis langsung ke dokumen.</p>
<pre><code>
&lt;script&gt;
console.log("Hai Dunia!");
alert("Hai Dunia!");
document.write("Hai Dunia!");
&lt;/script&gt;
</code></pre>

<h4>2. OPERATOR ARITMATIKA</h4>
<p>Operator matematika dasar meliputi: +, -, *, /, %, dan **. Digunakan untuk menghitung nilai numerik.</p>
<pre><code>
&lt;script&gt;
let x = 12, y = 4;
document.write(x + y + "&lt;br&gt;"); // 16
document.write(x - y + "&lt;br&gt;"); // 8
document.write(x * y + "&lt;br&gt;"); // 48
document.write(x / y + "&lt;br&gt;"); // 3
document.write(x % y + "&lt;br&gt;"); // 0
document.write(x ** y);            // 20736
&lt;/script&gt;
</code></pre>

<h4>3. OPERATOR AUGMENTED ASSIGNMENT</h4>
<p>Operator singkatan dari operasi dan penugasan seperti +=, -=, *=, /=, dan %=.</p>
<pre><code>
&lt;script&gt;
let nilai = 10;
nilai -= 2; // 8
nilai /= 2; // 4
document.write("Nilai akhir: " + nilai);
&lt;/script&gt;
</code></pre>

<h4>4. OPERATOR LOGIKA</h4>
<p>Operator logika digunakan untuk menggabungkan ekspresi boolean: && berarti “dan”, || berarti “atau”, dan ! berarti “tidak”.</p>
<pre><code>
&lt;script&gt;
let benar = true, salah = false;
document.write(benar && salah + "&lt;br&gt;"); // false
document.write(benar || salah + "&lt;br&gt;"); // true
document.write(!salah); // true
&lt;/script&gt;
</code></pre>

<h4>5. OPERATOR UNARY</h4>
<p>Operator yang hanya memiliki satu operand seperti typeof, ++, --, dan negasi (-).</p>
<pre><code>
&lt;script&gt;
let angka = 7;
document.write(typeof angka + "&lt;br&gt;"); // number
document.write(--angka + "&lt;br&gt;"); // 6
document.write(-angka); // -6
&lt;/script&gt;
</code></pre>

<h4>6. OPERATOR PEMBANDING</h4>
<p>Operator yang membandingkan dua nilai: ==, ===, !=, !==, >, <, >=, <=.</p>
<pre><code>
&lt;script&gt;
let umur = 18;
document.write(umur == "18" + "&lt;br&gt;"); // true
document.write(umur === "18" + "&lt;br&gt;"); // false
document.write(umur &lt; 20); // true
&lt;/script&gt;
</code></pre>

<h4>7. TIPE DATA ARRAY</h4>
<p>Array berfungsi menyimpan banyak data dalam satu variabel dengan indeks berurutan.</p>
<pre><code>
&lt;script&gt;
let hewan = ["Kucing", "Anjing", "Burung"];
hewan.push("Ikan");
document.write(hewan.join(" - "));
&lt;/script&gt;
</code></pre>

<h4>8. TIPE DATA BOOLEAN</h4>
<p>Tipe data boolean hanya memiliki dua kemungkinan nilai: true (benar) atau false (salah).</p>
<pre><code>
&lt;script&gt;
let skor = 55;
let lulus = skor &gt;= 60;
document.write("Apakah lulus? " + lulus);
&lt;/script&gt;
</code></pre>

<h4>9. TIPE DATA NUMBER</h4>
<p>Tipe data number digunakan untuk angka bulat maupun desimal.</p>
<pre><code>
&lt;script&gt;
let hasil = 0.2 + 0.1;
document.write(hasil + "&lt;br&gt;"); // 0.30000000000000004
document.write(hasil.toFixed(1)); // 0.3
&lt;/script&gt;
</code></pre>

<h4>10. TIPE DATA OBJECT</h4>
<p>Object menyimpan pasangan key dan value yang saling terkait.</p>
<pre><code>
&lt;script&gt;
let guru = {
  nama: "Budi",
  usia: 35,
  mapel: "Informatika"
};
document.write(guru.nama + " mengajar " + guru.mapel);
&lt;/script&gt;
</code></pre>

<h4>11. TIPE DATA STRING</h4>
<p>Teks yang diapit tanda kutip tunggal, ganda, atau backtick (template literal).</p>
<pre><code>
&lt;script&gt;
let user = "Rafli";
document.write("Halo, " + user + "!&lt;br&gt;");
document.write(`Selamat datang, ${user}!`);
&lt;/script&gt;
</code></pre>

<h4>12. VARIABLE</h4>
<p>Variabel digunakan untuk menyimpan nilai. Jenis deklarasi: var, let, dan const.</p>
<pre><code>
&lt;script&gt;
var nilai1 = 15;
let nilai2 = 25;
const nilai3 = 35;
document.write(nilai1 + nilai2 + nilai3);
&lt;/script&gt;
</code></pre>

<h4>13. IF EXPRESSION</h4>
<p>Digunakan untuk memeriksa kondisi tertentu dan menjalankan blok kode yang sesuai.</p>
<pre><code>
&lt;script&gt;
let poin = 72;
if (poin &gt;= 90) {
  document.write("Nilai A");
} else if (poin &gt;= 75) {
  document.write("Nilai B");
} else {
  document.write("Nilai C");
}
&lt;/script&gt;
</code></pre>

<h4>14. SWITCH</h4>
<p>Switch digunakan untuk memilih aksi berdasarkan nilai tertentu.</p>
<pre><code>
&lt;script&gt;
let status = "C";
switch (status) {
  case "A":
    document.write("Sangat Baik");
    break;
  case "B":
  case "C":
    document.write("Cukup Baik");
    break;
  case "D":
    document.write("Kurang");
    break;
  default:
    document.write("Tidak Dikenal");
}
&lt;/script&gt;
</code></pre>

<h4>15. PERBEDAAN IF DAN SWITCH</h4>
<p><b>If</b> cocok untuk kondisi yang kompleks atau melibatkan operator logika seperti && dan ||. Namun, struktur if yang terlalu panjang bisa sulit dibaca.</p>
<p><b>Switch</b> lebih sesuai untuk kondisi dengan nilai tunggal yang pasti, seperti pilihan menu atau kategori tetap.</p>
<pre><code>
&lt;script&gt;
// Contoh IF
let tinggi = 165;
if (tinggi &gt;= 170) {
  document.write("Tinggi");
} else {
  document.write("Tidak terlalu tinggi");
}

// Contoh SWITCH
let bulan = "Januari";
switch (bulan) {
  case "Januari":
    document.write("&lt;br&gt;Awal Tahun!");
    break;
  case "Desember":
    document.write("&lt;br&gt;Akhir Tahun!");
    break;
  default:
    document.write("&lt;br&gt;Bulan biasa.");
}
&lt;/script&gt;
</code></pre>
