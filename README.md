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

   Digunakan untuk **membuat bingkai atau border** pada table

2. Cellspacing

   Digunakan untuk **memperbesar garis cell (Bingkai atau border)**

3. Cellpadding

   Untuk memberi **jarak** antara tulisan dengan garis border atau Bingkai

Untuk 3 atribut diatas telah dianggap usang / deprecated, lebih baik dilakukan dengan css, disini tetap digunakan karena hanya untuk melihat efeknya pada tabel.

4. Colspan

   digunakan untuk **menggabungkan / merging** dua atau lebih cell secara **horizontal atau kolom**

5. Rowspan

   digunakan untuk **menggabungkan / merging** dua atau lebih cell **secara vertikal atau baris**

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

## Contoh penerapan colspan dan rowspan

1. #### Tabel sebelum marging:
   
   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td>1,1</td>
       <td>1,2</td>
       <td>1,3</td>
     </tr>
     <tr>
       <td>2,1</td>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,1</td>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>
   ```

   **Output:**
     <table border="1" cellspacing="0" cellpadding="10">
       <tr>
         <td>1,1</td>
         <td>1,2</td>
         <td>1,3</td>
       </tr>
       <tr>
         <td>2,1</td>
         <td>2,2</td>
         <td>2,3</td>
       </tr>
       <tr>
         <td>3,1</td>
         <td>3,2</td>
         <td>3,3</td>
       </tr>
     </table>

2. #### Tabel setelah marging:

   a. colspan

   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td>1,1</td>
       <td colspan="2">colspan 2</td>
     </tr>
     <tr>
       <td>2,1</td>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,1</td>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>
   ```

   **Output:**
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td>1,1</td>
       <td colspan="2">colspan 2</td>
     </tr>
     <tr>
       <td>2,1</td>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,1</td>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>

   b. rowspan

   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td rowspan="3">rowspan 3</td>
       <td>1,2</td>
       <td>1,3</td>
     </tr>
     <tr>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>
   ```

   **Output:**
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td rowspan="3">rowspan 3</td>
       <td>1,2</td>
       <td>1,3</td>
     </tr>
     <tr>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>

   c. Penerapan colspan dan rowspan bersamaan pada tabel

   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td rowspan="3">rowspan 3</td>
       <td colspan="2">colspan 2</td>
     </tr>
     <tr>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>
   ```

   **Output:**
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td rowspan="3">rowspan 3</td>
       <td colspan="2">colspan 2</td>
     </tr>
     <tr>
       <td>2,2</td>
       <td>2,3</td>
     </tr>
     <tr>
       <td>3,2</td>
       <td>3,3</td>
     </tr>
   </table>

3. #### Latihan Membuat Tabel

   **Kode yang dipakai:**

   ```html
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td>1,1</td>
       <td>1,2</td>
       <td>1,3</td>
       <td>1,4</td>
     </tr>
     <tr>
       <td>2,1</td>
       <td colspan="2" rowspan="2">
         <center><b>?</b></center>
       </td>
       <td>2,4</td>
     </tr>
     <tr>
       <td>3,1</td>
       <td>3,4</td>
     </tr>
     <tr>
       <td>4,2</td>
       <td>4,2</td>
       <td>4,3</td>
       <td>4,4</td>
     </tr>
   </table>
   ```

   **Output:**
   <table border="1" cellspacing="0" cellpadding="10">
     <tr>
       <td>1,1</td>
       <td>1,2</td>
       <td>1,3</td>
       <td>1,4</td>
     </tr>
     <tr>
       <td>2,1</td>
       <td colspan="2" rowspan="2">
         <center><b>?</b></center>
       </td>
       <td>2,4</td>
     </tr>
     <tr>
       <td>3,1</td>
       <td>3,4</td>
     </tr>
     <tr>
       <td>4,2</td>
       <td>4,2</td>
       <td>4,3</td>
       <td>4,4</td>
     </tr>
   </table>
