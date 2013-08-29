napi-bash
=========

Working on Fedora 19. Forked script from http://code.google.com/p/napi-bash/ 

INSTALLATION ON Fedora 19
=========

Wymagane pakiety:
p7zip, curl

W wersji oryginalnej program używał polecenia 7z przez co na Fedorze 19 wyświetlał informację o braku napisów. W F19 nie ma polecenia 7z, zamiast niego jest 7za. 

------------------------
   OPCJE INSTALACYJNE
------------------------
Domyślne opcje:
  PREFIX="/usr/local"
  MANPREFIX="$(PREFIX)/share"
  DESTDIR=""

------------------------
       INSTALACJA
------------------------
Przykład:
  make install PREFIX=/usr

Patrz: OPCJE INSTALACYJNE..

------------------------
      DEINSTALACJA
------------------------
Przykład:
  make uninstall PREFIX=/usr

Patrz: OPCJE INSTALACYJNE..
