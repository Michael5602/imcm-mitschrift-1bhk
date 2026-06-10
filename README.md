# IMCM-Mitschrift der 1bhk

Das ist das Readme.mg File unseres Reposetories
Die Dateieendung steht für ein Markdown - eine heute sehr weit verbreitet [Auszeichnungsprache](https://de.wikipedia.org/wiki/Auszeichnungssprache)
Weiter Auszeichnungssprachen sind:

- Hypertext Markup Language (HTML)
- Extensible Markup language (XML)
- Yet Anoter MArkup Language (YAML, YML)

> **Achtung!**
> Die Abkürzung Ml steht nicht immer für Markup Language , sie kann auch _Maschine Learning_ heißen.

## Playlist zur Funktionsweise des Internets

### Teil-1 What is the Internet

- das Internet wurde in den 1970er-Jahren entwickelt
- Motivation schaffung eines Dezentralen Netzwerkes (Kalter Krieg)
- Funktionsweise: Paketvermittlung (_Packet Switching_) Nachrichten werden in kleine Pakete aufgeteilt und unabhängig verschickt.
- Internet ist das Netz der Netze besteht aus vielen kleineren Netzen unterschiedlicher Internet anbiebeter (_Internet Service Provider ISP_) Salzburg Ag, Magenta, A1

### Teil-2 The Internet: Wires , Cables and Wifi.

Informationen werden im Internet als Bits übertragen.
Bits haben 2 werte 0 und 1, 8bits = 1byte
1byte = 256 verschiedene Werte (2 8)

Bits können über verschiedene Übertragunsmedien zwischen Computern versendet werden. Die Anzahl der Bits pro Sekunde wird als **Bandbreite** bezeichnet.
Bei einer bandbreite von 300 Mbts/s können 300 Millionen Bit über die Leitung laufen.
Übertragungsmedien:

1. Kupferdraht (**Ethernet**)

- billig
- einfache verarbeitung
- weit verbreitet
- hohe verluste mittlerdistanzen (100m)

**2. Licht / Glasfaserkabel**

- extrem schnell
- verlustfrei
- teuer und schwierige Verarbeitung
- geeignet für den Ozean

**3. Funk / Radiowellen**

- hoher Komfort, Internet übrall

### Teil-3 The Internet: IP

- Protkolle sind die Regeln der Komukation
- eines der wichtisten Protokolle ist die IP
- jedes Gerät im Internet hat zumindest eine IP
- das Domain Name System (Dns)
- Dns-Server führen Tabellen mit Domainamen und den etsprechenden Ip-Addressen

### Teil-4 Zuverlässigkeit

- über das Internet versendete Pakete werden in Pakete aufgeteilt.
- einzelne Pakete haben eine größen von c.a. 1,5 kB. D.h. ein Foto von 10 MB wird in c.a. 6600 Pakete aufgeteilt bevor es versendet wird.
- Pakete können unterschiedliche Routen nehmen die Route wird je nach Auslastung, Stöhrungen etc. durch spizelle Computer-die Router.
- dynamisch bestimmt.
- Jedes Paket enthält die Quell und Ziel Ip Addresse sowie eine eindeutige Paketnummer (_Transmision Control Protocol TCP_) kontrolliert das wenn was fehlt fordert es es nochmal an.
- TCP und ICP bilden das Rückrad des Internets TCP/ICP Stack.
- [TCP Modell](/assets/https___miro.medium.com_v2_resize_fit_720_format_webp_1_g1GzSjM5-J3aN2wjVz6qKA.png)

### Teil 5 HTTP HTML

- HTTP steht für hyper text tranfer Protocol
  nach dem Client sever Prinzip: - ein web client sendet eine request an einen web sever - der Web sever verarbeitet die anfragen und sendet eine Atwort zurück. Die Antwort enthält u.a einen sogenannten [Statuscode](https://de.wikipedia.org/wiki/HTTP-Statuscode)
  der Auskunft über die Verarbeitung der Anfrage gibt.

#### HTTP-Statuscode

- **1xx** - die Anfrage dauert noch
- **2xx** - die Anfrage war erfolgreich
- **3xx** - Um oder Weiterleitung
- **4xx** - Clientfehler (z.b. 404 - Page not found)
- **5xx** - Serverfehler 🥸🦓🐽🐚🪱👀🗣️

- HTTp Anfragen werden immer mit einer Methode übertragen
- Daten werden mit Get Fragen angefordert
- User Eingaben (z.b. Datei uploads..) werden mit post anfragen verschlüsselt.
- es gibt auch andere HTTP METHODEN die lernen wir aber später.
- HTTP können auch cookies enthalten (text datein die aus Schlüssel werte Paaren bestehen) sie werden bei jeder anfrage mitgesendet und ermöglichen so die identifikation.

### Teil-8 The Internet: How Search Works

- Such maschienen Bots durchstreifen ständig das www und katalogisiren Webseiten. Der entstehende Katalog wird auch Index gennant.
- Wenn wir einen suchbegriff suchen dan wird der (_Index_) durchsucht.
- Suchergebnisse werden auf Basis eines (Geheimen) Algoryhtmus geranked Ergbnisse die weiter oben stehen werden öfter, angeklickt.
- Einfluss auf das Ranking haben unteranderm:
  - im text vorkommende suchbegriffe (_Keywords_)
  - Wie viele links auf die Webseite gehen. (_Backlinks_)
- die suchergebnisse werden an die sucher angepasst! nicht jeder bekommt das gleiche zu sehen selbst wenn man das selbe sucht.
- [Startpage]()ist eine daten sparsame suchmaschiene, die Ihre Benutzer die verwendung von Google ohne Tracking oder Personalisirung erlaubt.
