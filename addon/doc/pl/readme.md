#Zdalne NVDA / NVDA Remote Access
Wersja 1.0

Dodatek Zdalne NVDA (oryginalnie NVDA Remote Access) pozwala po��czy� si� z innym komputerem, na kt�rym uruchomiony jest czytnik ekranu NVDA. Nie ma znaczenia, czy znajdujesz si� po drugiej stronie pokoju, czy po drugiej stronie �wiata. Po��czenie jest proste i jest tylko kilka polece� do zapami�tania. Mo�esz pod��czy� si� do komputera innej osoby, lub pozwoli� komu� zaufanemu pod��czy� si� do twojego systemu dla wykonania rutynowej konserwacji, diagnostyki problemu, albo przeprowadzenia szkolenia.

##Zanim zaczniesz

Musisz zainstalowa� NVDA na obu komputerach, oraz pobra� dodatek Zdalne NVDA.
Instalacja NVDA i tego dodatku s� standardowe. Je�li potrzebujesz wi�cej informacji, mo�esz je znale�� w podr�czniku NVDA.

##Rozpoczynanie zdalnej sesji przez serwer po�rednicz�cy
###Kontrolowany	 komputer
1. Otw�rz menu NVDA, Narz�dzia, Zdalne, Po��cz.
2. Wybierz klient w pierwszej grupie  przycisk�w opcji.
3. Wybierz Zezw�l na kontrol� tego komputera w drugiej grupie przycisk�w opcji.
4. W polu Host, wprowad� adres serwera, do kt�rego si� ��czysz, np. nvdaremote.com.
5. Wprowad� klucz w polu klucza, albo u�yj przycisku Generuj klucz.
Klucz jest niezb�dny osobie, kt�ra b�dzie kontrolowa� tw�j komputer.
Kontrolowana maszyna i inne do niej pod��czone, musz� u�ywa� tego samego klucza.
6. Naci�nij OK. Us�yszysz d�wi�k i po��czone.

###Komputer kontroluj�cy
1. Otw�rz menu NVDA, Narz�dzia, Zdalne, Po��cz.
2. Wybierz klient w pierwszej grupie  przycisk�w opcji.
3. Wybierz Kontroluj inny komputer w drugiej grupie przycisk�w opcji.
4. W polu Host, wprowad� adres serwera, do kt�rego si� ��czysz, np. nvdaremote.com.
5. Wprowad� klucz w polu klucza, albo u�yj przycisku Generuj klucz.
Klucz jest niezb�dny osobie, kt�ra b�dzie kontrolowa� tw�j komputer.
Kontrolowana maszyna i inne do niej pod��czone, musz� u�ywa� tego samego klucza.
6. Naci�nij OK. Us�yszysz d�wi�k i po��czone.


##Bezpo�rednie po��czenia
Opcja Serwer w oknie po��czenia pozwala ustanowi� bezpo�rednie po��czenie.
Po wybraniu tego, okre�l, jak� rol� b�dzie pe�ni� tw�j komputer.
Inna osoba po��czy si� z tob� u�ywaj�c roli przeciwnej.

Po wybraniu roli, mo�esz uzyska� adres IP przyciskiem Pobierz zewn�trzne IP, oraz upewni� si�, �e port jest prawid�owo przekazywany.
Je�li sprawdzenie wykryje, �e tw�j port (6837) jest nieosi�galny, pojawi si� okienko powiadomienia.
W��cz przekazywanie port�w i spr�buj ponownie.
Uwaga: proces ustawiania przekazywania port�w wykracza poza zakres tego dokumentu. Sprawd� instrukcj� obs�ugi swojego routera.

Wprowad� klucz w polu klucza, lub wybierz przycisk Generuj. Inna osoba b�dzie potrzebowa� twojego zewn�trznego IP oraz klucza, aby si� po��czy�.

Po naci�ni�ciu przycisku OK, zostaniesz po��czony.
Gdy pod��czy si� druga osoba, mo�na b�dzie normalnie u�ywa� zdalnego NVDA.

##Wysy�anie klawiszy
Po ustanowieniu po��czenia, na maszynie kontroluj�cej mo�na nacisn�� f11 aby rozpocz�� przesy�anie klawiszy.
Gdy NVDA wypowie Klawisze wysy�ane, naciskane klawisze b�d� trafia� do kontrolowanego komputera. Naci�nij f11 aby zako�czy� wysy�anie klawiszy i powr�ci� do kontroluj�cej maszyny.
Dla najlepszej kompatybilno�ci prosz� si� upewni�, �e uk�ad klawiatury jest taki sam na obu maszynach.

