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
