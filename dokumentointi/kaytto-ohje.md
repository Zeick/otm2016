# Tässä on erään lempisivustoni logo
![Näkyyköhän tämä teksti missään](http://im.haberturk.com/2011/08/21/661466_detay.jpg)

### Esimerkki C-ohjelmointikielilähdekoodista

```C
#include <stdio.h>
#define MAX 100
#define MIN -40

int main(void){
    int i,j,k;
    char *s;
    for(i = MIN; i <= MAX; i++){
        printf("%d\t%d\n",i,pow(i,2));
    }
    return 0;
}
```

### Esimerkki Javasta
```Java
public class Salla{
private int ika;
private int pituus;
private int paino;
private String tutkinto;

public Salla(int ika, int pituus, int paino, String tutkinto){
    this.ika = ika;
    this.pituus = pituus;
    this.paino = paino;
    this.tutkinto = tutkinto;
}

public int getIka(){
    return this.ika;
}
```

### Kokeillaan seuraavaksi taulukoiden tekemistä Markdownilla

Tieteenala | Tunnettu henkilö
---------- | ----------------
Fysiikka | Albert Einstein
Kemia | Antoine Lavoisier
Matematiikka | Carl Gauss
Biologia | Charles Darwin
Filosofia | René Déscartes
Politiikka | Mahatma Gandhi
Kuvataide | Leonardo da Vinci
Tietojenkäsittelytiede | John von Neumann
Sotatiede | Napoléon Bonaparte
Tekniikka | Thomas Edison
Psykologia | Sigmund Freud
Videopelit | Shigeru Miyamoto

### Lähdekoodia voi lisätä yläheittomerkkien väliin

Tässä esimerkki lähdekoodin lisäämisestä. Tämä on kätevä, kun halutaan näyttää pätkiä lähdekoodista.

Aliaksia voi kirjoittaa tiedostoon `~/.bashrc`, missä `~` on kotihakemisto.
