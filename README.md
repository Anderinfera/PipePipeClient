# PipePipe Andercoded

A modified version of [PipePipe](https://github.com/InfinityLoop1308/PipePipe), the client of PipePipe by InfinityLoop1308. It is not an official build and is not supported by the PipePipe developers: please report problems with this version [here](https://github.com/Anderinfera/PipePipeClient/issues), not in the PipePipe repository.

Download: [Releases](https://github.com/Anderinfera/PipePipeClient/releases). It installs next to the official PipePipe (app id `dev.ander.pipepipe`), so your settings and subscriptions have to be moved with export and import in Settings > Backup.

## Changes from PipePipe

- **SponsorBlock chapters in downloads**: a downloaded YouTube video (MP4 or WebM) gets a chapter for each SponsorBlock segment, so other players can show or skip them. On by default, can be turned off in Settings > SponsorBlock > "Add chapters to downloads".
- **Download progress for other apps**: a gallery or a file manager can read the state and progress of downloads, after you allow it (permission `dev.ander.pipepipe.permission.READ_DOWNLOAD_PROGRESS`).
- Own name, app id, update check (this repository's releases) and bug report link.

Versions are named after the PipePipe version they are based on, e.g. `5.6.0-ac1` is the first Andercoded release on top of PipePipe 5.6.0.

## Building

Needs JDK 25 and [PipePipeExtractor](https://github.com/InfinityLoop1308/PipePipeExtractor) checked out next to this folder (`../PipePipeExtractor`), at the commit the matching PipePipe release uses. Then run `./gradlew assembleRelease`.

## License

GNU General Public License v3.0, like PipePipe: see [LICENSE](LICENSE).

---

# PipePipe Andercoded (PL)

Zmieniona wersja [PipePipe](https://github.com/InfinityLoop1308/PipePipe), klienta PipePipe autorstwa InfinityLoop1308. To nie jest oficjalna wersja i twórcy PipePipe jej nie wspierają: problemy z tą wersją zgłaszaj [tutaj](https://github.com/Anderinfera/PipePipeClient/issues), a nie w repozytorium PipePipe.

Pobieranie: [Releases](https://github.com/Anderinfera/PipePipeClient/releases). Instaluje się obok oficjalnego PipePipe (identyfikator `dev.ander.pipepipe`), więc ustawienia i subskrypcje trzeba przenieść eksportem i importem w Ustawienia > Kopia zapasowa.

## Zmiany względem PipePipe

- **Rozdziały SponsorBlock w pobranych filmach**: pobrany film z YouTube (MP4 albo WebM) dostaje rozdział dla każdego segmentu SponsorBlock, więc inne odtwarzacze mogą je pokazać albo pominąć. Domyślnie włączone, można wyłączyć w Ustawienia > SponsorBlock > „Add chapters to downloads”.
- **Postęp pobierania dla innych aplikacji**: galeria albo menedżer plików może odczytać stan i postęp pobierania, gdy na to pozwolisz (uprawnienie `dev.ander.pipepipe.permission.READ_DOWNLOAD_PROGRESS`).
- Własna nazwa, identyfikator, sprawdzanie aktualizacji (wydania z tego repozytorium) i link do zgłaszania błędów.

Wersje mają nazwę od wersji PipePipe, na której bazują, np. `5.6.0-ac1` to pierwsze wydanie Andercoded na bazie PipePipe 5.6.0.

## Licencja

GNU General Public License v3.0, tak jak PipePipe: zobacz [LICENSE](LICENSE).
