# Lern-Periode 4

23.2 bis 5.4.2024

## Grob-Planung

1. Ich habe in allen Fächer genügende Noten und ich bin mit ihnen einigermassen zufrieden (ausser bei Französisch)
2. Mein Vorsatz war es, meine Projekte und Arbeitspakete genauer zu planen  (vorallem zeitlich). Ich möchte auf weiterhin versuchen, mich weniger ablenken zu lassen.
3. **Neu**: APIs, await und async benutzen.
4. Einen Discord Bot machen, der einem das Wetter zu einem bestimmten Zeitpunkt sagt.

## 20.2.2024

✍️ Heute habe ich mich entschieden, dass ich einen Discord Bot machen möchte, der einem die Wetterprognose sagen kann und mit await und async arbeitet. Zuerst wollte ich an dem "The Odin Project" weiterarbeiten, doch ich habe mich dann umentschieden, weil ich keine richtigen Testfälle machen kann, wenn ich an einem Kurs weiterarbeite (ich weiss ja nicht, was kommt) und dadurch wäre meine Dokumentation unvollständig.
(64 Wörter)

## 27.2.2024

- [ ] Discor.NET Framework durchlesen und durcharbeiten (Discord Bot erstellen)
- [ ] API von einer Wetterdatenbank holen, damit der Bot damit arbeiten kann
- [ ] Await und async Funktionen in den Bot coden, damit der Code wartet, bis die Daten von der API geholt wurden
- [ ]   Der Discord Bot beantwortet meine Fragen (Prompts) richtig 

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1               |     Ich habe einen Discord Bot erstellt                 |  Der Bot wird einfache Sachen gefragt (noch keine API)              |       Korrekte Antwort         |        Ja  |
| 2               |    Einen Prototyp Code schreiben, der eine API benutzt               |       Ich gebe einen Input, z.b. "wie wird das Wetter in Zürich morgen?"         |       ich kriege dem entsprechende Antwort.         |          |
|    3                  |        Await und Async funktioniert.        |                |          |
| 4               |                      |                |                |          |

✍️ Heute habe ich mich mit APIs auseinander gesetzt. Zuerst habe ich einen Discord Bot ohne jegliche Commands erstellt und diesen einem von mir neu erstellten Discord Bot hinzugefügt. Ich wollte keine normalen Chat-Bot Befehle machen, weil ich fand es recht simpel und wollte meine Zeit den await, async und API Funktionen zuwenden.
Zuerst wollte ich die Wetter API und async, await in einer Konsolen-App ausprobiere. Jedoch habe ich leider APIs noch nicht so ganz verstanden und möchte dann nächstes Mal versuchen, APIs richtig zu verstehen und zu verwenden. https://learn.microsoft.com/en-us/aspnet/web-api/overview/advanced/calling-a-web-api-from-a-net-client Dafür habe ich mich in der offizielen Microsoft Dokumentation eingelesen, aber bei mir hat es noch nicht ganz "geklickt".  (108 Wörter)

## 08.03.2024
- [x] API von einer Wetterdatenbank holen, damit der Bot damit arbeiten kann
- [x] (nur in die Konsolenapp) Await und async Funktionen in den Bot und die Konsolen-App coden
- [ ] Konsolen-App "Prototyp" in Discord Bot importieren
- [ ] (Ein Arbeitspaket zusätzlich, falls ich die API immernoch nicht ganz verstehe)

 | Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
 |       1          |  API prompt                     |      API sucht nach Wetter in einem Ort und Zeit           |         Wetter Forecast wird gegeben        |           |
|       2         |   Await, async funktioniert
 |      3           |  Code von Console-App zum Discord Bot importieren

  

Heute habe ich die API für die Konsolen-App gemacht und auch async/await benutzt. Mit dem verstehen der API hat mir die Microsoft Seite von letztem Mal geholfen, sowie auch die Seite von der API, die ich benutzt habe, ```
openweathermap.org ```. Bei der API für die Wetterdaten musste ich entweder die geografischen Breiten- und Längengrade der Stadt benutzen, oder eine zusätzliche API (Geocoder) benutzen, die diese Grade mittels Namen oder Postleitzahl rausgefunden hat. Für nächstes Mal möchte ich die APIs in meinen Bot "einfügen" und auch meinem Bot commands geben. (90 Wörter)


## 15.03.2024

- [ ] API von Konsolen-App in Bot einfügen
- [ ] API in Bot einfügen 2
- [ ] Discord Bot Commands geben
- [x] Am Modul 187 bei (Herr Fähndrich) arbeiten

Ich habe heute ein wenig weiter am Bot gearbeitet, aber ich fand, dass die Wetter API der Grossteil der Arbeit war und ich musste "nur" noch alles portieren und Discord Commands machen. Deswegen hab ist das Projekt für mich abgeschlossen und ich habe heute noch an der Dokumentation der dieswöchigen Aufträge des Moduls M187 gearbeitet, bei dem ich noch nichht ganz fertig bin und noch ein paar Aufträge des Moduls M106 gemacht. Ich möchte nächste Woche die Zeit im Lern-Atelier nutzen, diese Module dort nachzuarbeiten (hauptsächlich die M187-Doku), anstatt das zuhause zu machen. Ich habe mich sonst auch beschlossen, nächste Woche mit dem The Odin Project fortzufahren. Ich weiss, Sie haben dagegen geraten, weil wir bald ein Modul darüber haben werden, aber ich dachte mir, es könnte nicht schaden, mehr über Programmieren zu wissen (134 Wörter).

## 22.03.2024

- [ ] An der M187 Dokumentation weiterarbeiten
- [ ] Am Modul M106 weiterarbeiten
- [x] Am The Odin Project weiterarbeiten (Ziel: Eine "Class" abschliessen)
- [x] Am TOP weiterarbeiten (Ziel: Auch eine Class abschliessen, aber ich weiss nicht, wie lange und umfangreich eine ist)

Ich habe heute nur am The Odin Project gearbeitet. Ich habe ca. 3,5 "Classes" gemacht, dafür habe ich vergessen, an den Modulen M187 und M106 zu arbeiten. Ich habe eine kleine Webpage in HTML geschrieben, die auch einen Link hat und so ziemlich alles zeigt, was ich heute gelernt habe.
Beim nächsten Mal Lern-Atelier würde ich gerne versuchen, 3 Classes zu machen, etwa so viel wie heute. Die folgenden Classes im Project heissen Links& images (habe ich schon angefangen), Commit Messages und die drittnächste wäre ein Projekt. Entweder mache ich das Projekt, oder ich fange mit den CSS Foundations mit der Class "intro to CSS", an. Aber vermutlich schaffe ich von der Zeit her nur eine oder zwei (118 Wörter).


## 05.04.2024

- [x] The Odin Project Links & images in HTML abschliessen und Bilder in meine kleine Website einfügen.
- [x] The Odin Project Commit Messages machen.

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1               |  The Odin Project, Links & images abgeschlossen                    |  Code für Bild geschrieben              |          Bild wird auf der Seite angezeigt.      |    Ja      |
| 2             |  The Odin Project, Commit Messages abgeschlossen                    |                |                |          |
            
Ich habe den Rest der Class Links & Images abgeschlossen und habe das auch mit einem Bild auf meiner kleinen Website wiederlegt (auf index.html auf About klicken und dann landet man auf about.html und sieht das Bild). 
Ich habe auch die nächste Class "Commit Messages" abgeschlossen, die einem Tipps gibt, wie und wann man auf Github Änderungen dokumentieren sollte. Ich habe auch schon ein wenig mit dem Thema CSS Foundations angefangen. (71 Wörter)

## Reflexion

Formen Sie Ihre Zusammenfassungen in Hinblick auf Ihren VBV zu einem zusammenhängenden Text von 100 bis 200 Wörtern (wieder mit Angabe in Klammern).
