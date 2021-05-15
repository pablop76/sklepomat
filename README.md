# strona sklepomaty.com

![Sklepomaty](./sklepomaty.png)

## użyte technologie.

1. html,css,js
2. program tworzący pakiety [gulp.js](https://gulpjs.com/)

3. platforma front-end do tworzenia szybkich i wydajnych interfejsów internetowych [uikit](https://getuikit.com/)

## niezbędne oprogramowanie.

1. środowisko wykonawcze [node.js](https://nodejs.org/en/)
2. IDE (zintegrowane środowisko programistyczne) np: [Visual Studio Code](https://code.visualstudio.com/)

## knfiguracja projektu.

1. pobranie paczkę z projektem [github](https://github.com/pablop76/sklepomat)
2. wypakować
3. otworzyc folder za pomoca IDE
4. otworzyć terminal w katalogu projektu
5. zainstalowac zależności za pomocą komendy:

- npm install

## praca z projektem

1. uruchomienie / developer

- gulp

     pliki do edycji znajdują się w katalogu src/templates/ opisane według nazw sekcji na stronie


2. uruchomienie / produkcja

- gulp build

     Paczka produkcyjna tworzona jest w katalogu docs
     Obrazki prznoszone są automatycznie wyłacznie z katalogu images, więc obrazki takie jak favicon należy kopiować ręcznie w przypadku zmiany.
     Pliki produkcyjne do przeniesienia na serwer znajdują się w katalogu docs.
