# Politika privatnosti za PURESHIFT

**Zadnje ažuriranje:** 6. studenoga 2026.

## 1. Voditelj obrade

Voditelj obrade odgovoran za obradu podataka u vezi s Android aplikacijom **PURESHIFT** (u daljnjem tekstu „Aplikacija") je:

**Adonis Japalak**
Blücherstrße 39 
86165 Augsburg 
Deutschland

E-pošta: NextExchangeStudio@proton.me

## 2. Opće informacije o obradi podataka

PURESHIFT je aplikacija za planiranje smjena s upravljanjem zaposlenicima. Podaci o smjenama i zaposlenicima koje unosiš pohranjuju se lokalno na tvom Android uređaju. Za te podatke Aplikacije pružatelj ne upravlja središnjim poslužiteljem niti vlastitom sinkronizacijom u oblaku. U uobičajenom radu pružatelj ne dobiva kopiju tih podataka.

Osnovne funkcije Aplikacije mogu se koristiti izvan mreže. Opcionalno dijeljenje putem Wi-Fi mreže zahtijeva lokalnu mrežu. Pristup internetu potreban je ako na GitHubu otvaraš pravne informacije povezane u Aplikaciji.

Podaci mogu napustiti tvoj uređaj ako ih sam izvezeš ili podijeliš (odjeljak 5.), ako Android izradi sigurnosnu kopiju uređaja (odjeljak 7.) ili ako otvoriš vanjske poveznice (odjeljak 10.). Ako ih proslijediš drugoj aplikaciji ili usluzi u oblaku, dodatno vrijede njihovi uvjeti privatnosti.

Registracija ili korisnički račun nisu potrebni.

## 3. Koji se podaci obrađuju lokalno?

Na tvom se uređaju pohranjuju sljedeći podaci:

- Smjene i unosi smjena (datum, vremena, bilješke i, prema potrebi, mjesto rada koje si unio/unijela) te unosi zamjene smjena
- Vrste smjena (naziv, boja, broj sati i stanke) i grupe smjena
- Nazivi kalendara i grupa
- Postavke valute, izračuna plaće i poreza, savezne pokrajine, jezika, prikaza i widgeta
- Vrijeme početka mjerenja vremena u tijeku (mjerač vremena)
- Predlošci i postavke za PDF izvoz
- **Podaci o zaposlenicima**, ako koristiš upravljanje zaposlenicima i ispunjavaš ga (sva su polja dobrovoljna):
  - Ime i prezime te datum rođenja
  - Kontaktni podaci (privatna/poslovna e-pošta, telefon, mobitel i adresa)
  - Podaci o zaposlenju (datum početka/završetka, vrsta zaposlenja, odjel, radno mjesto i lokacija)
  - Podaci o naknadi (plaća, bankovni podaci i porezni razred)
  - Podaci o socijalnom osiguranju (broj socijalnog osiguranja, porezni identifikacijski broj, zdravstveno i mirovinsko osiguranje)
  - Podaci o godišnjem odmoru te kvalifikacije, osposobljavanja, potvrde i primopredaja ključeva

Za Android widgete lokalno se pohranjuje i sažetak nadolazećih smjena.

Za dijeljenje putem Wi-Fi mreže Aplikacija pohranjuje tehničke podatke o sinkronizaciji, među ostalim PIN za uparivanje, identifikatore i pristupne tokene uparenih uređaja, vrijeme zadnje sinkronizacije te postavku o automatskom prihvaćanju operacija pisanja.

## 4. Odgovornost za podatke o zaposlenicima

Ako Aplikaciju koristiš za upravljanje osobnim podacima drugih osoba, na primjer zaposlenika, moraš provjeriti tko je za tu obradu odgovoran u smislu zaštite podataka. Ovisno o uporabi, to posebno može biti tvoj poslodavac ili tvoja tvrtka.

Odgovorno tijelo mora imati pravnu osnovu za obradu, informirati ispitanike i primjereno zaštititi podatke. Za podatke o zaposlenicima mogu vrijediti posebni zakonski zahtjevi.

U uobičajenom radu pružatelj nema pristup lokalno pohranjenim podacima o zaposlenicima. Sigurnosne kopije, prijenosi koje pokreneš ti i vanjske usluge opisani su u sljedećim odjeljcima.

## 5. Prijenosi podataka koje pokreće korisnik

### 5.1 Sigurnosna kopija (Backup / Restore)

Funkcijom „Sigurnosna kopija podataka” možeš izvesti podatke Aplikacije kao JSON datoteku i ponovno ih uvesti. Potpuni izvoz može sadržavati i podatke o zaposlenicima.

Kod izvoza za razdoblje na odabrano se razdoblje ograničavaju samo unosi smjena i unosi zamjene smjena. Ostali podaci, na primjer matični podaci zaposlenika i postavke, i dalje mogu biti uključeni u cijelosti.

JSON datoteka nije šifrirana. Na Androidu lokaciju pohrane biraš putem sustavnog odabirnika datoteka. Ako za to odabereš aplikaciju za oblak, razmjenu poruka ili drugu aplikaciju treće strane, njezin pružatelj može primiti datoteku i obraditi je prema vlastitim uvjetima privatnosti. Pružatelj PURESHIFT-a ne dobiva kopiju.

### 5.2 PDF izvoz

Pri izradi PDF dokumenta iz tvojih podataka o smjenama datoteka se generira lokalno na uređaju. Zatim je možeš podijeliti, ispisati ili spremiti putem funkcija sustava. Ako za to odabereš drugu aplikaciju ili vanjsku uslugu, ona obrađuje datoteku prema vlastitim uvjetima privatnosti. PDF izvoz ne prenosi ništa pružatelju PURESHIFT-a.

### 5.3 Dijeljenje kalendara

Funkcija „Podijeli kalendar” lokalno izrađuje sliku tvog kalendara smjena. Tu sliku zatim možeš poslati drugim osobama ili aplikacijama putem funkcije dijeljenja na uređaju. Samo ti odlučuješ s kim je dijeliš.

### 5.4 Dijeljenje putem Wi-Fi mreže (sinkronizacija među uređajima)

Aplikacija opcionalno nudi „dijeljenje putem Wi-Fi mreže”. Ako ga aktiviraš, Aplikacija na tvom uređaju pokreće lokalni poslužitelj dostupan u istoj lokalnoj mreži. Drugi uređaj može se upariti pomoću prikazanog PIN-a te zatim preuzeti ili poslati podatke Aplikacije. Pritom se mogu prenijeti svi podaci Aplikacije, uključujući podatke o zaposlenicima.

Imaj na umu:

- Dijeljenje putem Wi-Fi mreže prema zadanim je postavkama isključeno i aktiviraš ga samo ti.
- Prijenos se odvija unutar lokalne mreže putem HTTP-a i nije šifriran. Funkciju koristi samo u pouzdanim mrežama, ne u javnim Wi-Fi mrežama.
- Za sinkronizaciju se ne koristi središnji poslužitelj pružatelja.
- Upareni uređaji mogu čitati podatke.
- Operacije pisanja uparenih uređaja prema zadanim se postavkama prihvaćaju bez dodatne potvrde („Uvijek prihvati”, u Aplikaciji prikazano kao „Immer akzeptieren”). Ako tu postavku deaktiviraš, dolazne se operacije pisanja odbijaju; upit za potvrdu pritom se ne prikazuje.
- Ako generiraš novi PIN, postojeća se uparivanja opozivaju.
- Nakon korištenja ponovno isključi dijeljenje putem Wi-Fi mreže.

## 6. Dopuštenja i funkcije sustava

Aplikacija koristi mrežne funkcije i funkcije sustava u sljedeće svrhe:

- **Mreža:** za opcionalno dijeljenje putem Wi-Fi mreže, za prikaz adrese lokalne mreže i za otvaranje povezane politike privatnosti i pravnih informacija u pregledniku
- **Vibracija:** za povratne informacije pri korištenju
- **Funkcije datoteka i dijeljenja:** za uvoz i izvoz datoteka sigurnosnih kopija te za dijeljenje PDF datoteka i datoteka kalendara. Na Androidu datoteke ili lokacije pohrane biraš putem sustavnog odabirnika.

Aplikacija ne koristi kameru, mikrofon, GPS lokaciju ni kontakte. Mjesto rada ili lokacija zaposlenika koju ručno uneseš nije GPS lokacija. Aplikacija ne šalje push obavijesti.

## 7. Sigurnosna kopija koju izrađuje operacijski sustav (Android)

Android aplikacija dopuštena je za sigurnosne kopije uređaja. Ako je sigurnosna kopija aktivirana na tvom uređaju odnosno u tvom Google računu, podaci Aplikacije mogu se automatski uključiti u Google sigurnosnu kopiju. To mogu biti i lokalno pohranjeni podaci o smjenama i zaposlenicima.

Hoće li se izraditi sigurnosna kopija ovisi o Androidu te o postavkama tvog uređaja i računa. Sigurnosnu kopiju izrađuje Google, a ne pružatelj PURESHIFT-a. Vrijede obavijesti o privatnosti tvrtke Google: https://policies.google.com/privacy

Ako ne želiš takvu sigurnosnu kopiju, provjeri i promijeni postavke sigurnosne kopije svog uređaja i Google računa.

## 8. Bez usluga analitike, praćenja i oglašavanja

Aplikacija ne sadrži usluge analitike, praćenja, oglašavanja ni društvenih mreža. Ne prikupljaju se identifikatori uređaja u svrhe oglašavanja ili analitike.

Za dijeljenje putem Wi-Fi mreže Aplikacija koristi lokalni identifikator uređaja i pristupne tokene za upareni uređaje. Ti podaci služe sinkronizaciji u lokalnoj mreži i ne prenose se pružatelju.

## 9. Obrada putem Google Playa

Kada preuzimaš ili ažuriraš Aplikaciju putem Google Playa, Google obrađuje podatke u vezi s radom trgovine i stavljanjem Aplikacije na raspolaganje. Koji se podaci obrađuju ovisi, među ostalim, o tvom Google računu, tvom uređaju i tvojim postavkama.

Pružatelj PURESHIFT-a nema utjecaj na tu obradu. Vrijede obavijesti o privatnosti tvrtke Google: https://policies.google.com/privacy

## 10. Pristup ovoj politici privatnosti i pravnim informacijama

Politika privatnosti i pravne informacije smješteni su na GitHubu. Kada u Aplikaciji otvoriš jednu od tih poveznica, odgovarajuća se stranica GitHuba učitava u tvom pregledniku. GitHub pritom prima tehnički nužne podatke o vezi, osobito tvoju IP adresu. Vrijede obavijesti o privatnosti tvrtke GitHub: https://docs.github.com/site-policy/privacy-policies/github-privacy-statement

## 11. Usluge izrade i distribucije

Aplikacija se razvija pomoću Expa te izrađuje i distribuira uz pomoć Expo Application Services (EAS). Za izradu Expo obrađuje tehničke podatke projekta i izrade. To treba razlikovati od podataka koje unosiš u Aplikaciju.

Tijekom rada PURESHIFT ne prenosi Expu unesene podatke o smjenama ni zaposlenicima.

## 12. Prava ispitanika

Podaci o smjenama i zaposlenicima uneseni u Aplikaciju pohranjuju se lokalno na tvom uređaju i nisu dostupni pružatelju putem središnjeg poslužitelja. Pružatelj stoga ne može preuzeti, izmijeniti ni izbrisati te lokalne sadržaje iz središnje baze podataka.

To ne znači da prava prema tijelima koja doista obrađuju podatke prestaju. Za podatke koje proslijediš putem sigurnosnih kopija, vanjskih poveznica ili aplikacija trećih strana mjerodavna su uključena tijela i njihove informacije o privatnosti. Osobe čije podatke bilježiš u Aplikaciji za svoja se prava obraćaju tijelu odgovornom za tu obradu, na primjer svom poslodavcu.

Svoje lokalne podatke možeš pregledavati, mijenjati i izvoziti u Aplikaciji. Deinstalacijom Aplikacije lokalno pohranjeni podaci Aplikacije u pravilu se uklanjaju s uređaja. Izvozne datoteke, kopije na drugim uređajima i Android sigurnosne kopije možda će se morati zasebno izbrisati.

Imaš i pravo podnijeti pritužbu nadzornom tijelu za zaštitu podataka.

## 13. Sigurnost podataka

Aplikacija pohranjuje svoje podatke u internu pohranu aplikacije na uređaju. Operacijski sustav štiti je od pristupa drugih aplikacija. Aplikacija pohranjene podatke dodatno ne šifrira.

Za zaštitu svog uređaja odgovoran/odgovorna si sam/sama. To osobito uključuje zaključavanje uređaja, šifriranje uređaja i ažuriran softver. Pri korištenju dijeljenja putem Wi-Fi mreže i pri dijeljenju datoteka dodatno vrijede napomene iz odjeljka 5.

## 14. Djeca

Aplikacija nije namijenjena djeci mlađoj od 16 godina.

## 15. Izmjene ove politike privatnosti

Ova politika privatnosti može se izmijeniti ako se promijene Aplikacija, obrada podataka ili pravna situacija. Trenutačna verzija dostupna je putem poveznice prikazane u Aplikaciji i, prema potrebi, na stranici trgovine.

## 16. Kontakt

Za pitanja o zaštiti podataka obrati se na: NextExchangeStudio@proton.me
