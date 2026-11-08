# Cosmic Zen – ingyenes támogatási oldal

Statikus GitHub Pages weboldal. Nem tartalmazza a Cosmic Zen alkalmazás forráskódját.

## Feltöltés

1. Hozz létre egy `cosmic-zen-support` nevű **Public** GitHub repositoryt a `SaporeSoftware` fiókban.
2. Töltsd fel a `index.html`, `privacy.html`, `style.css` fájlokat a repository gyökerébe.
3. GitHub repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/(root)` → Save.
4. Ellenőrizd a megnyíló weboldalt és a támogatási bejelentés linkjét.

Várható címek a publikálás után:
- Support URL: `https://saporesoftware.github.io/cosmic-zen-support/`
- Privacy Policy URL: `https://saporesoftware.github.io/cosmic-zen-support/privacy.html`

Ezek a címek csak a repository létrehozása és Pages engedélyezése után működnek.

## Kötelező felülvizsgálat nyilvános kiadás előtt

- Ellenőrizd, hogy valóban a `SaporeSoftware` fiókhoz tartozik-e a repository.
- Győződj meg arról, hogy az Issue funkció engedélyezett.
- Vizsgáld át a Flutter `pubspec.yaml` függőségeit és az iOS konfigurációt: analytics, crash reporting, cloud sync, reklám, SDK adatgyűjtés. Ezután pontosítsd az adatvédelmi tájékoztatót.
- Ellenőrizd, hogy az App Store Connect App Privacy válaszai pontosan tükrözik az alkalmazás és a használt külső SDK-k tényleges működését.
- A jelenlegi támogatási csatorna GitHub-fiókot igényel; ha szeretnél közvetlen e-mailes támogatást, adj hozzá később egy külön kapcsolattartási címet.
