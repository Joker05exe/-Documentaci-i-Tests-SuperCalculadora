# 🧮 SuperCalculadora — Implementació i instruccions

**Lliurament del projecte:**
1. Crear el repositori: [Enllaç creació repositori]
2. Clonar el repositori de la SuperCalculadora.
3. Un cop finalitzada l'activitat, escriu la URL del teu repositori en la caixa de text de lliurament.

---

## Objectiu
Implementar els mètodes d’una classe `SuperCalculadora` que permetin realitzar diferents operacions matemàtiques bàsiques.

## ✳️ Implementar els mètodes
La classe `SuperCalculadora` ha de contenir els següents mètodes:

* **`sumaPrimersNumeros(int n)`**: Retorna la suma dels primers `n` números positius (1 + 2 + ... + n).
* **`calcularFactorial(int n)`**: Retorna el factorial de `n` (ex. 5! = 5 × 4 × 3 × 2 × 1).
* **`sumaQuadrats(int n)`**: Retorna la suma dels quadrats dels primers `n` números (1² + 2² + ... + n²).
* **`calcularPotencia(int base, int exponent)`**: Retorna la base elevada a l'exponent. 
    * ⚠️ **Important:** Implementar **fent sumes** (no usar `*` ni `Math.pow()`).
* **`nombreDigits(int n)`**: Retorna el nombre de dígits de `n`.
* **`esPrimer(int n)`**: Retorna `true` si `n` és primer, `false` en cas contrari. Comprovar divisibilitat entre 2 i `n - 1`.
* **`esPerfecte(int n)`**: Retorna `true` si `n` és perfecte (la suma dels divisors, excepte el mateix, és igual a `n`).

## 📋 Mostrar menú d’operacions
Implementa el mètode `mostrarMenuConsola()` dins de la classe `SuperCalculadora`. Aquest mètode podrà contenir `System.out.println` per mostrar les opcions a l'usuari.

## 🚀 Mètode main
1. Mostrar el menú amb `mostrarMenuConsola()`.
2. Demanar a l'usuari que triï una opció.
3. Llegir per teclat els valors necessaris segons l'opció.
4. Mostrar el resultat.

## 🧭 Exemple de Menú
```text
Menú de SuperCalculadora:
1- Suma dels primers n números
2- Factorial d'un nombre
3- Suma dels quadrats dels primers n números
4- Potència d'un nombre
5- ...
0- Sortir
