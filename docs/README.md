# Metadatenprofile für Testaufgaben: Fremdsprachen Sek I
```
en1fr1
```

Autor/Organisation: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Fremdsprachen Sek I - Aufgabe"
```
https://raw.githubusercontent.com/iqb-vocabs/p52/master/unit.json
```

### Stimulus

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Niveaustufe GER Stimulus | [Vokabular](https://w3id.org/iqb/v26/ng/) | url: 'https://w3id.org/iqb/v26/ng/', Einmalauswahl, verberge Nummerierung | e2 |
| Syntaxkomplexität | [Vokabular](https://w3id.org/iqb/v25/sy/) | url: 'https://w3id.org/iqb/v25/sy/', Einmalauswahl, verberge Nummerierung | e3 |
| Abstraktionsgrad | [Vokabular](https://w3id.org/iqb/v25/ta/) | url: 'https://w3id.org/iqb/v25/ta/', Einmalauswahl, verberge Nummerierung | e4 |
| Stimulussorte | [Vokabular](https://w3id.org/iqb/v25/te/) | url: 'https://w3id.org/iqb/v25/te/', Mehrfachauswahl, verberge Nummerierung | e5 |
| Thema | [Vokabular](https://w3id.org/iqb/v25/th/) | url: 'https://w3id.org/iqb/v25/th/', Mehrfachauswahl, verberge Nummerierung | e6 |
| Vokabular | [Vokabular](https://w3id.org/iqb/v25/vf/) | url: 'https://w3id.org/iqb/v25/vf/', Einmalauswahl, verberge Nummerierung | e7 |
| Quellenangaben | Text |Mehrzeilig, Sprache(n): de | iqb_copyright |
| Stimuluszeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
### Hörsequenz

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Anzahl Sprecher:innen | Zahl |Kommastellen: 0, Mindestwert: 1, Maximalwert: kein | k2 |
| Nebengeräusche | Ja/Nein |Text für WAHR: störend, Text für FALSCH: nicht relevant | k3 |
| Sprechtempo | [Vokabular](https://w3id.org/iqb/v25/sp/) | url: 'https://w3id.org/iqb/v25/sp/', Einmalauswahl, verberge Nummerierung | k4 |
| Transkript | Text |Mehrzeilig, Sprache(n): de | iqb_transcript |
## Profil "IQB Fremdsprachen Sek I - Item"
```
https://raw.githubusercontent.com/iqb-vocabs/p52/master/item.json
```

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Lese-/Hörstil | [Vokabular](https://w3id.org/iqb/v26/lh/) | url: 'https://w3id.org/iqb/v26/lh/', Einmalauswahl, verberge Nummerierung | w8 |
| Geschätzte Niveaustufe GER | [Vokabular](https://w3id.org/iqb/v26/ng/) | url: 'https://w3id.org/iqb/v26/ng/', Einmalauswahl, verberge Nummerierung | s8 |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/fr/) | url: 'https://w3id.org/iqb/v27/fr/', Einmalauswahl, verberge Nummerierung | s3 |
| Funktionale kommunikative Kompetenz | [Vokabular](https://w3id.org/iqb/v56/fm/) | url: 'https://w3id.org/iqb/v56/fm/', Mehrfachauswahl, Zeige nur erste 2 Ebenen | s4 |
| Itemzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |
