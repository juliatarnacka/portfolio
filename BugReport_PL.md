# Szablon dla zgłoszenia błędu
**TYTUŁ** - _tytuł zgłoszenia_

**PRIORYTET** - _ważność zgłoszenia_

**ŚRODOWISKO** - _środowisko reprodukcji błędu_

**POWTARZALNOŚĆ** - _częstotliwość występowania_

**WARUNEK WSTĘPNY** - _warunek niezbędny do odtworzenia błędu_

**DANE TESTOWE** - _dane testowe niezbędne do odtworzenia błędu_

**KROKI REPRODUKCYJNE** - _kroki do odtworzenia błędu_

**OBECNY REZULTAT** - _obecny stan testowanego oprogramowania_

**OCZEKIWANY REZULTAT** - _oczekiwane, prawidłowe zachowanie oprogramowania_

**ZAŁĄCZNIKI** - _materiały dodatkowe (np. wizualne)_

**PODSUMOWANIE** - _miejsce do podsumowania zgłoszenia i przekazania dodatkowych uwag dla developera_

#Przykładowy bug na podstawie strony https://szkolawchmurze.org/

Tytuł: Nieklikalny numer telefonu w zakładce kontakt.

Priorytet: niski

Powtarzalność: błąd występuję każdorazowo, mimo odświeżania strony oraz zmiany przeglądarki.

Warunek wstępny: strona musi być udostępniona do użytku klientów, brak wtyczek mogących zakłócać działanie strony.

Dane testowe: https://szkolawchmurze.org/ -> zakładka "kontakt - szkoła w chmurze".

Kroki reprodukcyjne: 

1. Wejście na stronę https://szkolawchmurze.org/
2. Odszukanie zakładki "kontakt - szkoła w chmurze" na stronie
3. Kliknięcie w numer telefonu

Obecny rezultat: 
Numer nie jest klikalny oraz nie przekierowuje do innych komunikatorów (np. skype).

Oczekiwany rezultat: 
Numer jest klikalny oraz przekierowuje do innych komunikatorów (np.Skype). 

<img width="671" alt="Zrzut ekranu 2023-09-12 o 13 53 27" src="https://github.com/juliatarnacka/portfolio/assets/144791433/4525791a-6f82-4d47-8b0a-a7c2ad8b1abc">





