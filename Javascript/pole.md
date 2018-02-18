# Javascript - pole a práce s ním

## Vytvoření pole
* var pole = new Array();
* var pole = [];
* var pole = [1, "Apple", []];

### Přídání prvku do pole
* pole[0] = "Banana";
* pole[1] = "Plum";

### Vnořené pole
* pole2 = [["Apple", "Pear", "Blueberry", "Raspberry"]];

### Načtení hodnot z pole
* hodnota = pole[1];
* hodnota2 = pole2[0][1];

## Modifikační metody
### pop()
* Odstraní a vrátí poslední prvek z pole
* var pole = ["One", "Two", "Three"];
* pole.pop();
* vrací "Three" a vymaže jej z pole

### push()
* Přidá prvek na poslední index pole
* pole.push("Four");

### reverse()
* Převrací pořadí prvků
* pole.reverse();
* vrací ["Four", "Three", "Two", "One"]

### shift()
* Odstraní první prvek z pole a vrátí ho
* pole.shift();
* vrací "One"

### sort()
* Srovná hodnoty v poli vzestupně (nebo podle abecedy)
* pole.sort();
* vrací ["Four", "One", "Three", "Two"];

### splice()
* Vymaže prvek na daném pořadí a nahradí jej novým/i
* pole.splice(1,1,"Dvě", "Tři"); - (pořadí, od kterého prvku bude náhrada; počet nahrazených prvků; čím bude prvek nahrazen)
* vrací ["One", "Dvě", "Tři", "Three", "Four"];

### unshift()
* Přídá jeden (nebo více) prvků na začátek pole
* pole.unshift("Zero")
* vrací ["Zero", "One", "Two", "Three", "Four"];

## Přístupové metody
### concat()
* Spojí více polí do jednoho (původní jsou ale netknutá)
* pole1 = ["One"];
* pole2 = ["Two"];
* pole3 = ["Three"];
* pole = pole1.concat(pole2, pole3);
* pole vrací ["One", "Two", "Three"];

### join()
* Spojí prvky pole do textového řetězce (lze předat argument, který bude prvky oddělovat)
* pole.join(", ");
* Vrací One, Two, Three

### toString()
* Textová reprezentace pole (neřeší datový typ)
* var pole=["Do", "what", "you", "want"];
* pole.toString();
* vrací "Do what you want"

### indexOf()
* hledá první výskyt daného prvku v poli a vrací jeho indexové pořadí
* pole.indexOf("what");
* vrací číslo 1

### lastIndexOf()
* jako indexOf(), ale prohledává pole od konce
