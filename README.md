## Introduction
![Bash Logo](/assets/BashLogo.png)

### Skrypty Bash - Tworzenie prostych skryptów powłoki do automatyzacji zadań systemowych.

---

#### Czym jest bash?
> Bash - powłoka systemowa i **język skryptowy**, który służy jako interfejs do komunikacji (terminal) z systemem operacyjnym (glownie UNIX i UNIX-podobne (Linux)). **Celem dzisiejszej prezentacji jest omowienie jezyka skryptowego bash w kontekscie automatyzacji zadan w systemie**

---

### Bash jako język skryptowy
Pliki ktore uzywaja basha jako jezyka skryptowego zazwyczaj maja koncowce .sh
Pierwsza linia w skrypcie ktory uzywa basha jest zazwyczaj #!/bin/bash mowi to komputerowi ze do wykonania tego pliku powinnien zostac uzyty bash
Bash jest zazwyczaj uzywany do pisania prostych skryptow ktore automatyzuja jakies dzialania

#### Zalety Basha
- Bash jest wszedzie (jest domyslnym shellem w linuxie, kiedys byl w macos)
- Bash dziala jako interpreter i jezyk skryptowy 
- Pozwala automatyzowac wiele zadan
- Mozna odpalic go wszedzie uzywajac odpowiednich narzedzi
I wiele innych..

#### Skladnia Basha
0. **typy zmiennych**
```bash
number (...,-1,0,1,2,3, ... itp.) 
string (kazdy tekst zawarty w cudzyslowach)
array (tablica mogaca zawierac kazdy typ zawartosci w sobie)
assosciative array (tablica gdzie indexami sa stringi, zeby zadeklarowac tablice assioatywna trzeba uzyc deklaracji "declare -A <nazwa_tablicy>")

```
###### kazdy typ da sie zadeklarowac poprzez 'declare', mozna wiecej poczytac na [declare man page](https://linuxcommand.org/lc3_man_pages/declareh.html)

---

1. **przypisywanie zmiennych**
```bash
<nazwa_zmiennej>\=<typ_danych>
number:
x=1

string:
x="hello world"

array:
x=("array" 1 ("array2" "array3"))

assosciative array:
declare -A x
x["banana"]=5
x["apple"]=5

```
---

2. **odwolywanie sie do tych zmiennych**

---

3. **dzialania na zmiennych**

---

4. **warunki i petle**

---

5. **tabilce**

---

6. **podawanie argumentow**

---

7. **odwolywanie sie do innych plikow bash**

---
#### Cele automatyzacji
Glownym celem automatyzacji jest pozbycie sie potrzeby wlasnorecznego wykonywania tych zadań

#### Jakie przyklady podam?



