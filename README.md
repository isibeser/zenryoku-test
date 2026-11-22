# ZENRYOKU – Test-Fassungen

Frühe Test-Fassungen von **ZENRYOKU: Sigilborn**, dem Anime-Kampfspiel. Es kann ruckeln, abstürzen oder sich jederzeit ändern.
Diese Seite wird bei jeder neuen Fassung automatisch aktualisiert.

## Android

1. Am Handy öffnen: **[ZENRYOKU.apk herunterladen](https://github.com/isibeser/zenryoku-test/releases/download/zenryoku/ZENRYOKU.apk)**
2. Datei öffnen → **Installieren** (beim ersten Mal „Aus dieser Quelle zulassen“ erlauben).

Neue Fassung: denselben Link wieder öffnen und **drüber installieren** – dein Spielstand bleibt. Die App zeigt im Hauptmenü selbst an,
wenn es eine neue Fassung gibt („LADEN“).

**Einmalig:** Seit dem Wechsel auf den festen App-Schlüssel (Ende November 2026) musst du die alte App **ein letztes Mal löschen** und
neu installieren (Spielstand mitnehmen: vorher unter Optionen → Konto & Daten den Code notieren, danach „Code eingeben“). Danach nie wieder.

**Updates automatisch melden lassen (optional):** die kostenlose App **Obtainium** installieren (z. B. über F-Droid) → **App hinzufügen** →
Adresse `https://github.com/isibeser/zenryoku-test` → Hinzufügen. Neue Fassungen kommen dann als Benachrichtigung.

## iPhone (über SideStore)

Voraussetzung: SideStore ist auf deinem iPhone eingerichtet (einmalig mit PC/Mac und Kabel – Anleitung auf https://sidestore.io).

1. LocalDevVPN verbinden, SideStore öffnen.
2. Tab **Quellen** (Sources) → **+** → diese Adresse einfügen:

   `https://raw.githubusercontent.com/isibeser/zenryoku-test/main/quelle.json`

3. In der Quelle **ZENRYOKU** antippen → **Holen / Installieren**.
4. Neue Fassungen erscheinen in SideStore unter **Updates** → antippen.

### Nie wieder ablaufen lassen (einmal einrichten)

Apps über SideStore laufen 7 Tage, dann müssen sie verlängert werden. Das macht dein iPhone so jeden Abend selbst:

**Kurzbefehl anlegen** (App „Kurzbefehle“ → **+**, Name „Apps verlängern“):
1. Aktion **VPN festlegen** → VPN: **LocalDevVPN** → **Verbinden**
2. Aktion **Warten** → 3 Sekunden
3. Aktion von SideStore: **Refresh All Apps** – dort „Beim Ausführen anzeigen“ **aus**

**Automation 1** (Tab „Automation“ → **+** → **Tageszeit**): 21:00, **Täglich**, **Sofort ausführen** → Kurzbefehl „Apps verlängern“.

**Automation 2**: 21:10, **Täglich**, **Sofort ausführen** → neue leere Automation → **VPN festlegen** → LocalDevVPN → **Trennen**.
(Eigene Automation, weil der Kurzbefehl nach dem Verlängern manchmal stehen bleibt.)

Dazu: Einstellungen → Allgemein → **Hintergrundaktualisierung** → SideStore **an**.

**Testen:** den Kurzbefehl einmal von Hand starten und alle Nachfragen erlauben. Danach steht in SideStore bei den Apps wieder „7 DAYS“.
In den ersten Wochen ab und zu nachsehen, ob dort weiterhin 7 Tage stehen – auch bei SideStore selbst.

**Wichtig:** Nie ganz ablaufen lassen. Ist auch SideStore abgelaufen, musst du es wieder am PC einrichten.
