0. Opis

Poniższe pliki źródłowe sąnotatkami(skryptem), oraz slajdami do wykładu: Wstęp do Topologii i Geometrii Różniczkowej, Wydział Matematyki i Informatyki 
UAM, Poznań.

Korzystanie z nich w celach poszerzania swojej wiedzy jest dozwolone a nawet rekomendowane. Osoby chcące użyć tych materiałów w celach dydaktycznych 
proszone są o wcześniejszy kontakt ze mną, a przynajmniej poinformowanie mnie o tym fakcie.


1. Uwagi wstępne

Materiały podzielone są na 15 wykładów, które "pęcznieją" wraz ze swoim numerem, tj. ich długość i objętość zawartej treści jest mniej więcej 
proporcjonalna do ich numeru porządkowego. Dlatego zalecane jest przyśpieszanie pierwszych wykładów (Wykład drugi jest bardzo mały, na pierwszych 2
(fizycznych) wykładach można właściwie omówić treść z pierwszych 3 rozdziałów tych materiałów.

Wykłady 13 (o Twierdzeniu Gaussa-Bonneta), 14 i 15 (o geometriach nie-euklidesowych i powierzchniach o stałej krzywiźnie) są raczej poglądowe, dowodów 
tam jest raczej niewiele. Mają one raczej charakter informacyjny i motywujący do dalszej nauki geometrii różniczkowej.

Zdaję sobie sprawę, że typografia notatek/skryptu pozostawia wiele do życzenia. Jest to jednak skutek tego, że i skrypt i slajdy powstają z tych samych 
plików źródłowych. Coś, co wygląda dobrze na slajdzie niekoniecznie musi dobrze wyglądać w tekście i vice-versa. Wraz z kolejnymi uwagami mam jednak 
nadzieję ten aspekt polepszać. Wszystkie uwagi na ten temat są jak najbardziej mile widziane.


2. Kompilacja, Uwagi wstępne:

Jeśli ktoś nie posiada zainstalowanej czcionki Lucida Bright, musi usunąć/zastąpić linię
\usepackage{lucidabr} 
z pliku main.tex;


Cała mechanika dokumentu znajduje się w pliku main.tex (wszystkie \usepackage, własne definicje itp.). Jednak main.tex nie jest plikiem kompilowalnym tego 
dokumentu, tj. nie posiada np. komendy \documentclass{...}. Tę komendę posiadają pliki main.article.tex i main.beamer.tex i to je trzeba kompilować w celu 
uzyskania plików pdf.

Równocześnie w pliku main.tex można włączać lub wyłączać poszczególne wykłady.

Skrypt:
pdflatex main.article.tex

Prezentacja:
pdflatex main.beamer.tex
