---
layout: single
classes: wide
title: Über mich
permalink: /about/
author_profile: true
read_time: true
comments: true
---

Hallo, 
mein Name ist Dominik Schön. Ich beschäftige mich seit ca. 2005 mit den Themen Smart Home, Smart Building und Energieverbrauchsoptimierung im Eigenheim.

Die ersten Schritte
---

Begonnen hat alles in meiner 18 qm Ein-Zimmer-Studentenwohnung. Die Heizungsthermostate waren zu träge, um auf diesem kleinen Raum eine einigermaßen angenehme Raumtemperatur einzustellen. Noch schlimmer in einem Bad, das samt Duschkabine vielleicht 3 qm umfasste. Ich hab mich also ans tüfteln gemacht. Eingelesen und über [HomeMatic](https://www.eq-3.de/produkte/homematic.html) gestolpert. Gelesen, dass man HomeMatic Komponenten auch mittels eines USB-Sticks und ein bisschen Software auch steuern und programmieren könnte und dadurch zu [FHEM](https://fhem.de) auf einem Raspberry Pi gekommen.

Aus diesem Setup wurde zügig eine komfortable Regelung meines kleinen Reichs. Wenn ich die Wohnung verlassen hatte, wurde automatisch die Heizung ausgeschaltet. Bevor ich zurück kam, ging sie automatisch wieder an. Während ich zu Hause war, wurde die Temperatur durch eine PID-Steuerung und eine Pulsweitenmodulierung so geregelt, dass nahezu konstant eine angenehme Temperatur in der Wohnung herrschte.




Ich vergrößerte mich
---

Natürlich blieb ich nicht ewig in der 18 qm Wohnung. Mit dem nächsten Umzug in eine Zwei-Zimmer Wohnung konnte ich die bestehenden Komponenten mitnehmen. Der Handtuchwärmer wurde automatisch aufgewärmt, wenn meine Freundin oder ich zuhause waren. Die neue Siebträgermaschine dann automatisch vorgeheizt und wenn das Badfenster beim Verlassen der Wohnung noch offen war, gab es eine Benachrichtigung auf's Handy.




Eigentum
---

Mit dem nächsten Umzug erfüllten wir uns den Traum einer eigenen Wohnung - und die Möglichkeiten zur Automatisierung nahmen zu. Fußbodenheizung, eine Ventilsteuerung im Heizkreisverteiler, Wandthermostate in allen Räumen. Natürlich war da der Drang groß, auch die Fußbodenheizung zu steuern.

Aus dem Raspberry Pi wurde ein selbstgebauter Home-Server, der speziell auf einen niedrigen Stromverbrauch abzielt. Durch diesen Schritt war es mir möglich, verschiedene Systeme auf einem Rechner zu kombinieren. Backup-Speicher, Medienzentrale, Netzwerkspeicher für unser papierloses Büro, Smart Home, und so weiter waren nun alle an einem Ort gesammelt.




Das Haus
---

Seit 2019 lebe ich mit meiner Frau in einem Einfamilienhaus im Umland von Nürnberg. Seit dem Bezug dieses Hauses hat sich auch mein Setup etwas geändert. Neben den nach wie vor verwendeten HomeMatic-Komponenten ist ein free@home Bus-System in dem Haus verbaut. Geheizt wird über eine Luft-Wasser Wärmepumpe. 2020 wurde eine Photovoltaikanlage nachgerüstet und 2021 ein Elektroauto angeschafft. Es gibt also einiges an Optimierungspotenzial beim Stromverbrauch.

| Anwendungszweck        | Eingesetztes System| 
| ------------- |-------------| 
| Heizung      | [Viessmann Vitocal 200-S](https://www.viessmann.de/de/wohngebaeude/waermepumpe/split-luft-wasser-waermepumpen/vitocal-200-s.html) in Kombination mit [Vitoconnect 100](https://www.viessmann.de/de/viessmann-apps/vitoconnect-opto-ot2.html)| 
| Einzelraumregelung Temperatur     | [Busch-free@home](https://www.busch-jaeger.de/busch-freehome)      | 
| Photovoltaik | [17x Trina Solar 305 W, 2x SMA Sunny Boy 5.0, Sunny Boy Storage 5.0, BYD Battery-Box H 10,2 kWh](https://www.sunnyportal.com/Templates/PublicPageOverview.aspx?plant=54eadbb3-27af-44c9-8784-798b7ec81c95)      | 
|Steuerung Stromverbraucher| [Busch-free@home](https://www.busch-jaeger.de/busch-freehome) und [HomeMatic](https://www.eq-3.de/produkte/homematic.html) |
|Steuerung Licht| [Busch-free@home](https://www.busch-jaeger.de/busch-freehome), lifx und IKEA Tradfri |
|Wasserenthärtung| [Grünbeck softli.Q SD18](https://www.gruenbeck.de/produkte-branchen/produkte/enthaertungsanlagen/kalkschutz/softliqsd18/) |
|Mobilität| SMA EV Charger, Hyundai Kona electric (64kWh), NIU N1 |