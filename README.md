> gpg --version
gpg (GnuPG) 2.4.4
libgcrypt 1.10.3
Copyright (C) 2024 g10 Code GmbH
License GNU GPL-3.0-or-later <https://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Home: /home/matvey/.gnupg
Поддерживаются следующие алгоритмы:
С открытым ключом: RSA, ELG, DSA, ECDH, ECDSA, EDDSA
Симметричные шифры: IDEA, 3DES, CAST5, BLOWFISH,
                    AES, AES192, AES256, TWOFISH, CAMELLIA128,
                    CAMELLIA192, CAMELLIA256
Хеш-функции: SHA1, RIPEMD160, SHA256, SHA384, SHA512,
             SHA224
Алгоритмы сжатия: Без сжатия, ZIP, ZLIB,
                  BZIP2
> gpg2 --version
zsh: command not found: gpg2
> $ export GPG_PACKAGE_NAME=gpg
zsh: command not found: $
> export GPG_PACKAGE_NAME=gpg
> export PACKAGE_MANAGER=apt
> $PACKAGE_MANAGER install xclip
E: Не удалось открыть файл блокировки /var/lib/dpkg/lock-frontend - open (13: Отказано в доступе)
E: Невозможно получить блокировку внешнего интерфейса dpkg (/var/lib/dpkg/lock-frontend); у вас есть права суперпользователя?
> sudo $PACKAGE_MANAGER install xclip
[sudo] пароль для matvey: 
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово         
Следующие пакеты устанавливались автоматически и больше не требуются:
  libpkcs11-helper1t64 python3-netifaces
Для их удаления используйте «sudo apt autoremove».
Следующие НОВЫЕ пакеты будут установлены:
  xclip
Обновлено 0 пакетов, установлено 1 новых пакетов, для удаления отмечено 0 пакетов, и 107 пакетов не обновлено.
Необходимо скачать 17,6 kB архивов.
После данной операции объём занятого дискового пространства возрастёт на 54,3 kB.
Пол:1 http://ru.archive.ubuntu.com/ubuntu noble/universe amd64 xclip amd64 0.13-3 [17,6 kB]
Получено 17,6 kB за 0с (324 kB/s)
Выбор ранее не выбранного пакета xclip.
(Чтение базы данных … на данный момент установлено 257789 файлов и каталогов.)
Подготовка к распаковке …/xclip_0.13-3_amd64.deb …
Распаковывается xclip (0.13-3) …
Настраивается пакет xclip (0.13-3) …
Обрабатываются триггеры для man-db (2.12.0-4build2) …
> alias gsed=sed
> alias pbcopy='xclip -selection clipboard'
> alias pbpaste='xclip -selection clipboard -o'
> cd ${GITHUB_USERNAME}/workspace
> pushd .
~/matveech99/workspace ~
> source scripts/activate
> go get github.com/aktau/github-release


zsh: command not found: go
> sudo apt update && sudo apt install golang-go
Сущ:1 http://ru.archive.ubuntu.com/ubuntu noble InRelease
Пол:2 http://ru.archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]              
Пол:3 http://ru.archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]                      
Пол:4 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]         
Пол:5 http://ru.archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [1 028 kB]
Пол:6 http://ru.archive.ubuntu.com/ubuntu noble-updates/main i386 Packages [458 kB]
Пол:7 http://security.ubuntu.com/ubuntu noble-security/main amd64 Components [21,5 kB]
Пол:8 http://ru.archive.ubuntu.com/ubuntu noble-updates/main amd64 Components [161 kB]            
Пол:9 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Components [212 B]        
Пол:10 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Components [52,3 kB]
Пол:11 http://ru.archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Packages [993 kB]       
Пол:12 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Components [212 B]       
Пол:13 http://ru.archive.ubuntu.com/ubuntu noble-updates/restricted i386 Packages [17,8 kB]       
Пол:14 http://ru.archive.ubuntu.com/ubuntu noble-updates/restricted Translation-en [204 kB]
Пол:15 http://ru.archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Components [212 B]
Пол:16 http://ru.archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [1 059 kB]
Пол:17 http://ru.archive.ubuntu.com/ubuntu noble-updates/universe i386 Packages [640 kB]
Пол:18 http://ru.archive.ubuntu.com/ubuntu noble-updates/universe amd64 Components [376 kB]
Пол:19 http://ru.archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Packages [21,7 kB]
Пол:20 http://ru.archive.ubuntu.com/ubuntu noble-updates/multiverse i386 Packages [3 800 B]
Пол:21 http://ru.archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Components [940 B]
Пол:22 http://ru.archive.ubuntu.com/ubuntu noble-backports/main amd64 Components [7 076 B]
Пол:23 http://ru.archive.ubuntu.com/ubuntu noble-backports/restricted amd64 Components [212 B]
Пол:24 http://ru.archive.ubuntu.com/ubuntu noble-backports/universe amd64 Components [16,4 kB]
Пол:25 http://ru.archive.ubuntu.com/ubuntu noble-backports/multiverse amd64 Components [212 B]
Пол:26 https://repo.yandex.ru/yandex-browser/deb stable InRelease [4 336 B]
Получено 5 444 kB за 5с (1 013 kB/s)      
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово         
Может быть обновлено 107 пакетов. Запустите «apt list --upgradable» для их показа.
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово         
Следующие пакеты устанавливались автоматически и больше не требуются:
  libpkcs11-helper1t64 python3-netifaces
