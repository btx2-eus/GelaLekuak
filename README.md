# 🪑 GelaLekuak

**Tutoreentzako aulki-antolatzailea** — soziograma batean oinarrituta, gelako eserleku-banaketa optimoa sortzen duen web-aplikazioa.

🔗 **Aplikazioa**: https://btx2-eus.github.io/GelaLekuak/

## Zer egiten du?

Ikasleen nahiak jasota (norekin BAI / norekin EZ eseri), algoritmo batek eserleku-banaketa optimoa kalkulatzen du: gatazkak banandu, nahiak bete, eta tutoreak eskuz fintzeko aukera ematen du.

## Ezaugarriak

- **Datu-bilketa erraza, izen-akatsik gabe**: Google Forms gida (app-ak galdetegia sortzen dizu, izenak barruan, zerrenda itxiekin) edo eskuzko sarrera
- **Inportazio malgua**: Excel/CSV igo, kopiatu-itsatsi, edo txantiloia deskargatu — zutabe-mapaketa lagunduarekin
- **Lotu gabeko izenen abisuak**: gaizki idatzitako edo izen anbiguoak eskuz argitzeko panela
- **Gelaren egitura konfiguragarria**: errenkada kopurua, errenkada bakoitzeko mahai kopurua, mahaiak binaka/hirunaka pasabideekin
- **Optimizatzailea**: gatazkak −5, nahiak +3 (alboko bizilagunak ×2), lehen lerroko beharrak (📌) kontuan hartuta; ~1,2 s 28 ikasle arte, ~3 s 40 ikaslerekin
- **X-izpiak**: ikasle bat arrastatzean bere lagunak (berdez) eta gatazkak (gorriz) argiztatzen dira, toki bakoitzaren puntuazioa erakutsiz
- **Aingurak** (🔒): ikasleak tokian finkatu berriro optimizatzean
- **Talde anitz**, autogordetzea (localStorage), JSON esportazioa/inportazioa
- **Inprimatu/PDF**: gelako mapa A4 horizontalean
- **Ukipen-euskarria**: tabletan ere badabil

## Pribatutasuna

Datu guztiak **nabigatzailean bakarrik** gordetzen dira (localStorage). Ez da ezer zerbitzarira bidaltzen — ez dago backend-ik, eta **ez da kanpoko zerbitzaririk kontsultatzen**: menpekotasun guztiak (SheetJS eta letra-tipoak) biltegian bertan daude, beraz orria interneterik gabe ere badabil.

Google Forms bidezko bilketak **ez du helbide elektronikorik gordetzen** (`setCollectEmail(false)`), baina galdetegia **ez da anonimoa**: soziograma egiteko tutoreak jakin behar du nork zer erantzun duen, eta hala esaten zaie ikasleei galdetegian bertan. Ikasleen izenak eta aukeraketak **adingabeen datu pertsonalak** dira: erabili tutoretza/orientazio lanerako soilik.

## Teknikoki

HTML fitxategi bakarra (`index.html`) + `assets/` (SheetJS 0.20.3 eta letra-tipoak, autoalojatuak). Menpekotasun bakarra [SheetJS](https://sheetjs.com/) da, Excel fitxategiak irakurtzeko. Euskaraz. "Obsidian Ink / Velvet Curfew / Almond Hearth" paleta.

## Erabilera-gida

Mini-manual osoa: **[ERABILERA.md](ERABILERA.md)**. Aplikazioan bertan ere eskuragarri dago, albo-barrako **❓ Erabilera-gida** botoian.

**Etapa-arduradun eta orientaziorako gida laburra** (zer datu erabiltzen diren, zer arau bete behar diren, txostenaren bi mailak, metodoaren mugak): [btx2-eus.github.io/GelaLekuak/eskuliburua.html](https://btx2-eus.github.io/GelaLekuak/eskuliburua.html)

## Egilea eta lizentzia

Egilea: **Luken San Sebastián** ([luken@lasalledonostia.com](mailto:luken@lasalledonostia.com))

Lizentzia: **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.eu)** (Aitortu — EzKomertziala — PartekatuBerdin). Libre zara erabili, kopiatu eta moldatzeko, betiere egilea aitortuta, helburu ez-komertzialetarako, eta eratorritako lanak lizentzia berarekin partekatuta. Ikus [LICENSE](LICENSE).
