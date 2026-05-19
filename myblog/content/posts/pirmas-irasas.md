+++
title = 'Pirmas įrašas'
date = 2026-05-19T12:00:00+03:00
draft = false
+++

Sveiki, čia mano pirmas įrašas Hugo tinklalapyje. Šitas puslapis sugeneruotas
naudojant Hugo statinio puslapio generatorių ir PaperMod temą.

## Paveiksliukas

![Test image](/images/cipa-jo-2.jpg)

## Java kodo pavyzdys

Štai paprasta Java klasė, atspindinti laivo objektą:

```java
public class Laivas {
    private String pavadinimas;
    private int talpa;
    
    public Laivas(String pavadinimas, int talpa) {
        this.pavadinimas = pavadinimas;
        this.talpa = talpa;
    }
    
    public String getPavadinimas() {
        return pavadinimas;
    }
    
    public int getTalpa() {
        return talpa;
    }
}
```