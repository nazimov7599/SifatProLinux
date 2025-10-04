# 1. Operatsion tizim va distributiv haqida to‘liq ma’lumotni ekranga chiqaring.
uname -a
Linux ubuntu-s-1vcpu-512mb-10gb-sgp1-01 6.14.0-23-generic #23-Ubuntu SMP PREEMPT_DYNAMIC Fri Jun 13 23:02:20 UTC 2025 x86_64 x86_64 x86_64 GNU/Linux
lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 25.04
Release:	25.04
Codename:	plucky
# 2. Hozirgi foydalanuvchi nomini ekranga chiqaring.
whoami
timur
# 4. "uygavazifa" nomli yangi papka yarating.
#    Keyin shu papkaga o‘ting va qolgan ishlarni shu yerda davom ettiring.
mkdir uygavazifa
cd uygavazifa

# 5. Papka ichida uchta matnli fayl yarating.
#    - Yordam: matn yozish uchun `echo "matn" > faylnomi.txt` yoki `echo "matn" >> faylnomi.txt` dan foydalanishingiz mumkin.
#    - 1-fayl: o‘zingiz haqida bir necha qatorli qisqa matn yozingr
#    - 2-fayl: sevimli kitobingiz yoki film nomini yozing
#    - 3-fayl: bugungi sanani yozing. `date` buyrug'idan foydalaning sanani ko'rsatish uchun.

~/uygavazifa$ touch file{1..3}.txt
~/uygavazifa$ echo -e "Ismim Temur\nYoshim 26da\nQA sohasidan avval Call markazda ishlaganman" > file1.txt
~/uygavazifa$ echo "Intersteller film" > file2.txt
~/uygavazifa$ echo date > file3.txt

# 6. Papkada qanday fayllar mavjudligini ko‘rsating.
~/uygavazifa$ ls
file1.txt  file2.txt  file3.txt
# 7. Birinchi faylni nusxa ko‘chiring va yangi 'new_file.txt' nom bering.
~/uygavazifa$ cp file1.txt new_file1.txt

# 8. Ikkinchi fayl nomini 'renamed_file.txt' nomga o‘zgartiring.
~/uygavazifa$ mv file2.txt renamed_file.txt

# 9. Uchinchi faylni o‘chirib tashlang va yo‘qligini isbotlang.

~/uygavazifa$ rm -i file3.txt
rm: remove regular file 'file3.txt'? y
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/uygavazifa$ ls
file1.txt  new_file1.txt  renamed_file.txt

# 10. Birinchi fayldagi matnni oddiy ko‘rinishda va teskari ko‘rinishda ekranga chiqaring.
Barcha topshiriqlar muvaffaqiyatli bajarildi!
~/uygavazifa$ cat file1.txt 
Ismim Temur
Yoshim 26da
QA sohasidan avval Call markazda ishlaganman

~/uygavazifa$ tac file1.txt
QA sohasidan avval Call markazda ishlaganman
Yoshim 26da
Ismim Temur

11. "sinov" nomli yangi papka yarating, keyin uni o‘chirib tashlang.

rmdir sinov
ls
uygavazifa
12. Topshiriq:
#     - "katta" nomli papka yarating.
#     - uning ichida "kichik" nomli papka yarating.
#     - "kichik" papka ichiga yangi bo'sh fayl yarating
#     - butun "katta" papkani boshqa joyga nusxalab o‘tkazing.
#     - keyin asl "katta" papkani ichidagi barcha narsasi bilan birga butunlay o‘chirib tashlang.
#     - oxirida nusxa olingan joyda papka va fayl mavjudligini tekshiring.

timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ mkdir katta
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ cd katta
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/katta$ mkdir kichik
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/katta$ ls
kichik
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/katta$ cd ..
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ ls
katta  uygavazifa
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ cd katta/kichik
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/katta/kichik$ touch file1.txt
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/katta/kichik$ ls
file1.txt
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/katta/kichik$ cd ../..
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ cp -r katta uygavazifa
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ ls
katta  uygavazifa
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ rm -rf katta
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ ls
uygavazifa
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~$ cd uygavazifa
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/uygavazifa$ ls
file1.txt  katta  new_file1.txt  renamed_file.txt
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/uygavazifa$ cd katta
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/uygavazifa/katta$ ls
kichik
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/uygavazifa/katta$ cd kichik
timur@ubuntu-s-1vcpu-512mb-10gb-sgp1-01:~/uygavazifa/katta/kichik$ ls
file1.txt

 Yakuniy topshiriq:
#    Skript oxirida ekranga shunday xabar chiqishi kerak(`echo` dan foydalaning):
#    "Barcha topshiriqlar muvaffaqiyatli bajarildi!"

echo "Barcha topshiriqlar muvaffaqiyatli bajarildi!"

Barcha topshiriqlar muvaffaqiyatli bajarildi!
