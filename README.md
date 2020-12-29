# Jarkom_Modul5_Lapres_B04

- Syubban Fakhriya  05111840000042
- Feraldy Nathanael 05111840000066

## (A) Membuat topologi jaringan sesuai dengan rancangan yang telah diberikan

## (B) Melakukan subnetting dengan VLSM atau CIDR

## (C) Melakukan routing

## (D) Memberikan ip pada subnet **SIDOARJO** dan **GRESIK** secara dinamis menggunakan bantuan DHCP SERVER (selain itu menggunakan ip static)

## (1) Mengkonfigurasi **SURABAYA** menggunakan iptables tanpa MASQUERADE

## (2) Mendrop semua akses SSH dari luar topologi pada server yang memiliki ip DMZ (DHCP dan DNS SERVER) pada **SURABAYA**

## (3) Membatasi DHCP dan DNS server hanya boleh menerima maksimal 3 koneksi ICMP secara bersamaan yang berasal dari mana saja menggunakan **iptables pada masing-masing server**, selebihnya akan di drop.

## (4) Akses dari subnet **SIDOARJO** ke **MALANG** hanya diperbolehkan pada pukul 07.00 - 17.00 dari senin - jumat

## (5) Akses dari subnet **GRESIK** ke **MALANG** hanya diperbolehkan pada pukul 17.00 - 07.00 setiap hari

## (6) **SURABAYA** disetting sehingga setiap request dari client yang mengakses **DNS Server** akan didistribusikan **secara bergantian** pada **PROBOLINGGO** port 80 dan **MADIUN** port 80

## (7) Semua paket yang didrop oeh firewall (dalam topologi) tercatat dalam log pada setiap UML yang memiliki aturan drop.