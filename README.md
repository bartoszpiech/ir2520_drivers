# Poradnik instalacji drukarki iR2520

Aby poprawnie zainstalować iR2520 należy pobrać dobry sterownik i być połączonym z tą samą siecią co ona (na chwilę pisania poradnika sieć to "CE77"). Kiedyś napisałem już poradnik [jak zainstalować iR2520 na linuxa](https://github.com/bartoszpiech/printers). W tym poradniku zajmiemy się bardziej popularnymi systemami.

## Pobranie sterowników
Sterowniki możemy pobrać z oficjalnej strony [Canon](https://www.canon.pl/support/products/imagerunner/imagerunner-2520.html). Po wybraniu systemu operacyjnego należy odszukać sterowniki do drukarki w wersji URFII LT w sekcji "Pojedyncze sterowniki" (powinno być na samym dole). Gdyby zdjęli stronę wersja aktualna dostępna na dzień pisania poradnika jest udostępniona w kilku miejscach:

- [Dysk Google](https://drive.google.com/drive/folders/1Xl4gRg2d6l4fquFMUUtbhbomn-FBz4dx?usp=sharing)
- [serwer bartoszpie.ch](https://git.bartoszpie.ch/ir2520_drivers)
- [Github](https://github.com/bartoszpiech/ir2520_drivers)

## Instalacja sterowników na Windowsie

Aby zainstalować sterowniki, po pobraniu należy je wypakować, w Windowsie uruchamiając plik .exe (na dzień pisania poradnika nazwa pliku to `UFRIILT_Driver_V3080_32_64_03.exe`), po wypakowaniu trzeba przejść do wypakowanego katalogu i kliknąć program setup, który przeprowadzi nas przez instalację. trzeba zgodzić się na regulamin, zaznaczyć standardową instalację i poczekać aż program odnajdzie naszą drukarkę, po zainstalowaniu trzeba sprawdzić czy mamy zaznaczony druk dwustronny i odpowiednią wielkość kartek, chociaż domyślnie powinno być dobrze ustawione.

## Instalacja sterowników na Macu

TODO, To samo co wyżej

## Instalacja na Linuxie

Najlepiej instalować paczki od użytkowników (np. z AUR), potem w CUPS dodać drukarkę z odpowiednim sterownikiem.
