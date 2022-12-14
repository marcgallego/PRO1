# Laboratori de PRO1



## Sessió 10

- Vectors
    - Cerca dicotòmica
    - Fusió de vectors ordenats
    - Ús de `sort`, de la llibreria `algorithm` del C++

## Sessió 9

- Vectors
    - Vectors com a paràmetres (pas per referència i per referència constant)
    - Recorreguts i cerques líneals
    - Tractament d'strings com a vectors

## Sessió 8

- Recursivitat

## Sessió 7

- Funcions
    - Pas de paràmetres: per valor/per referència
    - Com fer codi modular?

## Sessió 6

- Consolidació
- Seqüències avançades
    - Finestres
    - Seqüència de seqüències

## Sessió 5

- Tractament de seqüències
    - Recorreguts
    - Cerques

## Sessió 4

- Bucles avançats
- Bucles dins bucles
- Repàs de visibilitat de variables
- Revisió de codis!


## Sessió 3

- Més `while`!
- Bucles `for`
- Lectura i tractament de seqüències d'entrada
- Imprimir decimals:

  ```cpp
  cout.setf(ios::fixed);
  cout.precision(4);
  // els doubles s'imprimiran amb 4 decimals rere el punt (per exemple, 23.2000)
  ```
- Número Pi:

  ```cpp
  #include <cmath>
  // ara podeu usar "M_PI"
  ```

## Sessió 2

- Particularitat de l'operador `and`

  ```cpp
  int x = 0;
  if (x != 0 and 1/x < LIMIT) { // funciona!
      ...
  }
  ```
  Com `x != 0` avalua `false`, el C++ s'estalvia d'avaluar la segona part!

  <br>
- Algunes normes
  - Mai dividireu entre 0!
  - Mai consultareu una variable no inicialitzada!
  - Visibilitat de variables
  - [Totes les normes per a la primera part del curs](https://pro1.cs.upc.edu/data/uploads/normes/normes-c1.pdf)

  <br>
- Condicionals
  - `if`, `else`, `else if`

  <br>
- Strings
  - Feu `#include <string>` per a usar-los
  - Hi podeu fer operacions de comparació (com `<`, `>`, `==`...)

  <br>
- Bucles `while`


## Sessió 1
- Programes i algorismes

- Terminal (UNIX)
    - Executant programes: `date`, `cal`
    - Paràmetres i flags: `cal 9 2004`, `bc -l`
    - Carpetes i fitxers: `ls`, `cat`, `cd`, `mkdir`, `rm`
    - Manual: `man`
    - <kbd>Ctrl</kbd>+<kbd>C</kbd> per a matar programes (exemple, `top`)
    
    <br>
- [Entorns de programació](https://lliçons.jutge.org/eines/index.html)
    - Tria de sistema operatiu
    - Editors de codi
    - Compilador de C++
    - `g++ -Wall -O2 -std=c++17 program.cc -o program.exe`
    - A classe, millor usar `p1++`
    - Altres consells (mida de font alta)
    
    <br>
- Logística del curs
    - Jutge (https://jutge.org)
    - Lliçons (https://lliçons.jutge.org)
    - [Problemes presentats](https://pro1.cs.upc.edu/presentats.html)

    <br>
- Primer programa i output
    - Instruccions: `cout`, `endl`
    - *Jutge*: [ Hello world! (P68688)](https://jutge.org/problems/P68688_en), [Hello and Bye! (X64734)](https://jutge.org/problems/_en)

    <br>
- Input i variables
    - Declaració i inicialització de variables
    - Instrucció de lectura: `cin`
    - *Jutge*: [Sum of two integer numbers (P57548)](https://jutge.org/problems/P57548_en)
    - Com anomenar variables?
        - Noms que s'expliquin per si mateixos
        - `camel_case`

    <br>
- Variables numèriques (`int`, `double`)
    - Operacions sobre números (unaries i binàries)
    - *Jutge*: [Promedio (P99182)](https://jutge.org/problems/P99182_es)
    - Conversions de tipus

    <br>
- Booleans (`bool`)
    - Comparacions numèriques (`>=`, `<`, `==`, `!=`, ...)
    - Operacions sobre booleans: `not`, `and` i `or `

    <br>
- Caràcters (`char`)
    - [Taula ASCII](https://en.cppreference.com/w/cpp/language/ascii)
    - Operacions amb caràcters (`cout << char('a' + 1); // imprimeix 'b'`)

    <br>
- Prioritat d'operacions
    - *Jutge*: [C++ Expression Evaluation Quiz (X81892)](https://jutge.org/problems/X81892_en)
    - Veure "[Data types and visibility](https://www.cs.upc.edu/~jordicf/Teaching/programming/pdf/IP04_DataTypes_Visibility.pdf)" (pàgina 15)
    

    <br>
- Altres temes
    - Comentaris (`// ...`, `/* ... */`)
    - Indentació (4 espais)
    - [LinuxUPC install party (21 de setembre d'11 a 17 h a l’aula A5102)](https://www.fib.upc.edu/ca/noticies/linux-install-party-2022)
