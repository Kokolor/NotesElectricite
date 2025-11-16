# Résistance
## **Explications**
### Une résistance freine le courant, et non la tension

La résistance est un composant électronique fondamental freinant le courant

## **Analogies**
### Analogie de l'eau
```
Pression (Tension) de 10 bars → Tuyau étroit (Résistance)  → Débit réduit de 2 litres/sec (Courant)
```

- La **pression** (tension) pousse l'eau
- Le **tuyau étroit** (résistance) limite le **débit** (courant)
- Résultat : il y a une **chute de pression** à travers le tuyau

## Lois et concepts
### La loi d'Ohm (!)
```
V = R × I

V = Tension (Volts)
R = Résistance (Ohms, Ω)  
I = Courant (Ampères)
```

#### Signification

**La résistance crée une relation entre tension et courant** :
- Plus de résistance → moins de courant pour la même tension
- Ou : plus de résistance → plus de tension nécessaire pour le même courant

## **Exemples**
### Exemple d'une LED simple
#### Sans résistance
```
Batterie 9V → LED → Cramée
```
- La LED prends au maximum 2V
- Les 9V "poussent" trop de courant
- Par conséquent, la LED grille

 #### Avec résistance
 ```
 Batterie 9V → Résistance [470 Ohm] → LED
 ```
 - Tension "disponible de 9V"
 - La LED consomme 2V
 - Il reste donc 7V à "absorber"
 - La résistance "freine ce courant" et "absorbe les 7V"
 - La LED reçoit uniquement le courant désiré
 
**Calcul** :
```
R = V / I = 7V / 0.015A = 467 Ohm ≈ 470 Ohm
```

### Exemple d'un diviseur de tension
### Circuit de base
```
        +9V
         |
        [R1] 1kΩ
         |
         ├─── Vout = ?
         |
        [R2] 1kΩ  
         |
        GND (0V)
```

### La formule
```
           R2
Vout = ───────── × Vin
        R1 + R2
```

#### Exemple de la formule
```
R1 = 1kΩ
R2 = 1kΩ
Vin = 9V

         1kOhm
Vout = ─────── × 9V = 0.5 × 9V = 4.5V
        1kOhm + 1kOhm
```

**Résultat : tension divisée par 2**
