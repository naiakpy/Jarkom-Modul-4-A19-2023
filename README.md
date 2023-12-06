# Laporan Resmi

# Kelompok A19:
| Nama | NRP |
| ---------------------- | ---------- |
| Nayya Kamila Putri Y | 5025211183 |
| Javier Nararya Aqsa Setiyono | 5025211245 |

## Topologi dan Pembagian Subnet
![topo](img/topologi.png)

## VLSM (Cisco Packet Tracer)

VLSM (Variable Length Subnet Mask) adalah metode subnetting yang memungkinkan penggunaan netmask yang berbeda untuk setiap subnet yang ada dalam jaringan. Pendekatan ini memungkinkan penempatan subnet dengan ukuran yang sesuai untuk memenuhi kebutuhan jumlah host dalam setiap subnet, sehingga mengoptimalkan penggunaan alamat IP yang tersedia. Dengan VLSM, subnet yang membutuhkan lebih banyak host dapat diberikan alamat yang lebih besar, sedangkan subnet yang membutuhkan jumlah host yang lebih sedikit diberikan alamat yang lebih kecil. Hal ini membantu efisiensi penggunaan alamat IP dalam jaringan.

## Subnetting

Hitung jumlah host di setiap subnet serta rutenya, lalu tetapkan netmask untuk setiap subnet.
![tabel1](img/tabel1.png)

Diperhatikan bahwa total host yang dibutuhkan adalah 4257, sehingga netmask subnet besar yang cocok untuk penggunaan tersebut adalah /19

Selanjutnya, buat Tree menggunakan metode VLSM (Variable Length Subnet Mask) untuk mengakomodasi kebutuhan host tersebut

![tree](img/Tree.jpg)

Lalu cari Network ID, Netmask, dan Broadcast Address tiap Subnetnya

![tabel2](img/tabel2.png)

Setelah didapatkan semua IP-nya, dapat langsung diimplementasikan di Cisco Packet Tracer

## Implementasi VLSM di Cisco
## Routing

### Fern
![fern](img/fern.png)

### Flamme
![flamme](img/flamme.png)

### Himmel
![himmel](img/himmel.png)

### Frieren
![frieren](img/frieren.png)

### Aura
![aura](img/aura.png)

### Denken
![denken](img/denken.png)

### Elsen
![elsen](img/elsen.png)

### Linie
![linie](img/linie.png)

### Lawine
![lawine](img/lawine.png)

### Heiter
![heiter](img/heiter.png)

## Hasil Testing
Berikut adalah beberapa hasil testing yang sudah di lakukan

![test](img/test1.png)

![test](img/test2.png)
