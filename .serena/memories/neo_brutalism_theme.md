# Neo-Brutalism Theme für NOVA Template

## Übersicht
Ein vollständiges Neo-Brutalism Theme wurde für das NOVA Shop-Template erstellt.

## Erstellte Dateien
- `templates/NOVA/themes/brutalist/sass/_variables.scss` - Alle SCSS-Variablen
- `templates/NOVA/themes/brutalist/sass/_allstyles.scss` - Import aller Base-Styles
- `templates/NOVA/themes/brutalist/sass/_brutalist_overrides.scss` - Komponenten-Overrides
- `templates/NOVA/themes/brutalist/sass/brutalist.scss` - Haupt-SCSS
- `templates/NOVA/themes/brutalist/sass/brutalist_crit.scss` - Critical CSS
- `templates/NOVA/themes/brutalist/custom.css` - Fertige CSS-Overrides

## Design-Prinzipien

### Farbpalette
- Primary (Electric Yellow): `#FFDE00`
- Schwarz: `#000000`
- Weiß: `#FFFFFF`
- Rot: `#FF3B30`
- Blau: `#0066FF`
- Orange: `#FF6B00`
- Grün: `#00CC66`
- Pink: `#FF1493`
- Background Paper: `#FFFDF5`

### Typografie
- Font: Poppins, Helvetica Neue, Arial
- Heading Weight: 900 (Extra Bold)
- Body Weight: 500
- Alle Headings: UPPERCASE
- Letter-spacing: -0.02em für Headings

### Border & Shadows
- Border-Width: 3px solid black
- Shadow: 4px 4px 0 black (Hard Shadow)
- Border-Radius: 0 (überall)
- Keine Transitions (abrupte Zustandswechsel)

### Buttons
- Hard Shadow mit Offset
- Bei Hover: Shadow verkleinert sich, Button verschiebt sich
- Bei Active: Shadow verschwindet komplett
- Uppercase Text, Bold Weight

### Cards & Product Boxes
- 3px schwarzer Border
- 6px Hard Shadow
- Header-Bereich in Electric Yellow
- Preis in Monospace-Font mit Yellow-Background

## SCSS kompilieren
Um das Theme zu nutzen, muss `brutalist.scss` zu `brutalist.css` kompiliert werden:
```bash
sass themes/brutalist/sass/brutalist.scss themes/brutalist/brutalist.css
sass themes/brutalist/sass/brutalist_crit.scss themes/brutalist/brutalist_crit.css
```

## Hinweise
- Das Theme erbt alle Base-Komponenten von `themes/base/`
- Custom.css enthält fertige CSS-Regeln falls kein SCSS-Kompilierung gewünscht
- Mobile Breakpoints reduzieren Shadow/Border-Größe für bessere Darstellung
