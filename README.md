## Janji
Saya Fachri Najm Noer Kartiman NIM 2106515 mengerjakan soal Latihan 5
dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya
maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan.
Aamiin.

# Tugas LATIHAN5DPBO2023
Download this starter project: [Starter Project](https://drive.google.com/file/d/1TEnEay74nhGcSS9PPzQcxksIlaQhTiZ2/view?usp=sharing) 
* Add more property (component type: any, except text field)
* Add method to reset form
* Refresh table after update and delete
* Add confirmation prompt before delete
* Build project (generate .jar file)

File README berisi desain program, penjelasan alur, dan dokumentasi saat program dijalankan (screenshot/screen record)

Submit link repository pada form berikut: [Form Pengumpulan](https://forms.gle/rvb1hKxbQVuYNbhKA) 

## Desain Program
Desain yang saya buat menggunakan 1 Class Utama:
* Mahasiswa
* Menu

`Class Mahasiswa` :
* **NIM** -> NIM mahasiswa, `string`
* **Nama** -> Nama mahasiswa, `string`
* **Nilai** -> Nilai mahasiswa, `string`
* **gender** -> Gender mahasiswa, `string`

`Class Menu` :
* **Set Tabel** -> Mengeset Tabel untuk ditampilkan, `void`
* **Insert Data** -> Menambah data, `void`
* **Update Data** -> mengubah data yang dipilih, `void`
* **Delete Data** -> menghapus data yang dipilih, `void`
* **Reset Form** -> Mereset Form, `void`

_Semua Class diatas dilengkapi dengan setter dan getternya_

## Design GUI
![JAR FILE](design.png)


## Alur Program Program GUI

Text field untuk mengisi data yang berisi nim, nama, nilai dan radio button untuk memilih gender mahasiswa

Mengisi text field dan memlih gender jika di klik `add` maka akan menambah data dan seluruh data akan ditampilkan di tabel

Mengisi text field dan memlih gender jika di klik `Cancel` maka TextField akan kosong

Memilih data jika ada data yang ingin dirubah maka rubah di text field nya atau gender radio button jika sudah maka klik `update`

Memilih data jika ada data yang ingin dihapus jika sudah maka klik `delete`

## Dokumentasi
**JAR FILE**

![JAR FILE](jar-file.png)

**Confirm Delete**
![Screenshot 2023-03-17 091422](https://user-images.githubusercontent.com/92314386/225795247-c63588f5-dc34-4781-9fc3-ee32bde74b70.png)

**Update Data**

![image](https://user-images.githubusercontent.com/92314386/225795139-feaef12f-4d59-4941-a108-e91bc4f8921e.png)

