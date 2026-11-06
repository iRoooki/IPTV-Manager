IPTV ACCOUNT MANAGER – PRIVATE WEB-APP

DATEIEN: index.html, manifest.webmanifest, sw.js

INSTALLATION / NUTZUNG:
1. Die drei Dateien gemeinsam auf einem HTTPS-Webspace hosten (z.B. GitHub Pages).
2. HTTPS-Adresse im iPhone-Safari öffnen und über Teilen > Zum Home-Bildschirm hinzufügen installieren.
3. Am PC die HTTPS-Adresse im Browser öffnen.
4. Master-Passwort (mindestens 12 Zeichen) erstellen.
5. Accounts anlegen; regelmäßig über „Backup“ eine verschlüsselte Sicherung speichern.

WICHTIG:
- Alle Accounts werden ausschließlich im lokalen Browser-Speicher gespeichert, AES-256-GCM-verschlüsselt mit einem per PBKDF2 abgeleiteten Schlüssel.
- iPhone und PC haben getrennte Tresore. Über Backup/Import können Daten manuell übertragen werden. Import ERSETZT alle lokalen Einträge.
- Keine Cloud-Synchronisierung, kein Backend, keine Analytics.
- Passwort vergessen oder Browserdaten gelöscht ohne Backup = Daten nicht wiederherstellbar.
- Die App sperrt sich nach 15 Minuten ohne Interaktion, aber bei aktiver Nutzung wird die Sperre verlängert.
- Ein HTTPS-Hosting ist nötig für die reguläre PWA-Installation und sicheren Browserbetrieb; localhost funktioniert für lokale Entwicklung.
- Kopierte Passwörter können in der Zwischenablage anderer Apps sichtbar sein.
- Vor dem produktiven Einsatz empfiehlt sich ein Test mit Dummy-Daten und ein Backup/Import-Test.
