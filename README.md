# Capstone-Project-Modul-2
## Latar Belakang
Airbnb merupakan platform online untuk orang menyewa tempat tinggal sementara ketika berpergian ataupun berlibur melalui website atau aplikasi airbnb. Pengguna dapat menemukan berbagai jenis properti yang tersedia untuk di sewa, seperti rumah, apartemen, kamar pribadi, hotel, dan sebagainya.  

Walaupun banyak pilihan tempat tinggal yang tersedia, properti tersebut bukanlah milik airbnb sendiri. Melainkan airbnb adalah broker yang bekerjasama dengan pemilik properti untuk mengiklankan propertinya agar dengan mudah dijangkau oleh orang orang. Dengan begitu airbnb dapat memberikan manfaat pada pemilik properti dan penyewa.

Salah satu manfaatnya **pemilik properti dapat dengan mudah mendapatkan penyewa** dan airbnb akan mengambil komisi untuk jasanya disetiap pemesanan. Selain itu penyewa juga bisa memberikan **review pada properti yang disewa agar bisa menambah daya tarik properti** tersebut dan memikat calon penyewa selanjutnya. Dan review tersebut juga **menggambarkan popularitas dari properti karena semakin banyak review menandakan properti tersebut banyak disewa**.  

Sayangnya terdapat ketimpangan pada jumlah review properti yang terdaftar di airbnb bangkok. Sehingga tidak semua pemilik properti mendapat popularitas yang baik. Untuk itu diadakan analisis bagaimana cara meningkatkan review properti yang telah terdaftar di airbnb?
Pada daftar properti yang telah terdaftar pada airbnb per tahun 2023, terdapat ketimpangan atas jumlah review yang diberikan oleh penyewa. hal ini ditunjukan dengan grafik berikut.

Dengan adanya permasalahan tersebut, sebagai seorang *data science*, kita akan membantu para pemilik properti yang telah terdaftar di airbnb ataupun pemilik properti yang berminat untuk bekerja sama dengan airbnb untuk **meningkatkan review properti di airbnb agar banyak penyewa yang menyewa properti mereka**, dengan menjawab pertanyaan berikut:

- **Bagaimana karakteristik properti yang telah direview di Bangkok?**
- **Bagaimana menentukan properti agar memungkinkan menjadi populer (banyak direview) di Bangkok?**

## Stakeholder
- Para pemilik properti yang ingin mendaftarkan propertinya ke AirBNB
## Data
Untuk menjawab pertanyaan di atas, kita akan menganalisa data properti yang sudah terdaftar pada AirBNB listing Bangkok. Dataset dapat diakses [di sini](https://drive.google.com/drive/folders/1A_KBMRFTS5Mthpp46nulso679ML4ZwTF).  

Dataset terdiri dari 15854 data properti yang terdaftar pada AirBNB, dengan 13 variabel yang menjelaskan karakteristik properti tersebut.

## Deskripsi Tabel
| No. | Variabel | Deskripsi |
|-|-|-|
| 1. | **ID** | Identifikasi unik AirBNB untuk setiap listing. |
| 2. | **Name** | Nama Daftar. |
| 3. | **host_id** | ID Unik airBNB untuk setiap host/user. |
| 4. | **host_name** | nama Host/Nama depan. |
| 5. | **Neighborhood** | kode geografis lingkungan menggunakan garis lintang dan garis bujur terhadap lingkungan. |
| 6. | **Latitude** | Menggunakan proyeksi Sistem Geodesi Dunia (WGS84) untuk garis lintang.|
| 7. | **Longitude** |  Menggunakan proyeksi Sistem Geodesi Dunia (WGS84) untuk garis bujur.|
| 8. | **Room Type** | Tipe ruangan yang dimiliki oleh AirBNB Bangkok. |
| 9. | **Price** | Harga harian dalam mata uang lokal. Catatan, tanda $ dapat digunakan meskipun lokal. |
| 10. | **minimum_nights** | Jumlah minimum masa inap malam untuk listing (kalender aturan mungkin berbeda). |
| 11. | **number_of_reviews** | Jumlah ulasan yang dimiliki dalam daftar. |
| 12. | **availability_365** | Lama properti dapat dipesan dalam hari untuk pemesanan berikutnya  |
| 13. | **number_of_reviews_ltm** | Jumlah ulasan yang dimiliki listingan (dalam 12 bulan terakhir). |

## Dashboard
https://public.tableau.com/app/profile/muhamad.cahyo.wicaksono/viz/AirbnbListingBangkok/DashboardforHost
