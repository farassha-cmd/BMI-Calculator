BMI Calculator - JavaFX + SceneBuilder

Isi project:
- pom.xml: konfigurasi Maven dan dependency JavaFX
- App.java: Main Class untuk menjalankan aplikasi
- BMIController.java: logika menghitung BMI dan tombol Clear
- BMIView.fxml: tampilan GUI yang dapat dibuka dan diedit di SceneBuilder

Cara membuka:
1. Ekstrak BMICalculator.zip ke folder yang mudah ditemukan.
2. Buka NetBeans.
3. Pilih File > Open Project, lalu pilih folder BMICalculator hasil ekstrak.
4. Tunggu Maven mengunduh dependency. Pastikan internet aktif.
5. Untuk menjalankan: klik kanan project > Run, atau jalankan Maven goal:
   clean javafx:run

Kebutuhan:
- JDK 17 atau lebih baru yang kompatibel
- NetBeans dengan dukungan Maven
- Internet saat pertama kali Maven mengunduh JavaFX

Membuka tampilan di SceneBuilder:
1. Buka SceneBuilder.
2. Pilih File > Open.
3. Pilih:
   src/main/resources/com/mycompany/bmicalculator/BMIView.fxml
4. File FXML ini juga bisa diedit dengan drag-and-drop di SceneBuilder.

Catatan:
- Jangan memindahkan BMIView.fxml dari folder resources tanpa menyesuaikan path di App.java.
- Kategori BMI yang digunakan adalah acuan umum untuk orang dewasa dan bukan diagnosis medis.
