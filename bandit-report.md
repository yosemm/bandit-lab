## Bandit Level 0->1
**Objetivo:** 
Encontrar la password del siguiente nivel. 
**Comandos utilizados:**
```bash
ls
cat
```

#### Explicacion: 
Se uso ls para ver si habia un README y lo lei con cat para encontrar la password.
#### Contrasena obtenida: 
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Bandit Level 1->2
**Objetivo:**
Encontrar la password del siguiente nivel.
**Comandos utilizados:**
```bash
ls
cat ./
```

#### Explicacion:
Se uso ls para ver si habia un archivo y lo lei con cat ./- para encontrar la password. 
El desafio es que el nombre era un guion. 
#### Contrasena obtenida:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## Bandit Level 2->3
**Comandos utilizados:**
```bash
ls
cat "./--spaces in this filename--"
```

#### Explicacion:
Se uso ls para ver si habia un archivo y lo lei con cat "" para encontrar la password. 
El desafio es que habia espacios en el nombre del archivo.
#### Contrasena obtenida:
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Bandit Level 3->4
**Comandos utilizados:**
```bash
ls -a
cat "./...Hiding-From-You"
```

#### Explicacion:
Se uso ls -a para ver si habia un archivo escondido y lo lei con cat "" para encontrar la password. 
El desafio es que el archivo estaba escondido.
#### Contrasena obtenida:
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## Bandit Level 4->5
**Comandos utilizados:**
```bash
ls -a
find ./inhere -type f -exec grep -E "[a-z]" {} \;
```

#### Explicacion: 
Use ls -a y vi que habia un folder llamado inhere. Luego revise este folder y vi que habian varios subfolders.
Decia que la password estaba en el unico archivo legible por humanos, entonces supuse que usando find, podia encontrar una cadena de texto entre todos los subfolders. Y cabal, encontre una cadena de texto y es la password.
#### Contrasena obtenida:
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw


## Bandit Level 5->6
**Comandos utilizados:**
```bash
ls
man find
find ./inhere -type f ! -executable -size 1033c
cat ./inhere/maybehere07/.file2
```

#### Explicacion:
Vi que habia un folder llamado inhere, y nuevamente el folder estaba lleno de subfolders. Pero, la pista mencionaba que tenia 1033 bytes de tamano y no era ejecutable.
Entonces con find busque archivos que no fueran ejecutables y cumplieran con el tamano y encontre el adecuado.
#### Contrasena obtenida:
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
