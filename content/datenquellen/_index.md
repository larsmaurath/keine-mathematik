---
date: "2016-11-06T13:00:25+05:30"
title: Datenquellen
---

***

Die größte Hürde für die ersten Schritte in der Fußballanalytik ist die Suche nach Datensätzen. Hier gibt es keinen Unterschied zwischen datenbasierter Analytik oder mehr qualitativen Herangehensweisen wie z.B. durch Videoanalyse. Für Hobbyanalysten ist es genauso schwer an Videomaterial ganzer Spiele im Weitwinkelformat zu kommen wie an Eventdatensätze. 

Durch einen größeren Fokus auf Daten und eine Vielzahl von neuen Unternehmen hat sich in dieser Hinsicht viel in den letzten Jahren getan. Dank Datenprovidern wie Statsbomb und Metrica Sports gibt es nun frei verfügbare Event- und Trackingdatensätze. Webseiten wie Transfermarkt.de und FBRef.com veröffentlichen verlässlich eine Vielzahl von Informationen die als Grundlage für verschiedene Projekte dienen können.

Dieser Artikel versucht eine Liste von frei verfügbaren Datensätzen zu sammeln um Interessierten den Einstieg zu erleichtern. Falls du einen Vorschlag hast der unten noch nicht aufgeführt ist lass es uns gerne [wissen](https://www.keinemathematik.de/contact/).

***

# [ClubElo](http://clubelo.com/)

Die Webseite clubelo.com hat sich einem, auf den ersten Blick, simplen Ziel verschrieben: eine Rangliste internationaler Klubs. Wohlgemerkt außerhalb jeglicher Ligenzugehörigkeit oder internationaler Wettbewerbe wie die Champions League. Dazu haben sich die Macher von der Elo-Methode aus der Welt des Schachs inspirieren lassen. Dort ermöglicht das Rating Spieler ähnlichen Levels in Turnieren gegeneinander anzusetzen. 

Da das Club Elo-Rating lediglich auf historischen Ergebnissen basiert ist es nicht sehr datenhungrig und kann daher auf eine große Anzahl von Ligen angewandt werden (präzisere Eventdatansätze sind oftmals nur für die großen fünf Ligen verfügbar).

Die Macher von Club Elo präsentieren unter anderem zwei Anwendungsgebiete ihres Ratings. Für zukünftige Spiele berechnen sie Wahrscheinlichkeiten für Heimsieg, Unentschieden und Auswärtssieg. Für individuelle Vereine produzieren sie Historien des Elo-Ratings bei Trainer und unterstreichen so deren Einfluss auf die Mannschaftsstärke.

Ein offensichtlicher Nachteil des Elo-Ratings ist, dass es nur auf historischen Daten basiert und so von Natur aus nicht vorausschauend ist. Ein Spitzentransfer wird sich so nur langsam durch bessere Resultate ins Rating niederschlagen.

![*Historisches Elo Rating - Bayern München (clubelo.com)*](/datenquellen/_index_files/elo1.png)

***

# [FBRef](https://fbref.com/en/)

FBRef ist eine Tochterseite von *Sports Reference*, das als Hobbyprojekt von Sean Forman und als Nachschlagewerk für Baseballdaten startete. Neben Fußball und Baseball gibt es auch noch Basketball- und Icehockeyableger. Schon im Jahr 2018 hatten diese Webseiten mehr als eine Milliarde Aufrufe was natürlich Bände für ihre Akzeptanz und Relevanz unter Sportfans spricht.

Große Vorteile von FBRef sind die große Breite und Historie an Wettbewerben und die standardisierte Darstellungsweise der Daten. FBRef geht sogar so weit einen Downloadbutton an Tabellen anzufügen um den Export zu CSV zu erleichtern. Das ist natürlich ein Service den andere Seiten oftmals vermissen lassen und jeder der schonmal versucht hat eine Tabelle von manuell nach Excel zu kopieren wird es zu schätzen wissen. 

Seit einiger Zeit arbeitet FBRef nun auch mit Statsbomb zusammen um fortgeschrittene Statistiken zu veröffentlichen. Ab der Saison 2017/2018 findet man nun für einige Ligen Expected Goals, Expected Assists, Pressures, Carries, Progressive Distance und Co. 

![*Top 10 Spieler nach xG - Bundesliga 2019/2020 (fbref.com)*](/datenquellen/_index_files/fbref.png)

***

# [FiveThirtyEight](https://projects.fivethirtyeight.com/soccer-predictions/)

FiveThirtyEight wurde 2008 von Nate Silver als Blog zur US-Präsidentschaftswahl ins Leben gerufen und erlangte nach präzisen Wahkprognosen vermehrt Aufmerksamkeit. In den Jahren nach der Wahl weitete sich das Themenfeld auch auf Sportthemen aus was sich durch Silvers' Hintergrund als quantitativer Baseballanalyst (siehe auch [Sabermetrics](https://de.wikipedia.org/wiki/Sabermetrics)) als naheliegend erwies.  
  
Seit 2007 veröffentlicht die Webseite Prognosen für den weltweiten Klubfußball (36 Ligen inklusive Champions League und Europa League). Für jede nationale Liga wird die Wahrscheinlichkeit für den Titelgewinn, Relegation und Qualifizierung fürs internationale Geschäft berechnet. 
  
Für individuelle Partien gibt es im Vorraus Wahrscheinlichkeiten für Heimsieg, Auswärtssieg und Unentschieden. Nach Ausgang des Spiels werden schussbasierte expected Goals (xG) und nicht-schussbasierte expected Goals (non-shot xG) veröffentlicht, die weiteren Hintergrund über den Spielverlauf bieten.

![*Top 10 des Global Club Soccer Rankings - April 2020 (fivethirtyeight.com)*](/datenquellen/_index_files/fivethirtyeight.png)

***

# [Metrica Sports](https://metrica-sports.com/)

Metrica Sports hat dieses Jahr den ersten frei verfügbaren [Trackingdatensatz](https://github.com/metrica-sports/sample-data) veröffentlicht. Er umfasst zwei anonymisierte Spiele und gibt erste Einblicke was mit detaillierten Trackingdaten alles möglich ist.

***

# [Statsbomb](https://statsbomb.com/)

Statsbomb ist sicherlich eines der Unternehmen, das über die letzten Jahre am Meisten für die Verbreitung von Daten im Fußball getan hat. Gründer Ted Knutson ist herrlich präsent auf Twitter und arbeitete schon bei Brentford FC und FC Midtjylland, zwei Clubs die jeweils einen großen Schwerpunkt auf Daten setzen. 

Ein Grund für den großen Einfluss von Statsbomb sind meiner Meinung nach die vielen Kommunikationskanäle mit der das Team mit Profis und Hobbyanalysten in Verbindung tritt: Twitter, ihre Webseite mit vielen Blogartikeln, ihre Podcast, ihre [Konferenz](https://statsbomb.com/conference/). Statsbomb war meines Wissens auch das erste Unternehmen dass das Teilen von Daten als Teil seiner Kultur sieht. 

Letztes Jahr (2019) veröffentlichte Statsbomb schrittweise [Eventdaten](https://statsbomb.com/2019/07/welcome-to-the-messi-data-biography/) für die komplette Barcelonakarriere von Lionel Messi. Statsbomb unterstützt zusätzlich den Frauenfußball durch Analyseartikel und frei verfügbare Daten zur englischen Women's Super League.

Weitere Hintetgründe über die Arbeit von Statsbomb findet ihr in einem [Interview](https://spielverlagerung.de/2020/02/08/wir-finden-bessere-spieler-fuer-das-gleiche-budget/?doing_wp_cron=1586045796.6078009605407714843750) von Ted Knutson mit spielverlagerung.de.

***

# [Transfermarkt](https://www.transfermarkt.de/)

Das deutsche Portal Transfermarkt.de und ihre internationalen Ableger fokussieren sich seit dem Jahre 2000 auf Transfergerüchte und Spielermarktwerte. Die Communitybasierte Datenbank umfasst mehr als 70.000 Vereine und 700.00 Spieler.

![*Marktwertanalyse Alphonso David (Transfermarkt.de)*](/datenquellen/_index_files/transfermarkt1.png)

Neben den Marktwerten gibt es viele weitere Datensätze wie z.B. einen detailierten Überblick über Verletzungshistorien.

![*Verletzungshistorie Marco Reus (Transfermarkt.de)*](/datenquellen/_index_files/transfermarkt2.png)

Leider gibt es meines Wissens keinen einfachen Weg Daten herunterzuladen, wie das zum Beispiel bei FBRef der Fall ist.

***

# [Understat](https://www.understat.com)

Understat veröffentlicht expected Goals-Werte für die fünf großen Ligen (und die russische Premjer-Liga) beginnend mit der Saison 2014/2015. Auf Teamlevel können wir so tatsächlich erzielte Tore mit dem Expected Goals-Wert vergleichen und so, je nach Auslegung, Effizienz oder Glück messen. Das Gleiche gilt selbstverstänglich auch für Gegentore. In der Theorie sollten sich Expected Goals und tatsächlich erzielte Tore über länger Zeiträume annähern.

![*Expected Goals vs tatsächlich erzielte Tore für die Bundesliga (Understat.com)*](/datenquellen/_index_files/understat1.png)

Auf Spielerebene erschließen sich durch diese Daten weitere interessante Geschichten. So zeigt die folgende Tabelle die Statistiken der Bundesliga Topscorer für die Saison 2018/2019. Obwohl Robert Lewandowski mit 22 Toren die Torjägerkanone gewann blieb er weit unter seinem (von Expected Goals auferlegten) Soll. Aber selbst mit ein bisschen Pech im Abschluss lässt sich bei Bayern mit der Vielzahl an generierten Chancen noch die Torjägerkanone sichern.

Die untige Tabelle erzählt auch die Geschichte des unglaublichen Bundesligaeinstands eines Paco Alcacer, der in der Hinrunde der Saison 2018/2019 alleine 10 Tore nach Einwechslung erzielte. Im Vergleich von Toren zu expected Goals zeigt sich hier das Alcacer fast 8 Tore mehr erzielt hat als erwartet. 

Eine weitere wichtige Statistik, die oft übersehen wird, ist die Anzahl der gespielten Minuten für die wir einen Großteil der anderen Statistiken anpassen sollten. Alcacer hat deutlich weniger Spielminuten bekommen als anderen Topscorer. So ist Alcacer's xG-Wert geringer als der von Marco Reus, doch da er weniger als die Hälfte an Einsatzzeit bekam dennoch der effizienter Scorer (siehe xG90-Spalte).

Die zwei obigen Beispiele werfen eine der Fragen auf die oft im Umgang mit dem expected Goals Werten oft aufkommt. Ist es nun gut seinen xG-Wert zu übertreffen oder kommt das auch immer mit Fragezeichen? Natürlich ist es immer erstmal gut den xG-Wert zu übertreffen da das heißt dass man Tore schießt die einam auch keiner mehr wegnehmen kann. 

![*Topscorer der Bundesliga für die Saison 2018/2019 (Understat.com)*](/datenquellen/_index_files/understat2.png)

Neben den xG-Tabellen gibt es noch viele weitere Datenschätze zu entdecken: Shotmaps für einzelne Spieler (nachfolgend die von Kai Havertz), Unterteilungen nach Schusssituationen (Nach Ecke, direkter Freistoß oder nach normalem Angriff) oder nach Körperteil (linker/rechter Fuß, Kopf).

![*Shotmap für Kai Havertz (Understat.com)*](/datenquellen/_index_files/understat3.png)

***

# [WyScout](https://wyscout.com/)

WyScout ist ein weiterer Datenanbieter der sich neben der Sammlung von Eventdaten vor allem auf Videoanalyse spezialisiert. 2019 veröffentlichte WyScout einen großen [Eventdatensatz](https://figshare.com/collections/Soccer_match_event_dataset/4415000/5), der sowohl die Saison 2017/2018 für die Bundesliga, Premier League, Serie A, La Liga und Ligue 1, als auch die Europameisterschaft 2016 und die Weltmeisterschaft 2018 umfasst. Insgesamt sind so 1,941 Begegnungen mit 4,299 Spielern und 3,251,294 Events frei verfügbar.

<style>
div.blue { background-color:#e6f0ff; border-radius: 5px; padding: 20px;}
</style>
<div class = "blue">

**Frei verfügbare Daten:**

- Metrica Sports: [Trackingdatensatz](https://github.com/metrica-sports/sample-data)
- Statsbomb: [Eventdatensätze](https://github.com/statsbomb/open-data)
- WyScout: [Eventdatensätze](https://figshare.com/collections/Soccer_match_event_dataset/4415000/5)

</div>
