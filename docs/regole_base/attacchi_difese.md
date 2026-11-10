# Attacks e Defenses

## Attacks

Quando una creatura effettua un Attack, sceglie un bersaglio entro la Range dell'Attack (Melee, Ranged o Area) ed effettua un Attack Check. La risoluzione dell'Attack dipende dal suo tipo e dalla sua Range.

### Attack Types

Esistono 2 tipi di Attack: Martial e Spell.

#### Martial Attacks

Una creatura effettua un Martial Attack quando effettua un Attack Check con una Weapon o un Unarmed Strike contro la Defense di un bersaglio.

- **Unarmed Strike:** Martial Attack effettuato con una qualsiasi parte del corpo della creatura, come pugno, gomitata, calcio, ginocchiata o testata.
- **Weapon Attack:** Martial Attack effettuato con una Weapon, come un'ascia, una spada o un arco. Puoi estrarre una Weapon come parte di un Attack effettuato con essa.

#### Spell Attacks

Una creatura effettua uno Spell Attack quando effettua un Attack Check con uno Spell o un'abilità simile (come il Trait Breath Weapon dell'Ancestry Dragonborn) contro la Defense di un bersaglio (vedi [Spellcaster Chapter](../magia/regole.md)).

### Attack Ranges

Gli Attack hanno 3 tipi di Range: Melee, Ranged o Area.

#### Melee Attack

Un Melee Attack è un Attack con Range Melee. La Melee Range di una creatura è 1 Space, salvo indicazione contraria.

#### Ranged Attack

Un Ranged Attack è un Attack con una Range espressa in Spaces (ad esempio 10 Spaces). La Range è determinata dal tipo di Weapon usata o dall'abilità con cui si effettua il Ranged Attack.

**Close Quarters:** hai DisADV ai Ranged Attack se ti trovi entro la Melee Range di almeno 1 nemico, a meno che quel nemico non sia **Incapacitated** (vedi [Conditions](../regole_generali/condizioni.md)).

**Weapon Ranges:** una Weapon che può essere usata per un Ranged Attack ha una Range indicata tra parentesi dopo la proprietà Ammo, Toss o Thrown (vedi [Equipment](../regole_generali/equipaggiamento.md)).

- **Normal Range:** il primo numero tra parentesi è la Range normale della Weapon. Puoi attaccare qualsiasi bersaglio entro questa Range.
- **Long Range:** il secondo numero tra parentesi è la Range lunga della Weapon. Puoi attaccare con DisADV i bersagli entro questa Range. Non puoi attaccare bersagli oltre la Range lunga della Weapon.

??? example "Esempio"
    Uno Short Bow con Range (15/45) attacca normalmente i bersagli tra 1 e 15 Spaces, con DisADV quelli tra 16 e 45 Spaces, e non può attaccare bersagli a 46 Spaces o più.

#### Area Attack

Una creatura effettua un Area Attack quando attacca i bersagli che si trovano entro un'area specificata (come Cone, Line o Sphere) coperta dall'Attack. Tipo e dimensioni dell'area sono determinati dall'Attack (vedi [Areas of Effect](../regole_generali/aree_effetto.md)).

!!! note "Nota"
    La penalità di Close Quarters non si applica agli Area Attack.

### Determining if an Attack Hits

Quando una creatura effettua un Attack, il risultato dell'Attack Check viene confrontato con la Defense del bersaglio. L'Attack colpisce (Hit) se il risultato dell'Attack Check è pari o superiore alla Defense del bersaglio (vedi [Damage](danni.md)).

??? example "Esempio"
    Un Champion di livello 4 con Prime Modifier 3 e Combat Mastery 2 attacca con una Longsword e ottiene 10 sul d20: il risultato è 15. Se la PD del bersaglio è 15 o meno l'Attack colpisce, altrimenti manca (Miss).

## Defenses

Quando una creatura effettua un Attack per infliggere danni a un bersaglio, il suo Check viene confrontato con una delle Defense del bersaglio (Precision Defense o Area Defense) per stabilire se l'Attack colpisce.

### Precision Defense

La Precision Defense (PD) misura la capacità di una creatura di evitare gli attacchi che si possono schivare, come un colpo preciso o un proiettile a distanza.

#### PD Calculation

La tua PD è pari a 8 + Combat Mastery + Agility + Intelligence. Se indossi un'Armor o impugni uno Shield (vedi [Equipment](../regole_generali/equipaggiamento.md)), aggiungi anche i rispettivi bonus alla PD.

- **Agility:** rappresenta la rapidità di reazione e la velocità fisica con cui eviti gli attacchi.
- **Intelligence:** rappresenta la capacità di prevedere il pericolo e posizionarti con giudizio, guadagnando il tempo per reagire.

**PD Formula:** 8 + Combat Mastery + Agility + Intelligence + bonus

### Area Defense

L'Area Defense (AD) misura la capacità di una creatura di sopportare gli attacchi che non si possono evitare, come esplosioni, onde d'urto o altri effetti ad ampio raggio.

#### AD Calculation

La tua AD è pari a 8 + Combat Mastery + Might + Charisma. Se indossi un'Armor o impugni uno Shield (vedi [Equipment](../regole_generali/equipaggiamento.md)), aggiungi anche i rispettivi bonus all'AD.

- **Might:** rappresenta la robustezza e la resistenza fisica con cui assorbi i danni al corpo.
- **Charisma:** rappresenta la determinazione interiore e la presenza con cui resisti agli assalti mentali e soprannaturali.

**AD Formula:** 8 + Combat Mastery + Might + Charisma + bonus
