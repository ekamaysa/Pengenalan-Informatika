# Hello Informatics !
## Menjelaskan dan Menginternalisasi Computational Thinking ⭐⭐⭐⭐⭐⭐⭐
https://ekamay10.wordpress.com/2023/12/20/computational-thinking/
## Menjelaskan Jenis-Jenis Mesin Komputasi ⭐⭐⭐

## Mengktifkan dan Mencoba Google Colab [v] ⭐⭐⭐⭐⭐

## Mencoba Console Sistem Operasi

### Windows CMD [v] ⭐⭐⭐⭐

Referensi [1](https://www.stationx.net/windows-command-line-cheat-sheet/)

### Linux Terminal Menggunakan Google Colab [v] ⭐⭐⭐⭐

## Membuat Algoritma Dalam Bentuk Flow Chart [v] ⭐⭐⭐⭐⭐


## Mencoba Scratch Bahasa Indonesia [v] ⭐⭐⭐⭐⭐⭐⭐


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

## Mendaftar, Mengeksplorasi, dan Mendemonstrasikan Penggunaan HackerRank [v] ⭐⭐⭐⭐⭐

## Mendemonstrasikan Pembuatan Aplikasi / Game Pada Platform : Mobile / Desktop / Web Browser ⭐⭐⭐⭐⭐

https://youtu.be/MYAxfq9hJkg?si=bRk_0C1oF3ucD14t
https://youtu.be/QLhx30OobS0?si=HLsLjRJ44Iy0C8ma

## Mencoba Instalasi Database (PostgreSQL / MySQL / dsb.) [v] ⭐⭐⭐

Referensi installer [PostgreSQL](https://www.postgresql.org/download/windows/)
Referensi tambahan [1](https://db-engines.com/en/ranking)

## Mencoba Eksplorasi dan Query Database Menggunakan Database Explorer (Dbeaver / dsb.) [v] ⭐⭐⭐

Referensi installer [Dbeaver](https://dbeaver.io/download/)
Referensi [1](https://www.w3schools.com/postgresql/postgresql_create_table.php)

## Mendemonstrasikan dan Menjelaskan Penggunaan Web Browser untuk Mengakses Halaman Website HTML [v] ⭐⭐⭐⭐

## Mendemonstrasikan dan Menjelaskan Komponen Dari Contoh Uniform Resource Locator (URL) [v] ⭐⭐

Referensi: [1](https://www.startertutorials.com/ajwt/uniform-resource-locator.html)

## Mencoba Pelacakan Informasi Server dari Alamat Domain [v] ⭐

Referensi terkait: [1](https://en.wikipedia.org/wiki/Country_code_top-level_domain) [2](https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains)

## Mencoba Pembuatan Halaman Web Menggunakan HTML, CSS, dan JavaScript [v] ⭐⭐⭐

Referensi tutorial 
- Isi konten halaman web : [HTML](https://www.w3schools.com/html/)
- Styling halaman web : [CSS](https://www.w3schools.com/css/)
- Interaktivitas halaman web : [JavaScript](https://www.w3schools.com/js/)

## Mencoba Penerapan Teknik Search Engine Optimization (SEO) Pada HTML [v] ⭐⭐⭐

Referensi []

## Mencoba Pembuatan File JSON [v] ⭐⭐⭐

## Mencoba Penggunaan Web Hosting Dengan Untuk Halaman HTML [v] ⭐⭐⭐


## Mencoba Penggunaan Web Hosting Dengan Untuk Web Service [v] ⭐⭐⭐

## Mencoba HTTP Request dan Web API dengan Hoppscotch / Postman [v] ⭐⭐

## Mendemonstrasikan Penggunaan Developer Tools Pada Web Browser (Firefox / Chrome) [v] ⭐⭐⭐⭐⭐

## Mengeksplorasi dan Menjelaskan Layanan Cloud Service yang Diminati (GCP / AWS / Azure) [v] ⭐⭐


## Mencoba Penggunaan Content Management System (Wordpress) [v] ⭐⭐⭐


## Mendemonstrasikan Akses Konten Multimedia (Image, Audio, Video) ⭐⭐⭐

## Mencoba Edit Konten Multimedia (Image, Audio, Video) [v] ⭐⭐

## Mencoba Pembuatan Game dan Simulasi Menggunakan Logo [v] ⭐⭐

## Mencoba Pemrosesan Konten Multimedia (Image, Audio) Menggunakan Google Colab [v] ⭐⭐⭐

## Mencoba Web Tool AI Discriminative (Image Classification) [v] ⭐⭐⭐⭐

## Mencoba Web Tool AI Generative (Text to Image, Text to Text) [v] ⭐⭐⭐⭐

## Mencoba Model Machine Learning Menggunakan Google Colab, TTS, Speechrecognition, dan HuggingFace [v] ⭐⭐⭐

## Mencoba Data Visualization Dengan Tools [v] ⭐⭐

## Mencoba Data Visualization Dengan Code [v] ⭐⭐

## Mendaftar dan Mencoba Eksplorasi HuggingFace [v] ⭐⭐⭐
https://huggingface.co/ekamay
<img width="960" alt="Screenshot 2023-12-22 003613" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/14e7c383-baa5-41ab-b3b6-ccc41250f382">

## Mendaftar dan Mencoba Eksplorasi Kaggle [v] ⭐⭐⭐⭐
https://www.kaggle.com/ekamaysar
<img width="960" alt="Screenshot 2023-12-22 004321" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/0d5752cf-dd9a-4956-b1fa-32edcfc536d8">

## Mencoba Protokol Komunikasi IoT (MQTT) [v] ⭐

## Mencoba Memproses File CSV Menggunakan Google Colab [v] ⭐⭐

## Mencoba Memproses File Big Data ORC Menggunakan Google Colab [v] ⭐⭐

## Menjelaskan Jurnal, Conference, Artikel, Grade Jurnal [v] ⭐⭐⭐⭐⭐

## Eksplorasi Artikel Jurnal / Conference di Repository Terekognisi Internasional (IEEE / Arxiv / Science Direct / ACM /DBLP) [v] ⭐⭐⭐⭐\


## Menonton Video Presentasi Tugas Akhir Informatika ⭐⭐⭐⭐⭐

## Mengeksplorasi Seluruh Profesi Terkait Informatika dan Profesi yang Diminati ⭐⭐⭐⭐

## Eksplorasi Tools Untuk Belajar Bahasa Inggris (Duolingo) ⭐⭐⭐
https://www.duolingo.com/profile/EkaMay

## Eksplorasi Tools Untuk Belajar Berbicara Bahasa Inggris (HelloTalk) ⭐⭐⭐ 
https://hellotalk.com/u/eka_may
## Eksplorasi Lowongan Pekerjaan IT ⭐⭐⭐


## Eksplorasi Lowongan Freelancer IT (Upwork / Toptal / Freelancer.com) ⭐⭐⭐


## Eksplorasi dan Pilih Topik yang Diminati di Roadmap.sh ⭐⭐⭐
https://roadmap.sh/account/update-profile
<img width="956" alt="Screenshot 2023-12-20 233713" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/33d1885a-1196-48f3-b60e-5b2490934b34">
<img width="957" alt="Screenshot 2023-12-20 233731" src="https://github.com/ekamaysa/Pengenalan-Informatika/assets/144700802/dfdb14b3-cfe4-46f5-ab4b-5c816e1268b0">

## Eksplorasi Top Github Project yang Diminati ⭐⭐ 


## Membangun Profil Linkedin dan Mengikuti Akun-Akun Inspirasif Bertema Informatika ⭐⭐⭐
https://www.linkedin.com/in/eka-maysa-rahmah-9741662a2/
## Membangun Profil Github Page ⭐⭐⭐⭐⭐
https://github.com/ekamaysa
## Mengikuti Workshop / Event / Course Terkait IT ⭐⭐⭐⭐


## Membaca dan Mengambil Inspirasi Dari Buku Bertema Informatika ⭐⭐⭐⭐⭐
