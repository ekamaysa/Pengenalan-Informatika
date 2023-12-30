# Hello Informatics !
## Menjelaskan dan Menginternalisasi Computational Thinking ⭐⭐⭐⭐⭐⭐⭐
https://ekamay10.wordpress.com/2023/12/20/computational-thinking/
## Menjelaskan Jenis-Jenis Mesin Komputasi ⭐⭐⭐

https://ekamay10.wordpress.com/2023/12/25/jenis-jenis-mesin-komputasi/

## Mengktifkan dan Mencoba Google Colab [v] ⭐⭐⭐⭐⭐
<img width="960" alt="Screenshot 2023-12-26 164635" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/f529b85c-8fc8-47a8-a4bc-1816589c8aab">
<img width="960" alt="Screenshot 2023-12-26 164959" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/80c70d69-ff4b-429c-bfd7-9334c75b0e41">

## Mencoba Console Sistem Operasi

### Windows CMD [v] ⭐⭐⭐⭐
<img width="960" alt="Screenshot 2023-12-26 223147" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/aff73342-0e5d-4240-9999-1dbfffdeb323">
<img width="960" alt="Screenshot 2023-12-28 223401" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/cf32c45f-5224-4506-b62f-1deee259d79a">

File yang saya cari tidak ditemukan terus entah apa faktor yang menyebabkan hal-hal tersebut


Referensi [1](https://www.stationx.net/windows-command-line-cheat-sheet/)

### Linux Terminal Menggunakan Google Colab [v] ⭐⭐⭐⭐
link : https://youtu.be/Y37YaJglPjI?si=O1MB343zPG6PUpsB

## Membuat Algoritma Dalam Bentuk Flow Chart [v] ⭐⭐⭐⭐⭐
link : https://youtu.be/_7NjJpxdc8g?si=ebvEpbv4Lz8Ei6ZS

<img width="460" alt="Screenshot 2023-12-26 233532" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/8d5586bb-b6ad-4b3e-9e51-e98b54f4a2ec">


## Mencoba Scratch Bahasa Indonesia [v] ⭐⭐⭐⭐⭐⭐⭐
link : https://youtu.be/mdYuPZOPx2w?si=uXcDSpCjUZH-A8G5

## Mencoba Algoritma Bubble Sort Menggunakan Java [v] ⭐⭐⭐

    public class BubbleSortHewan {

    public static void main(String[] args) {
        // Membuat array dari objek Hewan
        Hewan[] hewanArray = {
                new Hewan("Gajah", 500),
                new Hewan("Jerapah", 400),
                new Hewan("Singa", 300),
                new Hewan("Harimau", 450),
                new Hewan("Zebra", 350)
        };

        System.out.println("Daftar Hewan sebelum diurutkan:");
        printArray(hewanArray);

        bubbleSort(hewanArray);

        System.out.println("\nDaftar Hewan setelah diurutkan:");
        printArray(hewanArray);
    }

    // Metode untuk melakukan Bubble Sort pada objek Hewan
    static void bubbleSort(Hewan[] arr) {
        int n = arr.length;
        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                // Jika berat Hewan ke-j lebih besar dari berat Hewan ke-(j+1), tukar mereka
                if (arr[j].getBerat() < arr[j + 1].getBerat()) {
                    Hewan temp = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = temp;
                }
            }
        }
    }

    // Metode untuk mencetak elemen-elemen array Hewan
    static void printArray(Hewan[] arr) {
        for (Hewan hewan : arr) {
            System.out.println(hewan);
        }
    }
    }
// Kelas Hewan untuk merepresentasikan objek Hewan
    
    class Hewan {
    private String nama;
    private int berat;

    public Hewan(String nama, int berat) {
        this.nama = nama;
        this.berat = berat;
    }

    public int getBerat() {
        return berat;
    }

    @Override
    public String toString() {
        return "Hewan{" +
                "nama='" + nama + '\'' +
                ", berat=" + berat +
                '}';
    }
}

## Mencoba dan Mendemonstrasikan Penggunakan IDE ⭐⭐
link : https://youtu.be/8FqYTOK0PjI?si=G2Wq7CmXxmL7Xmhp

