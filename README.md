# GyvunaiPHP

## Užduotis
Sukurti PHP programą. Programa automatiškai nuskaito Duombazę, suformuoja gyvūnus ir paklausia vartotojo kurį gyvūną parodyti. Kai vartotojas įveda pasirinkimą pateikiama visa gyvūno informacija bei iškviečiamas jo judėjimo veiksmas.

## Duomenų struktūros aprašymas
Lentelėje yra duomenys apie įvairius gyvūnus. 
```
Gyvunas | Rūšis | Vardas | Svoris | Ugis | Veiksmas
dog mammal Bobikas 3.5 0.5 walk
cat mammal Silvestras 1.9 0.35 sneak
pigeon bird Tveetty 0.1 0.05 fly
```

## Architektūra:
* Kiekvienas gyvūnas paveldi iš klasės **Animal**. 
* Panaudoti **Factory** pattern suformuoti gyvūno objektui. 
* Panaudoti **mysqli** nuskaitant informaciją iš duombazės.
* Panaudoti **MVC** design pattern visos programos pagrindu
* Dažniausiai naudojamus veiksmus pasidėti į modulius
* Duomenis užklausas į duombazę reikia apsaugoti su **Prepared Statement**
* Duomenų objektai turi būti laikomi sąraše.
* Vengti switch/case!!!

## Reikalavimai programiniam kodui:
* Visas kodas turi sekti PHP naming convention.
* Programinį kodą laikyti GitHub saugykloje.
* Dirbant su git panaudoti branch ir merge, kad būtų matoma GitHub puslapyje.
* Nupiešti UML klasių diagramą su Google Draw ir pridėti nuorodą į GitHub readme dalį.
* Nupiešti UX diagramą