Для их удаления используйте «sudo apt autoremove».
Будут установлены следующие дополнительные пакеты:
  golang-1.22-go golang-1.22-src golang-src
Предлагаемые пакеты:
  bzr | brz mercurial subversion
Следующие НОВЫЕ пакеты будут установлены:
  golang-1.22-go golang-1.22-src golang-go golang-src
Обновлено 0 пакетов, установлено 4 новых пакетов, для удаления отмечено 0 пакетов, и 107 пакетов не обновлено.
Необходимо скачать 45,7 MB архивов.
После данной операции объём занятого дискового пространства возрастёт на 228 MB.
Хотите продолжить? [Д/н] y
Пол:1 http://ru.archive.ubuntu.com/ubuntu noble-updates/main amd64 golang-1.22-src all 1.22.2-2ubuntu0.3 [19,7 MB]
Пол:2 http://ru.archive.ubuntu.com/ubuntu noble-updates/main amd64 golang-1.22-go amd64 1.22.2-2ubuntu0.3 [25,9 MB]
Пол:3 http://ru.archive.ubuntu.com/ubuntu noble/main amd64 golang-src all 2:1.22~2build1 [5 078 B]
Пол:4 http://ru.archive.ubuntu.com/ubuntu noble/main amd64 golang-go amd64 2:1.22~2build1 [43,9 kB]
Получено 45,7 MB за 11с (4 225 kB/s)                                                              
Выбор ранее не выбранного пакета golang-1.22-src.
(Чтение базы данных … на данный момент установлен 257801 файл и каталог.)
Подготовка к распаковке …/golang-1.22-src_1.22.2-2ubuntu0.3_all.deb …
Распаковывается golang-1.22-src (1.22.2-2ubuntu0.3) …
Выбор ранее не выбранного пакета golang-1.22-go.
Подготовка к распаковке …/golang-1.22-go_1.22.2-2ubuntu0.3_amd64.deb …
Распаковывается golang-1.22-go (1.22.2-2ubuntu0.3) …
Выбор ранее не выбранного пакета golang-src.
Подготовка к распаковке …/golang-src_2%3a1.22~2build1_all.deb …
Распаковывается golang-src (2:1.22~2build1) …
Выбор ранее не выбранного пакета golang-go:amd64.
Подготовка к распаковке …/golang-go_2%3a1.22~2build1_amd64.deb …
Распаковывается golang-go:amd64 (2:1.22~2build1) …
Настраивается пакет golang-1.22-src (1.22.2-2ubuntu0.3) …
Настраивается пакет golang-src (2:1.22~2build1) …
Настраивается пакет golang-1.22-go (1.22.2-2ubuntu0.3) …
Настраивается пакет golang-go:amd64 (2:1.22~2build1) …
Обрабатываются триггеры для man-db (2.12.0-4build2) …
> go get github.com/aktau/github-release


go: go.mod file not found in current directory or any parent directory.
	'go get' is no longer supported outside a module.
	To build and install a command, use 'go install' with a version,
	like 'go install example.com/cmd@latest'
	For more information, see https://golang.org/doc/go-get-install-deprecation
	or run 'go help get' or 'go help install'.
> go install github.com/aktau/github-release


go: 'go install' requires a version when current directory is not in a module
	Try 'go install github.com/aktau/github-release@latest' to install the latest version
> go install github.com/aktau/github-release@v0.10.0
go: downloading github.com/aktau/github-release v0.10.0
go: finding module for package github.com/voxelbrain/goptions
go: finding module for package github.com/dustin/go-humanize
go: finding module for package github.com/github-release/github-release/github
go: downloading github.com/dustin/go-humanize v1.0.1
go: downloading github.com/github-release/github-release v0.10.1
go: downloading github.com/voxelbrain/goptions v0.0.0-20180630082107-58cddc247ea2
go: found github.com/dustin/go-humanize in github.com/dustin/go-humanize v1.0.1
go: found github.com/github-release/github-release/github in github.com/github-release/github-release v0.10.1
go: found github.com/voxelbrain/goptions in github.com/voxelbrain/goptions v0.0.0-20180630082107-58cddc247ea2
go: finding module for package github.com/kevinburke/rest/restclient
go: finding module for package github.com/tomnomnom/linkheader
go: downloading github.com/kevinburke/rest v0.0.0-20240617045629-3ed0ad3487f0
go: downloading github.com/tomnomnom/linkheader v0.0.0-20180905144013-02ca5825eb80
go: found github.com/kevinburke/rest/restclient in github.com/kevinburke/rest v0.0.0-20240617045629-3ed0ad3487f0
go: found github.com/tomnomnom/linkheader in github.com/tomnomnom/linkheader v0.0.0-20180905144013-02ca5825eb80
> git clone https://github.com/${GITHUB_USERNAME}/lab08 projects/lab09

