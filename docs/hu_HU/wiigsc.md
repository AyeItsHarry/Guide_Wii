---
title: "Wii játék shortcut-ok létrehozása"
---

{% include toc title="Tartalomjegyzék" %}

Használsz Wii backup betöltőt, és szeretnél játék parancsikonokat létrehozni, hogy elindíthasd őket a Wii menüjében? Akkor próbáld ki a WiiGSC-t (Wii Game Shortcut Creator), korábbi nevén Crap.

Brick esetén a [Priiloader telepítése elengedhetetlen](/priiloader). Továbbá telepítsd a BootMii-t (Boot2-ként, ha korai Wii-d van). A brickvédelem telepítése az útmutató helyes követésével együtt megóv a brickelődéstől. NE FOLYTASD, AMÍG NEM TELEPÍTETTED A PRIILOADER-T ÉS A BOOTMII-T!
{: .notice--warning}

NE készíts parancsikont a "Mario Party 9" vagy az "A Boy and His Blob" játékokhoz. Ez brickeli a Wii-odat.
{: .notice--warning}

A Wii menü 48 csatornára van korlátozva, nem számítva a meglévő rendszercsatornákat.
{: .notice--info}

### Követelmények

* Egy Wii
* Egy SD kártya vagy USB drive
* [YAWM ModMii Edition](yawmme)
* Egy Windows számítógép.
* [WiiGSC](https://wiidatabase.de/downloads/pc-tools/wiigsc-ehemals-crap/)

### Útmutató

1. Telepítsd a WiiGSC-t, majd kattints rá a jobb gombbal, és válaszd a **Futtatás rendszergazdaként** lehetőséget. Ha ezt nem teszed meg, a WiiGSC hibát fog dobni, amikor megnyitod.

    ![](/images/desktop-apps/wiigsc/wiigsc-home.png)

2. Válaszd ki az SD-kártyán vagy USB-meghajtón lévő ISO- vagy WBFS-fájl elérési útvonalát, és válaszd ki a használt betöltőt. A többi beállításnak úgy kell lennie, ahogy van.

    ![](/images/desktop-apps/wiigsc/wiigsc-selection.png)

Ha vWii-n vagy, használd a [Wiiforwarder2vWii](https://gbatemp.net/download/wiiforwarder2vwii-wii-forwarder-to-vwii-wii-u-forwarder-converter-beta-version.37254/) eszközt, hogy a WAD-et a vWii-n való használatra konvertáld.
{: .notice--info}

3. Telepítsd a generált WAD-et a [WAD manager](yawmme)-eddel.

<div class="notice--info" markdown="1">
Ha hibaüzenetet kapsz "The system files are corrupted", ne ess pánikba, ha telepítetted a Priiloader-t. Turn off your Wii, then [boot into Priiloader](priiloader#section-iii---entering-priiloader) using one of the available methods for your console. Lépj be a Homebrew Channel csatornába, és indítsd el a WAD managert a WAD eltávolításához. If priiloader was not installed, proceed to [BlueBomb](bluebomb).
</div>

[Kattints ide a tartalomjegyzékhez való visszatéréshez!](site-navigation)
{: .notice--info}