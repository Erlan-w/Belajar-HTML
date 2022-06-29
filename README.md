<p align="center">
    <h1 align="center">Belajar HTML Dasar</h1>
    <p align="center">Ini adalah Repository yang saya buat sebagai catatan materi HTML Dasar, <br> Materi ini akan saya lengkapi seiring dengan apa yang saya perlajari.</p>

## Table of Contents

- [Table](#table)
- [Atribut](#atribut)
- [Struktur Table](#struktur-Table)

## Table

Untuk membuat tabel pada halaman HTML, perintahnya harus ditulis diantara tag table.

**Tag yang dipakai:**

```html
<table>
  ... Tulis Kode Programnya Disini
</table>
```

## Atribut

Atribut yang digunakan untuk menghias table adalah sebagai berikut:

1. Border.

   Digunakan untuk membuat bingkai atau border pada table

2. Cellspacing

   Digunakan untuk memperbesar garis cell (Bingkai atau border)

3. Cellpadding

   Untuk memberi jarak antara tulisan dengan garis border atau Bingkai

Untuk 3 atribut diatas lebih baik dilakukan dengan css

4. Colspan

   digunakan untuk menggabungkan dua atau lebih cell secara **horizontal atau kolom**

5. Rowspan

   digunakan untuk menggabungkan dua atau lebih cell **secara vertikal atau baris**

## Struktur Table

Struktur table dapat di bedakan menjadi dua, yaitu:

1. #### Simple

   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td>baris 1, kolom 1</td>
       <td>baris 1, kolom 2</td>
     </tr>
     <tr>
       <td>baris 2, kolom 1</td>
       <td>baris 2, kolom 2</td>
     </tr>
   </table>
   ```

   **Output:**
   <table border="1" cellspacing="0" cellpadding="10">
       <tr>
         <td>baris 1, kolom 1</td>
         <td>baris 1, kolom 2</td>
       </tr>
       <tr>
         <td>baris 2, kolom 1</td>
         <td>baris 2, kolom 2</td>
       </tr>
     </table>

2. #### Kompleks

   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <thead>
       <tr>
         <th></th>
         <th>Kolom 1</th>
         <th>Kolom 2</th>
       </tr>

       <tr></tr>
     </thead>

     <tbody>
       <tr>
         <th>Baris 1</th>
         <td>baris 1, kolom 1</td>
         <td>baris 1, kolom 2</td>
       </tr>
       <tr>
         <th>Baris 2</th>
         <td>baris 2, kolom 1</td>
         <td>baris 2, kolom 2</td>
       </tr>
     </tbody>
   </table>
   ```

   **Output:**
   <table border="1" cellspacing="0" cellpadding="10">
       <thead>
         <tr>
           <th></th>
           <th>Kolom 1</th>
           <th>Kolom 2</th>
         <tr>
         </thead>
         <tbody>
           <tr>
             <th>Baris 1</th>
             <td>baris 1, kolom 1</td>
             <td>baris 1, kolom 2</td>
           </tr>
           <tr>
             <th>Baris 2</th>
             <td>baris 2, kolom 1</td>
             <td>baris 2, kolom 2</td>
           </tr>
         </tbody>
     </table>
