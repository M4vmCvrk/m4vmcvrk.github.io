---
layout: default
---

* * *

## hello 9

* * *

```python
import random

simboli = "abcdefghijklmnopqrstuvwxyz"

print(".")

while 1:
    duzina = int(input("Duzina: "))
    sifra  = ""
    for x in range(0,duzina):
        sranje = random.choice(simboli)
        sifra = sifra + sranje
    print(sifra)
    print(".")
#simboli==x
print(simboli)
```

<!--- D -->

* * *