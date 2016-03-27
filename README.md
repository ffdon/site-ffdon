gluon-config

 Community: www.freifunk-donau-ries.de
 
 aktuell verwendeter Gluon-Branch: v2015.1

 1st image run: gluon-ffdon-0.6+exp20160207 von user da

Testlauf gluon-ffdon-0.6.0a+exp2016032701 --> original kopiert, make -j1 GLUON_TARGET=ar71xx-generic
--> Ohne Fehler durchgelaufen

Testlauf gluon-ffdon-0.6.0b+exp2016032702 --> make dirclean, make -j1 GLUON_TARGET=ar71xx-generic
--> ungetestet

Testlauf gluon-ffdon-0.6.0c+exp2016032703 --> make update, make dirclean, make -j1 GLUON_TARGET=ar71xx-generic
--> Ohne Fehler durchgelaufen

--> Wo liegt der Unterschied zu dem risch gezogenen Branch
--> dort scheitert das backen


Testlauf gluon-ffdon-0.6.1d+exp2016032801
jetzt mit angepasster Site:
- Versionsnummer
- ohne Französisch
- ohne Englisch
- auf Donau-Ries angepasstem Txt
- evtl. mit Signatur --> https://www.youtube.com/watch?v=0yw8fHd8Ed8
durch
- clonen des Verzeichnisses mgk@gw01:~/ffdon-makegluon/gluon-ffdon-0.6.1d+exp2016032801$
- git clone https://github.com/ffdon/site-ffdon.git site
- make update
- make dirclean
- make -j1 GLUON_TARGET=ar71xx-generic
- 
