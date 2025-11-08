#Grundlagen Ein ABAP-Funktionspool ist ein spezieller ABAP-Programmtyp, der zur Kapselung wiederverwendbarer Prozeduren, sogenannter Funktionsbausteine, entwickelt wurde. Funktionsbausteine ​​ermöglichen eine gewisse Kapselung der Geschäftslogik und somit deren Wiederverwendung in verschiedenen Anwendungen innerhalb des SAP-Systems. Jeder Funktionspool ist mit einer Funktionsgruppe verknüpft, die verwandte Funktionsbausteine ​​enthält. Diese Struktur trägt zur Modularität und besseren Lesbarkeit des Codes bei.

Funktionspools zeichnen sich dadurch aus, dass sie globale Datendeklarationen verwalten, auf die alle Funktionsbausteine ​​innerhalb derselben Gruppe zugreifen können. Dadurch wird der Datenaustausch zwischen Funktionsbausteinen ermöglicht und Redundanzen werden reduziert. Funktionsbausteine ​​innerhalb eines Pools können sowohl remote (RFC) als auch lokal aufgerufen werden.

RFCs werden auch zukünftig in hybriden Systemlandschaften oder für schrittweise Datenmigrationen relevant bleiben. SAP konzentriert sich jedoch zunehmend auf moderne API-Technologien und ereignisgesteuerte Architekturen.


#### Useful Links
- #Article [Funktionsbausteine](https://help.sap.com/doc/saphelp_nw73ehp1/7.31.19/de-de/d1/801ea7454211d189710000e8322d00/content.htm?no_cache=true)
- #Article [Definition Funktionsbausteine](https://help.sap.com/doc/abapdocu_752_index_htm/7.52/de-de/abenabap_functions.htm)
- #Article [Funktion Gruppen](https://help.sap.com/doc/saphelp_snc700_ehp01/7.0.1/de-de/9f/db992335c111d1829f0000e829fbfe/content.htm?no_cache=true)
- #Article [RFC Funktionsbausteine](https://help.sap.com/docs/SAP_NETWEAVER_700/108f625f6c53101491e88dc4cf51a6cc/48920827feb35ed2e10000000a42189d.html?locale=de-DE)
- #Article [Verschiednene Typen von RFC-Aufrufen](https://community.sap.com/t5/application-development-and-automation-blog-posts/understanding-different-types-of-rfc-calls-in-sap-abap/ba-p/13745585)

