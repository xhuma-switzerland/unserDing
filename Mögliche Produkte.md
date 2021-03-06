#POD Server


# POD App
## Idee App zur einmaligen Registrierung in Gastrobetrieben
###Ausgangslage
Mit Corona muss man sich in Restaurants, Bars und Clubs oftmals registrieren. Sei das per Stift oder per App. Die Apps die ich kennengelernt haben, sind aber trotz allem zeitraubend und man muss immer dieselben Daten eingeben. Diese werden dann beim Betrieb gespeichert. Und jeder Gastrobetrieb hat wieder eine andere App. Der Kunde weiss grundsätzlich nicht wo seine Daten gespeichert sind und was mit ihnen gemacht wird. Im schlimmsten Fall werden sie gestohlen und verkauft (https://www.20min.ch/story/hacker-legen-kundendaten-von-corona-listen-offen-923896499465). 
###Idee
Wir stellen den vorhandenen Apps eine Schnittstelle zur Verfügung, bei welcher sie auf unsere im POD gespeicherten Daten zugreifen können. 

? 1. schnelle Umsetzung: Daten werden an die bestehenden Apps mitgeteilt

? 2. längerfristige Lösungen: Daten werden wie angedacht nicht geteilt, sondern nur verlinkt. Klären wer dann bei welchem Ereignis auf die Daten zugreifen darf. z.B. die Gesundheitsdirektion. 
###Analyse
In der Schweiz gibt es diverse Apps von verschiedenen Anbietern um die Daten der Kunden zu tracken. Folgend ein kurzer Überblick

Name | Beschreibung | Bewertung |
-----|------------- | ------ |

[Listmask](https://www.listmask.com) | Das Grundprinzip ist, dass die Telefonnummer des Kontakts mit einem Token maskiert wird, oder einfacher gesagt: Sie wird durch einen anonymen Zufalls-Code ersetzt. Aus 079123456 wird zum Beispiel V5KJM. Diesen Code nennen wir MaskID. Folglich geben Sie bei einem Besuch eines Geschäfts nicht Ihre Telefonnummer an sondern nur Ihre persönliche MaskID. Diese MaskID muss nur einmal angefordert werden und bleibt dann für Sie immer gleich. | Bei mir ist eine leere ID zurück gekommen. Die Daten werden zentral bei listmask gesammelt. | 

[Etables](https://www.etables.info)| Nützliche Informationen, ganz einfach am Tisch. Kostenlose App zur Erfassung von Kundendaten.| Kunde scannt den Code, gibt seine Daten ein. Die Daten werden wahrscheinlich auf dem Server von etables gespeichert.

[GetContact](https://getleedz.com/COVID19-ContactTracing?member=cfecdb276f634854f3ef915e2e980c31&refer=995ca733e3657ff9f5f3c823d73371e1 )|ach der Registrierung und Bezahlung über Paypal erhältst du per E-Mail den Download-Link zu deinem fixfertigen PDF-Flyer zum Selbstausdrucken. Die Laufzeit der Kampagne beträgt 12 Monate. Die Daten deiner Gäste werden nach 14 Tagen automatisch gelöscht. Übermittlung an Behörde ist jederzeit möglich. Für zusätzliche Optionen oder Fragen kontaktiere uns bitte. |

[Mindful](https://mindfulapp.io)|Mindful ist die kostenlose Check-in-App für Schweizer Unternehmen zur Sammlung von Kontaktdaten! So wollen wir mithelfen, die COVID-19 Pandemie in der Schweiz einzudämmen und eine zweite Welle zu verhindern.| Check-in und Check-out, Daten auf Handy aber auch auf Server. Aufenthalt wird nach 14 Tagen überall gelöscht. Daten werden auf Verlangen dem Kantonsärtzlichen Dienst zur Verfügung gestellt. 

[tastier](https://www.tastier.ch)|Eine Gratis Tracing Lösung welche sich flexibel an die individuellen Bedürfnisse anpassen lassen (Tisch- und Thekenservice) inkl. einer sichernen Selbst-Bezahllösung, Keine gedruckte Rechnung, kein Bargeld, Kartenlesegerät oder Service am Tisch nötig. Daten werden von Tastier sicher und datenschutzkonform gespeichert und gelöscht. Tastier unterstützt Sie auch, wenn die Gesundheitsbehörden Daten von Ihnen verlangen.|

[PoGastro](https://www.pogastro.com/de-ch/services/digitale-touchless-speisekarte )|Kostenlose Lösung für Touchless Speisekarte und Tracing Daten. Der Gast scannt mit seinem Handy einen QR-Code auf deinem Tischaufsteller und sieht sofort das Speiseangebot inkl. Bilder und Allergenen oder das Getränkeangebot. Ausserdem kann der Gast auf freiwilliger Basis direkt seine Daten eingeben um bei einem Covid-19 Verdachtsfall benachrichtigt zu werden.|Automatische Vernichtung nach 14 Tagen

[Upsave](https://upsave.ch)|Mit UPSAVE kannst du deine Kundendaten einfach und bequem erfassen und verwalten. Digital, sicher und automatisiert. | Vernichtung nach 14 Tagen automatisch.
