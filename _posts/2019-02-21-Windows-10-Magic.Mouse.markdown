---
layout: post
title: Apple Magic Mouse - Windows 10 Scroll Probleme
date: 2019-02-21 18:15
image: scroll.jpg
tags:
- Windows 10
- Apple
- Probleme
- Bootcamp
- Magic Mouse
- Maus
- Anleitung
- HowTo

---
Ihr habt euch auf eurem Mac Pro (oder iMac) Windows 10 installiert und alles ist toll. Dann aber stellt ihr fest, dass die Magic Mouse nicht richtig funktioniert. <!--more-->
Ihr habt sie über Bluetooth gepaired. [^1] Zwar könnt ihr klicken und sie benutzen, aber die *Scroll-Funktion* liegt brach. Das nervt, gerade weil man heutzutage praktisch überall scrollen muss. Aber zum Glück gibt es einfache Abhilfe [^2].

1. Ladet euch das [Bootcamp Treiber Paket](https://support.apple.com/kb/dl1720?locale=en_US) von Apple herunter. In meinem Falle war es das hier <code>BootCamp5.1.5621.zip</code>.
2. Entpackt die ZIP-Datei.
3. Öffnet das entpackte Archiv und wechselt in dem Pfad <code>\BootCamp5.1.5621\BootCamp\Drivers\Apple\</code> und installiert folgende Datei: <code>AppleWirelessMouse64.exe</code>
4. Deaktiviert die Maus, aktiviert sie wieder und schon sollte die Scrollfunktion zur Verfügung stehen.

![Windows BootCamp Treiber Magic Mouse](/assets/2019/02/treiber.jpg)

Das wars auch schon wieder :-)

*Bis bald.*

---

<small>
**Artikelbild**: Photo by [Michał Kubalczyk](https://unsplash.com/photos/zjn17WVQAZ4?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on Unsplash.
</small>

---

**Fußnoten**:

[^1]: Der Code lautet gemeinhin *0-0-0-0* oder *1-2-3-4*.
[^2]: Out-Of-The-Box wäre natürlich noch schöner, aber oft kann man einfach nicht alles haben.