## Mendaftar, Mengeksplorasi, dan Mendemonstrasikan Penggunaan HackerRank [v] ⭐⭐⭐⭐⭐
link : https://youtu.be/dJmwBTkfRcM?si=G82duNDk6NUx2uz_

<img width="350" alt="Screenshot 2023-12-25 181226" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/b5d0dbd1-51bd-4f89-8206-3adbacd661de">
<img width="350" alt="Screenshot 2023-12-28 223931" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/e06108e2-2080-446c-97e6-82ca4ee6c411">
<img width="350" alt="Screenshot 2023-12-28 224148" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/e067f1d7-5e59-417a-9951-a2e0d6fa51c0">
<img width="350" alt="Screenshot 2023-12-28 224436" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/8888c1fa-df0b-4ae0-a1e0-011e0203d10b">
<img width="350" alt="Screenshot 2023-12-28 225416" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/0d78bd32-ee78-4afd-acc7-7144c15e33b5">
<img width="350" alt="Screenshot 2023-12-28 225610" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/4152d347-61a4-4fd8-901b-2a5449341666">
<img width="350" alt="Screenshot 2023-12-28 230035" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/ae8548f7-5ad4-4187-a051-c7efc467120f">


## Mendemonstrasikan Pembuatan Aplikasi / Game Pada Platform : Mobile / Desktop / Web Browser ⭐⭐⭐⭐⭐

link : https://youtu.be/MYAxfq9hJkg?si=bRk_0C1oF3ucD14t

link : https://youtu.be/QLhx30OobS0?si=HLsLjRJ44Iy0C8ma

## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐
<img width="424" alt="Screenshot 2023-12-27 012247" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/af44f667-ae37-4f28-b3ae-71686ab57b10">
<img width="960" alt="Screenshot 2023-12-27 012630" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/9e356239-22f5-4e09-8cf2-fe90bccb88e4">
<img width="646" alt="Screenshot 2023-12-27 012859" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/c81a9c39-5710-4fc6-90da-bb34b15a6dfc">
<img width="534" alt="Screenshot 2023-12-27 013044" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/3f7ed09f-aca6-4175-a46e-7986fc09731f">



