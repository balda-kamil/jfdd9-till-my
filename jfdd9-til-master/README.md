# *scio me nihil scire*


# **TIL - today I learned 29/03/2018**

1.OGÓLNE

  - Prowadzący zajęcia rzekł "trzeba być biegłym w HTML i CSS oraz znać podstawy JS'a" - wtedy Cie przyjmą jako juniorka !
  - celuj na początku w duże korpo, ich stać na szkolenie Ciebie
  - KOMUNIKACJA jest bardzo ważna, gadaj i się pytaj !
  - wystrzegaj się firm gdzie psiane są apki na stare wersję IE
  

2. HTML

  - ```&nbsp;``` niełamliwa spacja 
  - ```<figure>, <figurecaption>``` znaczniki które powinny być na stronie kiedy umieszczamy wykresy giełdowe //trzeba uzupełnić
  - ```data-value``` do uzupełnienia
  
    


# **TIL - today I learned 30/03/2018**


1.HTML

  - Każdy element w HTML ma domyślnie pozycjonowanie statyczne ```position: static```
  - ```<main>``` może być max jeden na stronie // a co tam dokłądnie być powinno? wyjasnij proszę.
  - DOM :)))
  
  
2. CSS

  - FlexBox 
  - Media Queries
  - **Przeglądarka czyta selektory od tyłu!**
  - Pseudoklasy
  - w **DevTools** w sekcji **Computed** masz skompilowany finalny styl który się załadował. 
  
# **TIL - today I learned 03/04/2018**               

1.GIT

  - ```git clone ścieżka_url nazwa_folderu``` kopiuje wskazane repozytorium z GitHuba do wskazanego, bądź utworzonego przez nas folderu.
  - FORK, forki, forkowanie - co to znaczy? - jeśli chcesz jakieś repozytorium czyjeś rozwijać samodzielnie, robisz forka (widelec, rozgałęzienie). Oczywiście autor orginału może Twojego forka wciągnąć do siebie jeśli stwierdzi że jest spoko. Zauważ że to repozytorium jest zforkowane.
  - JEKYLL - https://jekyllrb.com/ - "Transform your plain text into static websites and blogs" - generowanie statycznych stron WWW, więcej pod adresem - http://sobak.pl/blog/jekyll-generowanie-statycznych-stron-html/-
 




2.Linux

  - ```chown``` - polecenie zmieniające właściciela pliku.
  - ```CTRL + R ``` reverse search, wyszukuje wszystkie komendy jakie wpisałeś.
  - ```CTRL + C``` -> Cancel ;)
  - ```cat``` pokazuje zawartość pliku :)
  - ```cat readme.md > readme2.md``` kopiuje zawartość pliku do innego pliku, bez otwierania ani jednego, ani drugiego.
  - ```cat readme.md >> readme2.md``` dopisuje jeden plik do drugiego pliku
  - GREP - super zaawansowany program szukający, bardzo stary i bardzo dobry
  - ```cat readme.md | grep Bash``` to znaczy ze w pliku readme.md szukamy frazy Bash
  - ```|``` - "pipe" jest to 'rura' która przekazuje coś gdzieś ;) w skrócie.
  - ```man grep``` czyli manual grep, szukasz instruckji co grepa, tak gdyby neta Ci zabrakło.
  - ```..``` - wyższy katalog
  - ```cd ..``` cd - change directory, w tym przypadku katalog wyżej
  - ```~``` przechodzisz do katalogu domowego
  - ```cat readme.md | less```komenda która otwiera plik, ale z początku a nie domyślnie na końcu
  - .ssh - agent haseł
  
  
  
# **TIL - today I learned 04/04/2018**