##Wy�lij Ctrl+Alt+Del
Podczas wysy�ania klawiszy, nie jest mo�liwe wys�anie kombinacji CTRL+Alt+del w zwyk�y spos�b.
Je�li musisz wys�a� CTRL+Alt+del, a zdalny komputer jest w trybie bezpiecznego pulpitu, u�yj tego polecenia.

##Zdalna kontrola nienadzorowanego komputera

Czasem mo�esz chcie� kontrolowa� zdalnie jaki� w�asny komputer. Jest to szczeg�lnie przydatne je�li podr�ujesz i chcesz kontrolowa� sw�j domowy PC z laptopa. Podobnie, dla kontroli komputera znajduj�cego si� w innym pokoju. Drobne przygotowania czyni� to wygodne i mo�liwe.

1. Wejd� do menu NVDA, Narz�dzia, Zdalne, Opcje.
2. Zaznacz pole wyboru , "��cz automatycznie z serwerem kontroli przy starcie".
3. Wype�nij pola Host i klucz i naci�nij OK.
4. Opcja generowania klucza nie jest dost�pna w tej sytuacji. Najlepiej jest u�y� klucza, kt�ry �atwo zapami�tasz i b�dziesz m�g� go u�y� ze zdalnej lokalizacji .

##Wyciszanie mowy na zdalnym komputerze
Je�li nie chcesz s�ysze� mowy zdalnego komputera, uruchom menu NVDA, Narz�dzia, Zdalne. Przejd� do polecenia "Wycisz zdaln� mow�" i naci�nij Enter.


##Ko�czenie sesji zdalnej

Aby zako�czy� zdaln� sesj�, wykonaj nast�puj�ce dzia�ania:

1. Na kontroluj�cym komputerze, naci�nij F11 aby zako�czy� wysy�anie klawiszy. Powiniene� us�ysze� komunikat: "Klawisze nie wysy�ane." Je�li zamiast tego us�yszysz, �e klawisze wysy�ane,  naci�nij F11 jeszcze raz.

2. Otw�rz menu NVDA, Narz�dzia, Zdalne, i naci�nij Enter na poleceniu Roz��cz.

##Wy�lij schowek
Opcja Wy�lij schowek w menu Zdalne, pozwala przes�a� tekst z twojego schowka.
Po jej aktywowaniu tekst w schowku zostanie przes�any do schowka innych maszyn.

##Konfigurowanie zdalnego NVDA do pracy na bezpiecznym pulpicie

Aby Zdalne NVDA mog�o pracowa� na bezpiecznym pulpicie, dodatek musi by� zainstalowany w NVDA dzia�aj�cym na bezpiecznym pulpicie.

1. Z menu NVDA wybierz Ustawienia, Og�lne.

2. Przejd� klawiszem Tab do przycisku U�ywaj zapisanych ustawie� NVDA na ekranie logowania i innych zabezpieczonych ekranach (wymaga uprawnie� administratora) i naci�nij Enter.

3. Odpowiedz twierdz�co na pytania dotycz�ce kopiowania twoich ustawie� i kopiowania dodatk�w, ewentualnie potwierd� komunikat kontroli konta u�ytkownika, kt�ry si� mo�e pojawi�.
4. Po skopiowaniu ustawie� zamknij powiadomienie przyciskiem OK. Przejd� klawiszem Tab do OK i naci�nij Enter, aby opu�ci� okno ustawie�.

Gdy Zdalne NVDA jest zainstalowane na bezpiecznym pulpicie, je�li aktualnie jeste� kontrolowany w zdalnej sesji,
bezpieczny pulpit b�dzie odczytywany, je�li si� pojawi.

##Wsp�praca
Chcieliby�my podzi�kowa� m.in. nast�puj�cym osobom, kt�re pomog�y urzeczywistni� projekt Zdalnego NVDA.

* Hai Nguyen Ly
* Chris Westbrook
* Thomas Huebner
* John F Crosotn III
* Darrell Shandrow
* D Williams
* Matthew McCubbin
* Jason Meddaugh
* ABDULAZIZ ALSHMASI.
* Tyler W Kavanaugh
* Casey Mathews
