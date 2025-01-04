# verdaechtigen-Datei-Hash-untersuchen
[Investigation findings.pdf](https://github.com/user-attachments/files/18306469/Investigation.findings.pdf)

Sehen Sie sich das folgende Szenario an. Führen Sie dann die schrittweisen Anweisungen aus.

Sie sind ein Level One Security Operations Center (SOC) Analyst bei einem Finanzdienstleistungsunternehmen. Sie haben eine Warnung über eine verdächtige Datei erhalten, die auf den Computer eines Mitarbeiters heruntergeladen wurde.

Sie untersuchen diese Meldung und stellen fest, dass der Mitarbeiter eine E-Mail mit einem Anhang erhalten hat. Bei dem Anhang handelte es sich um eine passwortgeschützte Tabellenkalkulationsdatei. Das Kennwort für die Tabellenkalkulation war in der E-Mail enthalten. Der Mitarbeiter lud die Datei herunter und gab dann das Passwort ein, um die Datei zu öffnen. Als der Mitarbeiter die Datei öffnete, wurde eine bösartige Nutzlast auf seinem Computer ausgeführt. 

Sie stellen die bösartige Datei sicher und erstellen einen SHA256-Hash der Datei. Vielleicht erinnern Sie sich aus einem früheren Kurs, dass eine Hash-Funktion ein Algorithmus ist, der einen Code erzeugt, der nicht entschlüsselt werden kann. Hashing ist eine kryptografische Methode, die zur eindeutigen Identifizierung von Malware verwendet wird und als eindeutiger Fingerabdruck der Datei dient.

Jetzt, da Sie den Hash der Datei haben, werden Sie VirusTotal verwenden, um weitere IoCs zu entdecken, die mit der Datei in Verbindung stehen.