Клонирование в «projects/lab09»...
remote: Enumerating objects: 388, done.
remote: Counting objects: 100% (388/388), done.
remote: Compressing objects: 100% (181/181), done.
remote: Total 388 (delta 170), reused 381 (delta 167), pack-reused 0 (from 0)
Получение объектов: 100% (388/388), 2.14 МиБ | 3.66 МиБ/с, готово.
Определение изменений: 100% (170/170), готово.
> cd projects/lab09
> git remote remove origin
> git remote add origin https://github.com/${GITHUB_USERNAME}/lab09
> gsed -i 's/lab08/lab09/g' README.md


> $PACKAGE_MANAGER install ${GPG_PACKAGE_NAME}
E: Не удалось открыть файл блокировки /var/lib/dpkg/lock-frontend - open (13: Отказано в доступе)
E: Невозможно получить блокировку внешнего интерфейса dpkg (/var/lib/dpkg/lock-frontend); у вас есть права суперпользователя?
> sudo $PACKAGE_MANAGER install ${GPG_PACKAGE_NAME}
Чтение списков пакетов… Готово
Построение дерева зависимостей… Готово
Чтение информации о состоянии… Готово         
Уже установлен пакет gpg самой новой версии (2.4.4-2ubuntu17.2).
gpg помечен как установленный вручную.
Следующие пакеты устанавливались автоматически и больше не требуются:
  libpkcs11-helper1t64 python3-netifaces
Для их удаления используйте «sudo apt autoremove».
Обновлено 0 пакетов, установлено 0 новых пакетов, для удаления отмечено 0 пакетов, и 107 пакетов не обновлено.
> gpg --list-secret-keys --keyid-format LONG
> gpg --full-generate-key
gpg (GnuPG) 2.4.4; Copyright (C) 2024 g10 Code GmbH
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Выберите тип ключа:
   (1) RSA и RSA
   (2) DSA и Elgamal
   (3) DSA (sign only)
   (4) RSA (sign only)
   (9) ECC (подписание и шифрование) *по умолчанию*
  (10) ECC (только для подписи)
  (14) Существующий ключ с карты 
Ваш выбор? 1
длина ключей RSA может быть от 1024 до 4096.
Какой размер ключа Вам необходим? (3072) 
Запрошенный размер ключа - 3072 бит
Выберите срок действия ключа.
         0 = не ограничен
      <n>  = срок действия ключа - n дней
      <n>w = срок действия ключа - n недель
      <n>m = срок действия ключа - n месяцев
      <n>y = срок действия ключа - n лет
Срок действия ключа? (0) 
Срок действия ключа не ограничен
Все верно? (y/N) y

GnuPG должен составить идентификатор пользователя для идентификации ключа.

Ваше полное имя: Matvey
Адрес электронной почты: shalnev95@list.ru
Примечание: Lipetsk
Вы выбрали следующий идентификатор пользователя:
    "Matvey (Lipetsk) <shalnev95@list.ru>"

Сменить (N)Имя, (C)Примечание, (E)Адрес; (O)Принять/(Q)Выход? O
Необходимо получить много случайных чисел. Желательно, чтобы Вы
в процессе генерации выполняли какие-то другие действия (печать
на клавиатуре, движения мыши, обращения к дискам); это даст генератору
случайных чисел больше возможностей получить достаточное количество энтропии.
Необходимо получить много случайных чисел. Желательно, чтобы Вы
в процессе генерации выполняли какие-то другие действия (печать
на клавиатуре, движения мыши, обращения к дискам); это даст генератору
случайных чисел больше возможностей получить достаточное количество энтропии.
gpg: создан каталог '/home/matvey/.gnupg/openpgp-revocs.d'
gpg: сертификат отзыва записан в '/home/matvey/.gnupg/openpgp-revocs.d/10572FF9F39EEB03B5E7B615F5357166648A8E9B.rev'.
открытый и секретный ключи созданы и подписаны.

pub   rsa3072 2025-05-01 [SC]
      10572FF9F39EEB03B5E7B615F5357166648A8E9B
uid                      Matvey (Lipetsk) <shalnev95@list.ru>
sub   rsa3072 2025-05-01 [E]

> gpg --list-secret-keys --keyid-format LONG
gpg: проверка таблицы доверия
gpg: marginals needed: 3  completes needed: 1  trust model: pgp
gpg: глубина: 0  достоверных:   1  подписанных:   0  доверие: 0-, 0q, 0n, 0m, 0f, 1u
/home/matvey/.gnupg/pubring.kbx
-------------------------------
sec   rsa3072/F5357166648A8E9B 2025-05-01 [SC]
      10572FF9F39EEB03B5E7B615F5357166648A8E9B
