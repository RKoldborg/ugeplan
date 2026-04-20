# 📅 Ugeplan – A4 print

**Giv børnene deres egen ugeplan – så de selv kan se holde sig opdateret uden skærme.**

Et lille gratis værktøj til forældre der bruger SkoleIntra. Du kopierer ugeplanen fra SkoleIntra, indsætter den her, og får den omdannet til en overskuelig, farverig A4-oversigt klar til print. Hæng den på køleskabet, så børnene selv kan følge med i ugen.

---

## Hvad gør det?

Siden læser den rå tekst fra SkoleIntra og reorganiserer den automatisk til en landskabs-A4 med én kolonne per ugedag. Hver dag viser fag, tidspunkter og beskrivelser fra lærerne – præcis som de er skrevet, uden fortolkning.

- **Ingen AI** – teksten struktureres udelukkende ved hjælp af mønstergenkendelse
- **Ingen login** – siden kræver ingen konto, ingen app og ingen installation
- **Ingen data forlader din browser** – al behandling sker lokalt på din enhed
- **Print-klar** – A4 landskab med farver der printer korrekt
- **Tilpasser sig indholdet** – skriftstørrelsen skalerer automatisk så alt passer på én side
- **Virker for alle klassetrin** – inkl. 0. klasse hvor ugeplanen typisk ikke har fag men aktiviteter

---

## Sådan bruger du siden

### 1. Åbn SkoleIntra i mobilvisning
Gør browservinduet smallere (eller brug din telefon), så siden skifter til mobilvisning med harmonika-menuer.

### 2. Åbn alle afsnit
Tryk på **Generelt** og alle ugedagene, så hele ugeplanen er synlig på skærmen.
> **Tip:** Start nedefra og arbejd opad – så går det hurtigst!

### 3. Kopier al tekst
Vælg alt på siden med **Ctrl/Cmd + A** og kopier med **Ctrl/Cmd + C**.

### 4. Indsæt og generer
Gå til [https://rkoldborg.github.io/ugeplan](https://rkoldborg.github.io/ugeplan), sæt teksten ind i feltet og tryk **"Strukturér ugeplan"** – eller brug **Ctrl/Cmd + Enter**.

### 5. Print eller gem som PDF
Tryk 🖨️ og vælg **"Gem som PDF"** for at gemme eller dele planen med dit barn.

---

## Videovejledning

Se en kort demonstration af hvordan siden bruges:
👉 [https://www.youtube.com/watch?v=LA425kGmmWE](https://www.youtube.com/watch?v=LA425kGmmWE)

---

## Tekniske detaljer

Siden er én enkelt HTML-fil uden eksterne afhængigheder udover Google Fonts. Der bruges ingen server, ingen database og ingen tredjeparts-tjenester. Alt kører i browseren.

Struktureringen fungerer ved at:
1. Opdele teksten i en generel introduktion og dagssektioner baseret på dagsoversrifter (fx "Mandag 20. apr.")
2. Identificere skemablokken nederst i hver dagssektion (tidslinje + fagkode-par som `08:00 - 08:45 / 03Y DAN 3yL`)
3. Matche fagbeskrivelser fra lærerens tekst til de tilsvarende slots i skemablokken
4. Gengive resultatet som en skaleret A4-side med adaptiv skriftstørrelse

---

## Disclaimer

Ugeplanen genereres direkte fra den tekst du indsætter og kan indeholde fejl eller mangler – fx hvis SkoleIntra-teksten er ustruktureret, indeholder usædvanlige fagkoder eller afviger fra det forventede format. Tjek altid den originale ugeplan på SkoleIntra ved tvivl.

Siden stilles gratis til rådighed **som den er og forefindes**, uden garanti for nøjagtighed eller tilgængelighed.

---

## Om projektet

Lavet af **Rune Koldborg J** som et lille side-projekt til eget brug – og delt frit i håb om at det kan være nyttigt for andre forældre.

Kildekoden er åben og kan ses og genbruges frit herfra.
