# projekt_python
Projekt na przedmiot podstawy programowania w języku python
Wykonany przez Mikołaja Jaworskiego

Użytkownicy mogą tworzyć konta, logować się i dodawać słówka do nauki. Program zawiera klasę "Uzytkownik" i "Aplikacja", które implementują funkcjonalność aplikacji.

Klasa "Uzytkownik" zawiera informacje o użytkowniku, takie jak nazwa użytkownika i hasło, a także słownik słówek do nauki i nauczonych słówek. Klasa ta zawiera również funkcje do testowania słówek, sprawdzania postępów i aktualizowania ostatniej sesji.

Klasa "Aplikacja" jest głównym punktem wejścia programu i zawiera informacje o wszystkich użytkownikach i ich kontach. Klasa ta zawiera funkcje do tworzenia kont, logowania i głównego menu aplikacji.

Program zapisuje informacje o kontach użytkowników w pliku tekstowym "login_data.txt", a informacje o ostatniej sesji są zapisywane w pliku tekstowym "username_session.txt".

Instrukcja obsługi i opis:

1. Po uruchomieniu aplikacji widzimy kafelek głównego menu w którym mamy do wyboru 3 pola.
	Po wpisaniu 1, wchodzimy w rejestracje, po czym musimy wpisać nazwę użytkownika i 
	ustawić odpowiadające nam hasło. Po rejestracji dane logowania są zapisane do pliku
	tekstowego "login_data.txt". Od teraz możemy logować się za pomocą podanej nazwy i 
	hasła.
2. Po założeniu konta, możemy wpisać 2, co przeniesie nas do panelu logowania. Po wpisaniu 
	poprawnej nazwy użytkownika i hasła zostaniemy przeniesieni do menu użytkownika.
3. Ostatnią funkcją menu głównego jest wyjście, i jak sama nazwa wskazuje po wpisaniu 3, 
	program po prostu się wyłącza. :)
4. W menu użytkownika mamy do wyboru 5 kafelków. Pierwszym z nich jest importowanie słówek
	Po wpisaniu 1, program poprosi nas o podanie ścieżki do pliku. Po podaniu ścieżki 
	program zapisze dane z pliku csv do swojego wewnętrznego słownika, tak aby można 
	było ich używać później w aplikacji.
5. Następną opcją pod numerem 2 jest test słówek, czyli główna część naszego programu. Po 
	uruchomieniu tego kafelka, będą wyświetlane kolejne słówka dla których trzeba 
	wpisać tłumaczenie. Za każdym odpowiedzianym słówkiem, program wyświetla nasz
	progres, żeby było wiadomo ile słówek zostało do końca, i na ile udało się 
	odpowiedzieć poprawnie. Po zakończeniu testu zostaniemy przeniesieni do menu.
6. Kolejną trzecią opcją, jest możliwość poprawienia się, czyli po wpisaniu 3 w menu,
	możemy podjąć się jeszcze raz słówek do których powtórki zostało nam 0 dni, polega	
	on na tym samym co test słówek, ale odpowiadamy tylko na te na które wcześniej 
	odpowiedzieliśmy źle.
7. Czwartą opcją w menu użytkownika jest sprawdzenie progresu, program po prostu wyświetli 
	nam ilość słówek którą zaliczyliśmy i ile słówek mamy do poprawy.
8. Ostatnią już opcją programu pod numerem 5 w menu użytkownika jest wylogowanie się, co
	jak sama nazwa wskazuje po prostu wyloguje nas i cofnie do menu głównego.
