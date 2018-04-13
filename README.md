# Intro-till-programmering
Detta projekt är gjort för att förenkla programmeringen för min klass i kursen teknologi.

### Kommentarer
Kommentarer är text som inte kommer att köras av programmet. Oftast använder man kommentarer för att få en struktur på sin kod. Så här ser kommentarer ut i en kodfil.
```cpp
// Detta är en enkelkommentar

/* Detta är en kommentar som
fungerar för flera kodrader. */
```

### Variabler
En variabel deklareras genom att ange variabeltypen följt av ett namn (ange relevanta namn för enkelhetens skull) sedan ett =-teken och slutligen värdet som variabeln ska ha. Så här ser variabler ut i en kodfil.
```cpp
const int led = 13;
```
Notera att vi har lagt till `const` framför variabeltypen. Detta betyder att variabeln är en konstant, det vill säga att den inte kommer att ändras. En LED pin, som i exemplet ovan kommer ju inte att ändras.

I exemplet nedan kan vi se en sensors värde, detta värde kommer ju att ändras beroende på t.ex en potentiometer och vi använder därför inte `const`.
```cpp
int sensorValue = 0;
```

### Loop
Loop metoden körs om och om igen i all oändlighet. Så här ser loop-metod ut i en kodfil.
```cpp
void Loop() {
  // Skriv koden som ska upprepas här.
}
```
