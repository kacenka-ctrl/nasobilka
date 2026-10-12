[README.md](https://github.com/user-attachments/files/33349446/README.md)
# 🚨 Záchranná akademie: Násobilka a dělení (3. třída)

Aplikace pro procvičování malé násobilky a dělení přizpůsobená na mobilní telefony (orientace na výšku – **Portrait mode**) s offline režimem a možností instalace přímo na plochu telefonu jako **PWA (Progressive Web App)**.

Obsahuje dvě motivující mise:
- 🚒 **Hasičský zásah:** Správný výpočet stříká vodu a hasí požáry budov, dítě postupuje od *Mladého hasiče* až po *Velitele zásahu*.
- 🚔 **Policejní zátah:** Správný kód zaklapne pouta a dopadne prchajícího lupiče, postup od *Kadeta* až po *Policejního prezidenta*.

---

## 📁 Struktura repozitáře

```text
├── index.html          # Hlavní portál / rozcestník misí s podporou PWA
├── hasici.html         # Hasičská verze hry (mobilní na výšku)
├── police_game.html    # Policejní verze hry (mobilní na výšku)
├── manifest.json       # PWA konfigurace (uzamčení na výšku, ikona, barvy)
├── sw.js               # Service Worker pro hraní offline bez internetu
└── README.md           # Návod na zprovoznění


## 📱 Jak aplikaci stáhnout a nainstalovat do mobilu

Díky standardu **PWA (Progressive Web App)** se aplikace chová jako běžná stažená aplikace z Google Play nebo App Store: nemá adresní řádek prohlížeče, je uzamčená na výšku a funguje i bez připojení k internetu (v autě, vlaku atd.).

### Pro telefony se systémem Android (Chrome):
1. Otevřete odkaz `https://<vase-jmeno>.github.io/nasobilka/` v prohlížeči **Google Chrome**.
2. Na úvodní obrazovce se zobrazí zelené tlačítko **„📲 Nainstalovat aplikaci do telefonu“** (nebo klepněte na 3 tečky vpravo nahoře a vyberte **„Přidat na plochu“** / **„Instalovat aplikaci“**).
3. Potvrďte instalaci.
4. Na ploše telefonu se vytvoří samostatná ikona **🚨 Násobilka**, která se spouští na celou obrazovku.

### Pro telefony Apple iPhone (Safari):
1. Otevřete odkaz v prohlížeči **Safari**.
2. Dole uprostřed klepněte na ikonu **Sdílet** (čtvereček se šipkou nahoru).
3. V nabídce sjeďte kousek níže a zvolte **„Přidat na plochu“** (*Add to Home Screen*).
4. Klepněte na **Přidat** vpravo nahoře.
5. Hra se uloží jako plnohodnotná aplikace přímo na plochu iPhone.

---

## 🎯 Herní a pedagogická pravidla
- **Žádné nudné opakování:** Dva totožné příklady se nikdy neobjeví po sobě. U násobení je povolena pouze komutativní záměna (např. $4 \times 3$ a následně $3 \times 4$), což posiluje pochopení principu násobení.
- **Výběr násobků:** Dítě si nahoře samo zaklikne libovolná čísla 1–10 (ve výchozím nastavení jsou předvybrány násobky 2, 3, 4 a 5 pro začátek 3. třídy).
- **Zadávání:** Velká dotyková tlačítka přímo na displeji, takže dítě nemusí bojovat s vyskakovací klávesnicí telefonu.
