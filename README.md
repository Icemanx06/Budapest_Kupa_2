	
Budapest Kupa 2 (Java)
A Budapest Kupát a Teljesítménytúrázók Társasága írta ki. Elnyerésének feltétele, hogy a 2017-re meghirdetett 144 túrából
legalább 10 túrán vegyen részt az ember, és igazoltan teljesítse is azt. Az ön feladata egy olyan program írása, amely az ebben
a sorozatban szereplő túrák adatait dolgozza fel.
A standard bemenet első sorában a feldolgozandó túrák darabszáma szerepel (N). A következő N sor egy-egy túra adatait tartalmazza
a következő formában: év;hónap;nap;túra_neve;túra_távja[;túra_távja]…
Az év, a hónap és a nap az év egy napjának leírására szolgál: az év az évszámot, a hónap a hónap éven belüli sorszámát,
a nap pedig a túra napját írja le az adott hónapon belül. Az év, hónap, nap adatok mindig egy valódi, létező dátumot jelölnek.
A túra_neve egy sztring, a túra_távja pedig minden előfordulásakor egy pozitív egész szám. Az említett adatokat pontosvessző karakterek
választják el egymástól egy soron belül. A pontosvessző karakter nem szerepel egyik túra nevében sem.
A programjának a standard kimenetre kell írnia a túrák adatait dátum szerint növekvő sorrendben!
Ha két túrát is ugyanazon a napon rendeznének meg, akkor ezeket a túrákat a nevük alapján állítsa lexikografikusan növekvő sorrendbe!
Azoknál a túráknál, amelyeket többféle távon is megrendeznek, csak a leghosszabb táv hosszát jelenítse meg a kimeneten!

Példa bemenet:
4
2017;04;01;Pipi;12
2017;01;21;Toldi Miklos emlektura;10;30;5;20;50;40
2017;04;01;Baba;22
2017;02;04;Kitaibel Pal emlektura;25;10;18;35

A példa bemenethez tartozó kimenet:
2017;01;21;Toldi Miklos emlektura;50
2017;02;04;Kitaibel Pal emlektura;35
2017;04;01;Baba;22
2017;04;01;Pipi;12
