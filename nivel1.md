# Java (llenguatge de programació)

> No s'ha de confondre amb [JavaScript](https://ca.wikipedia.org/wiki/JavaScript).

El **Java** és un [llenguatge de programació](https://ca.wikipedia.org/wiki/Llenguatge_de_programaci%C3%B3)  dissenyat el [1990](https://ca.wikipedia.org/wiki/1990)
per James Gosling amb altres companys de [Sun Microsystems](https://ca.wikipedia.org/wiki/Sun_Microsystems) a partir del
[llenguatge C](https://ca.wikipedia.org/wiki/Llenguatge_C). Des del seu naixement fou pensat com un llenguatge
[orientat a objectes](https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes). Entre el [13 de novembre](https://ca.wikipedia.org/wiki/13_de_novembre) de
[2006](https://ca.wikipedia.org/wiki/2006) i el maig del [2007](https://ca.wikipedia.org/wiki/2007) Sun va alliberar parts de Java com a
[programari lliure](https://ca.wikipedia.org/wiki/Programari_lliure) de [codi obert](https://ca.wikipedia.org/wiki/Codi_obert) amb llicència
[GPL](https://ca.wikipedia.org/wiki/GNU_General_Public_License). És un dels llenguatges de programació més utilitzats, i s'utilitza tant per aplicacions web com per
[aplicacions d'escriptori](https://ca.wikipedia.org/wiki/Programari).

#### Contigut

1. ***Característiques de Java***
2. ***Tipus de Dades***
	1.  ***Tipus de dada primitius o variables primitives***
	2.  ***BOOLEÀ (boolean)***
 	3.  ***CARÀCTER (char)***
 	2.  ***NUMÈRICS ENTERS (byte, short, int, long) i NUMERICS REALS (fload, double)***
3. ***Altres Característiques***
4. ***Sintaxi***
 	1.  ***Hola Món***

## Característiques de Java


### Aplicacions i miniaplicacions
* Els programes de Java es divideixen principalment en dues categories.
	 * Aplicacions: són programes autònoms i independents
 	 * Miniaplicacions: les miniaplicacions o applets Java són programes incrustats en pàgines HTML, i aquests s'executen damunt de navegadors Web.


#### Passos per crear un programa amb Java
* Crear un arxiu amb el codi del programa amb extensió .java.
ex. elmeuprograma.java

* Compilar el programa per crear l'arxiu executable (arxiu de bytecodes ) que tindrà l'extensió .class.
> ex. javac elmeuprograma.java
* Si es produeixen errors corregir-los.
* Executar el programa amb l'intèrpret de bytecode (JVM).
>  ex. java elmeuprograma
* Si el programa no funciona utilitzar el depurador per executar el programa pas a pas.


##### Programa d'exemple
Aquest programa escriu ["Hola món"](https://ca.wikipedia.org/wiki/Hola_m%C3%B3n) al [dispositiu de sortida predeterminat](https://ca.wikipedia.org/wiki/Perif%C3%A8ric) (no>

```
class HolaMon {
    public static void main (String args[])
    {
        System.out.print("Hola, món!");
    }
}
```
###### Referències
[Programming Language Popularity](https://web.archive.org/web/20090116080326/http://www.langpop.com/)
