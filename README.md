<p align="center">
    <h1 align="center">Belajar HTML Dasar</h1>
    <p align="center">Ini adalah Repository yang saya buat sebagai catatan materi HTML Dasar <br> Materi ini akan saya lengkapi seiring dengan apa yang saya perlajari.</p>
  
  ## Table of Contents
  - [Table](#table)
  - [Atribut](#atribut)
  - [Struktur Table](#struktur-Table)

## Table
Untuk membuat tabel pada HTML, perintahnya harus ditulis diantara tag table.

#### Tag Yang Digunakan

<Table>
  ... Tulis Kode Programnya Disini
</Table>

## Atribut 
atribut yang digunakan untuk menghias table adalah sebagai berikut:
- border
  untuk membuat bingkai table
- cellspacing
  untuk memperbesar garis cell
- cellpadding
  untuk memberi jarak antara tulisan dengan garis border

Untuk 3 atribut diatas lebih baik dilakukan dengan css

- colspan
- rowspan

## Struktur Table

struktur table dapat di bedakan menjadi dua, yaitu:

- ### Simple
  #### Kode yang dipakai:
    
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
    

  #### Output:
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

- ### Kompleks
  #### Kode yang dipakai:
    
      <table border="1" cellspacing="0" cellpadding="10">
        <thead>
          <tr>
            <th></th>
            <td>Kolom 1</td>
            <td>Kolom 2</td>
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
    

  #### Output:
    <table border="1" cellspacing="0" cellpadding="10">
        <thead>
          <tr>
            <th></th>
            <td>Kolom 1</td>
            <td>Kolom 2</td>
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