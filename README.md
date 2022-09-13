# avaluacio-inicial-m031t

# MP03 Grup 1T
# Avaluació Inicial

### Nom i cognoms:

1. Quin dels tres següents llenguatges de programació està més orientat a desenvolupar aplicacions web **empresarials**?

    a- C/C++

    b- php

    c- Java
    
    C-JAVA

2. Has programat abans de començar els estudis de DAW? On? Quant de temps?

    Resposta: 
    
    
    -Sí, 60 hores lectives, 40 hores per lliure.


3. Què és compilar un programa?

    Resposta:
    
    
    -Crea-lo i probar si funciona

4. Què és un llenguatge interpretat i en què es diferencia d'un llenguatge compilat?

    Resposta:


    -Un llenguatge interpretat, quan s'executa, no fa falta compilar-lo, i si dona error, dona error.ç
    -Un llengautge compilat, es compila abans de ser executat i t'avisa on està l'error.

5. Quins llenguatges de programació has fet servir?

    Resposta:  Python


6. Quina diferència hi ha entre un lleguatge de programació d’alt nivell i un de baix nivell?

    Resposta: 


    - Un d'alt nivell té més scripts i és més complexe, però pots fer més coses(té més oportunitats a l'hora de crear codi)
    - Un de baix nivell és simple i fàcil d'entendre, però no pots fer tantes coses com el complexe.

7. Explica què és un algorisme.

    Resposta:


    - Una sèrie de càlculs que fa el llenguatge per fer una operació o varies.

8. En el món de la programació Orientada a Objecte, digues quina diferència hi ha entre:

    a- Una classe i un objecte

    b- Una funció i un mètode
    
    
    Resposta d'a: Una classe serveix per crear objectes, és com un espai on es creen aquests.
    Un objecte és una unitat que conforma la classe.
    Exemple: en la classe "gat" hi ha l'objecte "tom" de "tom i jerry".


    -

    Resposta de b: Un mètode és una acció arraigada a la classe, perque aquest funciona amb l'objecte que etsá dins de la classe.
    Una funció no, aquesta va per lliure i realitza la seva acció independentment de formar part d'una classe o no.


    -

9. Feu un programa, amb el llenguatge de programació que vulgueu, que calculi l’àrea d’un quadrat i mostri el resultat per pantalla.

    (Escriu la resposta al darrere del full)
    Python:
    
    lado=float(input("ingresa la longitud de un lado del cuadrado en cm: "))
    area=lado*lado
    print("el area del cuadrado es" + area + "cm")

9. Feu un programa (amb el llenguatge de programació que vulgueu) que, donat un número qualsevol, imprimeixi la seva taula de multiplicar.

    (Escriu la resposta al darrere del full)
    Python:
    num=int(input("escribe un numero entero: "))
    for i in range (0,num)
        resultado = i*num
        print("%d x %d = %d")%(num,i,resultado)

10. Quin és el resultat d'executar el següent programa?

```java
public class Vehicle{
    public boolean used;
    public String make;
    
    public static void main(String... args){
        Vehicle v = new Vehicle();
        if(v.used) {
            System.out.println(v.make);
        } else {
            System.out.println(v.make.length());
        }
    }
}
```

    a - null
    b - 0
    c - Hi ha un error de compilació a la línia 7
    d - La línia 8 genera un error d'execució
    e - La línia 10 genera un error d'execució
    
    C
