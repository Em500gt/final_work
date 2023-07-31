egor@egor-VivoBook-S15-X510UF:~$ cat > "Домашние животные"
Аиди, Алано, Акита, Бульдог, Мейн-кун, Сибирская кошка, Хомяк обыкновенный   
egor@egor-VivoBook-S15-X510UF:~$ cat > "Вьючные животные"
egor@egor-VivoBook-S15-X510UF:~$ cat "Домашние животные" "Вьючные животные" > 
"Общий список животных"
egor@egor-VivoBook-S15-X510UF:~$ ls
 Desktop   docertask   docker   Documents   Downloads   Music   Pictures   Public   snap   
Templates   test   Videos   wordpress  'Вьючные животные'  'Домашние животные'  'Общий 
список животных'
egor@egor-VivoBook-S15-X510UF:~$ cat "Общий список животных" 
Аиди, Алано, Акита, Бульдог, Мейн-кун, Сибирская кошка, Хомяк обыкновенный
Верблюд, северный олень, козы, лама
egor@egor-VivoBook-S15-X510UF:~$ mv "Общий список животных" "Друзья человека"
egor@egor-VivoBook-S15-X510UF:~$ ls
 Desktop   docertask   docker   Documents   Downloads   Music   Pictures   Public   snap   
Templates   test   Videos   wordpress  'Вьючные животные'  'Домашние животные'  'Друзья 
человека'
egor@egor-VivoBook-S15-X510UF:~$ mkdir Animals
egor@egor-VivoBook-S15-X510UF:~$ mv "Друзья человека" Animals
egor@egor-VivoBook-S15-X510UF:~$ ls
 Animals   Desktop   docertask   docker   Documents   Downloads   Music   Pictures   Public   snap   
Templates   test   Videos   wordpress  'Вьючные животные'  'Домашние животные'
egor@egor-VivoBook-S15-X510UF:~$ cd Animals/
egor@egor-VivoBook-S15-X510UF:~/Animals$ ls
'Друзья человека'
egor@egor-VivoBook-S15-X510UF:~/Animals$ cd ..
egor@egor-VivoBook-S15-X510UF:~$ sudo apt install mysql-server
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages will be upgraded:
  mysql-server
1 to upgrade, 0 to newly install, 0 to remove and 180 not to upgrade.
Need to get 9.450 B of archives.
After this operation, 0 B of additional disk space will be used.
Get:1 http://by.archive.ubuntu.com/ubuntu jammy-updates/main amd64 mysql-server all 8.0.33-
0ubuntu0.22.04.4 [9.450 B]
Fetched 9.450 B in 0s (90,8 kB/s)        
(Reading database ... 214943 files and directories currently installed.)
Preparing to unpack .../mysql-server_8.0.33-0ubuntu0.22.04.4_all.deb ...
Unpacking mysql-server (8.0.33-0ubuntu0.22.04.4) over (8.0.33-0ubuntu0.22.04.2) ...
Setting up mysql-server (8.0.33-0ubuntu0.22.04.4)