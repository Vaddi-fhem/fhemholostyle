# FHEM Holo Style
Holo custom Style für FHEMWEB

## Installation

1. Hinzufügen des neuen Styles

```
update add https://raw.githubusercontent.com/Vaddi-fhem/fhemholostyle/master/controls_holo-style.txt
update check holo-style
update all holo-style
```

2. Select Style -> holo-style

3. Ein paar Anpassungen am Web-Device:

```
attr WEB JavaScripts codemirror/fhem_codemirror.js holo-style/custom.js
attr WEB roomIcons Save.config:message_attention
```

Speichern, Seite neu laden (F5), fertig

## Fehler melden

Bitte [hier](https://github.com/Vaddi-fhem/fhemholostyle/issues) einen Issue erstellen

## Vorschau

![FHEM Style](https://raw.githubusercontent.com/Vaddi-fhem/fhemholostyle/master/preview.png)

## DANKE:

Danke an [Matthias Kleine](https://github.com/klein0r) [Haus-automatisierung.com](http://www.haus-automatisierung.com)

Danke @ https://dribbble.com/shots/2084609-Smart-House-Icon-Set-Free
