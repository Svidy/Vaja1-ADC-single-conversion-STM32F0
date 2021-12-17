# Vaja1-ADC-single-conversion-STM32F0

Zelena LED je priključena na PA5 pin.
Kaj je pa priključeno na pin PA0? Potenciometer.
V Analog razdelku levo od sheme mikroprocesorja ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? 3 pretvornike.
Izbrani ADC pretvornik(i) ima(jo) oznako s trikotnikom. Kaj to pomeni? To pomeni, da je konflikt z pini/so že zasedeni.
Kaj morate storiti, da razrešite to omejitev? Vse zasedene pine moramo postaviti v stanje RESET, zato da ni nobenega konflikta.
Koliko je vseh vhodnih kanalov (seštejte oznake INxx). 15 vhodnih kanalov.
Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC1_IN3, pin PC2.
Preglejte, kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
10bit, od 0 do 1023,
12bit, od 0 do 4095,
14bit, od 0 do 16383.

Komentar: Na začetku nisva imela težav, ko pa sva prišla do nalaganja kode pa nama ni uspelo naložiti programa, čeprav
sva zamenjala računalnik, sva imela isti problem z nalaganjem(Failed to connect to GDB server).
