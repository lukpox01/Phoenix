# Phoenix

```ts
// Dynamické premenné
dyn x = 10;     // Deklarácia dynamickej premennej x s hodnotou 10
dyn y = "Ahoj"; // Deklarácia dynamickej premennej y s textovou hodnotou "Ahoj"

// Statické premenné
let cislo: int = 15;                            // Deklarácia statickej premennej cislo s typovým obmedzením int
let text: string = "Toto je statická premenná"; // Deklarácia statickej premennej text s typovým obmedzením string

// Podmienený príkaz if, ktorý kontroluje, či je premenná x väčšia ako 10
if (x > 10) {
    // Kód, ktorý sa vykoná, ak je podmienka splnená
    print("X je väčšie ako 10");
} else {
    // Alternatívny kód, ktorý sa vykoná, ak podmienka nie je splnená
    print("X je menšie alebo rovné 10");
}

// Definícia funkcie suma s dvoma parametrami typu int a návratovou hodnotou typu int
func suma(a: int, b: int) -> int {
    // Implementácia funkcie, ktorá vracia súčet parametrov a a b
    return a + b;
}

// Cyklus while, ktorý sa opakuje, kým je premenná i menšia ako 10
let i = 0;
while (i < 10) {
    // Vypíše hodnotu premennej i
    print(i);

    // Aktualizácia premennej i
    i++;
}

// Cyklus for, ktorý sa opakuje 5-krát s premennou i od 0 do 4
for (let i = 0; i < 5; i++) {
    // Vypíše hodnotu premennej i
    print(i);
}

// Definícia triedy Osoba s konštruktorom pre parametre meno (string) a vek (int)
class Osoba(meno: string, vek: int) {
    // Deklarácia atribútov
    dyn meno;
    dyn vek;

    // Inicializačná metóda
    _init_(meno: string, vek: int) {
        this.meno = meno;
        this.vek = vek;
    }

    // Definícia metódy pozdrav v triede Osoba
    pozdrav() {
        // Implementácia metódy, ktorá vypíše pozdrav s menom a vekom osoby
        print("Ahoj, volám sa " + this.meno + " a mám " + this.vek + " rokov.");
    }
}

dyn osoba1 = new Osoba(meno: "Jano", vek: 30);
osoba1.pozdrav();

```

### ***Language:*** **Phoenix** *(powerful, self-reliant)*
### ***Package Manager:*** **Pyre** *(platform where the Phoenix combusts before rebirth, signifying the space where packages are compiled)*
### ***Version Manager:*** **Aviary** *(manages a collection of birds/language versions)*
