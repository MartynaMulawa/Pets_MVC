# Pets
# System Zarządzania Zwierzętami

System Zarządzania Zwierzętami to aplikacja ASP.NET Core MVC do zarządzania zwierzętami i ich właścicielami. Aplikacja umożliwia dodawanie, edytowanie, usuwanie i wyświetlanie zwierząt, a także zarządzanie właścicielami i ich zwierzętami.

## Funkcje
- Logowanie i rejestracja. Tylko zalogowani użytkownicy mają dostęp.
- Dodawanie, edytowanie, usuwanie i wyświetlanie zwierząt
- Sortowanie zwierząt według nazwy, gatunku i właściciela
- Zarządzanie właścicielami i ich zwierzętami
- Wyświetlanie zwierząt danego właściciela
- Wyświetlanie danych i listy zwierząt dla posiadacza największej liczby zwierząt

### Uruchamianie aplikacji

1. Uruchom aplikację:

    ```sh
    dotnet run
    ```

2. Otwórz przeglądarkę i przejdź do `https://localhost:5001` (lub do adresu URL wyświetlonego w konsoli).

## Użycie

### Sortowanie zwierząt

Możesz sortować zwierzęta według nazwy, gatunku lub właściciela, klikając odpowiednie przyciski w interfejsie użytkownika.

### Zarządzanie zwierzętami i właścicielami

- Aby dodać nowe zwierzę lub właściciela, kliknij przycisk "Create New" na odpowiedniej stronie.
- Aby edytować istniejące zwierzę lub właściciela, kliknij link "Edit" obok odpowiedniego wpisu.
- Aby wyświetlić szczegóły zwierzęcia kliknij link "Details".
- Aby wyświetlić dane i liste zwierząt właściciela kliknij link "Details".
- Aby usunąć zwierzę lub właściciela, kliknij link "Delete".
- Aby zobaczyć listę zwierząt dla posiadacza największej liczby zwierząt kliknij "Owner With Most Pets"
- Aby się zalogować/zarejestrować kliknij przycisk w prawym górnym rogu.

