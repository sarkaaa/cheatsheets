# Javascript - proměnná, datové typy, operace

## Deklarace proměnné
* Javascript je slabě typovaný jazyk (podobně jako Python), nedefinuje se typ proměnné.
    - var promenna = "hello world";
    - var promenna = 13;
    - var promenna = true; 

## Datové typy
### NUMBER
  - číselné hodnoty
  - Not a Number (NaN):
    - 1
    - 45
    - 1027

### STRING
  - textové znaky
  
  "Hello world!"
  "1, 2, 3"
  "!#^$&>"

### BOOLEAN
  - pravda - nepravda
  true 1
  false 0

### UNDEFINED
  - proměnná je ve stavu, kdy je deklarováná, ale zatím není ještě inicializovaná

### NULL
  - nemá žádnou hodnotu
  null

### OBJECT
  - objekt, kolekce vlastností

## Operace
### MATEMATICKÉ OPERACE
  - sčítání (+)
  - odečítání (-)
  - násobení (*)
  - dělení (/)
  - modulo, dělení se zbytkem (%)

### POROVNÁVÁNÍ

|TYP|POPIS|PŘÍKLAD|
|---|-----|-------|
| **rovnost (==)** | - pokud se hodnoty **ROVNAJÍ**, vrací true - porovnávané hodnoty **převádí** na stejný datový typ | 1 == 1 -> true, "2" == 2 true, 5 == 4 false |
| **nerovnost (!=)** | - pokud se hodnoty **NEROVNAJÍ**, vrací true - porovnávané hodnoty **převádí** na stejný datový typ | "2" != 2 -> true, 1 != 1 -> false, 3 != 2 -> true |
| **striktní rovnost (===)** | - pokud se hodnoty **ROVNAJÍ**, vrací true - porovnávané hodnoty **NEpřevádí** na stejný datový typ  | "1" === 1 -> false, 4 === 4 -> true, 3 === 1 -> false |
| **striktní nerovnost (!==)** | - pokud se hodnoty **NEROVNAJÍ**, vrací true - porovnávané hodnoty **NEpřevádí** na stejný datový typ | "3" !== 1 -> false, 3 !== 3 -> false, 4 !==2 -> true|
| **větší než (>)** | - pokud je hodnota na levé straně **VĚTŠÍ** než hodnota na pravé straně, vrací true - porovnávané hodnoty **převádí** na stejný datový typ | 0 > 1 -> false, 2 > "" -> (0) true, 4 > 2 -> true |
| **větší nebo rovno (>=)** | - pokud je hodnota na levé straně **VĚTŠÍ NEBO ROVNA** hodnotě pravé straně, vrací true - porovnávané hodnoty **převádí** na stejný datový typ | 0 >= 1 -> false, 1 >= 1 -> true, "2" >= 2 -> true|
| **menší než (<)** | - pokud je hodnota na levé straně **MENŠÍ** než hodnota na pravé straně, vrací true - porovnávané hodnoty **převádí** na stejný datový typ | 0 < 1 -> true, 3 < "" -> (0) false, 2 < 2 -> false|
| **menší nebo rovno (<=)** | - pokud je hodnota na levé straně **MENŠÍ NEBO ROVNA** hodnotě pravé straně, vrací true - porovnávané hodnoty **převádí** na stejný datový typ | 0 <= 1 -> true, "2" <= 2 -> true, 3 <= 1-> false |

### LOGICKÉ OPERÁTORY

|TYP|POPIS|PŘÍKLAD|
|---|-----|-------|
| **and (&&)** | - násobení, "a zároveň" | true&&true -> true, 0&&1 -> 0, true&&false -> false |
| **or (\| \|) | - sčítání, "nebo" | true \| \| true -> true, 1 \| \| 0 ->1, 0 \| \| 2 -> 2 |
| **not (!)** | - negace | !true -> false, !0 -> true|