uid               [  абсолютно ] Matvey (Lipetsk) <shalnev95@list.ru>
ssb   rsa3072/DFEBA4D68A5A362F 2025-05-01 [E]

> gpg -K ${GITHUB_USERNAME}

gpg: error reading key: Нет секретного ключа
> gpg -K "Matvey (Lipetsk) <shalnev95@list.ru>"

sec   rsa3072 2025-05-01 [SC]
      10572FF9F39EEB03B5E7B615F5357166648A8E9B
uid         [  абсолютно ] Matvey (Lipetsk) <shalnev95@list.ru>
ssb   rsa3072 2025-05-01 [E]

> GPG_KEY_ID=$(gpg --list-secret-keys --keyid-format LONG | grep ssb | tail -1 | awk '{print $2}' | awk -F'/' '{print $2}')

> GPG_SEC_KEY_ID=$(gpg --list-secret-keys --keyid-format LONG | grep sec | tail -1 | awk '{print $2}' | awk -F'/' '{print $2}')

> gpg --armor --export ${GPG_KEY_ID} | pbcopy

> pbpaste
pbpaste%                                                                                           > open https://github.com/settings/keys
~/m/workspace/p/lab09 main !1 > Gtk-Message: 14:41:40.693: Not loading module "atk-bridge": The functionality is provided by GTK natively. Please try to not load it.
> 
> gpg --full-generate-key
gpg (GnuPG) 2.4.4; Copyright (C) 2024 g10 Code GmbH
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Выберите тип ключа:
   (1) RSA и RSA
   (2) DSA и Elgamal
   (3) DSA (sign only)
   (4) RSA (sign only)
   (9) ECC (подписание и шифрование) *по умолчанию*
  (10) ECC (только для подписи)
  (14) Существующий ключ с карты 
Ваш выбор? 1
длина ключей RSA может быть от 1024 до 4096.
Какой размер ключа Вам необходим? (3072) 4096
Запрошенный размер ключа - 4096 бит
Выберите срок действия ключа.
         0 = не ограничен
      <n>  = срок действия ключа - n дней
      <n>w = срок действия ключа - n недель
      <n>m = срок действия ключа - n месяцев
      <n>y = срок действия ключа - n лет
Срок действия ключа? (0) 
Срок действия ключа не ограничен
Все верно? (y/N) y

GnuPG должен составить идентификатор пользователя для идентификации ключа.

Ваше полное имя: matveech99
Адрес электронной почты: matveech99@gmail.com
Примечание: 
Вы выбрали следующий идентификатор пользователя:
    "matveech99 <matveech99@gmail.com>"

Сменить (N)Имя, (C)Примечание, (E)Адрес; (O)Принять/(Q)Выход? O
Необходимо получить много случайных чисел. Желательно, чтобы Вы
в процессе генерации выполняли какие-то другие действия (печать
на клавиатуре, движения мыши, обращения к дискам); это даст генератору
случайных чисел больше возможностей получить достаточное количество энтропии.
Необходимо получить много случайных чисел. Желательно, чтобы Вы
в процессе генерации выполняли какие-то другие действия (печать
на клавиатуре, движения мыши, обращения к дискам); это даст генератору
случайных чисел больше возможностей получить достаточное количество энтропии.
gpg: сертификат отзыва записан в '/home/matvey/.gnupg/openpgp-revocs.d/4B4C871DD731D7F6D11B2EF13FEBAA7E4C334353.rev'.
открытый и секретный ключи созданы и подписаны.

pub   rsa4096 2025-05-01 [SC]
      4B4C871DD731D7F6D11B2EF13FEBAA7E4C334353
uid                      matveech99 <matveech99@gmail.com>
sub   rsa4096 2025-05-01 [E]

> gpg --list-secret-keys --keyid-format LONG
gpg: проверка таблицы доверия
gpg: marginals needed: 3  completes needed: 1  trust model: pgp
gpg: глубина: 0  достоверных:   2  подписанных:   0  доверие: 0-, 0q, 0n, 0m, 0f, 2u
/home/matvey/.gnupg/pubring.kbx
-------------------------------
sec   rsa3072/F5357166648A8E9B 2025-05-01 [SC]
      10572FF9F39EEB03B5E7B615F5357166648A8E9B
uid               [  абсолютно ] Matvey (Lipetsk) <shalnev95@list.ru>
ssb   rsa3072/DFEBA4D68A5A362F 2025-05-01 [E]

sec   rsa4096/3FEBAA7E4C334353 2025-05-01 [SC]
      4B4C871DD731D7F6D11B2EF13FEBAA7E4C334353
uid               [  абсолютно ] matveech99 <matveech99@gmail.com>
ssb   rsa4096/640E5F5A66DE4987 2025-05-01 [E]

> gpg --list-secret-keys --keyid-format LONG
> $ gpg -K ${GITHUB_USERNAME}

zsh: command not found: $
> gpg -K ${GITHUB_USERNAME}

sec   rsa4096 2025-05-01 [SC]
      4B4C871DD731D7F6D11B2EF13FEBAA7E4C334353
uid         [  абсолютно ] matveech99 <matveech99@gmail.com>
ssb   rsa4096 2025-05-01 [E]

> GPG_KEY_ID=$(gpg --list-secret-keys --keyid-format LONG | grep ssb | tail -1 | awk '{print $2}' | awk -F'/' '{print $2}')
> GPG_SEC_KEY_ID=$(gpg --list-secret-keys --keyid-format LONG | grep sec | tail -1 | awk '{print $2}' | awk -F'/' '{print $2}')
> gpg --armor --export ${GPG_KEY_ID} | pbcopy
> pbpaste
pbpaste%                                                                                           > 
> gpg --armor --export ${GPG_KEY_ID}
-----BEGIN PGP PUBLIC KEY BLOCK-----

mQINBGgTYekBEAC3ISppHU3ylDRHXAuD5EN1hEet8zclsUNnV7/B8KJIgayG9RsL
7PhGlSqT3gL+g7Dwe03jZIul/Q9h0ahzMDktxCxL2JyJqqaMlUsR9qhY4A3NkMk1
ds8PAK78q3LJaXrUP4eECE89+JKNFSeRS0KgqkfTewhQ5YlPhCDbrH2sLt1dXn1c
X5301hCAJQbdJEpzsiOUMZ44mpMyXLHljv/m7rooTD7PvLqEAY8X9H3akQFvt5QV
gdK3aK3V86QRCNV4Xc5OzRkBy3QukftvowfZTMagmTjAV2UHYMUJVVOW/2v/GUEI
HfoWyEsb3S61wGGrzUCxAk45fgDpEyWWbfE8sNcEmEshvbChkB/WIVqjV2bP9eiS
qaa/TL6r7BsYyGAjNPZQb+Invi4OBTRgqhB3IxfTQcRpSYuH5EKW9wFoLnl53HlH
v3OXQB8ntCrZk4ln5/xqBfy+FrjA8KKzMA+l/N8WG7MxRsoHSTDc3rZ1x12xw7uk
vO4qDJFlApqpTCE2Aa4E+3NHV+5JH9Cf1d+6xDeKkFyrUjy8FLZogdLVAWPgvSci
U7fZP97Gl9Nyg2pmWyRoRiA/TwmIhu1pp4Zb4JIqdXSbW4BlCJHGvUJ+86rw8/ym
5CjjsoqgCbAmwK53vWRu+5LJU40v3leDDF7BClylhk4qgwaFHuf/8n/p7wARAQAB
tCFtYXR2ZWVjaDk5IDxtYXR2ZWVjaDk5QGdtYWlsLmNvbT6JAlEEEwEKADsWIQRL
TIcd1zHX9tEbLvE/66p+TDNDUwUCaBNh6QIbAwULCQgHAgIiAgYVCgkICwIEFgID
AQIeBwIXgAAKCRA/66p+TDNDU4iPEACudUTLshYvGWggRxyRRG21VNVBClvOLyah
9rwX2tnDSUO/GOT/2NFW9SZWE9RFHfZ9JHGGNkxEA3teu22mTFh95s6t1scXBf6H
BehVj7hohmdXmWAztWqRLABCzOplQn5SSfx+Z+kscpKwVaiR4WnG3DizFGZYUhPA
LUI/JRG2dSlNhUII2ODG4xzuIBOF9c94gnSRaCSvYYC+5mA+U4czCOP1SwGpDtXA
7kBY8gk6F5hwtMt4dTIXtLN1LaMGNPHACcoUkL7AB1T6gBokgl9jYmzYMlOVdkHE
CIOhcCrjXo+tpk9Qm8o5y7dtvjMXuRDjM00jylTOprKmsqwhLidtYBlIbUX7Yj4w
1zOhKlXTEkVorGaCuDF1iiKuzkbvOy+0K10Xq86ySFtY8u8LqT1oCETGrvB0aZ2n
10WNrqyWcUZN7IQmYRmBUPgfYYm4dSvqhfJgl4P3coY0h//1vRQ1x04RzMDwwbe1
GIv5O2GCBd5xg845XZn5cwOs6OZ4lLAssgc7iGdGADIsm6hVxR/dEfjsJ9IG1Iya
bctURuuhsQDu3Wv8iIj7oRDmXYsTqwoFgjj6xqQwWSC1M31wMd03/avMWy6D4iVK
lvtQ05HmblAltpTKMnqLqLcGc3lINX00L/2yWtiCDQyLOJNW6vCFr1k0bfHmAnhx
1/acHJ1WbrkCDQRoE2HpARAApo2YSCul9j2fCyIbxeFY0c4vZWc+lioxX82WVmDA
QnJlisGgbpECy9vHbpWNDM+hYhUOo8KmhsraEZieJjxkRw3jHy/dzzoXq485mKWG
d20W1kD3YCDglfNuemv1/xsv2NW76Em+ofk9yZOiDR49LHZ03u7oghkzYrCTw3uC
KDBjw3lO5rcHbuTA8zcwUaFPQmlSXQSNih0IWSFi3Q9ZuIKF/1QggP9dpb8A50Hj
AnOP2bfyW8ZF6FaCzqU8Y6+SMSo83xWRYwFQtDJO82A80NGuab1hnFHXdEXLot5W
JKXW43ya6GBUR6lTK+BsDp7cWkPQNQz72fEAxWCLFbeOa3Zukb+X8Bbc9mTvRE7J
oiFRPI1VBlY+k7ofNhopoSPaHPXFA5jOwSJUidPgo0Dz8JSwyPUESS4GTY8jMhU3
nI8k8bMqGsLVxmPyURves7tdeZn7CQScjp9hmtVGE/paxYl/OOw3zkZrJMP1bsch
p2AUnp0vQm3x+aP4gMZA1ej7J0bx9DZYPIdevXjv/zRkGLy2V5rEgfQSywNcNXfo
v6VmQdy6WKYpKyjFjBp8kD7z6HT9f3q6p/T2aICuDU6a3ypi8A69G8BEQ2U1rnP6
gP7+KVN2ptrYgwIulX3ZBkvwg8AHBDolYnvgsI16ur4OzZ122ZQs+vPccU2nSnAp
m2MAEQEAAYkCNgQYAQoAIBYhBEtMhx3XMdf20Rsu8T/rqn5MM0NTBQJoE2HpAhsM
AAoJED/rqn5MM0NTfNoP/2cfgY2GzdqmCOir4aWCb6KQe3+Ckn+hUqP4o4d2oCF0
Kg9ErLMvJnK3jhmYqwD/KnZmvUXUb20RYgoamZFwImktk2yQ5NSgKV/KYZCWAeCI
vOXw5VwKIdTAemuJQq/bJdKBsWyrJtEHaZ9RtyDRHg1vALJcw6vPflcFRayLX247
2BWa+iztpIGQsEAaOWzVXoClJmB9wHT++PRrgUkBoArW8yDs3aqwRQNR+7A8SfAz
SxqH2+o1QzmVH7T6K4698aZFO8+SAJgAmqSSFikd/xny4FgCDEqJ0viD3okfsvBv
bwPMCDAOGiOzb/vbMdG2TE0Lz5YSPMaDt6qJqi/yDqY1yiUwp/yFdUlwO/fA9bK3
1DIfM8qNc9788KXdVV1dl+9tUEhvGPvWFRyLkLEZ+Nbd7JiTXF1qjsGO/g0zqL62
hYYiObq1p71Z7ZCVlTMwmKVvrpVTzqcW0Y5tunOX+8oBk9Zto9qekqRU4gNhBch3
EiXcsMva6OCbcsm/cZ96ZoQCMTIWvqnhhSQ8AeVGVbBbdZxMQA8pc+0Ne0HqMdtv
9yVHlZw7y0r5q0rqyqEPp9I8Bn4EYKjoTpczAMenYhtpDA/MtbtSE/bOj8Z9a6h0
LZVzdYlD59r37yOYxcJQB6eXzA/6L43XAvIONonfjISPGQSDZjzcKddf8XjbvXit
=PA7r
-----END PGP PUBLIC KEY BLOCK-----
> git config user.signingkey ${GPG_SEC_KEY_ID}
> git config gpg.program gpg
> test -r ~/.bash_profile && echo 'export GPG_TTY=$(tty)' >> ~/.bash_profile
> echo 'export GPG_TTY=$(tty)' >> ~/.profile
> cmake -H. -B_build -DCPACK_GENERATOR="TGZ"
CMake Error: The current CMakeCache.txt directory /home/matvey/matveech99/workspace/projects/lab09/_build/CMakeCache.txt is different than the directory /home/matvey/matveech99/workspace/projects/lab06/_build where CMakeCache.txt was created. This may result in binaries being created in the wrong place. If you are not sure, reedit the CMakeCache.txt
CMake Error: The source "/home/matvey/matveech99/workspace/projects/lab09/CMakeLists.txt" does not match the source "/home/matvey/matveech99/workspace/projects/lab06/CMakeLists.txt" used to generate cache.  Re-run cmake with a different source directory.
> rm -rf _build
> cmake -H. -B_build -DCPACK_GENERATOR="TGZ"
CMake Deprecation Warning at CMakeLists.txt:1 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:9 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:9 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_set_config_location.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:13 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:34 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_private_data.cmake:12 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:35 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_initialize.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/Hunter:36 (include)
  cmake/HunterGate.cmake:540 (include)
  CMakeLists.txt:4 (HunterGate)


