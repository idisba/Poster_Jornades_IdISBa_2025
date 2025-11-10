# Pòster Jornades IdISBa 2026

Aquest repositori conté el projecte per generar el pòster de les Jornades IdISBa 2026 utilitzant **Quarto** i **Typst** per garantir la reproductibilitat.

## 📄 Contingut
- `poster.qmd` → Fitxer principal Quarto amb el contingut del pòster.
- `typst-template.typ` → Plantilla Typst per al disseny del pòster.
- `ref.bib` → Fitxer de bibliografia en format BibTeX.
- `poster.pdf` → Versió renderitzada del pòster (PDF).

## 🔍 Visualització del pòster
El PDF es pot descarregar directament des d’aquest enllaç:  
[**Descarregar pòster**](poster.pdf)

*(Si GitHub Pages està activat, també pots veure’l incrustat en una pàgina HTML.)*

## ▶️ Com reproduir el pòster
1. **Instal·la Quarto**  
   [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/)

2. **Instal·la Typst**  
   [https://typst.app](https://typst.app)

3. **Renderitza el pòster**  
   ```bash
   quarto render poster.qmd