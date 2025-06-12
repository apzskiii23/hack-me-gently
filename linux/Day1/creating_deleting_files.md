# Tworzenie i Usuwanie Plików w Linuksie
> Temat: Podstawowe operacje na plikach  
> Źródło: Roadmap.sh  
> Data: 2025-06-12

---

| Pytania / Kluczowe pojęcia                      | Notatki / Wyjaśnienia                                                                 |
| :---------------------------------------------- | :------------------------------------------------------------------------------------ |
| Jak utworzyć pusty plik?                        | `touch nowy_plik.txt` – tworzy nowy, pusty plik, jeśli nie istnieje.                  |
| Jak stworzyć plik z zawartością za pomocą echo? | `echo 'tekst' > plik.txt` – tworzy plik i zapisuje w nim podany tekst.                |
| Jak utworzyć plik używając cat?                 | `cat > plik.txt` – tworzy plik, pozwala wpisać tekst; zakończ Ctrl+D, aby zapisać.    |
| Jak usunąć plik?                                | `rm nazwa_pliku` – usuwa wskazany plik (operacja trwała).                             |
| Co robi `rm -i`?                                | `rm -i nazwa_pliku` – usuwa plik po potwierdzeniu; zapobiega przypadkowemu usunięciu. |
| Jak usunąć pusty katalog?                       | `rmdir nazwa_katalogu` – usuwa katalog tylko, gdy jest pusty.                         |

---

## Podsumowanie
> Komendy `touch`, `echo` i `cat` służą do tworzenia plików (pustych lub z zawartością), a `rm` i `rmdir` do usuwania plików oraz pustych katalogów, z opcją `-i` w `rm` pozwalającą na bezpieczne potwierdzenie przed skasowaniem.
