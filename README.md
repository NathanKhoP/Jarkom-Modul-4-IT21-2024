# Jarkom-Modul-4-IT21-2024

|Nama  | NRP |
|--|--|
| Nathan Kho Pancras | 5027231002 |
| Muhammad Andrean Rizq Prasetio | 5027231052 |

## Daftar Isi

- [Jarkom-Modul-4-IT21-2024](#jarkom-modul-4-it21-2024)
  - [Daftar Isi](#daftar-isi)
- [Prerequisites](#prerequisites)
  - [Topologi Awal](#topologi-awal)
  - [Proses Subnetting](#proses-subnetting)
  - [Rute](#rute)
- [VLSM](#vlsm)
  - [VLSM Tree](#vlsm-tree)
  - [Pembagian IP](#pembagian-ip)
  - [Konfigurasi](#konfigurasi)
    - [Hololive](#hololive)
    - [Holo-EN](#holo-en)
    - [Holo-Myth](#holo-myth)
    - [Gura\_Ame\_Ina (309 Hosts)](#gura_ame_ina-309-hosts)
    - [Kiara\_Calli (193 Hosts)](#kiara_calli-193-hosts)
    - [Project-Hope](#project-hope)
    - [Irys (2 Hosts)](#irys-2-hosts)
    - [Holo-Council](#holo-council)
    - [Kronii-Mumei (39 Hosts)](#kronii-mumei-39-hosts)
    - [Bae\_Fauna (22 Hosts)](#bae_fauna-22-hosts)
    - [HoloAdvent](#holoadvent)
    - [FuwaMoco (5 Hosts)](#fuwamoco-5-hosts)
    - [Shiori\_Nerissa (12 Hosts)](#shiori_nerissa-12-hosts)
    - [Biboo (10 Hosts)](#biboo-10-hosts)
    - [HoloID](#holoid)
    - [Area15](#area15)
    - [Moona (201 Hosts)](#moona-201-hosts)
    - [Risu (319 Hosts)](#risu-319-hosts)
    - [Iofi (140 Hosts)](#iofi-140-hosts)
    - [holoro](#holoro)
    - [Ollie (20 Hosts)](#ollie-20-hosts)
    - [Anya (3 Hosts)](#anya-3-hosts)
    - [Reine (10 Hosts)](#reine-10-hosts)
    - [holoh3ro](#holoh3ro)
    - [Zeta (81 Hosts)](#zeta-81-hosts)
    - [Kaela (71 Hosts)](#kaela-71-hosts)
    - [Kobo (146 Hosts)](#kobo-146-hosts)
    - [Holo-JP](#holo-jp)
    - [DEV\_IS](#dev_is)
    - [Re:GLOSS](#regloss)
    - [Ririka\_Raden (3 Host)](#ririka_raden-3-host)
    - [Ao (3 Hosts)](#ao-3-hosts)
    - [Hajime\_Kanade (7 Hosts)](#hajime_kanade-7-hosts)
    - [GEN:0](#gen0)
    - [MiComet (1501 Hosts)](#micomet-1501-hosts)
    - [Sora\_Robo\_AZKi (542 Hosts)](#sora_robo_azki-542-hosts)
    - [GEN:1](#gen1)
    - [FBK\_Matsuri (321 Hosts)](#fbk_matsuri-321-hosts)
    - [Aki\_Haachama (148 Hosts)](#aki_haachama-148-hosts)
    - [GAMERS](#gamers)
    - [Korone (51 Hosts)](#korone-51-hosts)
    - [Okayu (32 Hosts)](#okayu-32-hosts)
    - [Mio (36 Hosts)](#mio-36-hosts)
  - [Routing](#routing)
  - [Testing](#testing)
- [CIDR](#cidr)
  - [Penggabungan IP](#penggabungan-ip)
  - [CIDR Tree](#cidr-tree)
  - [Pembagian IP](#pembagian-ip-1)
  - [Konfigurasi](#konfigurasi-1)
    - [Hololive](#hololive-1)
    - [Holo-EN](#holo-en-1)
    - [Holo-Myth](#holo-myth-1)
    - [Gura\_Ame\_Ina (309 Hosts)](#gura_ame_ina-309-hosts-1)
    - [Kiara\_Calli (193 Hosts)](#kiara_calli-193-hosts-1)
    - [Project-Hope](#project-hope-1)
    - [Irys (2 Hosts)](#irys-2-hosts-1)
    - [Holo-Council](#holo-council-1)
    - [Kronii-Mumei (39 Hosts)](#kronii-mumei-39-hosts-1)
    - [Bae\_Fauna (22 Hosts)](#bae_fauna-22-hosts-1)
    - [HoloAdvent](#holoadvent-1)
    - [FuwaMoco (5 Hosts)](#fuwamoco-5-hosts-1)
    - [Shiori\_Nerissa (12 Hosts)](#shiori_nerissa-12-hosts-1)
    - [Biboo (10 Hosts)](#biboo-10-hosts-1)
    - [HoloID](#holoid-1)
    - [Area15](#area15-1)
    - [Moona (201 Hosts)](#moona-201-hosts-1)
    - [Risu (319 Hosts)](#risu-319-hosts-1)
    - [Iofi (140 Hosts)](#iofi-140-hosts-1)
    - [holoro](#holoro-1)
    - [Ollie (20 Hosts)](#ollie-20-hosts-1)
    - [Anya (3 Hosts)](#anya-3-hosts-1)
    - [Reine (10 Hosts)](#reine-10-hosts-1)
    - [holoh3ro](#holoh3ro-1)
    - [Zeta (81 Hosts)](#zeta-81-hosts-1)
    - [Kaela (71 Hosts)](#kaela-71-hosts-1)
    - [Kobo (146 Hosts)](#kobo-146-hosts-1)
    - [Holo-JP](#holo-jp-1)
    - [DEV\_IS](#dev_is-1)
    - [Re:GLOSS](#regloss-1)
    - [Ririka\_Raden (3 Host)](#ririka_raden-3-host-1)
    - [Ao (3 Hosts)](#ao-3-hosts-1)
    - [Hajime\_Kanade (7 Hosts)](#hajime_kanade-7-hosts-1)
    - [GEN:0](#gen0-1)
    - [MiComet (1501 Hosts)](#micomet-1501-hosts-1)
    - [Sora\_Robo\_AZKi (542 Hosts)](#sora_robo_azki-542-hosts-1)
    - [GEN:1](#gen1-1)
    - [FBK\_Matsuri (321 Hosts)](#fbk_matsuri-321-hosts-1)
    - [Aki\_Haachama (148 Hosts)](#aki_haachama-148-hosts-1)
    - [GAMERS](#gamers-1)
    - [Korone (51 Hosts)](#korone-51-hosts-1)
    - [Okayu (32 Hosts)](#okayu-32-hosts-1)
    - [Mio (36 Hosts)](#mio-36-hosts-1)
  - [Routing](#routing-1)
  - [Testing](#testing-1)

# Prerequisites

**NOTE:** Kelompok kami (IP prefix 10.74) menggunakan kombinasi:

- `GNS3` + VLSM
- `CPT` + CIDR

## Topologi Awal

![alt text](assets/topo-cpt-modul4.png)

## Proses Subnetting

![alt text](assets/topologi-with-subnet.png)

## Rute

| Nama Subnet | Rute | Jumlah IP | Netmask |
|-------------|------|-----------|---------|
| A1          | Hololive > HoloEN | 2         | /30     |
| A2          | Hololive > HoloEN > Holo-Myth | 2         | /30     |
| A3          | Hololive > HoloEN > Holo-Myth > Switch2 > Gur-ame-ina / Calli-ara | 503       | /23     |
| A4          | Hololive > HoloEN > Holo-Myth > HoloPromise > Project-Hope / Holo-Council | 3         | /29     |
| A5          | Hololive > HoloEN > Holo-Myth > HoloPromise > Project-Hope > Irys | 3         | /29     |
| A6          | Hololive > HoloEN > Holo-Myth > HoloPromise > Holo-Council > Switch4 > Kronii / Fauna | 62        | /26     |
| A7          | Hololive > HoloEN > HoloAdvent | 2         | /30     |
| A8          | Hololive > HoloEN > HoloAdvent > Switch > Fuwa / Shiori / Biboo | 28        | /27     |
| A9          | Hololive > HoloID | 2         | /30     |
| A10         | Hololive > HoloID > Area15 | 2         | /30     |
| A11         | Hololive > HoloID > Area15 > Switch6 > Moona / Risu / Iofi | 661       | /22     |
| A12         | Hololive > HoloID > holoro | 2         | /30     |
| A13         | Hololive > HoloID > holoro > Switch7 > Ollie / Anya / Reine | 34        | /26     |
| A14         | Hololive > HoloID > holoh3ro | 2         | /30     |
| A15         | Hololive > HoloID > holoh3ro > Switch8 > Zeta / Kaela / Kobo | 299       | /23     |
| A16         | Hololive > HoloJP | 2         | /30     |
| A17         | Hololive > HoloJP > Switch1 > DEV_IS / GEN:0 | 3         | /29     |
| A18         | Hololive > HoloJP > Switch1 > DEV_IS > Re:GLOSS > Ririka / Ao / Kanade | 14        | /28     |
| A19         | Hololive > HoloJP > Switch1 > GEN:0 > Switch 3 > MiComet / AZKi / GEN:1 | 2045      | /21     |
| A20         | Hololive > HoloJP > Switch1 > GEN:0 > Switch 3 > GEN:1 > Member > Matsuri / Haachama | 470       | /23     |
| A21         | Hololive > HoloJP > Switch1 > GEN:0 > Switch 3 > GEN:1 > GAMERS | 2         | /30     |
| A22         | Hololive > HoloJP > Switch1 > GEN:0 > Switch 3 > GEN:1 > GAMERS > Fubuki > Korone / Okayu / Mio | 120       | /25     |
| **Total**   |                      | **4263**  | **/19** |

# VLSM

## VLSM Tree

![alt text](assets/VLSMtree.png)

## Pembagian IP

| Subnet | Network ID  | Netmask          | Broadcast    | Range IP                     |
|--------|-------------|------------------|--------------|------------------------------|
| A1     | 10.74.19.72 | 255.255.255.252  | 10.74.19.75  | 10.74.19.73 - 10.74.19.74    |
| A2     | 10.74.19.76 | 255.255.255.252  | 10.74.19.79  | 10.74.19.77 - 10.74.19.78    |
| A3     | 10.74.12.0  | 255.255.254.0    | 10.74.13.255 | 10.74.12.1 - 10.74.13.254    |
| A4     | 10.74.19.48 | 255.255.255.248  | 10.74.19.55  | 10.74.19.49 - 10.74.19.54    |
| A5     | 10.74.19.56 | 255.255.255.248  | 10.74.19.63  | 10.74.19.57 - 10.74.19.62    |
| A6     | 10.74.18.128| 255.255.255.192  | 10.74.18.191 | 10.74.18.129 - 10.74.18.190  |
| A7     | 10.74.19.80 | 255.255.255.252  | 10.74.19.83  | 10.74.19.81 - 10.74.19.82    |
| A8     | 10.74.19.0  | 255.255.255.224  | 10.74.19.31  | 10.74.19.1 - 10.74.19.30     |
| A9     | 10.74.19.84 | 255.255.255.252  | 10.74.19.87  | 10.74.19.85 - 10.74.19.86    |
| A10    | 10.74.19.88 | 255.255.255.252  | 10.74.19.91  | 10.74.19.89 - 10.74.19.90    |
| A11    | 10.74.8.0   | 255.255.252.0    | 10.74.11.255 | 10.74.8.1 - 10.74.11.254     |
| A12    | 10.74.19.92 | 255.255.255.252  | 10.74.19.95  | 10.74.19.93 - 10.74.19.94    |
| A13    | 10.74.18.192| 255.255.255.192  | 10.74.18.255 | 10.74.18.193 - 10.74.18.254  |
| A14    | 10.74.19.96 | 255.255.255.252  | 10.74.19.99  | 10.74.19.97 - 10.74.19.98    |
| A15    | 10.74.14.0  | 255.255.254.0    | 10.74.15.255 | 10.74.14.1 - 10.74.15.254    |
| A16    | 10.74.19.100| 255.255.255.252  | 10.74.19.103 | 10.74.19.101 - 10.74.19.102  |
| A17    | 10.74.19.64 | 255.255.255.248  | 10.74.19.71  | 10.74.19.65 - 10.74.19.70    |
| A18    | 10.74.19.32 | 255.255.255.240  | 10.74.19.47  | 10.74.19.33 - 10.74.19.46    |
| A19    | 10.74.0.0   | 255.255.248.0    | 10.74.7.255  | 10.74.0.1 - 10.74.7.255      |
| A20    | 10.74.16.0  | 255.255.254.0    | 10.74.17.255 | 10.74.16.1 - 10.74.17.254    |
| A21    | 10.74.19.104| 255.255.255.252  | 10.74.19.107 | 10.74.19.105 - 10.74.19.106  |
| A22    | 10.74.18.0  | 255.255.255.128  | 10.74.18.127 | 10.74.18.1 - 10.74.18.127    |

## Konfigurasi

### Hololive

```bash
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

# A1 > HoloEN
auto eth1
iface eth1 inet static
    address 10.74.19.73
    netmask 255.255.255.252

# A9 > HoloID
auto eth2
iface eth2 inet static
    address 10.74.19.85
    netmask 255.255.255.252

# A16 > Holo-JP
auto eth3
iface eth3 inet static
    address 10.74.19.101
    netmask 255.255.255.252
```

### Holo-EN

```bash
# A1 > Hololive
auto eth0
iface eth0 inet static
    address 10.74.19.74
    netmask 255.255.255.252
    gateway 10.74.19.73

# A2 > Holo-Myth
auto eth1
iface eth1 inet static
    address 10.74.19.77
    netmask 255.255.255.252

# A7 > HoloAdvent
auto eth2
iface eth2 inet static
    address 10.74.19.81
    netmask 255.255.255.252
```

### Holo-Myth

```bash
# A2 > Holo-EN
auto eth0
iface eth0 inet static
    address 10.74.19.78
    netmask 255.255.255.252
    gateway 10.74.19.77

# A3 > Switch2 (Gura/Kiara)
auto eth1
iface eth1 inet static
    address 10.74.12.1
    netmask 255.255.254.0

# A4 > HoloPromise
auto eth2
iface eth2 inet static
    address 10.74.19.49
    netmask 255.255.255.248
```

### Gura_Ame_Ina (309 Hosts)

```bash
```

### Kiara_Calli (193 Hosts)

```bash
```

### Project-Hope

```bash
```

### Irys (2 Hosts)

```bash
```

### Holo-Council

```bash
```

### Kronii-Mumei (39 Hosts)

```bash
```

### Bae_Fauna (22 Hosts)

```bash
```

### HoloAdvent

```bash
```

### FuwaMoco (5 Hosts)

```bash
```

### Shiori_Nerissa (12 Hosts)

```bash
```

### Biboo (10 Hosts)

```bash
```

### HoloID

```bash
```

### Area15

```bash
```

### Moona (201 Hosts)

```bash
```

### Risu (319 Hosts)

```bash
```

### Iofi (140 Hosts)

```bash
```

### holoro

```bash
```

### Ollie (20 Hosts)

```bash
```

### Anya (3 Hosts)

```bash
```

### Reine (10 Hosts)

```bash
```

### holoh3ro

```bash
```

### Zeta (81 Hosts)

```bash
```

### Kaela (71 Hosts)

```bash
```

### Kobo (146 Hosts)

```bash
```

### Holo-JP

```bash
```

### DEV_IS

```bash
```

### Re:GLOSS

```bash
```

### Ririka_Raden (3 Host)

```bash
```

### Ao (3 Hosts)

```bash
```

### Hajime_Kanade (7 Hosts)

```bash
```

### GEN:0

```bash
```

### MiComet (1501 Hosts)

```bash
```

### Sora_Robo_AZKi (542 Hosts)

```bash
```

### GEN:1

```bash
```

### FBK_Matsuri (321 Hosts)

```bash
```

### Aki_Haachama (148 Hosts)

```bash
```

### GAMERS

```bash
```

### Korone (51 Hosts)

```bash
```

### Okayu (32 Hosts)

```bash
```

### Mio (36 Hosts)

```bash
```

## Routing



## Testing



# CIDR

## Penggabungan IP

## CIDR Tree

## Pembagian IP

## Konfigurasi

### Hololive

```bash
```

### Holo-EN

```bash
```

### Holo-Myth

```bash
```

### Gura_Ame_Ina (309 Hosts)

```bash
```

### Kiara_Calli (193 Hosts)

```bash
```

### Project-Hope

```bash
```

### Irys (2 Hosts)

```bash
```

### Holo-Council

```bash
```

### Kronii-Mumei (39 Hosts)

```bash
```

### Bae_Fauna (22 Hosts)

```bash
```

### HoloAdvent

```bash
```

### FuwaMoco (5 Hosts)

```bash
```

### Shiori_Nerissa (12 Hosts)

```bash
```

### Biboo (10 Hosts)

```bash
```

### HoloID

```bash
```

### Area15

```bash
```

### Moona (201 Hosts)

```bash
```

### Risu (319 Hosts)

```bash
```

### Iofi (140 Hosts)

```bash
```

### holoro

```bash
```

### Ollie (20 Hosts)

```bash
```

### Anya (3 Hosts)

```bash
```

### Reine (10 Hosts)

```bash
```

### holoh3ro

```bash
```

### Zeta (81 Hosts)

```bash
```

### Kaela (71 Hosts)

```bash
```

### Kobo (146 Hosts)

```bash
```

### Holo-JP

```bash
```

### DEV_IS

```bash
```

### Re:GLOSS

```bash
```

### Ririka_Raden (3 Host)

```bash
```

### Ao (3 Hosts)

```bash
```

### Hajime_Kanade (7 Hosts)

```bash
```

### GEN:0

```bash
```

### MiComet (1501 Hosts)

```bash
```

### Sora_Robo_AZKi (542 Hosts)

```bash
```

### GEN:1

```bash
```

### FBK_Matsuri (321 Hosts)

```bash
```

### Aki_Haachama (148 Hosts)

```bash
```

### GAMERS

```bash
```

### Korone (51 Hosts)

```bash
```

### Okayu (32 Hosts)

```bash
```

### Mio (36 Hosts)

```bash
```

## Routing

## Testing