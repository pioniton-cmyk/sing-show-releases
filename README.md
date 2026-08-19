# SING_SHOW — paczki aktualizacyjne

To repozytorium obsługuje **automatyczne aktualizacje** programu SING_SHOW (obsługa live'a śpiewanego na TikToku).

- `latest.json` — informacja o najnowszej wersji (program sprawdza ten plik).
- `releases/` — paczki ZIP z plikami programu.

Program sam sprawdza wersję po uruchomieniu i proponuje aktualizację. Przed podmianą plików robi kopię
poprzedniej wersji, więc zawsze można wrócić (panel AKTUALIZACJE → PRZYWRÓĆ).

**W paczkach nie ma żadnych kluczy ani poświadczeń** — klucz Euler Stream i plik tunelu Cloudflare
są dostarczane osobno z instalką i nigdy nie trafiają tutaj.
