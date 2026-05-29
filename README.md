README.md

# Yoeran's Verzamel Hub

Welkom bij mijn persoonlijke hub voor documenten, projecten en resources!

## 📋 Wat is dit?

Dit is een centrale verzamelplek waar ik al mijn ICT-, Techniek- en Marimba-specifieke documenten en projecten bij elkaar zet. Alles wordt weergegeven in een moderne, gebruiksvriendelijke interface.

## 🚀 Structuur

```
yoeran-hub/
├── index.html              # Hoofdpagina met alle secties
├── handleidingen.html      # Handleidingen & richtlijnen
├── lessen.html            # Lessenbank technieklessen
├── handige-links.html     # Verzameling nuttige links
├── hoorrecht.html         # Hoorrecht website (indien beschikbaar)
├── README.md              # Dit bestand
└── documents/             # Map voor documenten (optioneel)
    ├── ICT/
    ├── Techniek/
    └── Marimba/
```

## 📂 Secties

### 🖥️ **ICT**
- ICT-Kwaliteitskalender
- ICT-Jaarplan
- Handleidingen

### 🔧 **Techniek**
- POVO Techniek Implementatieplan
- Kwaliteitskaart Praktijklessen
- Observatieformulier
- Checklist Materialen
- Lessenbank

### 🏫 **Marimba**
- Marimba-specifieke projecten
- Hoorrecht Website

### 📌 **Overige**
- Handige Links

## 🛠️ Hoe te gebruiken

### **Lokaal testen**
1. Download alle bestanden
2. Open `index.html` in je browser
3. Klik door de verschillende secties

### **Op GitHub Pages hosten**

1. **Maak een GitHub repository aan:**
   - Ga naar https://github.com/new
   - Naam: `yoeran-hub` (of naar keuze)
   - Maak het Public
   - Klik "Create repository"

2. **Upload de bestanden:**
   - Sleep alle `.html` bestanden naar de repository
   - Commit de wijzigingen

3. **Zet GitHub Pages aan:**
   - Ga naar Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` (of `master`)
   - Folder: `root`
   - Klik "Save"

4. **Je site is live!**
   - Na een paar minuten zie je: `https://jouw-username.github.io/yoeran-hub`

## 📝 Hoe documenten toe te voegen

### **Optie 1: View Online (Aanbevolen)**

Voeg een link toe naar een online PDF viewer of embed:

```html
<!-- Voorbeeld met PDF viewer -->
<div class="viewer-container">
    <iframe class="pdf-viewer" 
        src="https://docs.google.com/gview?url=https://link-naar-je-pdf.com/document.pdf&embedded=true">
    </iframe>
</div>
```

### **Optie 2: Link naar extern bestand**

```html
<a href="path/to/document.pdf" target="_blank" class="btn btn-view">
    View Online
</a>
```

### **Optie 3: Embedded HTML**

Voor HTML documenten (zoals hoorrecht website):

```html
<a href="hoorrecht.html" class="btn btn-link" target="_blank">
    Ga naar site
</a>
```

## 🎨 Design Features

- **Glass Morphism Cards**: Modern design met frosted glass effect
- **Gradient Background**: Mooi kleurverloop (paars-blauw)
- **Responsive Layout**: Werkt op desktop, tablet en mobiel
- **Smooth Animations**: Fijne overgangen en hover effects
- **Tab Navigation**: Makkelijk schakelen tussen secties

## 🔄 Hoe inhoud aan te passen

### **In `index.html`:**
- Pas secties aan met meer/minder cards
- Voeg nieuwe buttons toe
- Wijzig kleuren in de `<style>` sectie

### **In aparte pagina's:**
- `handleidingen.html`: Voeg je handleidingen toe
- `lessen.html`: Voeg je lesopzetten toe
- `handige-links.html`: Voeg je nuttige links toe

### **Placeholders vervangen:**
- Zoek naar "placeholder" in de HTML
- Vervang met je eigen content
- Test lokaal voordat je pusht naar GitHub

## 🎯 Toekomstige uitbreidingen

- [ ] Document search functionaliteit
- [ ] Tags/filters per document
- [ ] Dark mode toggle
- [ ] Meer interactieve widgets
- [ ] Integratie met databases

## 📧 Contactinfo

**Yoeran Moreel**
- ICT-coördinator & Techniekdocent
- Marimba & Duif (Nissewijs)

## 📜 Licentie

Deze documenten zijn persoonlijk eigendom van Yoeran Moreel. 
View online enkel. Download of gebruik van documenten zonder toestemming is niet toegestaan.

---

**Bijgewerkt:** Mei 2026
**Versie:** 1.0