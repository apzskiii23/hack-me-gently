# Hierarchia Katalogów w Linuksie
> Temat: Filesystem Hierarchy Standard (FHS)  
> Źródło: Roadmap.sh  
> Data: 2025-06-12

---

| Pytania / Kluczowe pojęcia    | Notatki / Wyjaśnienia                                                  |
| :---------------------------- | :--------------------------------------------------------------------- |
| Co to jest katalog root (/) ? | Katalog główny systemu, najwyższy poziom hierarchii plików.            |
| Co zawiera /home?             | Katalogi domowe użytkowników.                                          |
| Jaką rolę pełni /bin?         | Podstawowe pliki wykonywalne (binarne) niezbędne do działania systemu. |
| Co znajduje się w /sbin?      | Narzędzia administracji systemem (binaria dla roota).                  |
| Co przechowuje katalog /etc?  | Pliki konfiguracyjne systemu i aplikacji.                              |
| Do czego służy /var?          | Dane zmienne, takie jak logi i pliki kolejki (spool).                  |
| Co zawiera /usr?              | Programy i dane dla użytkowników, niezbędne paczki.                    |
| Jaką rolę pełni /lib?         | Wspólne biblioteki współdzielone przez programy.                       |
| Do czego służy /tmp?          | Pliki tymczasowe, usuwane często przy restarcie systemu.               |
| Co znajduje się w /opt?       | Aplikacje firm trzecich instalowane w /opt.                            |

---

## Podsumowanie
> FHS w Linuksie definiuje logiczną strukturę katalogów od root (/) przez katalogi domowe, binaria, biblioteki, pliki konfiguracyjne, dane zmienne, biblioteki współdzielone, pliki tymczasowe aż po aplikacje zewnętrzne, co ułatwia nawigację i zarządzanie plikami.