Referensi installer [PostgreSQL](https://www.postgresql.org/download/windows/)
Referensi tambahan [1](https://db-engines.com/en/ranking)

## Mencoba Eksplorasi dan Query Database Menggunakan Database Explorer (Dbeaver / dsb.) [v] ⭐⭐⭐
<img width="514" alt="Screenshot 2023-12-27 013327" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/261a5c46-3049-4f78-ac32-3459b873953e">
<img width="427" alt="Screenshot 2023-12-27 013343" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/1597a601-cf75-4d7a-b0d1-0fc561fca0d8">
<img width="960" alt="Screenshot 2023-12-27 013402" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/d118d05f-a839-44f2-a5d7-26062d37e6f4">

Referensi installer [Dbeaver](https://dbeaver.io/download/)
Referensi [1](https://www.w3schools.com/postgresql/postgresql_create_table.php)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐
https://ekamay10.wordpress.com/2023/12/28/penggunaan-web-browser-untuk-mengakses-halaman-website-html/

link : https://youtu.be/2kNm7MEZPe4?si=jAZJVSD42jjLkI4C

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐
https://ekamay10.wordpress.com/2023/12/28/komponen-dari-contoh-uniform-resource-locator-url/

link : https://youtu.be/Zu6iz0JOE9c?si=WyCniyKo9VGTRvAn

Referensi: [1](https://www.startertutorials.com/ajwt/uniform-resource-locator.html)

## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐

Referensi terkait: [1](https://en.wikipedia.org/wiki/Country_code_top-level_domain) [2](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐
https://ekamay10.wordpress.com/2023/12/28/html-css-dan-javascript/

https://youtu.be/v_sCdc1Z5Ng?si=CRYt_QjdCKp9vijb

Referensi tutorial 
- Isi konten halaman web : [HTML](https://www.w3schools.com/html/)
- Styling halaman web : [CSS](https://www.w3schools.com/css/)
- Interaktivitas halaman web : [JavaScript](https://www.w3schools.com/js/)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐
link : https://youtu.be/zkEAfx9qeuc?si=Kw0ZnRhY-7DghBCc

Referensi []

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐
<img width="594" alt="Screenshot 2023-12-29 234620" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/640a80a3-d3cd-4e6f-bb1f-e45bedba5e19">

## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐
link : https://youtu.be/BFuj2KxYwAo

## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐
link : https://youtu.be/BFuj2KxYwAo?si=swx9yB8t8AeyriDq

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐
<img width="400" alt="Screenshot 2023-12-30 200540" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/f92637c2-e6b3-4d56-bdc8-79fd775d58b3">
<img width="400" alt="Screenshot 2023-12-30 200706" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/82f5097b-c56a-4168-8bae-d27c171ef2c3">


## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐
link : https://youtu.be/4fUt-wKWrJY

## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐
https://ekamay10.wordpress.com/2023/12/30/amazon-web-services-aws/
## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐


## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐
<img width="350" alt="Screenshot 2023-12-30 181600" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/d3b2673b-c2fd-4f80-bf53-c4b47d0af8ac">
<img width="350" alt="Screenshot 2023-12-30 181624" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/d70d85ff-b110-429e-b45b-e1994b2fdbde">
<img width="350" alt="Screenshot 2023-12-30 181641" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/34a7a40c-3d72-4028-8c23-64246aa0cfc8">
<img width="350" alt="Screenshot 2023-12-30 181709" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/c635a45f-e825-47c7-801d-4e7fea70b38a">


## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐
![1](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/6150de67-1bc8-484c-9ca4-9223dc4cf0ab)
![2](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/2f5d6d54-bd07-4822-9477-c2037537438a)
![33](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/edc0151a-962d-4e25-aedb-a044390a141e)
![44](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/34b9e832-8c32-48cc-9c8d-a43d87b12a1f)



## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐
<img width="400" alt="Screenshot 2023-12-30 184834" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/3bfd25a4-464c-43b4-96b5-23675bf47be5">
<img width="400" alt="Screenshot 2023-12-30 184751" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/2bd5ca3f-9478-4c0c-99b0-137dd959c1e7">

## Mencoba Pemrosesan Konten Multimedia (Image, Audio) Menggunakan Google Colab [v] ⭐⭐⭐
https://colab.research.google.com/drive/1eA2FdEZUUJL6FxNtT_Ezcvz6mtukXtjb#scrollTo=NS5c-yPgc6El

## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐
https://colab.research.google.com/drive/1eA2FdEZUUJL6FxNtT_Ezcvz6mtukXtjb#scrollTo=NS5c-yPgc6El

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐
https://colab.research.google.com/drive/1eA2FdEZUUJL6FxNtT_Ezcvz6mtukXtjb#scrollTo=NS5c-yPgc6El

## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐
https://colab.research.google.com/drive/1eA2FdEZUUJL6FxNtT_Ezcvz6mtukXtjb#scrollTo=NS5c-yPgc6El

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐
https://youtu.be/i7XZUMDAy9s

## Mencoba Data Visualization Dengan Code [v] ⭐⭐
https://colab.research.google.com/drive/1ZTDdRbK4i7FNMm5sVj7NMbD-iSXFz8kT?hl=id

link : https://youtu.be/SpfCNMX2F7c

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐
https://huggingface.co/ekamay
<img width="960" alt="Screenshot 2023-12-22 003613" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/14e7c383-baa5-41ab-b3b6-ccc41250f382">

## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐
https://www.kaggle.com/ekamaysar
<img width="960" alt="Screenshot 2023-12-22 004321" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/0d5752cf-dd9a-4956-b1fa-32edcfc536d8">

## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐
![WhatsApp Image 2023-12-30 at 20 33 28_6b154def](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/1a0d19a1-e968-4282-8cd2-ffbe54ae73be)

## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐
<img width="400" alt="File CSV " src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/f3a4d43a-7b26-499c-bd08-8902db3dbfdf">

## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐
<img width="350" alt="ORC" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/0aad6e7f-7199-4d8e-bc21-84689ce95899">
<img width="350" alt="ORC2" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/23261a89-b9d9-46df-b115-e97307993d4c">

## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐
https://wordpress.com/post/ekamay10.wordpress.com/37

## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐\
<img width="400" alt="Screenshot 2023-12-30 205054" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/679823d8-2b94-4e7b-8992-cda127cc9dca">
<img width="400" alt="Screenshot 2023-12-30 205110" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/01495a2a-b09e-46c5-a44f-a9a6a3ad58ab">
<img width="400" alt="Screenshot 2023-12-30 205124" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/ac4bddb9-b6aa-46e9-8df6-5916b2b79a4f">


## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐
<img width="500" alt="Screenshot 2023-12-30 205738" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/c111bef8-3b6b-4e05-a0a8-bd4024bbd4e4">


## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐
![Profesi Terkait Informatika](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/8eb06e10-6bf3-4083-b835-0f7b129b7ccf)

Penjelasan selengkapnya ada disini:
## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐
link : https://www.duolingo.com/profile/EkaMay

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 
link : https://hellotalk.com/u/eka_may
## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐
link : https://ekamay10.wordpress.com/2023/12/30/eksplorasi-lowongan-pekerjaan-it/
## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐
<img width="400" alt="Screenshot 2023-12-30 205906" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/49096d79-2b7d-49ff-a850-f5d7ee10d1b1">
<img width="400" alt="Screenshot 2023-12-30 205932" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/f77200c1-e5e0-492d-beab-f469e6058315">
<img width="400" alt="Screenshot 2023-12-30 205950" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/379ede3e-e23f-45dc-80e3-f2ac16160718">


## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐
https://roadmap.sh/account/update-profile
<img width="956" alt="Screenshot 2023-12-20 233713" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/33d1885a-1196-48f3-b60e-5b2490934b34">
<img width="957" alt="Screenshot 2023-12-20 233731" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/dfdb14b3-cfe4-46f5-ab4b-5c816e1268b0">

## Eksplorasi Top Github Project yang Diminati ⭐⭐ 
<img width="400" alt="Screenshot 2023-12-30 210356" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/3f61e7f4-35c4-4769-b20f-261d24c27120">
<img width="400" alt="Screenshot 2023-12-30 210424" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/5af94313-4e48-4320-ab3a-c67b77e16427">


## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐
link : https://www.linkedin.com/in/eka-maysa-rahmah-9741662a2/
## Membangun Profil Github Page ⭐⭐⭐⭐⭐
link : https://github.com/ekamaysa
## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐
![WhatsApp Image 2023-12-30 at 21 07 37_2f46b2fa](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/163853c3-f5be-4ea6-b732-912a3ef2886f)
![WhatsApp Image 2023-12-30 at 21 08 51_9966eaab](https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/996d8009-a6f7-442e-8378-4e386fdb41a2)

 
## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐
PENGENALAN KONSEP
MACHINE LEARNING
UNTUK PEMULA

Penulis : 

Gregorius N. Elwirehardja

Teddy Suparyanto

Bens Pardamean

Isinya :

Dengan revolusi industri 4.0, sistem cerdas atau sistem 
canggih dapat ditemukan di sekitar kita. Sebagai contoh, saat kita 
mengambil foto dengan kamera pada smartphone, kita dapat secara 
otomatis memfokuskan kamera pada wajah manusia, yaitu fitur face 
detection pada saat kita melakukan swafoto. Bahkan di dunia medis 
pun, banyak sistem Computer-Aided Diagnosis (CAD) yang bisa 
membantu dokter dalam melakukan pemeriksaan pada para pasiennya. Tentunya semua teknologi ini tidak lepas dari sistem cerdas, di mana teknologi Artificial Intelligence (AI) sudah berperan. Namun untuk melakukan tugas-tugas di atas, akan sangat memakan waktu jika kita memprogram rangkaian aturan satu persatu untuk setiap jenis penyakit demi membuat sistem cerdas tersebut. Untuk mengatasi masalah ini, teknologi Machine Learning dapat menjadi solusinya. Machine learning adalah bidang ilmu yang mempelajari cara membuat model AI dapat belajar. Umumnya, model AI ini disebut sebagai model machine learning, yaitu model algoritma komputasi yang mampu menyimpan serta mengubah knowledge yang ia miliki melalui proses pembelajaran dari data. Model Machine learning adalah salah satu jenis model AI yang paling banyak digunakan di era 4.0, baik untuk data berupa tabel, teks, suara, dan sebagainya.
