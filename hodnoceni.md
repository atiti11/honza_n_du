Ahoj,
posílám zpětnou vazbu na tvůj 4. domácí úkol.

Obrázky jsi měl nalinkované ze složky `/bonusovy-ukol`, která ale už v odevzdaném úkolu nebyla - absolutní cesty je potřeba dělat z adresáře, odkud pak pustíš live server - většinou to bývá adresář, kde máš `index.html` (a názve tohoto adresáře už se tam nedává). Správné nalinkování např. obrázku `bota.png` tedy není `/bonusovy-ukol/images/bota.png`, ale `/images/bota.png`. Také vzhledem k tomu, že tam používáš víc css souborů, tak je lepší přesunout do jedné složky, aby kmenová složka byla pokud možno co nejvíc čistá.

Webová stránka ti funguje dobře (po opravení odkazů na obrázky). Co se týče flexboxu, tak myslím, že jsi ho docela dobře pochopil a správně jsi ho použil. ;)

Co se týče html: první část (tzn. ty 4 obrázky na začátku) je trochu nepřehledná, protože není oddělená od druhé části (stačí prázdný řádek a člověk se už rychle chytí). Jednotlivé karty a jejich kontejner už jsou ale v pohodě.

Co se týče css: dobře, že jsi zakomentářoval styly pro `<body>` ve všech css souborech a pak jsi tyto styly definoval jen na jednom místě - to samé i pro `*`. Zároveň máš dobře ošetřené (tím, že se ti třídy u jednotlivých karet jemnují jinak), že se ti nestane, že by se např. na kartu 1 použily styly ze souboru `card-2.css` atp. To je rozhodně dobře, protože by se ti to pak nepěkně křížilo a něvěděl bys, co vlastně upravuješ apod. Taky je super, že sis vytáhnul barvy do proměnných, pořád je pěkný ten javascript u karty sluchátka ;) U některých breakpointů u media query jsem navrhla jejich posunutí na jinou hodnotu pro lepší konzistenci co se týče vycentrování.

Kdybys měl nějaké otázky, tak se určitě ptej a měj se hezky

Anička
