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


[![Demonstration](https://img.youtube.com/vi//0.jpg)](https://www.youtube.com/watch?v=nefWV0PMeh4)

## Verifikation

Bild: grobe "Struktur" einer Phishing Mail
Video: Demonstration


# Reflektion zum Arbeitsprozess

Gut: Was bei diesem Auftrag gut lief, oder was mir zumindest viel Freude bereitet hat, war das Schreiben der Phishing Mail.

Schlecht: Manchmal hatte ich das Problem, dass der Browser die Adresse nicht finden konnte und erhielt dann eine "Error 404" Fehlermeldung, Neustarten hat da meistens geholfen.

In diesem Modul hatte ich teilweise ein Paar "halbfertige" Arbeitsaufträge liegen gelasssen, beim nächsten Mal sollte ich darauf achten, dass wenn ich nicht in der Schule mit diesen fertig werden, sie vielleicht noch eventuell Zuhause vollenden sollte.

