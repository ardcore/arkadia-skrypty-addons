# Arkadia - Addons

Skrypty rozszerzające paczkę Adremena.

## Nowe aliasy

- `/wdp <co>` - włoży do pojemnika "other" podany przedmiot, można podać kilka po przecinku (np. `/wdp miecz,spizowa tarcze`)
- `/wzp <co>` - analogicznie, branie z pojemnika
- `/zbierz` - wykonaj zbieranie na wszystkich cialach (zdefiniowane monety, kamienie i extra)
- `/zbieraj_extra <co>` - dodatek do Adremenowego zbierania monet/kamieni, pozwala zdefiniować inne przedmioty do brania z ciał. Można podać kilka po przecinku. (np. /zbieraj_extra posrebrzane miecze,tarcze)
    - `/zbieraj_extra` bez parametrów pokazuje co obecnie zbieramy
    - `/zbieraj_extra off` wyłącza zbieranie
- `/pokaz_trase <id>` - skrót: `/p` - podswietli na mapie (na chwile) sciezke do `<id>`
- `/porownaj_ze_wszystkimi` - skrót `/pw` - pokaże tabelkę z porównaniem cech osób na lokacji względem Ciebie:

        /porownaj_ze_wszystkimi

        #  OSOBA                      SIL  ZRE  WYT  TOTAL 
        1  koscisty wyszczerzony ork  +3   -3   -4   -4    
        2  zoltooki szkaradny ork     +2   +3   +1   +6    

## Modyfikacje

- `/przeszukaj_mape` teraz podaje odległość

## Instalacja

1. Pobieramy paczkę [stąd](https://github.com/ardcore/arkadia-skrypty-addons/releases), rozpakowujemy
2. W Mudlecie klikamy `Package manager -> Install`, wybieramy rozpakowany plik `arkadia-addons.xml`
3. Restartujemy Mudleta