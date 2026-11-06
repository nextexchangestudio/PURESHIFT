# Politica de confidențialitate pentru PURESHIFT

**Ultima actualizare:** 6 noiembrie 2026

## 1. Operatorul de date

Operatorul responsabil pentru prelucrarea datelor în legătură cu aplicația Android **PURESHIFT** (denumită în continuare „Aplicația") este:

**Adonis Japalak**
Blücherstrße 39 86165 Augsburg Deutschland

E-mail: NextExchangeStudio@proton.me

## 2. Informații generale privind prelucrarea datelor

PURESHIFT este o aplicație de planificare a turelor, cu gestionarea angajaților. Datele despre ture și angajați pe care le introduci sunt stocate local pe dispozitivul tău Android. Pentru aceste date ale Aplicației, furnizorul nu operează un server central și nici o sincronizare proprie în cloud. În funcționarea normală, furnizorul nu primește nicio copie a acestor date.

Funcțiile de bază ale Aplicației pot fi utilizate offline. Partajarea opțională prin Wi-Fi necesită o rețea locală. Accesul la internet este necesar dacă deschizi pe GitHub informațiile juridice la care trimite Aplicația.

Datele pot părăsi dispozitivul tău dacă le exporți sau le distribui tu însuți (secțiunea 5), dacă Android efectuează o copie de rezervă a dispozitivului (secțiunea 7) sau dacă deschizi linkuri externe (secțiunea 10). Dacă le transmiți unei alte aplicații sau unui serviciu cloud, se aplică suplimentar condițiile de confidențialitate ale acestora.

Nu este necesară înregistrarea sau un cont de utilizator.

## 3. Ce date sunt prelucrate local?

Pe dispozitivul tău sunt stocate următoarele date:

- Ture și înregistrări de ture (data, orele, note și, eventual, un loc de muncă introdus de tine), precum și înregistrări de schimb de ture
- Tipuri de ture (denumire, culoare, număr de ore și pauze) și grupuri de ture
- Denumiri de calendare și de grupuri
- Setări privind moneda, calculul salariului și al impozitului, landul federal, limba, afișarea și widgeturile
- Ora de pornire a unei măsurări de timp în curs (cronometru)
- Șabloane și setări pentru exportul PDF
- **Datele angajaților**, dacă folosești gestionarea angajaților și o completezi (toate câmpurile sunt opționale):
  - Nume și data nașterii
  - Date de contact (e-mail privat/de serviciu, telefon, mobil și adresă)
  - Date privind angajarea (data de început/sfârșit, tipul angajării, departament, funcție și locație)
  - Date privind remunerația (salariu, date bancare și clasa de impozitare)
  - Date privind asigurările sociale (numărul de asigurări sociale, cod fiscal, asigurare de sănătate și de pensie)
  - Date privind concediul, precum și calificări, instruiri, certificate și predarea cheilor

Pentru widgeturile Android se stochează local, de asemenea, un rezumat al turelor următoare.

Pentru partajarea prin Wi-Fi, Aplicația stochează date tehnice de sincronizare, printre care PIN-ul de asociere, identificatorii și tokenurile de acces ale dispozitivelor asociate, momentul ultimei sincronizări și setarea privind acceptarea automată a operațiunilor de scriere.

## 4. Responsabilitatea pentru datele angajaților

Dacă folosești Aplicația pentru a gestiona date cu caracter personal ale altor persoane, de exemplu ale angajaților, trebuie să verifici cine este responsabil pentru această prelucrare în sensul legislației privind protecția datelor. În funcție de utilizare, acesta poate fi în special angajatorul sau compania ta.

Entitatea responsabilă trebuie să aibă un temei juridic pentru prelucrare, să informeze persoanele vizate și să protejeze datele în mod adecvat. Pentru datele angajaților pot exista cerințe legale speciale.

În funcționarea normală, furnizorul nu are acces la datele angajaților stocate local. Copiile de rezervă, transferurile inițiate de tine și serviciile externe sunt descrise în secțiunile următoare.

## 5. Transferuri de date inițiate de utilizator

### 5.1 Copie de rezervă (Backup / Restore)

Cu funcția „Copie de rezervă a datelor” poți exporta datele Aplicației ca fișier JSON și le poți importa din nou. Un export complet poate conține și datele angajaților.

La un export pe perioadă, doar înregistrările de ture și cele de schimb de ture sunt limitate la perioada aleasă. Alte date, de exemplu datele de bază ale angajaților și setările, pot fi în continuare incluse integral.

Fișierul JSON nu este criptat. Pe Android alegi locația de stocare prin selectorul de fișiere al sistemului. Dacă pentru aceasta selectezi o aplicație cloud, de mesagerie sau o altă aplicație terță, furnizorul acesteia poate primi fișierul și îl poate prelucra conform propriilor condiții de confidențialitate. Furnizorul PURESHIFT nu primește nicio copie.

### 5.2 Export PDF

La crearea unui document PDF din datele tale despre ture, fișierul este generat local pe dispozitiv. Apoi îl poți distribui, tipări sau salva prin funcțiile sistemului. Dacă pentru aceasta selectezi o altă aplicație sau un serviciu extern, acesta prelucrează fișierul conform propriilor condiții de confidențialitate. Exportul PDF nu transmite nimic furnizorului PURESHIFT.

### 5.3 Distribuirea unui calendar

Funcția „Distribuie calendarul” creează local o imagine a calendarului tău de ture. Poți trimite apoi această imagine altor persoane sau aplicații prin funcția de distribuire a dispozitivului. Tu decizi cu cine o distribui.

### 5.4 Partajare prin Wi-Fi (sincronizare între dispozitive)

Aplicația oferă opțional „partajare prin Wi-Fi”. Dacă o activezi, Aplicația pornește pe dispozitivul tău un server local, accesibil în aceeași rețea locală. Un alt dispozitiv se poate asocia cu PIN-ul afișat și poate apoi prelua sau trimite datele Aplicației. În acest proces pot fi transferate toate datele Aplicației, inclusiv datele angajaților.

Te rugăm să reții:

- Partajarea prin Wi-Fi este dezactivată în mod implicit și este activată doar de tine.
- Transferul are loc în rețeaua locală prin HTTP și nu este criptat. Folosește funcția doar în rețele de încredere, nu în rețele Wi-Fi publice.
- Pentru sincronizare nu se folosește niciun server central al furnizorului.
- Dispozitivele asociate pot citi date.
- În mod implicit, operațiunile de scriere ale dispozitivelor asociate sunt acceptate fără confirmare suplimentară („Acceptă întotdeauna”, afișat în Aplicație ca „Immer akzeptieren”). Dacă dezactivezi această setare, operațiunile de scriere primite sunt respinse; nu se afișează nicio solicitare de confirmare.
- Dacă generezi un PIN nou, asocierile existente sunt revocate.
- Dezactivează partajarea prin Wi-Fi după utilizare.

## 6. Permisiuni și funcții de sistem

Aplicația folosește funcții de rețea și de sistem în următoarele scopuri:

- **Rețea:** pentru partajarea opțională prin Wi-Fi, pentru afișarea adresei rețelei locale și pentru deschiderea în browser a politicii de confidențialitate și a informațiilor legale la care trimite Aplicația
- **Vibrații:** pentru feedback în timpul utilizării
- **Funcții de fișiere și de distribuire:** pentru importul și exportul fișierelor de copie de rezervă și pentru distribuirea fișierelor PDF și de calendar. Pe Android alegi fișierele sau locațiile de stocare prin selectorul sistemului.

Aplicația nu folosește camera, microfonul, localizarea GPS sau contactele. Un loc de muncă sau o locație a unui angajat introdusă manual de tine nu este o localizare GPS. Aplicația nu trimite notificări push.

## 7. Copie de rezervă realizată de sistemul de operare (Android)

Aplicația Android este permisă pentru copiile de rezervă ale dispozitivului. Dacă copia de rezervă este activată pe dispozitivul tău sau în contul tău Google, datele Aplicației pot fi incluse automat într-o copie de rezervă Google. Aceasta poate include și date despre ture și angajați stocate local.

Dacă se efectuează o copie de rezervă depinde de Android și de setările dispozitivului și ale contului tău. Copia de rezervă este efectuată de Google, nu de furnizorul PURESHIFT. Se aplică informările de confidențialitate ale Google: https://policies.google.com/privacy

Dacă nu dorești o astfel de copie de rezervă, verifică și modifică setările de copie de rezervă ale dispozitivului și ale contului tău Google.

## 8. Fără servicii de analiză, urmărire sau publicitate

Aplicația nu conține servicii de analiză, urmărire, publicitate sau rețele sociale. Nu sunt colectați identificatori de dispozitiv în scopuri publicitare sau de analiză.

Pentru partajarea prin Wi-Fi, Aplicația folosește un identificator local al dispozitivului și tokenuri de acces pentru dispozitivele asociate. Aceste date servesc sincronizării în rețeaua locală și nu sunt transmise furnizorului.

## 9. Prelucrarea de către Google Play

Când descarci sau actualizezi Aplicația prin Google Play, Google prelucrează date în legătură cu funcționarea magazinului și punerea la dispoziție a Aplicației. Ce date sunt prelucrate depinde, printre altele, de contul tău Google, de dispozitivul tău și de setările tale.

Furnizorul PURESHIFT nu are nicio influență asupra acestei prelucrări. Se aplică informările de confidențialitate ale Google: https://policies.google.com/privacy

## 10. Accesarea acestei politici de confidențialitate și a informațiilor legale

Politica de confidențialitate și informațiile legale sunt găzduite pe GitHub. Când deschizi unul dintre aceste linkuri în Aplicație, pagina GitHub corespunzătoare este încărcată în browserul tău. În acest proces, GitHub primește date de conexiune necesare din punct de vedere tehnic, în special adresa ta IP. Se aplică informările de confidențialitate ale GitHub: https://docs.github.com/site-policy/privacy-policies/github-privacy-statement

## 11. Servicii de compilare și distribuție

Aplicația este dezvoltată cu Expo și creată și distribuită cu ajutorul Expo Application Services (EAS). Pentru compilare, Expo prelucrează date tehnice ale proiectului și ale compilării. Acestea trebuie deosebite de datele pe care le introduci în Aplicație.

În timpul funcționării, PURESHIFT nu transmite către Expo date introduse despre ture sau angajați.

## 12. Drepturile persoanelor vizate

Datele despre ture și angajați introduse în Aplicație sunt stocate local pe dispozitivul tău și nu sunt disponibile furnizorului printr-un server central. Furnizorul nu poate, așadar, să preia, să modifice sau să șteargă acest conținut local dintr-o bază de date centrală.

Aceasta nu înseamnă că drepturile față de entitățile care prelucrează efectiv datele dispar. Pentru datele pe care le transmiți prin copii de rezervă, linkuri externe sau aplicații terțe, sunt relevante entitățile implicate și informațiile lor privind confidențialitatea. Persoanele ale căror date le înregistrezi în Aplicație se adresează, pentru drepturile lor, entității responsabile pentru această prelucrare, de exemplu angajatorului lor.

Îți poți vizualiza, modifica și exporta datele locale în Aplicație. Prin dezinstalarea Aplicației, datele Aplicației stocate local sunt, în principiu, eliminate de pe dispozitiv. Fișierele de export, copiile de pe alte dispozitive și copiile de rezervă Android pot trebui șterse separat.

Ai, de asemenea, dreptul de a depune o plângere la o autoritate de supraveghere a protecției datelor.

## 13. Securitatea datelor

Aplicația își stochează datele în memoria internă a aplicației de pe dispozitiv. Aceasta este protejată de sistemul de operare împotriva accesului altor aplicații. Aplicația nu criptează suplimentar datele stocate.

Ești responsabil pentru protecția dispozitivului tău. Aceasta include în special blocarea dispozitivului, criptarea dispozitivului și actualizări software la zi. La utilizarea partajării prin Wi-Fi și la distribuirea fișierelor se aplică suplimentar indicațiile din secțiunea 5.

## 14. Copii

Aplicația nu se adresează copiilor sub 16 ani.

## 15. Modificări ale acestei politici de confidențialitate

Această politică de confidențialitate poate fi adaptată dacă se modifică Aplicația, prelucrarea datelor sau situația juridică. Versiunea actuală poate fi accesată prin linkul afișat în Aplicație și, după caz, în pagina din magazin.

## 16. Contact

Pentru întrebări privind protecția datelor, te rugăm să te adresezi la: NextExchangeStudio@proton.me
