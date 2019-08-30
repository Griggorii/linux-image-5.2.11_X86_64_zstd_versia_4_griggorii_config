# linux-image-5.2.11_X86_64_zstd_versia_4_griggorii_config
linux-image-5.2.11_X86_64_zstd_versia_4_griggorii_config

Ядро берем с kernel.org конфиг оригинален 4 прошлой версии где ядро было ниже по цифре.

Если всё готово переименовываем его и кладём в папку с ядром переименовав там же в .config т.е проще 
говоря удалить часть названия если вы его скачали , а не скопировали далее в терминале выполняем make -j16 bindeb-pkg 
с условием что все dev зависимости установлены.

Готовые deb пакеты https://drive.google.com/open?id=14KQR4lv9BjzKu_-9cSTtYsYMwNrNSzC1
