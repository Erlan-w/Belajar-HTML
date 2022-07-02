<p align="center">
  <h1 align="center">Form</h1>

Membuat Form pada halaman HTML elementnya harus ditulis diantara tag form, seperti dibawah ini.

<br/>

**Tag yang dipakai**

```html
<form>
  ... Tulis Kode/element Programnya Disini
</form>
```

<h2 align="center" id="element-form">Element Form</h2>


1. input

    element ini digunakan agar user dapat memasukkan sesuatu dalam form, contoh penggunaannya seperti password, username, dll. <br/>


    a. jenis-jenis input

    |Type | Kode |
    | :--- | :----: |
    | Text | ```<input type="text">``` |
    | Password | ```<input type="password">``` |
    | Radio | ```<input type="radio">``` |
    | Checkbox | ```<input type="checkbox">``` |
    | Submit | ```<input type="submit">``` |
    | Reset | ```<input type="reset">``` |
    | Button | ```<input type="button">``` |

    <br/>

    > 📝 **Note** **:** <br/>
        1. untuk input type submit, reset, button **tidak** dibuat menggunakan input tetapi **menggunakan tag button** <br/>
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
    
    **Output:**
    
    > **Warning** **:** <br/>
      Untuk output dari kode diatas silahkan langsung gunakan pada file HTML atau bisa download file index.html di halaman depan (dashboard).
  
   <br/>
  
    > 📝 **Note** **:** <br/>
        1. **tag label** digunakan untuk **penanda/ memberikan info** tentang tag input <br/>
        2. atribut for & id **harus bernilai sama** antara tag input dan label <br/>
        3. agar dapat dipilih salah satu saja maka harus **ditambah atribut name** pada **input type radio** <br/>
        4. untuk membuat **multiple choice** gunakan **tag input type checkbox** bukan **type radio** <br/>

 <br/>
 
2. textarea

    element ini mirip dengan input, hanya saja dengan textarea jumlah karakter yang dapat dimasukkan lebih banyak, contoh penggunaannya seperti pesan, komentar, alamat.

3. select

    element ini digunakan untuk membuat dropdown/ kombo box.

4. button

    digunakan untuk mengirimkan data, dah hal - hal yang spesifik

5. label

    untuk menandai element input

 <br/>
<h2 align="center" id="pranala-menarik">Bacaan lebih lanjut</h2>

- [Table](../table/TABLE.md)
- [Dashboard](../README.md)