-- The C compiler identification is GNU 13.3.0
-- The CXX compiler identification is GNU 13.3.0
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Check for working C compiler: /usr/bin/cc - skipped
-- Detecting C compile features
-- Detecting C compile features - done
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Check for working CXX compiler: /usr/bin/c++ - skipped
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- [hunter] Calculating Toolchain-SHA1
CMake Deprecation Warning at CMakeLists.txt:1 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.


-- [hunter] Calculating Config-SHA1
-- [hunter] HUNTER_ROOT: /home/matvey/.hunter
-- [hunter] [ Hunter-ID: 23f1b5a | Toolchain-ID: fb15dbb | Config-ID: bf2be25 ]
CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:9 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:9 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_set_config_location.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:13 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:9 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_config_sha1.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:9 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_toolchain_sha1.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:10 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_set_config_location.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_apply_gate_settings.cmake:13 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_calculate_self.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_finalize.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_cache_run.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_create_cache_meta_directory.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_create_cache_meta_directory.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_load_from_cache.cmake:6 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:22 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_create_cache_meta_directory.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_save_to_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_create_cache_meta_directory.cmake:5 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_save_to_cache.cmake:4 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_save_to_cache.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_save_to_cache.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


CMake Deprecation Warning at /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_lock_directory.cmake:4 (cmake_minimum_required):
  Compatibility with CMake < 3.5 will be removed from a future version of
  CMake.

  Update the VERSION argument <min> value or use a ...<max> suffix to tell
  CMake that the project does not need compatibility with older versions.
Call Stack (most recent call first):
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_make_directory.cmake:7 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_save_to_cache.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_download.cmake:26 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/projects/GTest/hunter.cmake:8 (include)
  /home/matvey/.hunter/_Base/Download/Hunter/0.23.308/23f1b5a/Unpacked/cmake/modules/hunter_add_package.cmake:62 (include)
  CMakeLists.txt:24 (hunter_add_package)


-- [hunter] GTEST_ROOT: /home/matvey/.hunter/_Base/23f1b5a/fb15dbb/bf2be25/Install (ver.: 1.11.0)
-- Found GTest: /home/matvey/.hunter/_Base/23f1b5a/fb15dbb/bf2be25/Install/lib/cmake/GTest/GTestConfig.cmake (found version "1.11.0")  
-- Configuring done (0.9s)
-- Generating done (0.0s)
-- Build files have been written to: /home/matvey/matveech99/workspace/projects/lab09/_build
> cmake --build _build --target package
[ 25%] Building CXX object CMakeFiles/print.dir/sources/print.cpp.o
[ 50%] Linking CXX static library libprint.a
[ 50%] Built target print
[ 75%] Building CXX object CMakeFiles/demo.dir/demo/main.cpp.o
[100%] Linking CXX executable demo
[100%] Built target demo
Run CPack packaging tool...
CPack: Create package using TGZ
CPack: Install projects
CPack: - Run preinstall target for: print
CPack: - Install project: print []
CPack: Create package
CPack: - package: /home/matvey/matveech99/workspace/projects/lab09/_build/print-0.1.0.0-Linux.tar.gz generated.
> git tag -s v0.1.0.0
> git tag -v v0.1.0.0
object dee7d2337d0b2c600bbbc66c6b7d72e156a9a05a
type commit
tag v0.1.0.0
tagger matveech99 <matveech99@gmail.com> 1746102873 +0300

git tag -s v0.1.0.0
gpg: Подпись сделана Чт 01 мая 2025 15:34:58 MSK
gpg:                ключом RSA с идентификатором 4B4C871DD731D7F6D11B2EF13FEBAA7E4C334353
gpg: Действительная подпись пользователя "matveech99 <matveech99@gmail.com>" [абсолютное]
> git show v0.1.0.0

> git push origin main --tags
Перечисление объектов: 389, готово.
Подсчет объектов: 100% (389/389), готово.
При сжатии изменений используется до 16 потоков
Сжатие объектов: 100% (179/179), готово.
Запись объектов: 100% (389/389), 2.14 МиБ | 3.98 МиБ/с, готово.
Всего 389 (изменений 170), повторно использовано 388 (изменений 170), повторно использовано пакетов 0
remote: Resolving deltas: 100% (170/170), done.
To https://github.com/matveech99/lab09
 * [new branch]      main -> main
 * [new tag]         v0.1.0.0 -> v0.1.0.0
> github-release --version
zsh: command not found: github-release
> wget https://github.com/github-release/github-release/releases/download/v0.10.0/linux-amd64-github-release.bz2
bunzip2 linux-amd64-github-release.bz2
--2025-05-01 15:38:40--  https://github.com/github-release/github-release/releases/download/v0.10.0/linux-amd64-github-release.bz2
Распознаётся github.com (github.com)… 140.82.121.4
Подключение к github.com (github.com)|140.82.121.4|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 302 Found
Адрес: https://objects.githubusercontent.com/github-production-release-asset-2e65be/16349521/1b057100-4fd2-11eb-8b36-80fd02bb3601?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250501T123840Z&X-Amz-Expires=300&X-Amz-Signature=f0345ece8f4ef1c291a4121efa686c5560a24a0aae96f469b4ce9c31382f5920&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3Dlinux-amd64-github-release.bz2&response-content-type=application%2Foctet-stream [переход]
--2025-05-01 15:38:40--  https://objects.githubusercontent.com/github-production-release-asset-2e65be/16349521/1b057100-4fd2-11eb-8b36-80fd02bb3601?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250501T123840Z&X-Amz-Expires=300&X-Amz-Signature=f0345ece8f4ef1c291a4121efa686c5560a24a0aae96f469b4ce9c31382f5920&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3Dlinux-amd64-github-release.bz2&response-content-type=application%2Foctet-stream
Распознаётся objects.githubusercontent.com (objects.githubusercontent.com)… 185.199.110.133, 185.199.111.133, 185.199.108.133, ...
Подключение к objects.githubusercontent.com (objects.githubusercontent.com)|185.199.110.133|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 4586134 (4,4M) [application/octet-stream]
Сохранение в: ‘linux-amd64-github-release.bz2’

