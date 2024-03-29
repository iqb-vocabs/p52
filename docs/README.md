# Metadatenprofile für Testaufgaben: Französisch Sek I

ID of profile-store: `frs1`

Autor/Organisation: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Französisch Sek I - Aufgabe"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p52/master/unit.json`

### Stimulus

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Textniveau (GeR) | [Vokabular](https://w3id.org/iqb/v26/ng/) | url: 'https://w3id.org/iqb/v26/ng/', Einmalauswahl, verberge Nummerierung | e2 |
| Textkomplexität: Lexiko-Grammatik | [Vokabular](https://w3id.org/iqb/v25/le/) | url: 'https://w3id.org/iqb/v25/le/', Einmalauswahl, verberge Nummerierung | e3 |
| Textkomplexität: Abstraktionsgrad | [Vokabular](https://w3id.org/iqb/v25/ta/) | url: 'https://w3id.org/iqb/v25/ta/', Einmalauswahl, verberge Nummerierung | e4 |
| Textkomplexität: Thematischer Vertrautheitsgrad | [Vokabular](https://w3id.org/iqb/v25/ve/) | url: 'https://w3id.org/iqb/v25/ve/', Einmalauswahl, verberge Nummerierung | e5 |
| Textsorte | [Vokabular](https://w3id.org/iqb/v25/te/) | url: 'https://w3id.org/iqb/v25/te/', Einmalauswahl, verberge Nummerierung | e6 |
| Andere Textsorte | Text |Einzeilig, Sprache(n): de | iqb_other_text_type |
| Thema | [Vokabular](https://w3id.org/iqb/v25/th/) | url: 'https://w3id.org/iqb/v25/th/', Einmalauswahl, verberge Nummerierung | e7 |
| Anderes Thema | Text |Einzeilig, Sprache(n): de | iqb_other_topic |
| Länge des verwendeten Audioauszugs | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Wortanzahl | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein | iqb_word_count |
| Aufgabenzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |

### Quellenangaben

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Vermerk / Zitation | Text |Mehrzeilig, Sprache(n): de | iqb_copyright_citation |
| Transkript Original / Text Original | Text |Mehrzeilig, Sprache(n): de | iqb_copyright_original |

### Hörsequenz

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Sprecheranzahl / Sprechermerkmale | Text |Einzeilig, Sprache(n): de | k2 |
| Sprechtempo | [Vokabular](https://w3id.org/iqb/v25/sp/) | url: 'https://w3id.org/iqb/v25/sp/', Einmalauswahl, verberge Nummerierung | k3 |
| Varianten | [Vokabular](https://w3id.org/iqb/v25/fv/) | url: 'https://w3id.org/iqb/v25/fv/', Einmalauswahl, verberge Nummerierung | k4 |
| Nebengeräusche | [Vokabular](https://w3id.org/iqb/v25/ne/) | url: 'https://w3id.org/iqb/v25/ne/', Einmalauswahl, verberge Nummerierung | k5 |
| Transkript zur Aufgabe | Text |Mehrzeilig, Sprache(n): de | iqb_final_transcript |

## Profil "IQB Französisch Sek I - Item"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p52/master/item.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Lese-/Hörstil | [Vokabular](https://w3id.org/iqb/v26/lh/) | url: 'https://w3id.org/iqb/v26/lh/', Einmalauswahl, verberge Nummerierung | w8 |
| Geschätzte GeR Niveaustufe (a priori) | [Vokabular](https://w3id.org/iqb/v26/ng/) | url: 'https://w3id.org/iqb/v26/ng/', Einmalauswahl, verberge Nummerierung | s8 |
| Empirisch ermittelte GeR Niveaustufe | [Vokabular](https://w3id.org/iqb/v26/nb/) | url: 'https://w3id.org/iqb/v26/nb/', Einmalauswahl, verberge Nummerierung | s9 |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/ff/) | url: 'https://w3id.org/iqb/v27/ff/', Einmalauswahl, verberge Nummerierung | s3 |
| Bildungsstandards ESA | [Vokabular](https://w3id.org/iqb/v56/fe/) | url: 'https://w3id.org/iqb/v56/fe/', Mehrfachauswahl, Zeige nur erste 2 Ebenen, verberge Nummerierung | s4 |
| Bildungsstandards MSA | [Vokabular](https://w3id.org/iqb/v56/fm/) | url: 'https://w3id.org/iqb/v56/fm/', Mehrfachauswahl, Zeige nur erste 2 Ebenen, verberge Nummerierung | s5 |
| Itemzeit | Zahl |Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |

