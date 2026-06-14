# 🪑 GelaLekuak

**Tutoreentzako aulki-antolatzailea** — soziograma batean oinarrituta, gelako eserleku-banaketa optimoa sortzen duen web-aplikazioa.

🔗 **Aplikazioa**: https://btx2-eus.github.io/GelaLekuak/

## Zer egiten du?

Ikasleen nahiak jasota (norekin BAI / norekin EZ eseri), algoritmo batek eserleku-banaketa optimoa kalkulatzen du: gatazkak banandu, nahiak bete, eta tutoreak eskuz fintzeko aukera ematen du.

## Ezaugarriak

- **Datu-bilketa erraza, izen-akatsik gabe**: kiosko-modua (gailua gelan txandaka pasatu, ikasleek zerrenda itxitik aukeratzen dute), Google Forms gida, paperezko galdetegi inprimagarria
- **Inportazio malgua**: Excel/CSV igo, kopiatu-itsatsi, edo txantiloia deskargatu — zutabe-mapaketa lagunduarekin
- **Lotu gabeko izenen abisuak**: gaizki idatzitako edo izen anbiguoak eskuz argitzeko panela
- **Gelaren egitura konfiguragarria**: errenkada kopurua, errenkada bakoitzeko mahai kopurua, mahaiak binaka/hirunaka pasabideekin
- **Optimizatzailea**: gatazkak −5, nahiak +3 (alboko bizilagunak ×2), lehen lerroko beharrak (📌) kontuan hartuta; 40 ikasle arte segundo batean
- **X-izpiak**: ikasle bat arrastatzean bere lagunak (berdez) eta gatazkak (gorriz) argiztatzen dira, toki bakoitzaren puntuazioa erakutsiz
- **Aingurak** (🔒): ikasleak tokian finkatu berriro optimizatzean
- **Talde anitz**, autogordetzea (localStorage), JSON esportazioa/inportazioa
- **Inprimatu/PDF**: gelako mapa A4 horizontalean
- **Ukipen-euskarria**: tabletan ere badabil

## Pribatutasuna

Datu guztiak **nabigatzailean bakarrik** gordetzen dira (localStorage). Ez da ezer zerbitzarira bidaltzen — ez dago backend-ik.

## Teknikoki

HTML fitxategi bakarra (`index.html`), menpekotasun bakarra [SheetJS](https://sheetjs.com/) (CDN) Excel fitxategiak irakurtzeko. Euskaraz. "Obsidian Ink / Velvet Curfew / Almond Hearth" paleta.

## Erabilera-gida

Mini-manual osoa: **[ERABILERA.md](ERABILERA.md)**. Aplikazioan bertan ere eskuragarri dago, albo-barrako **❓ Erabilera-gida** botoian.

## Egilea eta lizentzia

Egilea: **Luken San Sebastián** ([luken@lasalledonostia.com](mailto:luken@lasalledonostia.com))

Lizentzia: **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.eu)** (Aitortu — EzKomertziala — PartekatuBerdin). Libre zara erabili, kopiatu eta moldatzeko, betiere egilea aitortuta, helburu ez-komertzialetarako, eta eratorritako lanak lizentzia berarekin partekatuta. Ikus [LICENSE](LICENSE).
