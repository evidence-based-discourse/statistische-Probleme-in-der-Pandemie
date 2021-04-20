# Anzahl der Tests

#### Die Anzahl der durchgeführten Tests wird bei Entscheidungen über Maßnahmen nicht oder nur unzureichend berücksichtigt.


Corona-Tests helfen dabei infizierte Menschen zu detektieren. 
Diese Personen, sowie auch enge Kontaktpersonen der vorangegangenen Tage können in einer Quarantäne 
untergebracht werden, was eine weitere Ausbreitung des Virus verhindert. 

Zusätzlich wird aber die Anzahl der positiven Tests als quantitaves Maß für die 'Stärke' der 
Pandemie verwendet. Derzeit wird der Inzidenzwert als Maßstab der Pandemie verwendet. 
Der Inzidenzwert ist dabei die Anzahl der positiv Getesteten je *100.000* Einwohner in den 
vorangegangen *7* Tagen. 
Dieser Wert ist unabhängig davon, wie viele Menschen unter den *100.000* sich tatsächlich getestet haben.
Wenn also in *7* Tagen *25* positive Fälle in einer Region mit *100.000* Einwohnern gefunden wurden, 
dann ergibt sich ein Inzidenzwert von *25*. Bei *50* positive Fälle wäre es eine Inzidenz von *50*, und so weiter.

Das bringt jedoch einige Risiken mit sich, insbesondere wenn zusätzlich zu den Menschen mit 
konkretem Verdacht auf CoViD-19 sich noch viele Menschen ohne Symptome testen lassen: 
Wenn doppelt so viele Menschen getestet werden, können auch etwa doppelt so 
viele positive Tests erwartet werden. Folglich ist natürlich auch der Inzidenzwert deutlich erhöht. 
Ironischerweise führte der erhöhte Inzidenzwert sogar zu noch mehr Tests von Menschen ohne Verdacht
auf Corona oder Symptomen, wodurch der Inzidenzwert noch weiter steigt.

In der Nachfolgenden Abbildung ist ein Beispiel mit zwei Dörfern dargestellt, 
welche jeweils etwa *1000* Einwohner haben und von denen jeweils *16* oder *1,6%* 
infiziert sind. In dem linken Dorf werden in einer Woche *12,5%* der Einwohner 
(zufällig und symptomlos) getestet. 
Unter den *125* Getesteten wurden *2* Menschen positiv getestet. 
Da die Anzahl der positiv getesteten ins Verhältnis mit allen *1000* Einwohnern gesetzt und
anschließend für *100.000* Einwohner hochgerechnet wird, 
ergibt sich ein Inzidenzwert von 
<img src="https://render.githubusercontent.com/render/math?math=\frac{2}{1000} \cdot 100.000=200">.  
Würde dieser Inzidenzwert nun dazu führen, dass im Nachbardorf mit gleich vielen 
Einwohnern und positiven nicht nur *12,5%* sondern sogar *50%* der Menschen getestet werden,
dann würde der Inzidenzwert auf 
<img src="https://render.githubusercontent.com/render/math?math=\frac{8}{1000} \cdot 100.000=800">
steigen. So kann sehr einfach gesehen werden, dass der Inzidenzwert nicht als alleiniges 
Maß für die Stärke der Pandemie herangezogen werden kann.
 
![AnzahlDerTests.png](AnzahlDerTests.png)

Einige Mathematiker fordern, die Anzahl der positiven Tests ins Verhältnis mit allen Tests zu setzen. 
Das würde bei der Testung von symptomlosen Menschen tatsächlich helfen, birgt aber die Gefahr 
einer starken Überschätzung, wenn hauptsächlich Menschen mit Symptomen getestet werden. 
Ein Beispiel: Wenn eine kleine Gruppe von Reiserückkehrern mit starken Symptomen einer 
Tropenkrankheit auf eben diese getestet werden, und die Hälfte davon tatsächlich positiv ist, 
dann kann dieses Verhältnis keinesfalls auf die restliche Bevölkerung übertragen werden.
Ansonsten würde hochgerechnet werden, dass die Hälfte der Bevölkerung eine Tropenkrankheit hat.

Eine bessere Möglichkeit wäre, bei der Testung die Information zu berücksichtigen, ob Symptome 
vorliegen oder die betreffende Person Kontakt zu einer an CoViD-19 erkrankten Person hatte.
Diese Information hilft dabei, das Verhältnis der positiven Tests unter den Menschen ohne Verdacht 
auf CoViD-19 unter Berücksichtigung der Testgüte (Sensitivität und Spezifität) auf die Bevölkerung 
hochzurechnen. Dies würde tatsächlich einen Wert liefern, welcher als Maß für die 'Stärke' der 
Pandemie herangezogen werden kann und auf Basis dessen Handlungsmaßnahmen beschlossen werden können.
