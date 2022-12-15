# Lern-Bericht
Luka Pantic

## Einleitung

In diesem Modul haben wir das Thema "Applikationssicherheit" behandelt, darunter zu verstehen sind Dinge wie: verschiedene Angriffsarten (zum Beispiel, Cross Site Scripting, Interpreter Injections oder Cross Site Request Forgery), potenzielle Sicherheitslücken und wie man solchen Angriffen zuvorkommen kann.

## Was habe ich gelernt?

In diesem Modul habe ich gelernt, wie man einen "Phishing-Link" mittels einer "Session Fixation" erstellen kann.

## Beschreibung

Bei der Session Fixation geht es darum, dem "Opfer" seine eigene Session-ID unterzujubeln, damit sich dieser Benutzer quasi für den Benutzer anmeldet. Dies geht, da JSF bereits beim "Eingloggbildschirm" eine SessionID erstellt, welche man sich einfach über die "Entwicklertools" des Browsers raussuchen kann. Diese SessionID kopiert der "Angreifer" dann schliesslich in den Link der Anmeldeseite und schickt diesen dem Opfer per E-Mail zu, meistens in Form einer Phishing Mail.

Ein solcher Link und Mail können zum Beispiel so aussehen:

![Screenshot 2022-12-15 102332](https://user-images.githubusercontent.com/69889967/207822006-09851e90-81fb-4112-a15e-e8b8ace29a48.png)


* Ein deutliches, aussagekräftiges Bild oder eine kommentierte Bildschirm-Aufnahme
* Ein gut dokumentierter Code-Fetzen
* Ein Link zu einem *selbst aufgenommenen* youtube-Video oder `.gif`.

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
