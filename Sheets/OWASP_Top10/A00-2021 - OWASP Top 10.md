# Top 10 Web Application Security Risks

Es gibt drei neue Kategorien, vier Kategorien mit Namens- und Scoping-Änderungen und einige Konsolidierungen in den Top 10 für 2021.

## Anpassungen 2017 / 2021

![[Pasted image 20221031123851.png]]

## OWASP Top 10 Übersicht

[[A01-2021 - Broken Access Control]] rückt von der fünften Position auf; 94% der Anwendungen wurden auf irgendeine Form von Broken Access Control getestet. Die 34 Common Weakness Enumerations (CWEs), die der Broken Access Control zugeordnet wurden, wiesen mehr Vorkommen in Anwendungen auf als jede andere Kategorie.

- Metadatenmanipulation (Cookies, JSON Web Token (JWT)
- Parametermanipulation ()
- Unsichere direkte Objektreferenzen ()
- Erhöhung von Privilegien

[[A02-2021 - Cryptographic Failures]] verschiebt sich um eine Position auf 2, früher bekannt als Sensitive Data Exposure, was eher ein breites Symptom als eine Ursache war. Der erneute Fokus liegt hier auf Fehlern im Zusammenhang mit Kryptographie, das oft zur Offenlegung sensibler Daten oder zur Kompromittierung des Systems führt.

[[A03-2021 - Injection]] gleitet nach unten in die dritte Position. 94% der Anwendungen wurden auf irgendeine Form der Injektion getestet, und die 33 CWEs, die dieser Kategorie zugeordnet sind, weisen die zweitmeisten Vorkommen in Anwendungen auf. <font color='yellow'>Cross-site Scripting</font> wird ab 2021 auch hier zugeordnet.

[[A04-2021 - Insecure Design]] ist eine neue Kategorie ab 2021 mit Schwerpunkt auf Risiken im Zusammenhang mit Konstruktionsfehlern. Erfordert Einsatz von Bedrohungsmodellierung, sicheren Entwurfsmustern und -prinzipien sowie Referenzarchitekturen.

[[A05-2021 - Security Misconfiguration]] steigt von #6 in der vorherigen Ausgabe auf; 90% der Anwendungen wurden auf irgendeine Form von Fehlkonfiguration getestet. Mit mehr Verschiebungen in hochgradig konfigurierbare Software ist es nicht verwunderlich, dass diese Kategorie aufsteigt. Die frühere Kategorie für XML External Entities (XXE) ist jetzt Teil dieser Kategorie.

[[A06-2021 - Vulnerable and Outdated Components]] wurde zuvor mit dem Titel Using Components with Known Vulnerabilities betitelt und ist #2 in der Top 10 Community-Umfrage, hatte aber auch genügend Daten, um die Top 10 durch Datenanalyse zu erreichen. Diese Kategorie steigt von # 9 im Jahr 2017 und ist ein bekanntes Problem, das wir nur schwer testen und bewerten können. Es ist die einzige Kategorie, in der keine Common Vulnerability and Exposures (CVEs) den enthaltenen CWEs zugeordnet sind, sodass ein Standard-Exploit und eine Auswirkungsgewichtung von 5,0 in ihre Bewertungen einbezogen werden.

[[A07-2021 - Identification and Authentication Failures]] war zuvor Broken Authentication und rutscht von der zweiten Position nach unten und umfasst jetzt CWEs, die eher mit Identifikationsfehlern zusammenhängen. Diese Kategorie ist immer noch fester Bestandteil der Top 10, aber die erhöhte Verfügbarkeit standardisierter Frameworks scheint zu helfen.

[[A08-2021 - Software and Data Integrity Failures]] ist eine neue Kategorie für 2021, die sich auf Annahmen in Bezug auf Software-Updates, kritische Daten und CI/CD-Pipelines konzentriert, ohne die Integrität zu überprüfen. Eine der am höchsten gewichteten Auswirkungen von CVE/CVSS-Daten (Common Vulnerability and Exposures/Common Vulnerability Scoring System), die den 10 CWEs in dieser Kategorie zugeordnet sind. Die unsichere Deserialisierung von 2017 ist jetzt Teil dieser größeren Kategorie.

[[A09-2021 - Security Logging and Monitoring Failures]] war zuvor Insufficient Logging & Monitoring und wird aus der Branchenumfrage  hinzugefügt, von # 10 zuvor. Diese Kategorie wird erweitert, um mehr Arten von Fehlern einzubeziehen, ist schwierig zu testen und wird in den CVE/CVSS-Daten nicht gut dargestellt. Fehler in dieser Kategorie können sich jedoch direkt auf die Sichtbarkeit, die Alarmierung von Vorfällen und die Forensik auswirken.

[[A10-2021 - Server-Side Request Forgery]] wird aus der Top 10 Community-Umfrage  hinzugefügt. Die Daten zeigen eine relativ niedrige Inzidenzrate mit überdurchschnittlicher Testabdeckung sowie überdurchschnittliche Bewertungen für Exploit- und Impact-Potenzial. Diese Kategorie stellt das Szenario dar, in dem die Mitglieder der Sicherheitscommunity uns sagen, dass dies wichtig ist, obwohl es zu diesem Zeitpunkt nicht in den Daten veranschaulicht wird.