# rpi4_OS_benchmarking
The following OSs were installed on a Raspberry Pi 4
* Alpine
* Arch Linux ARM
* DietPi
* Fedora 35
* FreeBSD
* Kali
* Kali (32 bit)
* Manjaro
* Raspberry Pi OS (new Raspbian)
* Ubuntu 20.04 LTS
* Ubuntu 21.10
* Ubuntu 21.10 (32 bit)
* openSUSE Tumbleweed

# Results
Rank | OS | Net runtime | Pvalue*
|:---:|:---:|:---:|:---:|
1 | Rasberry Pi OS | 156.54 | 2.55e-6
2 | DietPi (1.8 GHz) | 158.60 | 8.31e-5
3 | FreeBSD | 163.77 | 3.84e-9
4 | Ubuntu 21.10 (32 bit) | 171.76 | 9.25e-12
5 | Ubuntu 21.10 | 176.44 | 1.03e-5
6 | Manjaro | 180.51 | .331
6 | openSUSE | 182.03 | 4.53e-11
7 | Kali (32 bit) | 188.93 | 7.08e-4
8 | Arch Linux ARM | 189.71 | .292
8 | DietPi | 191.09 | 1.38e-3
9 | Fedora 35 | 194.76 | 1.52e-8
10 | Kali | 198.18 | 8.36e-12
11 | Ubuntu 20.04 LTS | 281.84 | 5.44e-8
12 | FreeBSD (600 MHz) | 409.53 | 8.36e-12
13 | Alpine (running on RAM) | 975.14 | 

(*values comepare current row to the row below)
