videi
---

`lab vezbe` - [link](https://www.youtube.com/watch?v=lakrCvoOsAc&list=PLWLPHZCdUNsOqqpTIgkloVXuPODRUEfin)

<br>

repo
---
> **clone**

- `git clone`
- yes
- pwd
- `cd KOL1`
- `code .`

> **commit**

- `git add *`
- `git commit -m "Gotov kolokvijum"`
- `git push`
- pwd


<br>

komande
---

> **path**
- `pwd`
- `cd` `cd ~` `cd /`
- `ls` `ls /`

> **direktorijum**
- `dir`
- `mkdir`
- `rmdir`

> **fajlovi**
- `touch`
- `rm`

<br>

biblioteke
---

- stdio.h
- stdlib.h
- string.h


<br>

argumenti
---

> **uzimanje argumenata iz terminala**

```c

int main(int argc, char* argv[]){

}

```

> **konverzija**

```c

tmp = atof(argv[i]);

```

<br>

compile
---
- `gcc imeFajla.c`
> **kada zelimo da damo posebno ime**
>
> `gcc imeFajla.c -o program`

> **ako zelimo da run-ujemo taj fajl**
> 
> `./program`

> **prosledjivanje argumenata**
>
> `./program 1 2 4 56 8`

<br>

debug
---

> **prvo moramo ka kompajlujemo**
>
> `gcc imeFajla.c -g -o program`

> **debug**
>
> `dbg program`

- `break 12`
- `condition 1 sum > 15`
- `run`
- `step`
- `print sum`
- `next`
- `quit`

<br>

fajlovi
---

- `FILE * f`
- `f = fopen("/proc/self/status", "r");`
- `fclose(f);`
- `fscanf(f, "%s", buff);`

> **provera da li je fajl otvoren**
>
> ```c
>  if(f == 0){
>    printf("doslo je do greske");
>    return -1;
>  }
> ```

> **prolazenje kroz ceo fajl**
>
> ```c
>
> while (!feof(f)){
>
> }
>
> ```












