# Datenschutzerklärung für Phutto

Stand: 13. November 2026

**Verantwortlicher und Kontakt**

Philipp Schrock  
Deutschland  
E-Mail: [Philipp.Schrock@iCloud.com](mailto:Philipp.Schrock@iCloud.com)

**Daten in der App**

Phutto ist ein nichtkommerzielles Hobbyprojekt zur Verwaltung von Spielern und Spielständen.

Die App speichert eingegebene Spielernamen, Spielerkennungen, Punkte, Spielverläufe einschließlich Korrekturen, Sitzordnungen und Partieergebnisse mit Zeitangaben. Daraus werden die angezeigten Statistiken berechnet. 
Für Spielernamen können auch Spitznamen, Pseudonyme oder frei erfundene Bezeichnungen verwendet werden. Die Angabe des echten Namens ist nicht erforderlich.

Laufende Partien werden lokal gespeichert, damit sie fortgesetzt werden können. Auch Einstellungen wie Sprache, Gerätename und Anzeigeoptionen werden auf dem Gerät gespeichert. Eine eigene Registrierung bei Phutto ist nicht erforderlich.

**iCloud-Synchronisierung**

Wenn iCloud für Phutto verfügbar ist, synchronisiert die App regelmäßige Spielerprofile und abgeschlossene Partien automatisch über Apples CloudKit. Gäste bleiben dabei als Teilnehmer ihrer jeweiligen Partie enthalten.

Die synchronisierten Daten liegen in der privaten CloudKit-Datenbank des jeweiligen iCloud-Kontos. Als Entwickler habe ich über das Entwicklerportal keinen regulären Zugriff auf diese Daten.

Laufende Partien werden durch diese Funktion nicht zwischen Geräten synchronisiert.

Informationen zur Verarbeitung durch Apple findest du unter [Apple Account und iCloud – Datenschutz](https://www.apple.com/de/legal/privacy/data/de/apple-account/).

**Ändern und Löschen von Daten**

Spielerprofile können umbenannt und archiviert werden. Archivierung bedeutet keine Löschung; eine endgültige Profil-Löschung bietet die App derzeit nicht an. Profiländerungen werden über iCloud synchronisiert. Bereits gespeicherte Partien behalten ihre ursprünglichen Teilnehmernamen.

Abgeschlossene Partien können in der Statistik nach Bestätigung gelöscht werden. Diese Löschung wird über iCloud auf andere Geräte übertragen. Ein technischer Löschvermerk mit der Partiekennung bleibt erhalten, damit ältere Kopien die Partie nicht erneut einspielen.

Bei einer Deinstallation werden die lokalen Spieldaten entfernt. Bereits synchronisierte iCloud-Daten werden dadurch nicht gelöscht und können nach einer Neuinstallation wieder geladen werden.

**Lokales Mehrgerätespiel**

Beim Mehrgerätespiel tauschen die verbundenen Geräte Spielerdaten, Spielstände, Sitzordnung und Eingaben aus. Zur Verbindung verwendet Phutto Gerätenamen, appinterne Gerätekennungen und lokal gespeicherte Verbindungsinformationen.

Das Gastgebergerät verwaltet und speichert die Partie. Die Live-Übertragung erfolgt über die lokale Geräteverbindung, nicht über iCloud.

Auf Clients werden vollständige Spielstände nur im Arbeitsspeicher gehalten und nicht als eigene Partie in der Historie gespeichert. Noch nicht bestätigte Eingaben werden zur Wiederholung nach Verbindungsproblemen lokal gespeichert. Sie werden entfernt, wenn die App die entsprechende Antwort oder eine Abbruchmeldung erhält. Ohne diese Rückmeldung können sie gespeichert bleiben. Auch Verbindungsinformationen können für einen Wiedereinstieg erhalten bleiben.

**Werbung und Analyse**

Phutto enthält keine Werbung und keine eingebundenen Tracking- oder Analyse-SDKs.

Für Betaversionen über TestFlight gilt zusätzlich: Apple erfasst Nutzungs- und Absturzinformationen und stellt dem Entwickler Informationen zur Verfügung. Eingereichtes Testfeedback wird ebenfalls weitergegeben. Einzelheiten beschreibt Apple unter [TestFlight und Datenschutz](https://www.apple.com/legal/privacy/data/en/test-flight/).

**Diese Website**

Diese Website wird über GitHub Pages bereitgestellt. Laut GitHub werden beim Besuch IP-Adressen zu Sicherheitszwecken protokolliert. Weitere Informationen findest du in der [GitHub-Datenschutzerklärung](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Der Datenschutz-Link in Phutto öffnet diese Website erst nach Antippen im Browser. Die App hängt dabei keine Spieler-, Partie- oder Geräteinformationen an die Adresse an.

**Kontakt und Datenschutzrechte**

Wenn du mir eine E-Mail schreibst, verwende ich deine E-Mail-Adresse und die von dir mitgeteilten Informationen zur Bearbeitung deiner Anfrage.

Im Rahmen der gesetzlichen Voraussetzungen hast du Rechte auf Auskunft, Berichtigung, Löschung und Einschränkung der Verarbeitung deiner personenbezogenen Daten. Du kannst dich außerdem bei einer Datenschutzaufsichtsbehörde beschweren.

Bei Fragen oder zur Ausübung deiner Rechte kannst du dich an die oben genannte E-Mail-Adresse wenden.
