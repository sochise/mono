# MONO - Neuro-Focus Tool

## O projektu
MONO je webová aplikace pro hlubokou práci (Deep Work), která kombinuje:
-   **Timer** pro pracovní bloky.
-   **Zvukové kulisy** (Hnědý šum, YouTube soundtracky).
-   **Neuro-Insights** blog.

## 🚀 Jak nasadit do produkce (Online)

Aplikace je připravena jako statická webová stránka. Pro její spuštění **není potřeba** žádný backend server (Python/Node.js). Stačí nahrát soubory na libovolný statický hosting.

### Možnost 1: Netlify (Nejjednodušší)
1.  Jděte na [Netlify Drop](https://app.netlify.com/drop).
2.  Přetáhněte celou složku `MONO` do okna prohlížeče.
3.  Aplikace bude okamžitě online na URL typu `https://vas-nazev.netlify.app`.

### Možnost 2: GitHub Pages
1.  Vytvořte repository na GitHubu.
2.  Nahrajte soubory:
    ```bash
    git remote add origin <vas-github-repo-url>
    git push -u origin main
    ```
3.  V nastavení repository na GitHubu (Settings -> Pages) vyberte "Deploy from branch" a zvolte `main`.

### Možnost 3: Vercel
1.  Pokud máte Vercel účet, nainstalujte CLI: `npm i -g vercel`.
2.  Spusťte příkaz:
    ```bash
    vercel --prod
    ```

## Lokální Vývoj
Pokud potřebujete aplikaci upravovat lokálně a testovat YouTube API (které vyžaduje server), použijte:
```bash
python3 -m http.server 8000
```
Otevřete: `http://localhost:8000`
