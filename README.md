# Kalorie AI — PWA v0.1

## Instalacja wyłącznie z telefonu

1. Pobierz ZIP i rozpakuj na telefonie.
2. Utwórz publiczne repozytorium GitHub (np. `kalorie-ai`).
3. Wgraj pliki z katalogu `kalorie-ai-pwa` do głównego katalogu repozytorium (nie sam ZIP).
4. W repozytorium wybierz Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
5. Otwórz adres `https://TWOJ_LOGIN.github.io/kalorie-ai/` w Chrome na Androidzie.
6. Menu Chrome (⋮) → „Zainstaluj aplikację” / „Dodaj do ekranu głównego”.

GitHub Pages może potrzebować kilku minut na publikację. PWA wymaga HTTPS. Nie wgrywaj do repozytorium prywatnych zdjęć ani kluczy API.

## Działa
- Ręczne dodawanie posiłków, gramatura i wartości na 100 g.
- Prosta lokalna baza przykładowych produktów (orientacyjne wartości, sprawdzaj etykiety).
- Skanowanie EAN/UPC przez BarcodeDetector w obsługiwanych przeglądarkach, lub ręczny kod.
- Wyszukiwanie w Open Food Facts (wymaga internetu).
- Lokalna historia, bilans, makro, wykres 7 dni i cel kalorii.
- Zdjęcie jako podgląd przy dodawaniu, bez wysyłania na serwer i bez zapisu do historii.
- Opcjonalna średnica talerza zapisywana w historii, bez automatycznego wyliczania masy.

## Nie działa jeszcze
- Automatyczne rozpoznawanie potraw i szacowanie gramatury ze zdjęcia (wymaga osobnego backendu AI).
- Trwały zapis zdjęć w historii.
- Synchronizacja między urządzeniami.

Historia jest zapisywana w localStorage przeglądarki i może zniknąć po wyczyszczeniu danych witryny.
