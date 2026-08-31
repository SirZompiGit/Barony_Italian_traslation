<div align="center">

![Barony ITA](https://i.postimg.cc/sgNkF2QX/small-preview.png)

# Barony ITA — Traduzione italiana / Italian Translation

**Versione mod `v0.6` · Compatibile con Barony `v5.0.2`**
*Instruments of Destruction: Part 1 + DLC Deserters & Disciples*

[![Discord](https://img.shields.io/badge/Discord-entra-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/enbZQV2s49)
[![Steam Workshop](https://img.shields.io/badge/Steam_Workshop-iscriviti-1b2838?style=for-the-badge&logo=steam&logoColor=white)](https://steamcommunity.com/sharedfiles/filedetails/?id=3641251022)

**[🇮🇹 Italiano](#-italiano) · [🇬🇧 English](#-english)**

</div>

---

## 🇮🇹 Italiano

Mod di traduzione in italiano di **Barony**, DLC inclusi.

### ✨ Novità della v0.6

La v0.6 riscrive la mod da zero sui file di **Barony v5.0.2**, l'aggiornamento *Instruments of Destruction: Part 1* con il DLC *Deserters & Disciples*.

> [!IMPORTANT]
> **Se usi ancora la v0.5.1 su Barony 5.0.2, disinstallala.** Barony sostituisce per intero i file di dati forniti da una mod: i file della v0.5.1 sono quelli del gioco 4.3.2 e toglierebbero dal gioco **192 oggetti e 163 incantesimi**, oltre a tooltip, mostri e luci del nuovo aggiornamento.

**Tradotto tutto il contenuto nuovo di v5.0.2**

| | |
|---|---|
| 🧙 **5 classi** | Bardo, Guastatore, Erede, Eremita, Paladino |
| 🌿 **5 razze** | Driade, Miconide, Salamandra, Gremlin, Gnomo |
| 🔮 **~80 incantesimi** | e 3 nuove scuole di magia (Stregoneria, Misticismo, Taumaturgia) |
| 🏺 **Stazioni di utilità** | calderone, officina, forziere del vuoto, altare Assist |
| 🔑 **Serrature e pulsanti** | chiavi, serrature a muro, portoni di ferro |
| 🏆 **~70 obiettivi** | nomi e descrizioni |
| 🪧 **Cartelli del dungeon** | file mai tradotto prima |

**Copertura**

| File | Stato |
|---|---|
| `lang/en.txt` | 5.728 / 5.728 voci |
| Nomi oggetti e incantesimi | 524 oggetti + 212 incantesimi |
| Tooltip oggetti | 126 tooltip + 578 template |
| Compendio | Codex, Oggetti, Magia, Mostri, Mondo, Obiettivi |
| Libri leggibili | 34 / 34 |
| Tutorial | 11 script + cartelli del dungeon |
| Storia e finali | 21 file |
| Temi | Merry, Scarony |

In totale **16.105 stringhe tradotte**.

**Metrica e formattazione**

Il vincolo di questa versione è che il testo italiano **stia dentro i riquadri**. Ogni stringa è stata misurata contro l'originale inglese:

- le 1.238 voci di `lang/en.txt` che sforavano sono state riscritte
- le 282 righe del compendio che uscivano dal pannello sono state rispezzate (l'inglese sta in 46 colonne, l'italiano arrivava a 66)
- ricalcolati gli indici che dipendono dal testo tradotto: evidenziazioni della ruota dei richiami e dei cartelli tutorial, indici di riga delle descrizioni razza

**Correzioni a bug della v0.5**

- 6 voci che inglobavano la chiave successiva — in gioco si leggeva letteralmente `5085 o premi X per cancellare`
- 4 chiavi duplicate che nascondevano i nomi dei mirini
- il pulsante "Entra nel Dungeon" mostrava il testo sbagliato
- il tratto **"Nuoto più veloce"** era sparito dalla razza Umano
- un `%d` di troppo che poteva far sballare l'output
- 199 voci con uno spazio di troppo a inizio riga, che spostava il testo a destra
- un BOM UTF-8 e una lettera accentata nei libri, che in gioco si vedevano come caratteri strani

**Mod più leggera**

Da **692 a 102 file** (11 MB → ~2 MB). Erano rimaste dentro 590 copie identiche di file del gioco: 323 PNG di oggetti, i modelli del compendio, i temi, il font, la guida in PDF. Ora la mod contiene solo i file che hanno davvero testo tradotto.

**Stile**

- Nomi di oggetti e incantesimi compatti in stile videogioco (`pozione cura`, `pergamena identifica`, `libro fulmine`)
- Glossario di **327 termini fra parentesi quadre** normalizzato: un concetto ha sempre lo stesso nome in tutta la mod
- Testo interamente **ASCII** (`e'`, `perche'`, `piu'`): i font `pixel_maz` usati dai cartelli non hanno i glifi accentati
- Logo del titolo con lo scudo nei colori della bandiera italiana

### ✅ Compatibilità

**Barony v5.0.2** (Instruments of Destruction: Part 1 + DLC Deserters & Disciples).

> [!WARNING]
> Per le versioni precedenti del gioco usa la **v0.5.1**, non questa.

### 📥 Installazione

1. Vai su **[Releases](../../releases)** e scarica l'ultima versione (`Source code`).
2. Estrai lo ZIP.
3. Copia **il contenuto della cartella** dentro la cartella `mods` nella directory principale di Barony.
4. Avvia il gioco e attiva la mod dal menu **Mods**.

**Trovare la cartella del gioco (Steam):** tasto destro su *Barony* → **Proprietà** → **File installati** → **Sfoglia**.

In alternativa, iscriviti alla mod dalla [pagina Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3641251022).

### ⚠️ Cosa resta in inglese (di proposito)

- Nomi propri: Dyrnwyn, Gungnir, Parashu, Sharur, Khryselakatos, Baphomet, Robin Hood…
- Il latino dei cartelli dell'Underworld e dell'Inferno
- I nomi interni dei comandi nei tutorial: il gioco li usa per pescare l'icona del tasto, tradurli romperebbe i glifi

### 🔧 Roadmap

- Verifica in gioco di tutte le schermate e correzione di eventuali sovrapposizioni residue
- Rifinitura stilistica dove il testo è stato accorciato molto per rientrare
- Aggiornamento a *Instruments of Destruction: Part 2* quando uscirà

### 👥 Autori

- **SirZompi**
- **JustKoal96**

**Partecipanti:** Thombi

### 🤝 Contribuire

Il progetto è **pubblico**: chiunque può aiutare e diventare collaboratore.

- Segnala stringhe mancanti, testi tagliati o sovrapposti → [Issues](../../issues) o [Discord](https://discord.gg/enbZQV2s49)
- Proponi correzioni di traduzione o miglioramenti di stile
- Apri una Pull Request

Quando segnali un problema di testo, allega uno **screenshot** e indica dove appare: è la cosa più utile per correggerlo in fretta.

---

## 🇬🇧 English

Italian translation mod for **Barony**, DLCs included.

### ✨ What's new in v0.6

v0.6 rebuilds the mod from scratch on the **Barony v5.0.2** data files — the *Instruments of Destruction: Part 1* update with the *Deserters & Disciples* DLC.

> [!IMPORTANT]
> **If you are still running v0.5.1 on Barony 5.0.2, uninstall it.** Barony fully replaces the data files a mod provides: the v0.5.1 files are the 4.3.2 ones and would strip **192 items and 163 spells** out of the game, along with tooltips, monsters and lights from the new update.

**All new v5.0.2 content translated**

| | |
|---|---|
| 🧙 **5 classes** | Bard, Sapper, Scion, Hermit, Paladin |
| 🌿 **5 races** | Dryad, Myconid, Salamander, Gremlin, Gnome |
| 🔮 **~80 spells** | plus 3 new magic schools (Sorcery, Mysticism, Thaumaturgy) |
| 🏺 **Utility stations** | cauldron, workbench, void chest, Assist shrine |
| 🔑 **Locks and buttons** | keys, wall locks, iron doors |
| 🏆 **~70 achievements** | names and descriptions |
| 🪧 **Dungeon signs** | a file that had never been translated |

**Coverage**

| File | Status |
|---|---|
| `lang/en.txt` | 5,728 / 5,728 entries |
| Item and spell names | 524 items + 212 spells |
| Item tooltips | 126 tooltips + 578 templates |
| Compendium | Codex, Items, Magic, Monsters, World, Achievements |
| Readable books | 34 / 34 |
| Tutorials | 11 scripts + dungeon signs |
| Story and endings | 21 files |
| Themes | Merry, Scarony |

**16,105 translated strings** in total.

**Text metrics**

The hard rule for this release is that Italian text must **fit inside the UI boxes**. Every string was measured against the English original:

- the 1,238 `lang/en.txt` entries that overflowed were rewritten
- the 282 compendium lines that spilled out of the panel were re-wrapped (English fits in 46 columns, Italian was reaching 66)
- indices that depend on the translated text were recomputed: callout-wheel and tutorial-sign word highlights, race description line indices

**Bugs fixed from v0.5**

- 6 entries that swallowed the following key — in-game you literally read `5085 o premi X per cancellare`
- 4 duplicate keys that hid the crosshair names
- the "Enter Dungeon" button showed the wrong text
- the **"Faster swimming"** trait had gone missing from the Human race
- a stray `%d` that could garble output
- 199 entries with an extra leading space that shifted the text right
- a UTF-8 BOM and an accented letter in the books, which showed up as garbage characters

**Slimmer mod**

From **692 to 102 files** (11 MB → ~2 MB). 590 byte-identical copies of game files were still in there: 323 item PNGs, the compendium models, the themes, the font, a PDF guide. The mod now ships only the files that actually carry translated text.

**Style**

- Compact, game-style item and spell names (`pozione cura`, `pergamena identifica`, `libro fulmine`)
- A normalised glossary of **327 bracketed terms**: one concept always uses the same word across the whole mod
- Fully **ASCII** text (`e'`, `perche'`, `piu'`): the `pixel_maz` fonts used by signs have no accented glyphs
- Title logo with the shield in the colours of the Italian flag

### ✅ Compatibility

**Barony v5.0.2** (Instruments of Destruction: Part 1 + Deserters & Disciples DLC).

> [!WARNING]
> For older game versions use **v0.5.1**, not this one.

### 📥 Installation

1. Go to **[Releases](../../releases)** and download the latest version (`Source code`).
2. Extract the ZIP.
3. Copy **the folder contents** into the `mods` folder in Barony's main directory.
4. Launch the game and enable the mod from the **Mods** menu.

**Finding the game folder (Steam):** right-click *Barony* → **Properties** → **Installed Files** → **Browse**.

Alternatively, subscribe on the [Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=3641251022).

### ⚠️ What stays in English (on purpose)

- Proper nouns: Dyrnwyn, Gungnir, Parashu, Sharur, Khryselakatos, Baphomet, Robin Hood…
- The Latin on the Underworld and Hell signs
- Internal command names in the tutorials: the game uses them to look up the key icon, translating them would break the glyphs

### 🔧 Roadmap

- In-game pass over every screen to catch any remaining overlap
- Polishing the wording where text had to be cut short to fit
- Update for *Instruments of Destruction: Part 2* when it lands

### 👥 Authors

- **SirZompi**
- **JustKoal96**

**Contributors:** Thombi

### 🤝 Contributing

The project is **public**: anyone can help out and become a collaborator.

- Report missing strings, cut-off or overlapping text → [Issues](../../issues) or [Discord](https://discord.gg/enbZQV2s49)
- Suggest translation fixes or style improvements
- Open a Pull Request

When reporting a text issue, attach a **screenshot** and say where it appears — that's the single most useful thing for fixing it quickly.
