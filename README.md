Update Sync 09.06.2026 9:15 Was hat sich geändert:
---
Änderungen der Passwortrichtlinien (Kurzfassung)
Version Update: 12.04.2026 → 05.06.2026
Struktur-Änderungen:

Komponenten: 10 → 7 (3 Komponenten entfernt/konsolidiert)
Capabilities: 2 → 1 (1 Capability entfernt)

Was sich konkret geändert hat:
Entfernt (Datei 12.04 )Neu/Umbenannt (Datei 05.06 )

Anlassbezogene Passwortwechsel→ zusammengefasst in Passwortrichtlinie

Blockieren von Passwort Recycling→ Blockieren von Passwort-Recycling (Umbenennung)

Trivialpasswörter→ Blockieren von Trivialpasswörtern (Umstrukturiert)

Passwortmanager→ Bereitgestellter Passwortmanager (Präzisiert)

—→ Deaktivierung vorkonfigurierter Authentisierungsmittel (Neu)

—→ MFA- und Biometriekonfiguration (Neu)

---


Weggelassen ohne Ersatz:

Einhaltung der Löschfristen

Entsperr- und Wiederherstellungsverfahren

Gruppenkonten-Passwortwechsel

Kriterien für Passwortqualität

Weisung zur Erstellung von Passwörtern

---
Die AG 1 hat die Aufgabe sich an der inhaltlichen Verbesserung und Weiterentwicklung der Anforderungen und Maßnahmen in der Stand-der-Technik – Bibliothek und zur Sicherung der Qualität und Aktualität zu beteiligen.

Erste Aufgaben sollte die Festlegung eines gemeinsamen Verständnis der QS sein. Hierzu wird eine Diskussion gestartet.

Von der Meldung an das BSI ist folgendes vorgehen vorgesehen: Diskussion daraus -> Issue -> Pull Request. Da dies sowohl für uns als auch das BSI noch "Neuland" :) müssen wir das genaue vorgehen noch abstimmen.

Weiteres Angebot, was sich in der ersten Beteiligungsphase ls Hilfreich herausgestellt hat ist ein regelmässiges Treffen. Ich schlage als nächsten Termin Do. 13.11 um 15:30 vor einladung folg.Ergänzt um ein Angebot für Nachzügler die sich gerne noch Beteiligen wollen dazu eine PM an mich mit individuellem Termin.


Welche Bereiche werden / wurden bearbeitet Tabelle

Übergreifende Themen (Diskussionen)

|ISMS|jetzt--> Methodik

Verantwortlichkeiten aller Praktiken


# Stand der Technik Bibliothek

Diese Bibliothek stellt strukturierte Sammlungen von
BSI-Sicherheitsvorschriften nach dem aktuellen Stand der Technik in der
Informations- und Cybersicherheit bereit. Diese Dokumente werden hier als
maschinenlesbare OSCAL-Dokumente veröffentlicht. Das OSCAL-Framework dient als
einheitliches Format für maschinenlesbare Dokumente im Compliance-Prozess und
ermöglicht einen datenzentrierten Ansatz für die Sicherheitsdokumentation.
Weitere Informationen zur Datenstruktur der Inhalte finden Sie in der
[Dokumentation zu OSCAL](./documentation/OSCAL.md).

## 📁 Für Anwender

Sie sind in einer Institution mit der Informationssicherheit betraut oder
auditieren diese und möchten die Inhalte des BSI dafür nutzen?

**→ Besuchen Sie das [Control-Layer-Verzeichnis](./control_layer/)**

**→ Nutzen Sie den
[Stand der Technik-Viewer](https://bsi-community.github.io/Stand-der-Technik-Viewer/),
um sich die Inhalte aus der Stand der Technik Bibliothek in einer
nutzungsfreundlichen Umgebung anzeigen zu lassen**

Im Control Layer finden Sie die veröffentlichten Kataloge, Profile,
aufgelösten Kataloge und Mappings. Aufgelöste Kataloge können direkt in einer
Institution verwendet werden.

Wiederverwendbare Beschreibungen konkreter Implementierungen durch Produkte,
Dienste, Richtlinien, Prozesse oder Workflows finden Sie im
[Implementation Layer](./implementation_layer/).

## ✏️ Für Editoren

Sie arbeiten gemeinsam mit dem BSI an der Entwicklung von Vorschriften und
möchten die aktuellen Grundlagendokumente hierfür prüfen oder bearbeiten?

**→ Besuchen Sie den [Control Layer](./control_layer/)**

Die veröffentlichten maschinenlesbaren Quellkataloge und Profile befinden sich
innerhalb der jeweiligen fachlichen Bereiche unter `sources/`.

## 🚀 Erste Schritte

1. **Als Anwender:** Wählen Sie im [Control Layer](./control_layer/) den für
   Ihre Institution passenden aufgelösten Katalog.
2. **Als Editor:** Wenn Sie Interesse an einer Zusammenarbeit mit dem BSI
   haben, wenden Sie sich bitte an stand-der-technik@bsi.bund.de.

Der [Assessment Layer](./assessment_layer/) ist für zukünftige
maschinenlesbare Artefakte zur Planung, Durchführung und Nachbereitung von
Prüfungen vorgesehen.

## 🤝 Mitwirken

Wir begrüßen Beiträge zur Verbesserung der Sicherheitsstandards. Bitte lesen
Sie unsere [Beitragsrichtlinien](./CONTRIBUTING.md).

## 📞 Kontakt und Support

**Disclaimer zu GitHub Issues & Discussions:**

Die Issues und Discussions in diesem Repository werden nicht durch das BSI
moderiert, bearbeitet oder beantwortet. Sie können dennoch von der Community
eröffnet und für den gegenseitigen Austausch genutzt werden.

Das BSI behält sich das Recht vor, Beiträge mit unangemessenem oder
unzulässigem Inhalt ohne Vorankündigung vollständig zu löschen.

Für allgemeine Fragen und Feedback nutzen Sie bitte das BSI Service Center.

- **Allgemeine Anfragen an das BSI:** [BSI Service Center](https://www.bsi.bund.de/DE/Service-Navi/Kontakt/kontakt_node.html)
- **Sicherheitsbedenken:** [BSI Sicherheitserreichbarkeiten](https://www.bsi.bund.de/static/security/security.txt)

## 📄 Lizenz

Dieses Repository steht unter der **Creative Commons Attribution-ShareAlike
4.0 International Lizenz (CC BY-SA 4.0)**. Details sind in der
[LICENSE](./LICENSE)-Datei enthalten.

Alle Beiträge zu diesem Repository werden unter denselben Lizenzbedingungen
wie das Repository selbst veröffentlicht.

---

*Gemeinsam stärken wir die Cybersicherheit und verbessern die
Widerstandsfähigkeit unserer Prozesse und Systeme.*
