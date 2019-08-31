## Informazioni generali

Il dump in formato CSV incluso in questa release contiene le informazioni relative alle release pubblicate fino ad oggi (2019-08-30) su TNTVillage. Le voci sono in ordine decrescente per data di creazione della release.
Nel dump NON è inclusa la descrizione testuale estesa delle release (corpo delle release).
Il file può essere consultato comodamente utilizzando LibreOffice Calc/Microsoft Excel/Google Spreadsheet. Il contenuto è leggibile tramite qualunque editor di testo che supporti file grandi.


## Legenda campi del file CSV

DATA: data in formato ISO 8601
HASH: info_hash codicato in esadecimale
TOPIC: ID numerico relativo alla discussione (forum TNTVillage)
POST: ID numerico relativo al messaggio (forum TNTVillage)
AUTORE: nome utente dell'autore della release
TITOLO: titolo della release
DESCRIZIONE: metadati relativi alla release
DIMENSIONE: dimensione complessiva dei file della release (in byte)
CATEGORIA: ID numerico relativo alla categoria della release


## Legenda ID categoria 

- 1  - Film TV e programmi
- 2  - Musica
- 3  - E Books
- 4  - Film
- 6  - Linux
- 7  - Anime
- 8  - Cartoni
- 9  - Macintosh
- 10 - Windows Software
- 11 - Pc Game
- 12 - Playstation
- 13 - Students Releases
- 14 - Documentari
- 21 - Video Musicali
- 22 - Sport
- 23 - Teatro
- 24 - Wrestling
- 25 - Varie
- 26 - Xbox
- 27 - Immagini sfondi
- 28  - Altri Giochi
- 29 - Serie TV
- 30 - Fumetteria
- 31 - Trash
- 32 - Nintendo
- 34 - A Book
- 35 - Podcast
- 36 - Edicola
- 37 - Mobile


## Informazioni URL release (forum TNTVillage)

Data una voce nel file CSV, tramite l'ID numerico incluso nel campo "TOPIC" è possibile risalire al corrispondente URL della release sul forum di TNTVillage.

*Esempio:* TOPIC -> 10965, URL release -> http://forum.tntvillage.scambioetico.org/index.php?showtopic=10965

In pratica è sufficiente inserire in coda all'URL di base l'ID numerico del "TOPIC".
URL di base: 

http://forum.tntvillage.scambioetico.org/index.php?showtopic=

Qualora il forum di TNTVillage dovesse risultare inaccessibile, è possibile consultare le pagine delle release utilizzando il servizio Wayback Machine offerto dall'Internet Archive: 

https://web.archive.org/

Dato un URL di una release sul forum di TNTVillage è possibile generare un URL valido per la Wayback Machine aggiungendo in testa ad esso la seguente stringa: https://web.archive.org/web/

*Esempio:*

*URL release:* http://forum.tntvillage.scambioetico.org/index.php?showtopic=10965

*URL Wayback Machine:* https://web.archive.org/web/http://forum.tntvillage.scambioetico.org/index.php?showtopic=10965


## Informazioni tecniche relative al file CSV

Il file CSV utilizza il carattere di virgola (,) come separatore.

Il carattere di terminazione di linea è quello standard UNIX (\n).

- Il carattere per il quoting è: ".
- Il carattere per l'escaping è: ".

Viene effettuato il quoting di tutti i campi non numerici.
