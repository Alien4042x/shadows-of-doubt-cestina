# 🇨🇿 Shadows of Doubt – Čeština (verze v41.03)

Kompletní (AI-asistovaný) překlad hry **Shadows of Doubt** do češtiny.  

> ⚠️ Překlad využívá LLM model **Gemini** (Google), takže může obsahovat drobné chyby nebo divné fráze. Vše se ale postupně ladí!

---

## 📥 Instalace

1. Stáhni nejnovější verzi z [Releases na GitHubu](https://github.com/alien4042x/shadows-of-doubt-cestina/releases):
   - `Source code (zip)` **nebo** `Source code (tar.gz)`
   - [Zobrazit všechny verze →](https://github.com/alien4042x/shadows-of-doubt-cestina/releases)

2. Najdi složku, kde máš nainstalovanou hru, např.:

   ```
   C:\SteamLibrary\steamapps\common\Shadows of Doubt\Shadows of Doubt_Data
   ```

3. Rozbal stažený balíček a **nahraď** složku `StreamingAssets` tou novou ze staženého archivu.

4. Spusť hru – v nastavení jazyků by měla být k dispozici **čeština**.

---

## ⚠️ Známé nedostatky

- **Texty sdílející jeden překladový label** – např. `Bin` se používá pro `Odpadkový koš` i `Kontejner`. V češtině to zní jinak, ale engine hry to nerozlišuje.
- **Některé dialogy zůstanou v angličtině**, protože nejsou ještě přeloženy nebo se přidaly později (hlavně z `DDS/dds.blocks.csv`).
- **Fonty a diakritika** – některé znaky nejsou úplně perfektní, záleží na použitém fontu. Zvažuju vytvoření upraveného font assetu.
  
---

## 📌 Stav projektu

- [x] Základní překlad hotový
- [x] Přeloženy desítky systémových souborů (`blocks.csv`, `stringtables.csv`, atd.)
- [x] Průběžné ladění češtiny (stylistika, nejasnosti, příliš doslovný překlad)
- [x] Revize jednotlivých herních kontextů (UI, rozhovory, dokumenty)
- [x] Úprava fontů pro 100% kompatibilitu s diakritikou

---

## 🤝 Jak můžeš pomoct?

- Nahlas chyby, divné věty nebo špatné formátování jako **Issue**
- Nebo vytvoř **Pull Request** s návrhem úpravy
- Můžeš přispět i kontrolou kontextu vět (v některých případech engine používá jeden text pro více scén)

