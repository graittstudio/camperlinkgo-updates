# CamperLinkGo - installatie en updates

Hier staan de installatiebestanden (APK's) van **CamperLinkGo**, een Android-app om camperplekken te vinden, te bewaren en erheen te navigeren. Een grAItt Studio-app.

Deze map bevat alleen de APK's onder **Releases**. Er staat geen broncode en geen persoonlijke gegevens in.

## Installeren (eerste keer)

1. Open de [nieuwste release](../../releases/latest) op je Android-telefoon.
2. Tik onder **Assets** op het bestand `camperlinkgo-<versie>.apk` en download het.
3. Open het bestand. Android vraagt eenmalig om **installeren uit onbekende bronnen** toe te staan voor je browser. Dat staat je toe via *Instellingen* in dat venster.
4. Als Google Play Protect waarschuwt dat het een onbekende app is, kies **Toch installeren**.

## Updates

De app kijkt zelf of hier een nieuwere versie staat (hooguit één keer per dag, en met een tik in het menu onder **Controleer op updates**). Staat er een nieuwere versie, dan verschijnt bovenin de app **Nieuwe versie beschikbaar** met een knop **Installeren**. Je favorieten, foto's en instellingen blijven staan.

De app controleert voor het installeren of de update met de eigen sleutel van CamperLinkGo is ondertekend. Een bestand met een andere sleutel wordt niet geïnstalleerd.

## Controleren dat een bestand echt van ons is

Het ondertekeningscertificaat van de APK's heeft deze SHA-256-vingerafdruk:

```
03:88:61:B4:39:0C:F3:16:36:8C:86:F3:2E:AC:CA:B9:CF:B2:7D:B2:94:1C:42:DD:32:F4:A9:82:B6:EB:E8:04
```

Met de Android SDK controleer je dat met `apksigner verify --print-certs bestand.apk`.

## Privacy

CamperLinkGo bewaart je favorieten, foto's en camper alleen op je eigen telefoon. Voor kaarten, plaatsen zoeken en camperplekken gebruikt de app OpenStreetMap-diensten; je locatie wordt alleen gebruikt terwijl de app open is.
