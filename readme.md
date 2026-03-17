## Eksloracja danych - przykładowy problem 1

### Przygotowanie środowiska

 1. Wykonaj 'fork' tego repozytorium.
 2. Sklonuj fork do lokalnego folderu
 3. Pobierz zbiór danych ze strony https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?resource=download 
 4. Utwórz w lokalnym folderze folder data/ (katalog data/ powinien być w .gitignore)
 5. Przekopiuj do folderu data/ pliki 


    ![alt text](files.png)

### Zadanie

 1. Zapoznaj się z notatnikiem judge.ipynb
 2. Utwórz roboczy branch
 3. W katalogu src/ znajdziesz plik system111333.py. Zmodyfikuj go tak, aby nazwa zawierała numer indeksu jednego z uczestników grupy projektowej. W treści tego pliku powinna znajdować się implementacja twojego systemu oceniającego.
 4. Rozwiąż zadanie
    - Przygotuj pod-zadania dotyczące tego problemu na tablicy Kanban
    - Zaplanuj daty wykonania zadań
    - Przydziel zadania członkom zespołu
    - Zaplanuj dwie iteracje
    - Termin spotkania dotyczącego mini-projektu: 17.03.2026
 5. Umieść rozwiązanie w katalogu, do którego dostęp znajdziesz na stronie kursu (tylko plik z systemem).

Termin wykonania zadania: 31.03.2026

### Dlaczego nasz system powinien być lepszy?
#### Lepszy niż AverageMovieRating
Bo nie zwraca tej samej wartości dla wszystkich użytkowników — uwzględnia osobisty profil ocen użytkownika i jego preferencje gatunkowe.
#### Lepszy niż AverageUserRating
Bo nie ignoruje jakości / popularności konkretnego filmu.
#### Lepszy niż GlobalAverageMovieRating
Bo używa informacji specyficznej zarówno dla filmu, jak i użytkownika.
#### Lepszy niż NaiveRating
To oczywiste — nie zwraca stałej 2.5.