1. CSS

  - ```media queries  - @media```slużą do zmiany sposobu wyswietlania w zależności od urządzenia. *Always Design for Mobile First*
  - ```viev port``` - jest to widoczny obszar strony internetowej na monitorze czy urządzeniu.
  - jednostki w CSS mamy relatywne ```%, em/rem, ex/ch, vw/vh, vmax, vmin ``` i absolutne ```pc, cm, mm, in, pt, pc(picas)```
    ```em``` odnoszą się do swojego parenta, a ```rem``` do root'a (html'a)
  - ```ch``` szerokośc cyfry 0(hmm.. podobno jeśli chcesz żeby w nagłówku napisac określoną ilośc znakow to może się przydac :)
  - ```vh``` relatywne do 1% wysokości viewportu(wysokość viewport'u)
  - ```vw``` relatywne do 1% wysokości viewportu(szerokośc viewport'u)
  - ```line height``` może byc pisane bez jednostki
  - ```aspect ratio``` Tworzy elastyczne elementy ktore zachowują swój współczynnik prorcji (4:3, 16:9, itd)
  
  
2. Narzędzia

  - Google Audits - znajdują się w DevTools'ach w Chromie.
  
  
# **TIL - today I learned 05/04/2018**

1. Bootstrap

  - Jaka jest różnica pomiędzy frameworkiem, a biblioteką? odp. **FLOW CONTROL!** (kontrola przepływu)
    "You call library, framework calls you" :) 
    Framework to szkielet, a Twój kod to są jego mieśnie które nim poruszają.
    Biblioteka, wykonuje określone, dobrze zdefiniowane operacje. 
    Framework  determinuje składnię, której używasz, a biblioteka jest rozwiązaniem, które możesz wywołać do rozwiązania spotkanego problemu. Framewok jest bardziej kompleksowy
    
  - nie każda wersja Bootstrapa współpracuje z Reactem, do tego najlepsza będzie wersja 3.3.7
  
  - co to ```bootstrap.css.map```? "Wielu programistów tworzy arkusze stylów CSS za pomocą preprocesora CSS, takiego jak Sass, Less lub Stylus. Ponieważ generowane są pliki CSS, edycja plików CSS bezpośrednio nie jest tak pomocna.                                
                                    W przypadku preprocesorów obsługujących mapy źródłowe CSS program DevTools umożliwia edycję na żywo plików źródłowych preprocesora w panelu Źródła i przeglądanie wyników bez opuszczania DevTools lub odświeżania strony. Podczas sprawdzania elementu, którego style są dostarczane przez wygenerowany plik CSS, panel Elementy wyświetla łącze do oryginalnego pliku źródłowego, a nie wygenerowanego pliku .css."
                              
  - *GRID* CSS Grid jest sposobem pozycjonowania elementów. Działa on trochę jak tabela, gdzie możemy definiować ilość kolumn, wierszy oraz „scalać” poszczególne komórki.
 
 
# **TIL - today I learned 06/04/2018** 
  
 
1. Bootstrap

  - ```Okno Modalne```? Bootstrap Modal (czyli po naszemu okna modalne Bootstrap) jest JavaScript’owym okienkiem wyskakującym (pop-up), który jest w pełni konfigurowalny i „responsywny”. Jest to świetny sposób by łatwo, nawet bez pisania kodu JS, stworzyć spełniające wszelkie standardy okienka pop-up na tworzonych przez nas stronach internetowych.
  - Okna Modalne wrzucaj na sam doł kodu ze względu na SEO.
  - ```Lorem Pixel``` - taki dummy content jak lorem ipsum ale obrazkowy, może się przydac. 
  
2. Spotkanie HR'owe.

  - Profil GitHub'a z imienia i nazwiska
  - Link do LinkedIn'a na profilu.
  - Po kursie klikasz w opcje "Szykam Pracy" żeby można bylo łatwiej szukac,
  - ważne jest zeby na GitHubie były same zielona kwadracy, rob często commity,
  - CV - przejrzyste, czytelne, wygląd ma znaczenie. Kolory muszą być biznesowe. Korzystaj z gotowych szablonow (na pracuj.pl czy InterView Me)
  - CV piszemy pod konkretną oferte pracy.
  - numer telefonu w takim formacie xxx-xxx-xxx
  - Zdjęcie do CV nie musi byc w garniturze, ewentualnie w sportowej marynarce. Zdjęcie musi ukazywać Ciebie od pasa w gorę. Podobny uśmiech.
  - Nieukonczone studia, wpisywać jak najbardziej.
  - **UMIEJĘTNOŚCI** tylko technologiczne w skali Juniora wpisywać. 1 kropką cos tam słyszał, 5 kropek można z nim na dany teamt gadać godzinami.

3. GIT

  - przenoszenie plikow między katalogami rób zawsze w osobnym commicie!
  - git add *html dodawanie wszystkich plikot HTML'owych po zmianach
  - GIT FETCH - pobieranie informacji o repozytorium (bezpieczne, stosuj przed każdym PULL'em)
  - -u == --set-upstream (SetUpstream to ustawia domyślną gałąź zdalną dla bieżącej gałęzi lokalnej.
        Wszelkie przyszłe polecenia git pull (z bieżącym lokalnym oddziałem check-out),
        spróbuje wprowadzić commit z <remote-branch> do bieżącego lokalnego oddziału.)
  - HEAD jest odniesieniem do najnowszego commita na danej branchy. Pozwala Ci się rozglądać po danym commicie na ktorym obecie jest umieszona.
  - git checkout  przeskakuje do poprzedniego brancha
  - DETATCHED HEAD - poczytać
  
# **TIL - today I learned 09/04/2018**

1. Wprowadzenie do UX

    1. Product Design ? Chodzi o cały proces tworzenia użytecznych produktów i doświadczeń, począwszy od zdefiniowania prawdziwych problemów ludzi i myślenia o możliwych rozwiązaniach. To ostatecznie doprowadzi do najlepszego projektu.
    2. UI / UX - o co kaman? - **User Interface** to zbiór elementów i reguł w kontekście projektowania wuzualnego danego produktu. **UI Designer** to swojego rodzaju artysta, jego praca odpowiada na pytanie czy dany prokjekt jest ładny i zgodny z zasadami projektowania.
       **User Experience** bada jakośc interakcji pomiędzy człwiek - strona www/ aplikacja / maszyna. UX Designer to swego rodzaju naukowiec badający dane. Odpowiada na pytanie jak ulepszyć dany produkt pod kątem uzyteczności dla użytkownika końcowego? 
    4. Aby by
    
2. JavaScript

    1. typeOf zwraca ciąg znaków określający jakieog typu jest badana wartośc
    2. Koersja - zamiana typów
    3. Kolokwialnie mowiąć to co jest przez "." musi byc obiektem np. ```Math.floor(21.3);```, a po kropce wywołujemy metody jak np .map; .floor;
    4. Objekt (w skrocie) to wartośc która potrafi gromadzić inne wartości. 
    5. [] == [] ```false``` bo tablica jets obiektem, a wtedy zachowuje się jak ===.
    6. Prototypy - Prototypy to mechanizm, za pomocą którego obiekty JavaScript dziedziczą funkcje od siebie nawzajem
    7. THIS - krótkie wyjasnienie (zobaczymy czy wlasciwe niebawem..)```this to obiekt, który jest po lewej stronie kropki.```
    8. VAR ma zakre funkcyjny, LET i CONST zakres blokowy.
    9. funckcja jak się wykona to potem po sobie posprząta... 
    10. Funkcja zawsze widzi wszytskie zmienne ktore widziala w momencie deklarowania.
    11. typeof new -> zawsze object
        Wszystkie funkcje konstruktora podczas tworzenia z słowem kluczowym "new" zawsze będą typem "obiektu"
        ```javascript
            var str = new String('String');
            var num = new Number(100);

            typeof str; // It will return 'object'
            typeof num; // It will return 'object' 

        Ale 

            var func = new Function();
            typeof func; // It will return 'function'.
            
   

# **TIL - today I learned 10/04/2018**

1. Kochana'y JavaScript.

    -TERNARY OPERATOR - OPERATOR WARUNKOWY ```condition ? expr1 : expr2 ``` condition - czyli jakiaś operacja ktora zwraca true lub false i w zalezności od tego wykonuje się expr1(true), albo expr2(false)
    -Instrukcja warunkowa - "Jeśli kupisz mi zabawkę to nie bede plakał" - np. IF, ELSE, ELSE IF, SWITCH
    -Wywolanie funkcji też jest wyrażeniem.
    -taki maly tip.. jak coś na MDN'ie jest w [] to jest to opcjonalne, nie musimy tego wpisywac zeby kod zadziałał.
    -W dokumentacji SORY jest napisane że musi być 1,-1,0 .  to jest poprawna fukncja sortująca liczby ;)
       [1,2,3,4].sort(function compare(a,b){})
       var result = a > b ? 1 : a < b ?-1 : 0
       return result;



    
-   W JS'ie funkcja i metoda to to samo.
-   Indeksowanie w tabelach jest od 0;
-   **Funckje w JS są tzw. obywatelami pierwszej kategorii(first class citizens) oraz obiektami. Oznacza to że mozesz je przekazywać jako parametry do innych funkcji, oraż ze same mogą mieć metowy.**

**Troche o hoistingu**
-   ```var a;``` czy też ```function one()``` deklaracja; 
-   ```a = 5;``` inicjalizacja(hoisting tego nie rusza);
-   ``` var a = 5;``` deklaracja i inicjalizacja w jedym zapisie, ale i tak dwa etapy
-   **HOISTING** - przenoszenie DEKLARACJI na początek danego zakresu(czyli jeśli są w zakresie globalnym to na początek globalnego, a jak w lokalnym to na początek lokalnego) (to jest pierwszy krok, po nim następuje drugi w którym nasz kod jest wykonywany - i to dlatego możemy odnoieść się do zmiennej którą deklraujemy na dole kodu)
    Hoistingowi ulega tyklo deklaracja, inicjalizacja pozostaje dokładnie w tym sameym miejscu w jakim byla. 
    **NAJPIERW HOISTINGOWI ULEGAJĄ FUNKCJE!!!** one są przed zmiennymi wrzucane na górę kodu.
    

   - PURE FUNCTIONS - są to "funkcje czyste" czyli takie ktore do oblicznia wyniku przyjmuja tylko parametry wejściowe , jedynym ich zadaniem jest zwracanie obliczanej wartości.  
   - Pary KLUCZ-WARTOŚĆ no np jak masz ```arr=[4,6,7,3,55]``` to pod kluczem arr[4] kryje się watość 55. Indeks można nazwać kluczem. **W obiektach to Ty definiujesz klucze** np. ```var osoba = { nazwa: "Kamil Balda"};``` klucz ```nazwa``` wartość ```Kamil Balda```
   
**Trochę o THIS**

Istnieje 6 sposobow na wywolanie THIS.

   1. ```.bind()``` (wiązać) metoda .bind() tworzy nową funkcję ktora kiedy jest wywoływana posiada THIS'a ustawionego na podaną wartość, z podaną sekwencją argumentów poprzedzającą wszelkie podawane podczas wywoływania nowej funkcji.  
   2. ```.apply()``` metoda .apply() wywołuje funkcje podstawiając wartość THIS i argumnety przedstawione w postci tablicy.
        ```Skladnia apply oraz call są prawie identyczne, rożnica jest to że call() akceptuje liste argumentow, a apply() przyjmuje pojedyncza tablice argumentow```
   3. ```.call()``` wywołuje funckję z podaną wartością THIS i argumentami podanymi indywidualnie
   4. przy uzyciu "." / wywolanie z kropką / wywolujemy this jako metodę obiektu. This odwoluje się do tego co jest po lewej stronie kropki.
   5. wywołanie z NEW np. new Clazz -> powstaje nowy pusty obiekt, który jest ustawiany jako kontekst wywolania tej fukncji [```this === nowy objekt```]
   6. ```arrow functions``` this jest ustawiany leksykalnie i zalezy od miejsca w ktorym dana funkcja zostala zdefiniowana. this w funkcji strzalkowej zawsze wskazuje na to samo co w funkcji "powyżej"
   
   
   
   
# **TIL - today I learned date???**
    
   1. Koersja - zamina typów
   2. "to co jest przed "".""" musi byc obiektem,a  obkiekt to wartośc ktora potrafi gromadzić w sobie inne wartości
   3. Prototypt, kontekrs, zakres => wyjasnij i sie ucz!
   4. VAR ma skope funkcyjny, LET i CONST blokowy
   5. funkcja jak się wykona to po sobie posprząta,
   6. Funkcja zawsze widzi wszystkie zmienne które widfziala w momencie deklarowania.
   
   
   
# **TIL - this week I learned date??**

   1. Funkcja i metoda to to samo ;)
   2. .appendChild  dodaje elementy do wyswietlania
   3. order -1 - pierwsza pozycja w flex box
   4. callback - wywołanie zwrotne ktore jednocześnie jest metoda obiektu,
   5. THIS wskazuje na currenttarget, a nie target
   6. pamietaj ciolku ze tabela sklada się z takiego czegoś jak tbody i thead...
   7. createElement
   8. apply ustawia cos np tablice jako this'a
   9. $('#game') - lapie wszystkie elementy o id game
   10. 3 stany Promisa - wyjasnić
   11. dobra praktywa - nie nadpisywac prototypów.
   12. zadne funkcja nie pamieta THIS'a oprócz BIND'a ktory ma go na stale
   13. nie ruszać czegoś co znajduje sie w folderze vendor
   14. addEventListener - pod this podstawia nam klikniety element
   15. Display none ucieka z layoutu
   16. This nie zostanie przypisany, dopóki obiekt nie wywola funkcji w ktorej jest zdefiniowany
   17. Pierwszy parametr w metodzie apply zawsze ustawia wartość THIS jawnie
   18.  ```...``` Spreed Operator - operator który bierze wartości po kropkach i rozkłada je na osobne lementy.
   19. Request Animation Frame ?
   20. moment.js dobra bibliteka jesli chcesz w swojej aplikacji uzywać do czegoś czasu
   21. chce spać...
   

# **TIL - 23.04.2018**

  1. BEZSTANOWOŚĆ HTTP - tzn. ani serwer (ani klient) nie przechowuje informacji o tym, jakie były wcześniej zapytania pomiędzy określonym serwerem i klientem oraz nie posiada stanu wewnętrznego.
  2. GET - Pobieranie zasobu lub jego wyświetlenie, np. wyświetlenie formularza lub strony. Parametry można przekazywac jedynie poprzez adres (np. ?nazwa=wartosc&nazwa2=wartosc2)
  3. POST - Przesłanie danych zapisanych jako pary klucz-wartość do serwera (np. wysłanie formularza, gdzie kluczem jest nazwa danego pola a wartością wpisana przez nas wartość). 
  Metoda ta pozwala przesyłać także pliki (a także wiele pliki oraz pary klucz-wartość jednocześnie). Parametry są przekazywane w ciele zapytania,
  można także przekazywać parametry poprzez adres (tak jak w metodzie GET)
  4. JSON -> Podczas wymiany danych między przeglądarką a serwerem dane mogą być tylko tekstem.
     JSON jest tekstem i możemy przekonwertować dowolny obiekt JavaScript na JSON i wysłać JSON na serwer.
     
     Możemy również przekonwertować dowolny JSON odebrany z serwera na obiekty JavaScript.
     
     W ten sposób możemy pracować z danymi jako obiekty JavaScript, bez skomplikowanych analiz i tłumaczeń.
     
     ```var x = {a: 10, b: 20}```
     JSON.stringifity(x) pokaże się:
     ```"{"a": 10, "b": 20}"```
     
     JSON.Parse(text) -> z powrtotem funkcja z góry wróci do orginalnego elementu.
     
     
  5. ```FETCH``` zwraca obiekt który jest Promisem który ma 3 stany : 1. Pending, 2. Resolved, 3.Reject
     W razie pozytywnej odpowiedzi serwera robimy .THEN i co ma się stać.
     Fetch uderza do miejsca gdzie przeglądarka ma dostęp. 
     
  6. **THEN zwraca PROMISA**
  
  
  **REACT** React to deklaratywna, wydajna i elastyczna biblioteka JavaScript do budowania interfejsów użytkownika.
  React.Component - czyli podziel sobie user interface na mniejsze cześci do uzytku, mysl o każdej cześci jakby byla izolowana. 

  
  
  
# **TIL - 24.04.2018**

   1. CLUSTER w NODE.JS - Moduł klastra zapewnia sposób tworzenia procesów podrzędnych, które działają jednocześnie i współużytkują ten sam port serwera.
      Node.js uruchamia programowanie z pojedynczym gwintem, które jest bardzo wydajne pod względem pamięci, ale aby skorzystać z wielordzeniowych systemów komputerowych, moduł Cluster umożliwia łatwe tworzenie procesów potomnych, z których każdy działa na własnym pojedynczym wątku, w celu obsługi obciążeni
     
   2. NVM - Node Version Manager (https://github.com/creationix/nvm) - Simple bash script to manage multiple active node.js versions
   3. LTS - znaczy Long Term Support
   4. BrainJS - JS do sztucznej inteligencji
   5. REPL - REPL oznacza Read Eval Print Loop i reprezentuje środowisko komputerowe, takie jak konsola systemu Windows lub powłokę Unix / Linux, w której wprowadzono polecenie, a system odpowiada z wyjściem w trybie interaktywnym. Node.js lub Node dostarczane są w pakiecie ze środowiskiem REPL. Wykonuje następujące zadania
        
        READ - Odczyt - odczytuje dane wejściowe użytkownika, analizuje dane wejściowe w strukturze danych JavaScript i zapisuje je w pamięci.
        
        Eval - pobiera i ocenia strukturę danych.
        
        PRINT - Drukuj - Drukuje wynik.
        
        Loop - Pętla powyższe polecenie, dopóki użytkownik nie naciśnie ctrl-c dwa razy.
   
   6. NPM - Node Package Manager - Npm jest aplikacją wiersza poleceń, za pomocą której można instalować aplikacje dostępne w repozytorium Npm. Strona domowa aplikacji zawiera wyszukiwarkę pakietów. Repozytorium jest publiczne i darmowe dla pakietów Open Source, ale istnieją także prywatne repozytoria dostępne za opłatą[4]. Npm jest standardowo dostępny, jeśli zainstalowane jest środowisko Node.js.
   7. Komendy NPM
        ```init```Interaktywnie utwórz plik package.json
        ```install```Install a package
        ```search```Search a package
        ```uninstall```Uninstall a package
        
        Reszta jest w **https://docs.npmjs.com/** [CLI commands]
   
   8. Package-Lock.json
    
    
    ```package-lock.json jest generowany automatycznie dla wszelkich operacji, w których npm modyfikuje drzewo node_mulules lub package.json. Opisuje ono dokładnie wygenerowane drzewo, tak aby kolejne instalacje mogły generować identyczne drzewa, niezależnie od aktualizacji zależności pośrednich.
                         
    Ten plik jest przeznaczony do zatwierdzenia w repozytoriach źródłowych i służy różnym celom:
                           
    Opisz pojedynczą reprezentację drzewa zależności, dzięki której członkowie zespołu, wdrożenia i ciągła integracja będą gwarantować instalację dokładnie takich samych zależności.
                           
    Zapewnienie użytkownikom możliwości "podróży w czasie" do poprzednich stanów modułu node_modules bez konieczności zatwierdzania samego katalogu.
                           
    Aby ułatwić lepszą widoczność zmian drzewa poprzez czytelne różnice kontrolne.
                           
    Zoptymalizuj proces instalacji, pozwalając npm na pomijanie powtarzających się metadanych dla wcześniej zainstalowanych pakietów.```
    
    
    
   9. Twoja apka nie wystartuje bez NPM Install! ;)
   10. NPM start -> włączamy serverek
   11. NPM RUN BUILD - 2 tryby:
        -Developerski
        -Produkcyjny
        
   12. REACT NATIVE (natywny zanczy właściwy danemu środowisku informatycznemu, programowi, językowi programowania itd.)
       React Native lets you build mobile apps using only JavaScript. It uses the same design as React, letting you compose a rich mobile UI from declarative components.
       
   13. **REACT SKŁADA SIĘ Z :**
        - **KOMPONENTÓW**
        - **STANU**
        - **PROPSÓW**
        - **CYKLU ŻYCIA KOMPONENTÓW**
        
   14. render() musi zwrócić coś co potrafi narysować, oczywiscie oprócz obiektu. Jego nie rysuje.
   15. clasy te do stylow -> className, a nie class jak bylo wczesnej. 
   
   
   
# **TIL - 25.04.2018**

   1. Propsy - Propsy to argumenty - Propsy do komponentów przekazywane są po prostu jako argumenty. A konkretnie: Jeden argument, który jest obiektem.
   2. W JSX uzywaj tylko podwójnych cudzysłowii ""
   3. w obręcie JSX to co jest w {} jest JS'em
   4.W React pod THIS zawsze siedzi component
   5. Currying - to proces dzielenia funkcji na szereg funkcji, z których każda przyjmuje jeden argument.
   6. RENDER zwraca jedną wartosc, można wszytsko wpakować w DIV'a albo uzyc <React.Fragment>
   7. State to wewnętrzna cecha każdego z komponentow. 
   8. modyfikacja stanu wewnatrz RENDER'a zawsze skutkuje nowym RENDER'em
   9. componentDidMount - Metoda componentDidMount() jest najodpowiedniejszym miejscem na aktualizację stanu komponentu czy to bezpośrednio czy w wyniku wywołania AJAX.
   10. każda iteracja userem zayna się od handle, np. handleClick
   11. STATIC? Metoda Statyczna- Co to jest metoda statyczna? Metoda statyczna to metoda / funkcja istniejąca w klasie, a nie w jej instancji. Najprostszą różnicą jest to, że metoda statyczna nie ma do niej dostępu i ma przed nią słowo kluczowe.
   12. getDerivedStateFromProps - UZUPEŁNIĆ! Coś sie znalazlo ale to nie wyjasnia sprawy
   13. DESTRUKTURYZACJA
   
        ```javascript 
           var first = jakaśTamTablica[0];
           var second = jakaśTamTablica[1];
           var third = jakaśTamTablica[2]; ten kod jest bez destrukturyzacji
           
           var [first, second, third] = jakaśTamTablica; ```- a ten jest z destrukturyzacja :) 
           
   14. STATE - Do przechowywania stanu komponentu. Ponadto, state można mutować dzięki funkcji ```setState```
   
# **TIL - 26.04.2018**
   1. react-router-dom - strona lub apka sie zmienia bez przeładowania storny.
   
   ```import {```
    ``` BrowserRouter as Router,```
    ``` Route,```
     ```Link```
  ``` } from 'react-router-dom';```
  
  2. TRZY ETAPY ŻYCIA COMPONENTU
  
    1.MOUNTING
        -getInitialState Wywołane raz przed zamontowaniem komponentu. Zwracana wartość będzie używana jako wartość początkowa this.state
        -getDefaultProps
        -componentWillMount
        -render
        -componentDidMount
    2.UPDATING
        -componentWillReceiveProps
        -shouldComponentUpdate
        -componentWillUpdate
        -render
        -componentDidUpdate
    3.UNMOUTING
        -componentWillUnmount
        
  3. Stan komponentu - Każdy komponent React będący klasą dziedziczącą z React.Component może posiadać swój własny, wewnętrzny stan. Na stanie komponentu opierają się wszystkie interakcje z interfejsem użytkownika oraz wszystkie dynamiczne zmiany wyglądu danego komponentu.
    Wiąże się to z cyklem życia komponentu. każda zmiana stanu komponentu powoduje ponowne wywołanie metody render (oraz metod render wszystkich komponentów dzieci, jeśli takie istnieją).
  
  4. setState Do zmiany stanu komponentu służy specjalna metoda this.setState dziedziczona z klasy React.Component:
    “Declare state changes separately from the component classes.” huh? :D 
    
    ```class User {
         ... 
         increaseScore () {
           this.setState({score : this.state.score + 1});
         }
         ...
       }```
       
   
  Zwróć uwagę, jak działa funkcja setState (). Przekazujesz mu obiekt zawierający części stanu, który chcesz zaktualizować. Innymi słowy, przekazany obiekt będzie miał klucze odpowiadające kluczom w stanie składnika, a następnie setState () aktualizuje lub ustawia stan przez scalenie obiektu ze stanem. Tak więc "stan ustalony".
  Mozesz tez przekazać do setState funkcje.. łooo :D **'the function accepts the previous state and current props of the component'**
  
  setState może byc asynchronczne, React może grupować wiele wywołań setState () w pojedynczą aktualizację w celu zwiększenia wydajności.
  "Ponieważ this.props i this.state mogą być aktualizowane asynchronicznie, nie powinieneś polegać na ich wartościach do obliczania następnego stanu." cokolwiek to znaczy :) 


# **TIL - 27.04.2018**

  1. ```React Portals``` -   wyjasnić   
  2. ```Session Storage``` - jest podobny do Window.localStorage, jedyną różnicą jest to że dane magazynowane w localStorage nie mają okreslonej "daty wazności", dane zawarte w sessionStorage zostaną wyczyszczone kiedy zamkniemy zakładkę przeglądarki, kiedy sesja strony sie skończy. 
  3. ```Local Storage``` - są to dane przechowywane w przeglądarce użytkownika. Duże ilości danych mogą być przechowywane, bez wpływu na wydajnosc witryny. Nie ma tutaj określonej "daty wazności" danych.  
  4. ```JSON Parse``` - analizuje łanńcuch znaków JSON i konstruuje wartość lub obiekt JS'owy opisny przez ten ciąg.
  5. ```JSON Stringify``` - odwrotnie do JSON Parse. Podaje się zapis JS'owy, ta metoda robi z JS'a ciąg JSON, opcjonalnie zastepując wartości.
  6. ```JavaScript Object Notation - JSON``` format teksowy, słjuży do wymiany danyc, bazujący na JS'ie  
  7. Jesli metoda jest ```static``` to nie mają dostępu do kontekstu konkretnego elementu (brak THIS'a) 
  

# **TIL - 07.05.2018** (powrót po majówce ;) 

  1. Chcesz najwiekszą wartośc z tablicy? Math.max przychodzi z pomocą.. ale ej, Math.max przyjmuje jako argumenty minimum dwie liczby,a  Ty chcesz wpakować tam tablice?
     Da się tak zrobić: ```Math.max.apply(null, NaszaTablica)``` zapisł dlugi i w ogóle..
     Lepiej jest używać ES6 i spreed operator(...)->  Math.max(...NaszaTablica) latwo i przyjemnie ;)
  2. ```Promisy``` obiekty ```PROMISE``` jest uzywany do obłsugi zdarzeń asynchronicznyc, ktore mają "ważne gwarancje", a są ciezkie do obliczenia za pomoca callback, jest to otoczka wokół wartości która może być lub nie być znana. 
     Super zostalo to wyjasnione na Type od Web "Ktoś obiecuje Ci że dostaniesz prezent, Nie wiesz kiedy to nastąpi ani nawet czy aby napewno to nastąpi" , ale niezależnie od tego - ostatecznie keidys dowiesz sie czy obietnica została otrzymana czy też nie. *Tak dokladnie działa Promise*
     Promisy mogą być w 3 stanach:
        1.PENDING (oczekujący)
        2. RESOLVED (roziwązany)
        3. REJECTED (odrzucony) 
        ```.then(present => console.log('Super prezent!' , present))
           .catch(error => console.log('nie ma prezentu', error)); ```
  4. ```RENDER PROPS``` W React dzielimy kod między komponenty używając propsów, której wartością jest funkcja.
    Komponent które będzie renderowany przyjmuje funkcje ktora zwraca element i wywoluje go zamist implementować własną logikę renderowania. 
  5. ```Object.values, Object.keys, Object.entries``` A wiec zalóżmy że mamy kilka obiektów w jednym obiekcie, I chcemy się do nich odwolać. Jeśli chcesz się odwolać do nazw tych obiektów uzyjesz Object.keys, jesli do wartości uzyjesz Object.values a jak do jednego i drugiego to Object.entries.
      see: *https://www.dropbox.com/s/rh7nm9uihhxu9ny/Screenshot%202018-05-07%2012.11.49.png?dl=0*
  6. ```STRONICOWANIE``` co to takiego? A no np. wpisz sobie w wyszukiwarce google frazę np. "praca" - pokaże się jakieś 15 najlepszych linków. Cale szczeście bo na fraze praca google może nam przekazać dużo więcej adresów (pewnie kilka milionow) a tyle nie chcemy.. Stornicowanie robi heh, podział na strony. Tyle.
  7. formatch FETCH do wkucia na pamięć!. ;)    
 
 
# **TIL - 08.05.2018**

   1. Contekst to mechanizm który łączy Consumera z Providerem
   2. Consumer musi otrzymać funckję o swoim skrzydle (przykład w TaskList.js linia 26)
   3. HOC - Higher Order Component
   
# **TIL - 09.05.2018**

   1. API - Application Programing Interface - sposób w jaki programy/ aplikacje ze sobą rozmawiają
   2. WebAPI - interfejs komunikacyjny korzystający z protokołu http i formatu JSON lub XML, pozwala na komunikajce miedzy uzytjiwbujanu a systemem na serwerze.
   3. w adresie URL po ? wywoływane sa parametry np ```https://www.youtube.com/?hl=pl&gl=PL``` pomiedzy PL a GL jest 'ampersand'
   
# **TIL - 10.05.2018**

   1. OpenStreet Map - otwarte mapy, ponoć bardzo fajne
   2. MapBox
   3. REST Verbs Table - ```http://www.restapitutorial.com/lessons/httpmethods.html```
   4. FETCH - ```https://developers.google.com/web/updates/2015/03/introduction-to-fetch```
   
# **TIL - 14.05.2018**

   1. Różnica pomiędzy autoryzacją, a autentykacją{**uwierzytelnienie**} => Uwierzytelnianie ma pozwolić na stwierdzenie, czy użytkownik jest faktycznie tym, za którego się podaje.
                                                      Autoryzacja jest w programowaniu jakby kolejnym krokiem. Jak już uwierzytelnimy użytkownika, to odbywamy kolejny proces stwierdzania, czy ten użytkownik ma dostęp do określonego zasobu (np. pliku). Autoryzacja jest więc kontrolą dostępu.
                                                      
   2. Bazy danych relacyjne, a nierelacyjne? 
   3. Object.entries() metoda która zwraca tablice z otrzymanego obiektu w postaci [key, value] <br />
   
   ```const object1 = { foo: 'bar', baz: 42 };``` <br />
    ``` console.log(Object.entries(object1)[1]);``` <br />
    ```// expected output: Array ["baz", 42] .```
   
   4. NULL ustawia NIC
   5. METODY W FIREBASE ```once``` Odsłychuje dokladnie jedno zdarzenie określonego typu zdanrzenia, a nastepnie przestaje nasluchiwać. 
   ```on``` podstawowy sposób odczytu danych z bazy danych. Twoje wywolanie zwrotn zostanie uruchomine dla danych początkowych i ponownie, gdy tyko dane ulegna zmienie.
   
   
# **TIL - 16.05.2018**

   1. Co jest narzedziem w programowaniu?
    ```https://blog.strefakursow.pl/10-przydatnych-narzedzi-dla-programistow-projektantow/```
   2. Co jest językiem programowania?
        to czym możemy zaprogramowanić jakąś logikę, jakis zbiór zasad określających, kiedy ciąg symboli tworzy program komputerowy oraz jakie obliczenia opisuje.
   3. Co jest frameworkiem?
        Szkielet budpwy aplikacji, definiuje on strukture aplikacji oraz ogólny mechanizm jej dzialania, a także dostarcza zestaw komponentów i bibliotek ogólego przeznaczenia do wykonywania okreslonych zadań
   4.  Co to biblioteka?
        Jest to zbiór prekompilowanych procedur z których program może korzystać. Procedury, czasami nazywane modulami, są przechowywane w formacie obiektowym. **Biblioteki są szczególnie przydatne do przechowywania często uzywanyh procedur, ponieważ nie ma potrzeby bezpośredniego łączenia ich z każdym programem, który ich używa. 
   5. Co to jest metodyka?
        To są zasady którymi należy sie kierowac tworząc jakiś system, żeby kazdy nie robił p swojemu, bez standardów. Pozwala konstruować, planować, kontrolować, rozwijac system.
   6. **HR**
        - Pytac sie o dalszy ciąg rekrutacji
        - Po 2 tygodniach bez odpowiedzi można do dzwonic do firmy
   7. ENZYME (narzędzie od AirBNB) sluzy do testowania JS'a dla REACT, które ułatwia manipulowania i przechodzenie przez dane wejsciowe komponentów w REACT Components.
   8. **JSX - Pozwala nam napisać składnię HTML, która dostaje przekształcone w lekkie obiekty JavaScript.**
   
   
   **REDUX** - wprowadzenie
   
   1. AKCJA w REDUX - akcja to "ładunek, paczka" które przesylają dane z Twojej aplikacji do "STORE", sa jedynym zrodlem informacji dla "STORE", wysyla się je za pomocą  ```store.dispatch()```
   2. ```STORE``` jest obiektem który posiada, przetrzymuje ```state tree``` drzewo stanu aplikacji. W REDUX app powinien byc tylko jeden store, ponieważ kompozycja odbywa sie do stronie ```REDUCER'a```
     ```dispatch(action)``` podstawowa funkcja wysyłki do store
     ```getState()``` zwraca obecny STATE ze STORE
     ```subscriber(listener)``` rejestruje funkcję która ma zostac wywołana przy zmianach stanu 
   3. ```REDUCER``` <br />
        ```type Reducer<S, A> = (state: S, action: A) => S```
        REDUCER (funkcja redukująca) - akceptuje 'akumulacje' oraz wartość, potem zwraca nowa wartosc, sluży do zredukowania zbioru wartości do pojedynczej wartości.
        
 
# **TIL - 16.05.2018**

   1. Deklaracja funkcji ```function foo(){...}```
   2. Wyrażenie funkcji <br />
            - z nazwą ```var foo = function bar(){...}```<br />
            - bez nazwy ``` var foo = function(){...}``` <br />
   3. IIFE - Immeadietly-Invoked Function Expression ```(function(){...}())```
   4. Klasy w JS'ie nie ulegają hoistingowi
   5. Layout w CSS -> rozmieszenie elementów na stroenie www
   6. Dlaczego nie stylować po ID w CSSie?
        Jest to jedna z best practise! ID jest zawsze bardziej szczegółowe niż klasa. Chodzi tutaj o specyficznośc selektorów, chcemy tego unikać bo może to prowadzić do różnego rodzaju bledów. 
   7. Pseudo-klasy w CSS to np :hover 
        **jest to słowo kluczowe dodane do selektora, które określa specjalny stan wybranych elementów**                    
   8.  Pseudo-elementy w CSS?
        Są to słowa kluczowe dodane do selektora, ktora pozwalają na stylizacje określonej częsci wybranego element. 
        <br />np. ```::after```<br />
        . ```::before```<br />
        . ```::marker```<br />
        . ```::first-line```<br />
        . ```::first-letter```<br />
        
   9. CSS visibility:hidden - znika, ale trzyma layout strony(jest renderowany ale go nie widać)
   10. CSS display: none - ustawia wyokość i szerokośc na 0px, nie trzyma layoutu, cokolwiek może zajać jego miejsce. 
   11. CSS margin collapse - nakładnie sie marginesów, gornego z dolnym. Chodzi o to ze odległość od siebie bedzie wynosila wartośc tego większego marginesu.
        wyłączyć to można kożystając z <br />
        ```float: left / right``` <br />
        ```position: absolute``` <br />
        ```display: inline-block``` <br />
   12.CSS FLEX GROW - Określa jaką ilość dostepnej przestrzni wewnątrz konternera ma zajmować dany element. Kontener mozemy podzielić na max 12 częsci.
    ok dajmy na to jeden element ma flex-grow: 3, drugi ma flex-gow: 1
    pierwszy zajmie 75% szerokości kontenera, a drugi 25%. 
   13. Bootstrap to framework, albo biblioteka zalezy gdzie szukasz.
    Jest to najpopularniejszy HTML, CSS i JS framework do tworzenia responsywnych, mobile first projektow w internecie.
   14. Różnica miedzy frameworkiem, a biblioteką.<br />
   Framework -> nadaje styl kodowania<br />
   Biblioteka-> pozwala rozwiazac jakiś problemy np MOMENT JS<br />
   15. 
