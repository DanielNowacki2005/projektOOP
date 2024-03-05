# projektOOP
projekt // nazwy klas,metod,poł nie bedą takie same jak w kodzie<br>
założenia bedzię to aplikacja desktopowa mająca na celu udawac aplikacje do zarządu bilbioteki:<br>
Po włączeniu ma się pokazać okno na której do wyboru jest opcja wypożycz,odłóż,przedłóż,zobacz, dodaj i usuń.<br>
Po wybraniu powinno się pokazac inne okno na którym zależnie co wybraliśmy powinno robić dziłanie na danych.<br>
Robienie zmian na danych bedzię poprez wpisanie lub wybranie możliwych pól i wpciśniecię zatwierdz.<br>
Jednocześnie po wybraniu powinno się zapisać co się zmieniło i pokazać na tej stronie.<br>
każda zarejestrowana ksiązka powinna być zapisanna tak<br>
String:autor, String:nazwa, String:rok wydania, int:egzemplarz, boolean:pozyczona.<br>
oraz array wypożyczenia o polach:<br>
String:imie,String:autor + nazwa,int:egzemplarz,Date:do<br>
Funcje:<br>
wypożycz,odłóż,przedłóż,zobacz, dodaj i usuń.<br>
Po nazwach można wywnioskować że bedą robić to na danych i jak.<br>
klasy<br>
książka,osoba,wypożyczni, spis, autor i Iosoba.<br>
pola i rodzaje klas<br>
abstrakcyja autor.<br>
String imie,nazwisko<br>
Interface Isoba<br>
pola <br>
String:imie<br>
String:nazwisko<br>
void metody<br>
void usun<br>
dodaj<br>
klasa ksiązka
autor
String:autor, String:nazwa, String:rok wydania, int:egzemplarz, boolean:pozyczona.
klasa osoba:
String:imie,nazwisko';
klasa wypożycznia dziedziczy od osoba
SString:autor + nazwa,int:egzemplarz,Date:
