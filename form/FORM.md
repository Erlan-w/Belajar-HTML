<p align="center">
  <h1 align="center">Form</h1>

<br/>

Membuat Form pada halaman HTML elementnya harus ditulis diantara tag form, seperti dibawah ini.

<br/>

**Tag yang dipakai**

```html
<form>
  ... Tulis Kode/element Programnya Disini
</form>
```

<br/>

<h2 align="center" id="element-form">Element Form</h2>

<br/>

1. input

    element ini digunakan agar user dapat memasukkan sesuatu dalam form, contoh penggunaannya seperti password, username, dll.
<br/>

    a. jenis-jenis input

    |Type | Kode | Output|
    | :--- | :----: | :---: |
    | text | ```<input type="text">``` | <input type="text" value="input type text" disabled> |
    | password | ```<input type="password">``` | <input type="password" value="password" disabled> |
    | radio | ```<input type="radio">``` | <input type="radio" disabled> |
    | checkbox | ```<input type="checkbox">``` | <input type="checkbox" value="checkbox" disabled> |
    | submit | ```<input type="submit">``` | <input type="submit" value="submit" disabled> |
    | reset | ```<input type="reset">``` | <input type="reset" value="reset" disabled> |
    | button | ```<input type="button">``` | <input type="button" value="button" disabled> |
    |

    <br/>

    > :note: **Note:**
        1. untuk input type submit, reset, button **tidak** dibuat menggunakan input tetapi **menggunakan tag button**
        2. untuk **memasukkan angka** tetap menggunakan **input type text**

    <br/>

    b. Cara penggunaannya

    **Kode yang dipakai:**

    ```html
    <form>
      // input type text
      <label for="username">Username</label>
      <input type="text" id="username">

      <br>

      // input type radio
      <input type="radio" id="radio" name="jenis kelamin">
          <label for="radio">Pria</label>
      <input type="radio" id="radio" name="jenis kelamin">
          <label for="radio">Wanita</label>

      <br>

      // input type checkbox
      <input type="checkbox" id="menyanyi">
        <label for="menyanyi">Menyanyi</label>
      <input type="checkbox" id="olahraga">
        <label for="olahraga">Olahraga</label>
      <input type="checkbox" id="membaca">
        <label for="membaca">Membaca</label>

      // button
      <button type="submit">Submit</button>
    </form>
    ```
    <br/>

    **Output:**
    <label for="username">Username</label> <input type="text" id="username" disabled>
      <br>
    <input type="radio" id="radio" name="jenis kelamin" disabled><label for="radio" disabled>Pria</label><input type="radio" id="radio" name="jenis kelamin" disabled><label for="radio">Wanita</label>
    <br>
    <input type="checkbox" id="menyanyi" disabled><label for="menyanyi">Menyanyi</label><input type="checkbox" id="olahraga" disabled><label for="olahraga">Olahraga</label><input type="checkbox" id="membaca" disabled><label for="membaca">Membaca</label>
    <br>
    <button type="submit" disabled>Submit</button>
    <br>

    > :note: **Note:** 
        1. **tag label** digunakan untuk **penanda/ memberikan info** tentang tag input
        2. atribut for & id **harus bernilai sama** antara tag input dan label
        3. agar dapat dipilih salah satu saja maka harus **ditambah atribut name** pada **input type radio**
        4. untuk membuat **multiple choice** gunakan **tag input type checkbox** bukan **type radio**

    <br/>

2. textarea

    element ini mirip dengan input, hanya saja dengan textarea jumlah karakter yang dapat dimasukkan lebih banyak, contoh penggunaannya seperti pesan, komentar, alamat.

3. select

    element ini digunakan untuk membuat dropdown/ kombo box.

4. button

    digunakan untuk mengirimkan data, dah hal - hal yang spesifik

5. label

    untuk menandai element input

