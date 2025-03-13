# Dokument zahteva - Sistem elektronskog glasanja i direktne demokratije

Ovaj dokument sadrži sumirane zahteve i ideje iznete u okviru diskusije na Discord serveru IT Srbija u vezi sa elektronskim glasanjem i implementacijom direktne demokratije kroz postojeći izborni sistem u Srbiji.

## 1. Opšti zahtevi
- Sistem treba da omogući direktno demokratsko odlučivanje unutar postojeće zakonske regulative (bez potrebe za izmenom zakona).
- Primena sistema kroz osnivanje specijalizovane političke stranke koja statutom reguliše obavezno glasanje predstavnika prema odluci članova.

## 2. Zahtevi za sigurnost i transparentnost
- Implementacija zero-trust principa glasanja (niko nema privilegovan pristup podacima).
- Upotreba blockchain tehnologije za čuvanje glasova kako bi se garantovala transparentnost i nemogućnost izmene rezultata.
- Sistem mora biti open-source (kako bi se mogao nezavisno proveriti).
- „Receipt-free“ glasanje: onemogućavanje generisanja dokaza glasačke namere pojedincima (sprečavanje prinude i trgovine glasovima).

## 3. Zahtevi za privatnost
- Glasanje mora biti anonimno: identitet glasača ne sme biti povezan sa sadržajem glasa.
- Glasovi se beleže na način koji omogućava anonimno brojanje glasova (homomorfna enkripcija).
- Biračima omogućiti proveru da li je njihov glas registrovan bez otkrivanja sadržaja glasa (zero-knowledge ili zero-knowledge proof).

## 4. Sprečavanje zloupotreba i „bugarskog voza“
- Osigurati identitet birača kroz kombinaciju digitalne lične karte i biometrijske autentifikacije (npr. otisak prsta).
- Omogućiti glasanje na namenskom hardveru (poput bankomata), uz biometrijsku proveru identiteta.
- Sistem mora imati mogućnost da proveri status birača (npr. da li je birač živ, ima li pravo glasa).

## 5. Sprečavanje prinude i kupovine glasova
- Implementacija mehanizma koji sprečava dokazivanje glasačke namere (receipt-free glasanje).
- Mogućnost višestrukog glasanja (revote) do krajnjeg trenutka zatvaranja glasanja (sprečavanje kupovine i prinude).
- Postojanje "prinudnog glasa" (duress PIN), gde se pod prinudom šalje glas koji je automatski označen ili naknadno poništen.

## 6. Autentifikacija birača
- Digitalna autentifikacija uz pomoć pametne lične karte ili digitalnog ID-ja.
- Dvostruka evidencija glasanja: jedna potvrđuje činjenicu glasanja (odvojeno od identiteta i sadržaja glasa), a druga beleži anonimizovane glasove za prebrojavanje.

## 7. Transparentnost rezultata
- Javna dostupnost kriptovanih rezultata glasanja.
- Nezavisne provere integriteta rezultata (bilo koji građanin ili institucija može nezavisno proveriti tačnost ukupnih rezultata).

## 8. Dodatne tehničke preporuke
- Platforma mora imati visok nivo zaštite od cyber-napada.
- Mora se sprečiti mogućnost dokazivanja glasanja trećoj strani nakon glasanja.
- Obezbeđenje fizičke infrastrukture koja garantuje sigurnost uređaja i procesa.

## 9. Predlozi za naziv stranke (do sada izneti)
- "Direktna Demokratija"
- "Stranka Studenata"
- "Res publica – javna stvar"

## 10. Sledeći koraci
- Prikupljanje dodatnih predloga za naziv stranke.
- Glasanje zajednice o konačnom radnom nazivu.
- Formiranje radnih grupa za tehničku realizaciju predloženog sistema.

Ovaj dokument je radna verzija i otvoren je za dodatne sugestije i promene.

