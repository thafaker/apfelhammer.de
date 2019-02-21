---
layout: post
title: Apple Magic Mouse - Windows 10 Scroll Probleme
date: 2019-02-21 18:15
image: "/scroll.JPG"
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
**Ihr** habt euch auf eurem _Mac Pro_ (oder iMac oder Macbook) Windows 10 installiert und alles ist toll. Dann aber stellt ihr fest, dass die _Apple Magic Mouse_ nicht richtig funktioniert. <!--more-->

Ihr habt sie über Bluetooth gepaired. [^1] Zwar könnt ihr klicken und sie benutzen, aber die _Scroll-Funktion_ liegt brach. Das nervt, gerade weil man heutzutage praktisch überall scrollen muss. Aber zum Glück gibt es einfache Abhilfe: [^2]

1. Ladet euch das [Bootcamp Treiber Paket](https://support.apple.com/kb/dl1720?locale=en_US) von Apple herunter. In meinem Falle war es das hier <code>BootCamp5.1.5621.zip</code>.
2. Entpackt die ZIP-Datei.
3. Öffnet das entpackte Archiv und wechselt in dem Pfad <code>\BootCamp5.1.5621\BootCamp\Drivers\Apple</code> und installiert folgende Datei: <code>AppleWirelessMouse64.exe</code>
4. Deaktiviert die Maus, aktiviert sie wieder und schon sollte die Scrollfunktion zur Verfügung stehen.

![Windows BootCamp Treiber Magic Mouse](/assets/2019/02/treiber.JPG)<small>Windows BootCamp Treiber Magic Mouse</small>

Das wars auch schon wieder :-)

_Bis bald._

---

<small>
**Artikelbild**: Photo by [Michał Kubalczyk](https://unsplash.com/photos/zjn17WVQAZ4?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on Unsplash.
</small>

---

**Fußnoten**:

[^1]: Der Code lautet gemeinhin _0-0-0-0_ oder _1-2-3-4_.
[^2]: Out-Of-The-Box wäre natürlich noch schöner, aber oft kann man einfach nicht alles haben.