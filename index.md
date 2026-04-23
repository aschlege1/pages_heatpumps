# **Datenbasierter Überblick zu Wärmepumpen-Kenndaten**


## Wärmepumpen stehen im Zentrum der Wärmewende und sind eine Schlüsseltechnologie für die nachhaltige Gebäudetechnik. Doch wie schneiden die verfügbaren Modelle auf dem Markt hinsichtlich Effizienz, Einsatzbereich und Umweltverträglichkeit ab?

**Text** *: Prof. Dr. Manuel Lämmle und Leroy Tomás*

In diesem Beitrag werfen wir einen datenbasierten Blick auf die technischen Kenndaten von 2443 Wärmepumpenmodelle, die ein HeatPump Keymark-Zertifikat erhalten haben. Mit Hilfe detaillierter Auswertungen von Wirkungsgrad, Jahresarbeitszahl, Kältemittel, Geräuschemissionen und Einsatzmöglichkeiten entsteht ein umfassender Überblick über den aktuellen. Dieser liefert nicht nur repräsentative Werte, sondern bietet auch fundierte Einblicke für die Planung und Wärmepumpenauswahl.

## **Datengrundlage**

Die untersuchten Kennwerte stammen aus der Heat Pump KEYMARK-Datenbank, die alle zertifizierten Produkte enthält [(EHPA, 2025)](#quelle1). Das HP KEYMARK ist ein freiwilliges, unabhängiges europäisches Zertifizierungszeichen für Wärmepumpen, Kombinationswärmepumpen und Warmwasserbereiter. Es basiert auf unabhängigen Drittprüfungen und bestätigt die Einhaltung der Produktanforderungen gemäß den HP KEYMARK-Programmbestimmungen sowie der Effizienzanforderungen der Ökodesign-Richtlinien der EU nach Verordnung 813/2013 [(EU, 2013)](#quelle2).
Die Kennwerte auf den Datenblätter des HP KEYMARK-Zertifikat basieren auf mehreren europäischen Normen, insbesondere auf DIN EN 14511 hinsichtlich Prüfbedingungen für elektrisch angetriebene Wärmepumpen sowie DIN EN 14825 zu Prüfmethoden für die saisonale Energieeffizienz und Ökodesign-Richtlinien von Wärmeerzeuger. In der Regel wird bei den Datenblattangaben zwischen Low- und Medium-Temperaturanwendung unterschieden: dies entspricht einer Heizwasser-Temperatur von 35 °C, vergleichbar mit einer Fußbodenheizung, bzw. einer Heiztemperatur von 55 °C, wie typisch für eine Radiatorheizung. Eine detaillierte Beschreibung der Datenblatt-Kennwerte sind in der EU Verordnung zu finden [(EU, 2013)](#quelle2).
In Deutschland ist das HP KEYMARK-Zertifikat in der BAFA-Liste der förderfähigen Produkte enthalten, was bedeutet, dass Wärmepumpen mit diesem Zertifikat für staatliche Förderungen, wie das Marktanreizprogramm (MAP), anerkannt sind.

## **Datenübersicht**
Die einzelnen Datenblatt-Kennwerte wurde am 30.01.2025 heruntergeladen, per Webscraping konvertiert und als maschinenlesbarer Datensatz gespeichert. In der Datenbank befinden sich zum Zeitpunkt des Datenabrufs insgesamt 182 Hersteller aus 22 Ländern mit 2443 individuellen Wärmepumpen-Typen. Damit stellt der Artikel eine aktualisierte Auswertung der Arbeiten von [(Oltersdorf et al., 2022)](#quelle5) aus dem Jahr 2022 dar. 
Abbildung 1 zeigt drei Tortendiagramme, die eine erste Übersicht über die Daten liefern. China (17,6 %), Deutschland (16,8 %) und Frankreich (15,9 %) sind als Herstellerländer mit den meisten Wärmepumpen vertreten. Bezüglich der eingesetzten Kältemittel setzen mehr als die Hälfte R32 als Kältemittel ein, gefolgt von R410A und R290.  Zur besseren Übersicht der Wärmepumpengröße wurden die Wärmepumpen in unterschiedliche Kategorien entsprechend ihrer Heizleistung eingruppiert. In der Leistungsklasse 5-10 kWth liegt mit 43,7 % der Großteil der Wärmepumpen. Dagegen haben nur 11,2 % der zertifizierten Wärmepumpen eine Heizleistung von mehr als 20 kWth. Somit lässt sich festhalten, dass es bei kleineren und mittleren Wärmepumpen bis 20 kWth eine große Auswahl an Modellen gibt, während der Markt für Keymark-zertifizierte Wärmepumpen mit einer Leistung von > 20 kWth  übersichtlicher ist. 

<iframe src= "visualisation/Herstellerland1.html" width= "500px" height= "500px" style="border:none;">
</iframe> 

<iframe src= "visualisation/leistungsklasse1.html" width= "500px" height= "500px" style="border:none;">
</iframe> 

<iframe src= "visualisation/kaeltemittel1.html" width= "500px" height= "500px" style="border:none;">
</iframe> 
<!-- Warum sind die drei nicht gleich groß?-->
*Abbildung 1: Anteil von WP-Modellen nach Herstellerland, Kältemittel und Leistungsklasse*

Weitere Kategorien sind in Tabelle 1 zusammengefasst, jeweils unter Angabe der Anzahl an Wärmepumpen je Unterkategorie sowie der prozentuale Anteil. Daraus wird deutlich, dass 83 % aller Modelle Luft-Wasser-Wärmepumpen sind. Hinsichtlich der Bauweise werden 43 % als außenaufgestellter Monoblock-, 42 % als Split-, und 16 % als Innenaufstellte Geräte angeboten. 69 % aller Modelle sind reversibel betreibbar und können sowohl Heizen als auch Kühlen. 

<iframe src= "visualisation/tabelle1.html" width= "100%" height= "500px" style="border:none;">
</iframe> 

*Tabelle 1: Anzahl und prozentualer Anteil von Wärmepumpen-Modellen in unterschiedlichen Kategorien*

## **Leistung und Effizienz**
Die Leistung und Effizienz von Wärmepumpen werden in dem folgenden Abschnitt untersucht. Der SCOP (Seasonal Coefficient of Performance) gibt das Verhältnis von abgegebener Heizenergie zur aufgenommenen elektrischen Energie einer Wärmepumpe über eine Heizperiode unter realistischen, jahreszeitabhängigen Bedingungen an. Er ist damit ein geeigneter Kennwert um die Effizienzen der Wärmepumpen zu vergleichen.
Abbildung 1 zeigt die Saisonale Arbeitszahl SCOP in Abhängigkeit der Heizleistung jeweils bei einer Heiztemperatur von 35 °C, kategorisiert nach dem Wärmepumpen-Typ (Luft-Wasser-Wärmepumpe, Sole-Wasser und Wasser-Wasser-Wärmepumpe, und Sonstige Wärmepumpen). Brauchwasser-Wärmepumpen sind in der Übersicht nicht dargestellt, da für diese keine Nennleistung angegeben wird. Für eine bessere Darstellung der Heizleistung ist die x-Achse in logarithmischer Form aufgetragen. Zwischen dem SCOP und der Nennleistung ist kein direkter Zusammenhang feststellbar, d.h. die Effizienz ist in erster Linie unabhängig von der Wärmepumpen-Leistung. Jedoch zeichnet sich ab, dass Sole/Wasser und Wasser/Wasser-Wärmepumpen im Mittel deutlich effizienter sind als Luft-Wasser-Wärmepumpen. 

<iframe src= "visualisation/keymark_scop_scatterplot.html" width= "100%" height= "500px" style="border:none;">
</iframe> 

*Abbildung 2: Saisonale Arbeitszahl SCOP in Abhängigkeit der WP-Nennleistung bei einer Heiztemperatur von je 35 °C*

Dieser Zusammenhang wird genauer in Abbildung 3 analysiert, in der Boxplots der saisonalen Arbeitszahl, sowohl bei 35 °C (Low) und bei 55 °C (Medium), dargestellt ist. Hieraus wir ersichtlich, dass im Mittel die Sole-Wasser und Wasser-Wasser Wärmepumpen einen um 0,6 Punkte höheren SCOP als Luft-Wasser-Wärmepumpen erzielen. Der Vergleich der niedrigen und mittleren Heiztemperaturen in grün und orange verdeutlicht die Wichtigkeit von möglichst niedrigen Heiztemperaturen: eine Reduktion der Heizkreistemperaturen von 55 °C auf 35 °C erhöht den SCOP um 1,2 Punkte von 3,4 auf 4,6 bei Luft-Wasser-Wärmepumpen. Dies entspricht langjährigen Monitoring-Ergebnissen des Fraunhofer ISE von Wärmepumpenanlagen im Feld (Vergleiche z.B. [(Lämmle et al., 2023)](#quelle4) und [(Günther, 2025)](#quelle3)).

<iframe src= "visualisation/bild3_version3.html" width= "100%" height= "500px" style="border:none;">
</iframe> 

*Abbildung 3: SCOP bei 35°C und 55°C Heiztemperatur in Abhängigkeit von Wärmepumpen-Bauarten mit Angabe der Median-Werte*

Kennfelder der Arbeitszahl COP (Coefficient of Performance) in Abhängigkeit der Quell- und Heiztemperatur sind in Abbildung 4 dargestellt, wobei dabei nur Luftwärmepumpen betrachtet werden. Die Arbeitszahl wird standardmäßig bei den vier Luft-Außentemperaturen TLuft = -7 °C, 2 °C, 7 °C und 12 °C und bei zwei Heizungs-Vorlauftemperaturen TVL = 35°C und 55 °C charakterisiert. Die blauen und roten Punkte entsprechen jeweils denBetriebspunkten einer einzelnen Wärmepumpe. Durch die Ermittlung einer Regressionskurve können die mittleren COP-Kurven für Luftwärmepumpen in Abhängigkeit der Außentemperatur wie folgt berechnet werden:
COP (T_VL=35 °C)=4,14+0,226⋅T_Luft+0,0091⋅T_Luft^2
COP (T_VL=55 °C)=2,99+0,175⋅T_Luft+0,0079⋅T_Luft^2

<iframe src= "visualisation/bild4_cop_kennfelder.html" width= "100%" height= "500px" style="border:none;">
</iframe> 

*Abbildung 4: Durchschnittliche COP-Kennfelder von Luftwärmepumpen Regressionskurve und Vorhersageintervall mit einer 90%-Wahrscheinlichkeit*

## **Minimal- und Maximaltemperaturen**
Neben den Arbeitszahlen ist eine Betrachtung der Einsatztemperaturen von besonderem Interesse. Dazu wird auf Datenblättern die TOL (temperature operating limit) angegeben, die die Mindest-Außentemperatur beschreibt, ab der ein Wärmepumpenbetrieb möglich ist. Unterhalb der Temperatur schalten Wärmepumpen ab. 83 % Wärmepumpenmodellen geben eine Mindest-Außentemperatur von TOL = -10 °C an. Für Außentemperaturen von – 20 °C und noch geringer, sind 15 % der WP-Modelle geeignet. 
Insbesondere bei Bestandsgebäuden ist eine ausreichend hohe Heizungswasser-Vorlauftemperaturen entscheidend. Auf dem Datenblatt ist dies unter WTOL (water temperature operating limit) zu finden. Hierbei zeichnet sich ein deutlicher Einfluss des Kältemittels ab, bei dem die Temperatur des kritischen Punktes maßgeblich die maximalen Einsatztemperaturen beeinflusst. Abbildung 5 vergleicht die maximalen Vorlauftemperaturen in Abhängigkeit der vier häufigsten Kältemittel. Im Durchschnitt erreichen R290-Wärmepumpen mit dem Kältemittel Propan die höchsten Vorlauftemperaturen von 70 °C. Teilweise gibt es R290-Wärmepumpen, die sogar Heizungswasser-Vorlauftemperaturen bis zu 80 °C liefern. R32 und R407C mit einem Mittelwert von 60 °C, sowie R410A mit 65 °C sind demnach bei Anwendungsfällen mit höheren Temperaturanforderungen weniger geeignet. 

<iframe src= "visualisation/Abb5-roland-final.html" width= "100%" height= "500px" style="border:none;">
</iframe> 

*Abbildung 5: Maximale Heizungswasser-Vorlauftemperaturen (WTOL) bei unterschiedlichen Kältemittel*

## **Schallpegel**
Bei Wärmepumpen ist ebenfalls die Geräuschentwicklung von Interesse. Diese wird auf den Datenblättern getrennt nach Schalldruck innen und außen als gewichteter Schalldruckpegel in dB(A) ausgewiesen. Geprüft wird der Schalldruckpegel nach Norm DIN EN 12102-1, in der das Vorgehen zur Bestimmung des Schallleistungspegels von luftgekühlten Klimageräten, Wärmepumpen und Entfeuchtern festgelegt ist. Die Innenlautstärke wird dabei nur für Split- und innenaufgestellte Geräte ausgewiesen; die Außenlautstärke für alle WP-Typen.  Abbildung 6 zeigt die Verteilung der Schalldruckpegel, wobei der innere Schalldruckpegel mit einem Medianwert von 42 dB(A) deutlich geringer ausfällt als der äußere Schalldruckpegel mit 60 dB(A). Interessant ist auch die große Schwankungsbreite zwischen den Wärmepumpen-Modellen: vor allem die Schallbelastung außen zeigt eine große Spreizung mit Werten zwischen 35 dB(A) und 95 dB(A). 

<iframe src= "visualisation/boxplot_schall_neu1.html" width= "100%" height= "500px" style="border:none;">
</iframe>

*Abbildung 6: Schalldruckpegel Innen und Außen in dB(A) mit Median.*

Tabelle 2 fasst die wichtigsten Leistungs-, Schall- und Temperaturwerte mit Minimal -und Maximalwerten sowie den Werten des 1., 2. und 3 Quantils zusammen. Die Tabelle erlaubt damit, einzelne WP-Modelle hinsichtlich ihrer Leistung in die Gesamtschau von Wärmepumpen einzugruppieren und ist somit besonders für potentielle Wärmepumpen-Käufer, Fachplaner und Installateure und relevant.

<iframe src= "visualisation/tabelle2_statistik.html" width= "100%" height= "500px" style="border:none;">
</iframe>

*Tabelle 2: Statistische Übersicht der wichtigsten Kenngrößen mit Mittelwert, Minimal- und Maximalwerten und drei Quartile*

## **Entwicklungstrends**
Unter Berücksichtigung des Zertifizierungsdatums lassen sich Entwicklungstrends identizieren. Aufgrund der F-Gas-Verordnung der Europäischen Union sind Wärmepumpenhersteller verpflichtet, die Menge klimaschädlicher fluorierter Kältemittel (F-Gase) zu reduzieren. Dies fördert den Trend zu Niedrig-GWP-Kältemitteln, insbesondere R32 mit einem GWP von 675 und R290 (Propan) mit einem GWP von 3. Im Jahr 2016 und 2017 setzen über 80 % der Wärmepumpen das Kältemittel R410A (GWP = 2088) ein. Seit 2018 gewinnt R32 an Bedeutung und erreicht 2021 einen Höchstanteil von 79 %. Ab 2022 stieg der Anteil von R290 kontinuierlich an und liegt 2024 bei 38 %.

<iframe src= "visualisation/Zertifizierung1.html" width= "100%" height= "500px" style="border:none;">
</iframe>

*Abbildung 7: Entwicklungstrends und Anteile Kältemittel*

Hinsichtlich der Leistungsdaten sind nur geringfügige Veränderungen über die Jahre festzustellen. Die saisonale Effizienz SCOP bei einer Heiztemperatur von 35 °C steigt im Mittel von 4,62 im Jahr 2017 auf 4,75 im Jahr 2024. Dies entspricht einer Effizienzsteigerung von ca. 3 %. Bei einer Heiztemperatur von 55 %, sowie bei den COP-Nennwerten sind die Veränderungen in einer ähnlichen Liga.  Lediglich bei den maximalen Vorlauftemperaturen ist ein klarer Trend zu höheren Temperaturen festzustellen (2017: 57 °C, 2024: 62 °C). Dies ist u.a. auf die größere Verbreitung von R290 zurückzuführen.
Es sei darauf hingewiesen, dass die Auswertung auf dem aktuellen Stand der Keymark-Datenbank basiert. Kennwerte von Modellen, die nicht mehr in der Datenbank geführt werden, liegen nicht vor. Außerdem umfassen die Jahre 2016–2018 nur wenige Modelle. Beide Effekte können zu leichten Verzerrungen der Darstellung führen. Zudem werden keine Marktanteile dargestellt, sondern lediglich die jährlichen Zertifizierungen zusammengefasst.

## **Zusammenfassung**
Die vorliegende datenbasierten und statistischen Auswertung der zertifizierten Wärmepumpen-Modelle der Heat Pump Keymark-Datenbank zeichnet ein detailliertes Bild des aktuellen Stands der Wärmepumpentechnologie. In einem dynamischen Wärmepumpenmarkt ist es so möglich, Wärmepumpen im Vergleich zum Marktumfeld hinsichtlich Leistungsdaten, Temperaturwerte und Schallemissionen einzuordnen und zu vergleichen. Außerdem lässt sich der Trend zum natürlichen Kältemittel Propan sowie zu höheren Vorlauftemperaturen identifizieren. 
Die Auswertung stellt jedoch nur ein aktueller Ausschnitt der zertifizierten Wärmepumpen-Modelle dar. Sie ist nicht repräsentativ mit den installierten Modellen, da hierfür keine Marktdaten vorliegen. Für zukünftige Auswertungen wäre denkbar, die Keymark-Datenbank mit weiteren Datensätze zu kombinieren, wie zum Beispiel Listenpreisen, um damit ein besseres Verständnis des Zusammenhangs von Leistungsdaten und Preisen und zu bekommen. 

---
## Literatur
<a id="quelle1"> </a> [1] EHPA, 2025. Heat Pump KEYMARK [WWW Document]. URL https://keymark.eu/en/products/heatpumps/heat-pumps (accessed 2.13.25).  
<a id="quelle2"> </a> [2] EU, 2013. Commission Regulation (EU) No 813/2013 of 2 August 2013 implementing Directive 2009/125/EC of the European Parliament and of the Council with regard to ecodesign requirements for space heaters and combination heatersText with EEA relevance.  
<a id="quelle3"> </a> [3] Günther, D., 2025. WP-QS im Bestand – Entwicklung optimierter Versorgungskonzepte und nachhaltiger Qualitätssicherungsmaßnahmen für Wärmepumpen im EFH-Bestand - Fraunhofer ISE [WWW Document]. Fraunhofer-Inst. Für Solare Energiesysteme ISE. URL https://www.ise.fraunhofer.de/de/forschungsprojekte/wp-qs-im-bestand.html (accessed 2.13.25).  
<a id="quelle4"> </a> [4] Lämmle, M., Metz, J., Kropp, M., Wapler, J., Oltersdorf, T., Günther, D., Herkel, S., Bongs, C., 2023. Heat Pump Systems in Existing Multifamily Buildings: A Meta‐Analysis of Field Measurement Data Focusing on the Relationship of Temperature and Performance of Heat Pump Systems. Energy Technol. 11, 1–12. https://doi.org/10.1002/ente.202300379  
<a id="quelle5"> </a> [5] Oltersdorf, T., Nienborg, B., Fugmann, H., Miara, M., 2022. Stand der Technk von Haushaltswärmepumpen in Europa - Eine Breitenanalyse. DKV Jahrestag. Magdebg.

---

<img src="visualisation/Images/manuel_Laemmle.jpg" width= "200" height="200" >

*Quelle: HS Offenburg*

Manuel Lämmle ist seit 2023 Professor für Energieinformatik an der Hochschule Offenburg und leitet die Forschungsgruppe „Energieeffiziente Gebäudetechnik“. Zuvor forschte er am Fraunhofer ISE und an der Universität Freiburg an smarten Energiekonzepten für Gebäude und Quartiere. 

<img src="visualisation/Images/leroy_Tomás.png" width= "200" height="200" >

*Quelle: HS Offenburg*


Leroy Tomás ist seit 2020 wissenschaftlicher Mitarbeiter am Institut für nachhaltige Energiesysteme und studierte zuvor Erneuerbare Energien und Daten Engineering an der Hochschule Offenburg.