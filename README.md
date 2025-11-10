# 📌 Pòster Jornades IdISBa 2025

Aquest repositori conté el projecte per generar el pòster de les Jornades IdISBa 2025 utilitzant **Quarto** i **Typst** per garantir la reproductibilitat.


## 🔍 Visualització del pòster
El PDF es pot descarregar directament des d’aquest enllaç:  
👉 **[Descarregar pòster](poster_plataforma_2025.pdf)**

---

## 📂 Contingut del projecte
- **`poster_plataforma_2025.qmd`** → Fitxer principal Quarto amb el contingut del pòster.
- **`ref.bib`** → Fitxer de bibliografia en format BibTeX. No s'ha inclòs al póster, però està la plantilla està preparada.
- **`poster_plataforma_2025.pdf`** → Versió renderitzada del pòster (PDF).
- **`_extensions.yml`** → Manifest de l’extensió Quarto:
  - Defineix quina plantilla Typst s’utilitza (`typst-template.typ`).
  - Exposa paràmetres configurables des del YAML del `.qmd` (mides, colors, columnes).
- **`typst-template.typ`** → Plantilla principal Typst:
  - Defineix la funció `poster(...)` que construeix el disseny.
  - Controla tipografies, marges, columnes, interlineat i espais.
  - Rep els paràmetres del YAML i aplica el layout.
- **`typst-show.typ`** → Regles d’estil:
  - Configura headings (`#v(...)` per espais abans/després).
  - Defineix interlineat (`leading`) i espai entre paràgrafs (`spacing`).
  - Permet modularitzar l’estil per mantenir el codi net.

---

## ▶️ Com reproduir el pòster (RStudio)
1. **Instal·la Quarto** (ja instal·lat):  
   https://quarto.org/docs/get-started/

2. **Instal·la Typst** (ja instal·lat):  
   https://typst.app

3. **Obre el projecte a RStudio**:
   - Assegura’t que el directori conté el fitxer `poster.qmd`.

4. **Renderitza el pòster**:

```bash
   quarto render poster.qmd
```