linux-amd64-github-relea 100%[=================================>]   4,37M  4,67MB/s    за 0,9s    

2025-05-01 15:38:42 (4,67 MB/s) - ‘linux-amd64-github-release.bz2’ сохранён [4586134/4586134]

> chmod +x linux-amd64-github-release
> sudo mv linux-amd64-github-release /usr/local/bin/github-release
[sudo] пароль для matvey: 
> github-release --version
github-release v0.10.0
> github-release --version
github-release v0.10.0
> github-release release \
    --user ${GITHUB_USERNAME} \
    --repo lab09 \
    --tag v0.1.0.0 \
    --name "libprint" \
    --description "my first release"
> export PACKAGE_OS=`uname -s` PACKAGE_ARCH=`uname -m`
> export PACKAGE_FILENAME=print-${PACKAGE_OS}-${PACKAGE_ARCH}.tar.gz
> github-release upload \
    --user ${GITHUB_USERNAME} \
    --repo lab09 \
    --tag v0.1.0.0 \
    --name "${PACKAGE_FILENAME}" \
    --file _build/*.tar.gz
> github-release info -u ${GITHUB_USERNAME} -r lab09
tags:
- v0.1.0.0 (commit: https://api.github.com/repos/matveech99/lab09/commits/dee7d2337d0b2c600bbbc66c6b7d72e156a9a05a)
releases:
- v0.1.0.0, name: 'libprint', description: 'my first release', id: 215979788, tagged: 01/05/2025 at 12:34, published: 01/05/2025 at 12:39, draft: ✗, prerelease: ✗
  - artifact: print-Linux-x86_64.tar.gz, downloads: 0, state: uploaded, type: application/octet-stream, size: 5.9 kB, id: 251016489
> wget https://github.com/${GITHUB_USERNAME}/lab09/releases/download/v0.1.0.0/${PACKAGE_FILENAME}
--2025-05-01 15:40:56--  https://github.com/matveech99/lab09/releases/download/v0.1.0.0/print-Linux-x86_64.tar.gz
Распознаётся github.com (github.com)… 140.82.121.4
Подключение к github.com (github.com)|140.82.121.4|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 302 Found
Адрес: https://objects.githubusercontent.com/github-production-release-asset-2e65be/976038908/35e912e9-aed1-4e5c-bc66-b218b18167c9?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250501T124056Z&X-Amz-Expires=300&X-Amz-Signature=1d00cdfeb4776fda4757975a3ff747c7961d1e0d42bc8a809207e8d82ece8623&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3Dprint-Linux-x86_64.tar.gz&response-content-type=application%2Foctet-stream [переход]
--2025-05-01 15:40:57--  https://objects.githubusercontent.com/github-production-release-asset-2e65be/976038908/35e912e9-aed1-4e5c-bc66-b218b18167c9?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20250501%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250501T124056Z&X-Amz-Expires=300&X-Amz-Signature=1d00cdfeb4776fda4757975a3ff747c7961d1e0d42bc8a809207e8d82ece8623&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%3Dprint-Linux-x86_64.tar.gz&response-content-type=application%2Foctet-stream
Распознаётся objects.githubusercontent.com (objects.githubusercontent.com)… 185.199.111.133, 185.199.110.133, 185.199.108.133, ...
Подключение к objects.githubusercontent.com (objects.githubusercontent.com)|185.199.111.133|:443... соединение установлено.
HTTP-запрос отправлен. Ожидание ответа… 200 OK
Длина: 5863 (5,7K) [application/octet-stream]
Сохранение в: ‘print-Linux-x86_64.tar.gz’

print-Linux-x86_64.tar.g 100%[=================================>]   5,73K  --.-KB/s    за 0s      

2025-05-01 15:40:57 (16,0 MB/s) - ‘print-Linux-x86_64.tar.gz’ сохранён [5863/5863]

> tar -ztf ${PACKAGE_FILENAME}
print-0.1.0.0-Linux/cmake/
print-0.1.0.0-Linux/cmake/print-config-noconfig.cmake
print-0.1.0.0-Linux/cmake/print-config.cmake
print-0.1.0.0-Linux/include/
print-0.1.0.0-Linux/include/print.hpp
print-0.1.0.0-Linux/bin/
print-0.1.0.0-Linux/bin/demo
print-0.1.0.0-Linux/lib/
print-0.1.0.0-Linux/lib/libprint.a
> git add .
> git commit -m"lab 09 done"
