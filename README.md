# Proiectare-microsistem

Să se proiecteze un microsistem cu următoarea structură:
-unitate central cu microprocesorul 8086;
-128 Ko memorie EPROM, utilizând circuite 27C512;
-64 Ko memorie SRAM, utilizând circuite 62256;
-interfaţă serială, cu circuitul 8251, plasată în zona 0650H – 0652H sau 0E50H – 0E52H, în
funcţie de poziţia microcomutatorului S1;
-interfaţă paralelă, cu circuitul 8255, plasată în zona 0260H – 0266H sau 0360H – 0366H, în
funcţie de poziţia microcomutatorului S2;
-o minitastatură cu 9 contacte;
-24 LED-uri;
-un modul de afişare cu 7 segmente, cu 6 ranguri (se pot afişa maxim 6 caractere hexa simultan).
-un modul LCD, cu 2 linii a câte 16 caractere fiecare, cu o interfaţă la alegerea studentului.
Toate programele în limbaj de asamblare vor fi concepute sub formă de subrutine. Programele 
necesare sunt:
-rutinele de programare ale circuitelor 8251 şi 8255;
-rutinele de emisie/ recepţie caracter pe interfaţa serială;
-rutina de emisie caracter pe interfaţă paralelă;
-rutina de scanare a minitastaturii;
-rutina de aprindere/ stingere a unui led;
-rutina de afişare a unui caracter hexa pe un rang cu segmente.
