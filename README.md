# Jarkom-Modul-4-B01-2022

Anggota :
> Ichsanul Aulia - 05111840007001\
> Alfin Indrawan - 5025201199\
> Graidy Megananda - 5025201188

---
## Tabel Konten
- [Pembagian tugas](#pembagian-tugas)
- [Soal 1](#nomor-1)
- [Soal 2](#nomor-2)
- [Soal 3](#nomor-3)
- [Soal 4](#nomor-4)
- [Soal 5](#nomor-5)
- [Soal 6](#nomor-6)
- [Soal 7](#nomor-7)
- [Soal 8](#nomor-8)
- [Soal 9](#nomor-9)
- [Soal 10](#nomor-10)
- [Soal 11](#nomor-11)
- [Soal 12](#nomor-12)
- [Soal 13](#nomor-13)
- [Soal 14](#nomor-14)
- [Soal 15](#nomor-15)
- [Soal 16](#nomor-16)
- [Soal 17](#nomor-17)
- [Kesulitan](#kesulitan)

## Pembagian Tugas
> Ichsanul Aulia - 7 hingga 11\
> Alfin Indrawan - 1 hingga 6\
> Graidy Megananda - 12 hingga

## Nomor 1
### Soal CIDR
1. Kondisi Node Awal
 
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step1.png?raw=true)

 
| Subnet | Alias                         | Jumlah IP | Netmask |
| ------ | ----------------------------- | --------- | ------- |
| A1     | guideau-the minister          | 1001      | 22      |
| A2     | the minister-the order        | 2         | 30      |
| A3     | the order-asnaf               | 51        | 26      |
| A4     | the order-the reisnonace      | 2         | 30      |
| A5     | the reisnonace-the beast      | 2         | 30      |
| A6     | the reisnonace-the magical    | 2         | 30      |
| A7     | the magical-haines-corvekt    | 271       | 23      |
| A8     | minister-dauntless            | 2         | 30      |
| A9     | matt cugat-the instrument     | 121       | 25      |
| A10    | the reisonance-the instrument | 2         | 30      |
| A11    | the dountless-phanora-johan   | 251       | 24      |
| A12    | the instrument-the profound   | 2         | 30      |
| A13    | the profound-spendrow         | 121       | 25      |
| A14    | keith-the firefist-the queen  | 211       | 24      |
| A15    | the instrument-the firefist   | 2         | 30      |
| A16    | heiga-the profound            | 71        | 25      |
| A17    | the queen-the witch           | 2         | 30      |
| A18    | the firefist-oakleave         | 501       | 23      |
 
2. Penggabungan subnet Pertama (B)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step2.png?raw=true)

| Subnet | Alias   | Jumlah IP | Netmask |
| ------ | ------- | --------- | ------- |
| B1     | A8,A11  | 251       | 23      |
| B2     | A14,A17 | 211       | 23      |
| B3     | A13,A16 | 121       | 24      |

3. Penggabungan subnet Kedua (C)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step3.png?raw=true)

| Subnet | Alias  | Jumlah IP | Netmask |
| ------ | ------ | --------- | ------- |
| C1     | B1,A1  | 1001      | 21      |
| C2     | B2,A18 | 501       | 22      |
| C3     | B3,A12 | 121       | 23      |

4. Penggabungan subnet Ketiga (D)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step4.png?raw=true)

| Subnet | Alias  | Jumlah IP | Netmask |
| ------ | ------ | --------- | ------- |
| D1     | C1,A2  | 1001      | 20      |
| D2     | C2,A15 | 501       | 21      |
| D3     | C3,A9  | 121       | 22      |

5. Penggabungan subnet Keempat (E)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step5.png?raw=true)

| Subnet | Alias | Jumlah IP | Netmask |
| ------ | ----- | --------- | ------- |
| E1     | D1,A3 | 1001      | 19      |
| E2     | D2,D3 | 501       | 20      |

6. Penggabungan subnet Kelima (F)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step6.png?raw=true)

| Subnet | Alias  | Jumlah IP | Netmask |
| ------ | ------ | --------- | ------- |
| F1     | E1,A4  | 1001      | 18      |
| F2     | E2,A10 | 501       | 19      |

7. Penggabungan subnet Keenam (G)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step6.png?raw=true)

| Subnet | Alias | Jumlah IP | Netmask |
| ------ | ----- | --------- | ------- |
| G1     | F1,A5 | 1001      | 17      |
| G2     | F2,A6 | 501       | 18      |

8. Penggabungan subnet Ketujuh (H)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step7.png?raw=true)

| Subnet | Alias | Jumlah IP | Netmask |
| ------ | ----- | --------- | ------- |
| H1     | G2,A7 | 501       | 17      |

9. Penggabungan subnet Kedelapan (I)
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/step8.png?raw=true)

 | Subnet | Alias | Jumlah IP | Netmask |
| ------ | ----- | --------- | ------- |
| I1     | H1,G1 | 1001      | 16      |
 
### Pohon IP
 
![alt text](https://github.com/Graidy27/Jarkom-Modul-4-B01-2022/blob/main/calculation.png?raw=true)

### Tabel Pembagian IP

| Subnet | Alias                         | IP              | Subnet Mask     | Length |
| ------ | ----------------------------- | --------------- | --------------- | ------ |
| A1     | guideau-the minister          | 192.173.0.0     | 255.255.252.0   | 22     |
| A2     | the minister-the order        | 192.173.8.0     | 255.255.255.252 | 30     |
| A3     | the order-asnaf               | 192.173.16.0    | 255.255.255.192 | 26     |
| A4     | the order-the reisnonace      | 192.173.32.0    | 255.255.255.252 | 30     |
| A5     | the reisnonace-the beast      | 192.173.64.0    | 255.255.255.252 | 30     |
| A6     | the reisnonace-the magical    | 192.173.160.0   | 255.255.255.252 | 30     |
| A7     | the magical-haines-corvekt    | 192.173.192.0   | 255.255.254.0   | 23     |
| A8     | minister-dauntless            | 192.173.5.0     | 255.255.255.252 | 30     |
| A9     | matt cugat-the instrument     | 192.173.138.0   | 255.255.255.128 | 25     |
| A10    | the reisonance-the instrument | 192.173.144.0   | 255.255.255.252 | 30     |
| A11    | the dountless-phanora-johan   | 192.173.4.0     | 255.255.255.0   | 24     |
| A12    | the instrument-the profound   | 192.173.137.0   | 255.255.255.252 | 30     |
| A13    | the profound-spendrow         | 192.173.136.0   | 255.255.255.128 | 25     |
| A14    | keith-the firefist-the queen  | 192.173.130.0   | 255.255.255.0   | 24     |
| A15    | the instrument-the firefist   | 192.173.132.0   | 255.255.255.252 | 30     |
| A16    | heiga-the profound            | 192.173.136.128 | 255.255.255.128 | 25     |
| A17    | the queen-the witch           | 192.173.131.0   | 255.255.255.252 | 30     |
| A18    | the firefist-oakleave         | 192.173.128.0   | 255.255.254.0   | 23     |
