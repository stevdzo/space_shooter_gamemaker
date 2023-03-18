# space_shooter_gamemaker

Cilj ove igre je da igrač uništi 3 glavna neprijateljska svemirska broda koja se pojavljuju na poslednjem nivou. Do tada, igrač mora da pazi i da uništava nadolazeće bombe, male brodove, satelite. 

Na prvom nivou, igrač se susreće sa neprijateljima (u ovom slučaju bombama) i uslov da pređe na sledeći nivo je pre svega da ne bude dodirnut, ili upucan od strane istih, jer je tada igrač izgubio. Ukoliko bombe odu izvan opsega mape, bombe bivaju uništene. (to važi za svaki nivo).
Na drugom nivou se, pored bombi, pojavljuju i mali brodovi koji nasumično pucaju u smeru kretanja. Uslov za prelazak na sledeći nivo je isti za svaki nivo. 
Na trećem nivou pojavljuju se rotirajuci sateliti koji ciljaju igrača. Oni se kreću nasumično gore, dole, levo, desno i njihovo ponašanje je nepredvidivo. 
Četvrti nivo je finalni nivo, u njemu se pojavljaju, uz sve prošle navedene neprijatelje, 3 velika svemirska broda, koji pucaju nasumično u smeru kretanja bombi i brodova i pucaju igrača, krećući se gore-dole. 

Korišćenjem već standardnih slova za kontrolu (W, A, S, D), igrač upravlja avionom. Lasere ispaljuje na slovo P.
Igrač igru počinje sa 100 životnih poena (HP). Kolizijom sa bilo kojim neprijateljem, igrač je izgubio I mora da krene igru ispočetka.
Igrač neograničeno ispaljuje zelene lasere koji skidaju 10 životnih poena koga god da pogode.
Uništenjem neprijatelja, igrač sakuplja poene:
•	Bomba – 50 poena;
•	Mali Brod – 100 poena;
•	Rotirajući Satelit – 150 poena;
•	Veliki Brod – 2000 poena.
Od trećeg nivoa, javlja se prva pomoc, kojom kada je pokupi, igrač vraća sebi 20 životnih poena.
Crveni laser igraču skida 20 HP i 20 poena i ispaljuju ga mali brod I veliki svemirski brod.
Žute bombice ispaljuju rotirajuci satelit i veliki brod i svakim pogotkom skida igraču 10 HP i 20 poena. 

Neprijatelji (Enemies)
•	Bomba – 40HP – Kreće se ka igraču – Ne ispaljuje ništa;
•	Mali Brod – 20HP – Kreće se ka igraču – Ispaljuje crvene lasere;
•	Rotirajući Satelit – 100HP – Nasumično se kreče u svim pravcima – Ispaljuje  žute bombice;
•	Veliki Brod – 500HP – Kreće se po vertikali velikom brzinom – Ispaljuje crvene lasere i žute bombice velikom brzinom.

Grafiku igre sam radio u samom Gamemakeru-u I u Photoshopu.
Zvučni efekti 
Zvučne efekte sam pravio u programu Fruity Loops Studio 12 i dorađivao ih u Audacity-u.

https://user-images.githubusercontent.com/71758728/226129812-b28b476d-a2a9-4a5c-b7ce-68bec97e18bf.mp4


