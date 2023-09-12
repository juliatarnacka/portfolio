# Szablon dla przypadku testowego 

**TEST - _Tytuł testu_**

**ŚRODOWISKO TESTOWE**

**URZĄDZENIA I APLIKACJE TESTOWE**

**WARUNKI TESTOWE**

**DANE TESTOWE**

**KROKI TESTOWE**

**OCZEKIWANY REZULTAT**

**RZECZYWISTY REZULTAT**

**PODSUMOWANIE**

**WYNIK TESTU**

**ZAŁĄCZNIKI**

#Przykładowy test case na podstawie strony https://szkolawchmurze.org/

1. Test - sprawdzenie wyszukiwarki na stronie
2. Środowisko testowe - https://szkolawchmurze.org/blog
3. Urządzenia i aplikacje testowe:
Macbook Pro, Chrome: Wersja 116.0.5845.179
4. Warunki testowe:**
Hasło do wyszukiwania: "Odkładanie","Odkładanie wszystkiego na póżniej - o prokrastynacji", "póżniej"
5. Kroki testowe:
  1.Przejdź do strony "https://szkolawchmurze.org/blog"
  2.Przejdz do pola wyszukiwania "szukaj" i wpisz "Odkładanie wszystkiego na póżniej - o prokrastynacji"
6. Oczekiwany rezultat: Po wpisaniu danych testowych, strona wyświetla artykuł "Odkładanie wszystkiego na póżniej - o prokrastynacji"
7. Rzeczywisty rezultat:

TC1 - Wyszukanie hasła "Odkładanie wszystkiego na póżniej - o prokrastynacji"
Wyszukiwarka poprawnie wyświetla wyszukiwany artykuł.

TC2 - Wyszukanie hasła "Odkładanie"
Wyszukiwarka poprawnie wyświetla wyszukiwany artykuł

TC3 - Wyszukanie hasła "Odkładanie wszystkiego na póżniej - o prokrastynacji" tylko wielkimi literami
Wyszukiwarka poprawnie wyświetla wyszukiwany artykuł

TC4 - Wyszukiwanie hasła "później"
Wyszukiwarka nie znajduje artukułu zawierającego słowo "później"

8.Podsumowanie - Wyszukiwanie haseł "Odkładanie","Odkładanie wszystkiego na póżniej - o prokrastynacji", "póżniej" zakończone nie zgodnie z oczekiwanym rezultatem.
9.Wynik testu: Niezaliczony. 
