# Metadatenprofile für Testaufgaben: Mathematik Primar

ID of profile-store: `1map`

Creator: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Mathematik Primar - Aufgabe"

ID of profile: [https://raw.githubusercontent.com/iqb-vocabs/p111/master/unit.json](https://raw.githubusercontent.com/iqb-vocabs/p111/master/unit.json)

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Entwickler:in | Text | Einzeilig, Sprache(n): de   | iqb_author |
| Klassenstufe | [Vokabular](http://w3id.org/openeduhub/vocabs/educationalLevel/) | url: 'http://w3id.org/openeduhub/vocabs/educationalLevel/', Mehrfachauswahl, Dialogbox, Nummerierung unterdrückt | f0 |
| Für SPF geeignet | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | a1 |
| Kopfhörereinsatz | [Vokabular](https://w3id.org/iqb/v24/kh/) | url: 'https://w3id.org/iqb/v24/kh/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | iqb_phones |
| Leitidee | [Vokabular](https://w3id.org/iqb/v10/i1/) | url: 'https://w3id.org/iqb/v10/i1/', Einmalauswahl, Zeige nur erste Ebene, Dialogbox | w8 |
| Aufgabenzeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Stimuluszeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Quellenangaben | Text | Mehrzeilig, Sprache(n): de   | iqb_copyright |
| Unverträgliche Aufgaben | Text | Einzeilig, Sprache(n): de   | iqb_compatibility |

## Profil "IQB Mathematik Primar - Item"

ID of profile: [https://raw.githubusercontent.com/iqb-vocabs/p111/master/item.json](https://raw.githubusercontent.com/iqb-vocabs/p111/master/item.json)

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/mp/) | url: 'https://w3id.org/iqb/v27/mp/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | s3 |
| Anforderungsbereich | [Vokabular](https://w3id.org/iqb/v10/a1/) | url: 'https://w3id.org/iqb/v10/a1/', Einmalauswahl, Dialogbox, Nummerierung unterdrückt | s4 |
| Inhaltsbezogener Bildungsstandard primär | [Vokabular](https://w3id.org/iqb/v10/i1/) | url: 'https://w3id.org/iqb/v10/i1/', Einmalauswahl, Dialogbox | s7 |
| Inhaltsbezogener Bildungsstandard sekundär | [Vokabular](https://w3id.org/iqb/v10/i1/) | url: 'https://w3id.org/iqb/v10/i1/', Mehrfachauswahl, Dialogbox | s8 |
| Prozessbezogener Bildungsstandard primär | [Vokabular](https://w3id.org/iqb/v10/p1/) | url: 'https://w3id.org/iqb/v10/p1/', Einmalauswahl, Dialogbox | s5 |
| Prozessbezogener Bildungsstandard sekundär | [Vokabular](https://w3id.org/iqb/v10/p1/) | url: 'https://w3id.org/iqb/v10/p1/', Mehrfachauswahl, Dialogbox | s6 |
| Itemzeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |
| Geschätzte Schwierigkeit | [Vokabular](https://w3id.org/iqb/v26/ea/) | url: 'https://w3id.org/iqb/v26/ea/', Einmalauswahl, Dialogbox | e4 |
| Technische Besonderheiten der Antwortoptionen | [Vokabular](https://w3id.org/iqb/v27/ti/) | url: 'https://w3id.org/iqb/v27/ti/', Mehrfachauswahl, Dialogbox | iqb_itemtech |

