# Statistische Probleme bei der Rechtfertigung von Maßnahmen gegen die Pandemie

Das Ziel dieses Projektes ist ein öffentlicher und transparenter Diskurs zu statistischen Problemen bei der Rechtfertigung von Maßnamen in der Pandemie.
Unsere Grundannahme ist, dass Maßnahmen dem gesamtgesellschaftlichen Ziel der Minimierung 
von Leid dienen müssen.

## Motivation

Es ist nicht die Absicht dieser Seite die Maßnahmen gegen die Ausbreitung von CoViD-19 als Ganzes verwerfen zu wollen. 
Es ist auch nicht die Absicht dieser Seite die Gefährlichkeit von CoViD-19 in Frage zu stellen. 
Und schon gar nicht ist es die Absicht abzustreiten, dass Menschen an CoViD-19 gestorben sind. 
Vielmehr ist es die Absicht in einem offenen, transparenten Diskurs massive statistische Probleme anzusprechen, 
damit die Maßnahmen für das Wohl der Gemeinschaft verbessert werden können. 
Das Ziel von Maßnahmen ist aus unserer Sicht, das gesamte Leid der direkten und indirekten Auswirkungen durch Corona aus 
ganzheitlicher Sicht – wie auch immer es gemessen wird – zu minimieren.

Wir haben uns dazu bewusst für die diese Plattform entschieden, da wir der Meinung sind, dass Wahrheit nicht statisch vorliegt, 
sondern erst in einem kollektiven lebendigen Prozess erarbeitet werden muss. 
Wenn man auf die historische Entwicklung von Wissenschaften und Weltbildern zurückblickt, dann erkennt man, dass diese 
erst in einem Prozess entwickelt worden sind. 
Dieser Prozess war immer mit einem wissenschaftlichen Diskurs verbunden, in welchem unterschiedliche Experten sich ausgetauscht, 
kritisiert, korrigiert und auch über Sachverhalte gestritten haben. 
Die Entwicklung wissenschaftlicher Modelle profitierte dabei stets von einem offenen Diskurs, 
unter welchem ein Konsens erreicht werden konnte. 
Wir haben die Hoffnung, dass ein offener transparenter Diskurs besonders gut mit Github ermöglicht werden kann. 
Denn dort kann man sich zu gewissen Fragestellungen austauschen, sogar einzelne Sätze kritisieren, 
korrigieren, diskutieren, auf Basis dessen verbessern 
und wenn kein Konsens erzielt werden kann, sogar eine eigene Richtung (oder AbZWEIGung) 
mittels einem „fork“ und „branch“ einschlagen.

Beiträge welche dem Diskurs klar schaden, haben hier jedoch keinen Platz und werden, wenn es uns nötig erscheint, gelöscht. 
Dazu zählen:
-	Beleidigungen: Jede Form von Beleidigungen und Denunzierungen einer Person oder Gruppe.
-	Geschwafel: Das Produzieren von viel Text ohne konkretem Inhalt stört den wissenschaftlichen Diskurs und wird somit bei 
subjektiver Überschreitung einer gewissen Toleranzgrenze ebenfalls entfernt.
-	Themenabweichung: Es ist oftmals nicht einfach den Kern eines Punktes exakt zu verstehen. Wenn Kritik von einem Punkt klar 
abweicht und somit nicht den Punkt an sich kritisiert, sollte die Kritik eher eigenständig formuliert werden.

Wir stimmen darin überein, dass diese Krise eine Vielzahl von Perspektiven aufweist und mehrere Fachgebiete umfasst: 
Virologie, Epidemiologie, Medizin, Statistik, Datenwissenschaften, Wissenschaftstheorie, Politikwissenschaften, Psychologie, 
Gesellschaftswissenschaften, Ethik und Zukunftsforschung. 
Derzeit liegt der Fokus klar auf der statistisch-mathematischen Seite, bei Bedarf und der dafür nötigen Expertise von 
Mitwirkenden können jedoch weitere Perspektiven mit aufgenommen werden.

---

## 1. Statistische Probleme

In diesem Kapitel werden einzelne Probleme aus dem statistischen Bereich kurz zusammengefasst. 
Jedes Problem ist, sobald verfügbar, mit einer ausführlicheren Erklärung mit Quellenangaben verlinkt.

### [1.1. Anzahl der Tests](docs/1/1/AnzahlDerTests.md)
Die Anzahl der durchgeführten Tests wird bei Entscheidungen über Maßnahmen nicht oder nur unzureichend berücksichtigt.

### [1.2. Sensitivität und Spezifität](docs/1/2/Sensitivität_und_Spezifität.ipynb)
Der Anteil der falsch-positiven Tests unter allen positiven Tests wird bei Entscheidungen über Maßnahmen unzureichend berücksichtigt.

### 1.3. Definition von "an oder mit CoViD-19" verstorben
Eine eingetragene Begleitkrankheit von CoViD-19 (*U07* im ICD-Code) wird meist als hauptsächliche Todesursache angführt und führt somit zu einer Verzerrung der Statistik.

### 1.4. CoViD-19 wird selten mit anderen Krankheiten verglichen
Um die Gefährlichkeit von Krankheiten bewerten zu können ist ein Vergleich notwendig.

---

## 2. Modellbasierte Probleme

### 2.1. Entscheidungen werden auf einen Aspekt reduziert
Die zu optimierende Zielfunktion für die zu beschließenden Entscheidungen berücksichtigen hauptsächlich CoViD-19. Leid aufgrund anderer physische und psychische Krankheiten, sowie weitere Faktoren werden ignoriert.

### 2.2. Modelle werden nicht ausreichend empirisch validiert
Auch Modelle welche aus mehreren an sich plausiblen Schritten bestehen besitzen eine hohe Anzahl an Freiheitsgraden und bergen somit die Gefahr, auf zukünftigen Daten nicht erfolgreich zu sein. Daher ist eine gute emprische Validierung unerlässlich.

### 2.3. Prädiktive Modelle waren bisher kaum erfolgreich
Zurückblickend waren jene prädiktive Modelle welche vergangene Maßnahmen rechtfertigten nicht erfolgreich.

### 2.4. Korrelationen werden mit Kausalitäten verwechselt
Oftmals wurden Maßnahmen erst bei stagnierenden Inzidenzzahlen und somit bei bereits sinkendem R-Werte gesetzt. Daher liegt natürlicherweise eine Korrelation zwischen Maßnahmen und einem niedrigen R-Wert vor, aber nicht automatische eine Kausalität.

### 2.5. Regionen mit geringen Maßnahmen werden oftmals ignoriert
Die Validierung eines Modells muss auch für Regionen mit abweichenden Maßnahmen und Pandemie-Strategien standhalten.

---

## 3. Wissenschaftstheoretische Probleme

### 3.1. Die Annahme der Kausalität, Politiker entscheiden aufgrund von unabhängigen wissenschaftlichen Ergebnissen muss hinterfragt werden
Es gibt eine Vielzahl von Fällen in denen Politiker Druck auf die Forschung ausübten, Expertenteams politisch motiviert besetzt wurden und Wissenschaftler mit nicht erwünschten Ergebnissen politisch ausgeschlossen oder medial verpöhnt wurden.

