## Domácí úkol

Ve čtvrté lekci jsme si ukázali jak používat `switch` a také jsme si ukázali uplný základ Objektově orientovaného programování v Javě. Tento je vaším domácím úkolem implementovat řešení následujícího problému:

Pro geometrické tvary trojúhelník, čtverec, obdélník, kruk vytvořte program, který spočítá obsah a obvod. Můžete použít následující tabulku, případně [Heronův vzorec](https://cs.wikipedia.org/wiki/Heron%C5%AFv_vzorec)

| Tvar     | Obvod | Obsah  |
|----------|:-------------:|------:|
| Obdélník | o = 2 * (a + b)   | A = a * b  |
| Čtverec   | o = 4 * a        | A = a^2 |
| Trojúhelník  | o = a + b + c  | A = 1/2 * z * v  |
| Kruk    | o = 2 * π * r      | A = π * r^2   |

Vytvořte dvě implementace:
1. Vytvořte jednoduchou implementaci pomocí výrazu `switch`.
2. Navrhněte objektový model, který umožní použít jednotný přístup k výpočtu obvodu a obsahu nezávisle na interní implementaci. A udělejte implementaci pro tyto 4 základní typy objektů. Když budeme mít čas, tak můžete program i rozšířit o další typy, případně další výpočty (např. minimální velikost obdélníkového papíru, kam se objekt vejde).
