# MONO - Neuro-Focus Tool

![MONO Logo](assets/logo-icon.png)

**MONO** je webová aplikace ("Attention Management System") navržená pro hlubokou práci (Deep Work). Respektuje neurobiologické limity mozku pomocí ultradiánních rytmů a cirkadiánní adaptivity.

## 🌟 Klíčové Funkce
-   **Focus Mode:** Pracovní bloky bez rozptylování.
-   **Audio Engine:** Generativní Hnědý šum (Brown Noise) pro zvýšení soustředění.
-   **Neuro-Adaptivita:** Automatické přepínání do "Jantarového módu" po 18:00.
-   **YouTube Integrace:** Přehrávání lo-fi/ambientních videí na pozadí.
-   **Offline-First:** Data se ukládají pouze lokálně (LocalStorage).

## 📚 Dokumentace
Kompletní technická dokumentace (Architektura, Datové toky, UI/UX) je k dispozici v souboru [documentation.html](documentation.html) nebo přímo v aplikaci v sekci **Manuál**.

## 🚀 Jak spustit
Projekt je statická webová stránka (HTML/JS/CSS).

### Lokální Vývoj (Doporučeno)
Aplikace vyžaduje HTTP server pro správnou funkci YouTube API.
```bash
python3 -m http.server 8000
```
Otevřete: [http://localhost:8000](http://localhost:8000)

### Nasazení (Produkce)
Stačí nahrát na libovolný statický hosting (GitHub Pages, Netlify, Vercel). `index.html` je vstupní bod.

## 🛠 Tech Stack
-   **Core:** Vanilla JavaScript (ES6+)
-   **Style:** Tailwind CSS (CDN)
-   **Audio:** Web Audio API
-   **State:** Reaktivní Store Pattern

---
*Created by Google Deepmind Team 2025*
