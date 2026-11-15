# Sťahovač

macOS appka na sťahovanie videa a zvuku z odkazov (YouTube, Instagram, X, TikTok, SoundCloud a ďalšie), so strihom úseku, DJ mixom, separáciou stôp a analýzou tempa. Dizajn **Navorum Glass · Cyan signál**.

## Inštalácia
1. Stiahni najnovší `Stahovac-X.Y.Z.dmg` zo [stránky vydaní (Releases)](../../releases/latest).
2. Otvor DMG a pretiahni **Sťahovač** do priečinka **Applications**.
3. Spusti appku. Je podpísaná Developer ID a notarizovaná Apple, takže pri prvom spustení nie je potrebný žiadny obchádzací postup.

**Požiadavky:** Mac s procesorom Apple Silicon (M1 alebo novší) a macOS 12 alebo novší.
Prvé spustenie funkcií *Stems* a *Analýza* doinštaluje potrebné knižnice (~100 MB až ~700 MB).

## Aktualizácie
Appka pri štarte (a potom každých pár hodín) pozrie najnovšie vydanie na tomto repozitári. Ak je novšie, ukáže oznámenie **„Je dostupná verzia …“**. Po kliknutí na **Stiahnuť** sa v prehliadači stiahne nový DMG, ktorý rovnako pretiahneš do Applications. Appka sa sama nič neinštaluje. Aktualizácie môžeš skontrolovať aj ručne kliknutím na číslo verzie vľavo dole. Tlačidlo **yt-dlp** aktualizuje samotný nástroj na sťahovanie.

## Súkromie
Appka nezbiera ani neodosiela žiadne údaje o používateľovi. Sieťové spojenia sú len: odkazy, ktoré do appky vložíš (na príslušné služby), a kontrola novej verzie na `api.github.com`.

## Upozornenie
Sťahovač je nástroj. Za dodržanie autorských práv a podmienok služieb, z ktorých sťahuješ, zodpovedá používateľ. Sťahuj len obsah, na ktorý máš právo.

## Súčasti tretích strán
Pozri [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md): FFmpeg (GPL-2.0+), yt-dlp (Unlicense), písmo Mulish (SIL OFL 1.1).

---
*Zdrojový kód appky nie je v tomto repozitári zverejnený, repozitár slúži na distribúciu vydaní.*
