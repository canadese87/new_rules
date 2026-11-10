# Damage

## Degrees of Damage

Ogni Attack ha una quantità di danni base inflitta con un Hit. Questo valore è indicato insieme alla Weapon (vedi [Equipment](../regole_generali/equipaggiamento.md)) o nella descrizione dello Spell (vedi [Spellcaster Chapter](../magia/regole.md)). Se il Check supera la Defense del bersaglio di 5 o più, il bersaglio subisce danni extra e può subire effetti aggiuntivi (vedi Check & Save Outcomes in [Checks e Saves](checks_saves.md)).

### Hit e Miss

Quando effettui un Check contro la Defense di un bersaglio, il Check è un Miss se il risultato è inferiore alla Defense del bersaglio ed è un Hit se il risultato è pari o superiore alla Defense del bersaglio.

### Hit Success (each 5)

Un Attack infligge +1 danno aggiuntivo per ogni 5 punti di cui il risultato del Check supera la Defense del bersaglio. Se il risultato supera la Defense del bersaglio di 5 o più, è un Heavy Hit. Se la supera di 10 o più, è un Brutal Hit. I Brutal Hit sono considerati Heavy Hit ai fini degli effetti che si attivano con un Heavy Hit.

!!! note "Nota"
    Oltre il Brutal Hit si continua a contare a scatti di 5: con un risultato di 15 o più sopra la Defense si ottiene un ulteriore +1 danno per ogni 5 punti.

### Degrees of Damage Table

| Check vs Defense | Result | Damage |
|---|---|---|
| Inferiore | Miss | Nessun danno |
| Pari o superiore | Hit | Base Damage |
| +5 o più | Heavy Hit | Base Damage + 1 |
| +10 o più | Brutal Hit | Base Damage + 2 |

### Critical Hits

Quando ottieni 20 sul d20 per un Attack, è un Critical Hit. Un Critical Hit colpisce automaticamente il bersaglio, ignora la Damage Reduction e infligge +2 danni aggiuntivi.

!!! note "Nota"
    Un Attack può ottenere un Critical Hit anche se il risultato del Check non supera la Defense del bersaglio di 5 o più: in tal caso il bersaglio subisce semplicemente i danni base +2. Normalmente però un Critical Hit supera la Defense di 5 o 10, e il bersaglio subisce +2 danni per il Critical Hit più +1 danno per ogni 5 punti di cui il risultato supera la sua Defense.

### Adding Damage Order

Somma i danni nel seguente ordine:

1. **Base Damage:** parti dai danni base dell'Attack.
2. **Heavy & Critical Hits:** aggiungi i danni bonus da Critical Hit e da Heavy Hit o superiori.
3. **Action Points:** aggiungi i danni bonus derivanti da AP spesi (Maneuver, Class Feature, AP Enhancement, ecc.).
4. **Situational Bonuses:** aggiungi i danni bonus situazionali (Class Feature, Magic Item, ecc.).

Dopo un Hit, il GM indica se l'Attack è un Heavy Hit o superiore. Il GM applica poi le eventuali Resistance o Vulnerability per determinare i danni totali subiti dal bersaglio.

## Damage Types

Esistono 12 damage type, ognuno dei quali rappresenta un diverso modo di ferire una creatura.

| Damage type | Descrizione |
|---|---|
| Bludgeoning | Ciò che colpisce con forza contundente, come un martello o un pugno. |
| Piercing | Ciò che perfora, come una freccia o delle zanne. |
| Slashing | Ciò che taglia, come una lama o un artiglio. |
| Fire | Ciò che brucia, come il fuoco o altre forme di calore intenso. |
| Cold | Ciò che congela, come il ghiaccio o il freddo intenso. |
| Lightning | Ciò che folgora, come il fulmine o altre forme di elettricità. |
| Poison | Ciò che avvelena, come le tossine. |
| Corrosion | Ciò che corrode e consuma, come acidi ed effetti di ruggine. |
| Psychic | Ciò che aggredisce la mente, come gli attacchi psichici. |
| Radiant | Ciò che brucia con la luce, come la luce sacra, i laser e le radiazioni. |
| Umbral | Ciò che ferisce l'anima, come il potere oscuro o ultraterreno. |
| True | Tipo di danno speciale che non può essere ridotto in alcun modo. |

### Damage Type Categories

I damage type (tranne True) sono organizzati nelle seguenti categorie:

- **Physical Damage:** Bludgeoning, Piercing e Slashing.
- **Elemental Damage:** Cold, Corrosion, Fire, Lightning e Poison.
- **Mystical Damage:** Psychic, Radiant e Umbral.

## Damage Vulnerability, Resistance e Immunity

La Resistance riduce i danni subiti da una creatura, la Vulnerability li aumenta. Possono derivare da capacità naturali, Class Feature, Magic Item, ecc.

### Damage Resistance

- **Resistance (X):** i danni subiti del tipo indicato sono ridotti di X ogni volta che la creatura subisce danni di quel tipo.
- **Resistance (Half):** i danni subiti del tipo indicato sono dimezzati (riduzione minima di 1 danno).

??? example "Esempio"
    Con Fire Resistance (2) e 7 danni Fire subisci 5 danni. Con Fire Resistance (Half) e 7 danni Fire subisci 4 danni (metà di 7 è 3,5, arrotondato per eccesso a 4). Con Radiant Resistance (Half) e 1 danno Radiant, la metà è 0,5 arrotondata a 1, ma poiché la Resistance riduce almeno 1 danno, i danni scendono a 0.

### Damage Immunity

I danni subiti del tipo indicato sono ridotti a 0.

### Damage Vulnerability

- **Vulnerability (X):** i danni subiti del tipo indicato aumentano di X ogni volta che la creatura subisce danni di quel tipo.
- **Vulnerability (Double):** i danni subiti del tipo indicato sono raddoppiati.

??? example "Esempio"
    Con Poison Vulnerability (2) e 3 danni Poison subisci 5 danni. Un Werewolf con Vulnerability (Double) alle Silvered Weapons che subisce 5 danni da un Attack ne subisce invece 10.

## Damage Reduction

La Damage Reduction (DR) concede Damage Resistance (Half) contro gli Attack, tranne contro i Critical Hit e gli Heavy Hit (o superiori). Esistono 3 tipi di Damage Reduction:

- **Physical Damage Reduction (PDR):** protegge dai damage type Bludgeoning, Piercing e Slashing.
- **Elemental Damage Reduction (EDR):** protegge dai damage type Cold, Corrosion, Fire, Lightning e Poison.
- **Mystical Damage Reduction (MDR):** protegge dai damage type Radiant, Psychic e Umbral.

!!! note "Nota"
    Oggetti o mostri speciali possono avere tipi specifici di DR per determinati damage type (ad esempio "Fire Damage Reduction").

??? example "Esempio"
    Un Attack con risultato 12 contro PD 10 colpisce e infligge 4 danni Bludgeoning; il bersaglio ha PDR e i danni sono dimezzati a 2. Con un risultato di 15 (Heavy Hit) la PDR viene ignorata e il bersaglio subisce 4 danni più 1 per l'Heavy Hit.

## Stacking Damage Vulnerabilities, Resistances e Immunities

- **Damage Resistance X e Vulnerability X:** se una creatura ottiene Damage Resistance X o Damage Vulnerability X da più fonti, i valori si sommano.
- **Damage Resistance (Half) e Vulnerability (Double):** più fonti di Damage Resistance (Half) o di Damage Vulnerability (Double) non si cumulano.

??? example "Esempio"
    Con Lightning Resistance (Half) da una Class Feature e la EDR dell'Armor (che include Lightning Resistance), subisci comunque metà dei danni Lightning, non un quarto.

## Bonus Damage

Se un Attack ottiene un bonus ai danni (ad esempio da una Feature o da un Enhancement), i danni bonus sono dello stesso tipo dell'Attack, salvo indicazione contraria.

### Multiple Damage Types

Quando un Attack infligge più tipi di danno e ottiene un bonus ai danni, scegli quale damage type riceve i danni bonus.

??? example "Esempio"
    Un Barbarian in Rage colpisce con un martello magico che infligge 2 danni Bludgeoning e 2 danni Lightning: può applicare il +1 danno della Rage ai danni Bludgeoning o ai danni Lightning.

### Against Multiple Targets

Se un Attack con più bersagli ottiene un bonus ai danni, i danni bonus si applicano a un solo bersaglio a tua scelta. L'Attack beneficia comunque di Critical Hit, Heavy Hit e superiori contro ciascun bersaglio.

## Damage Modifications

I danni totali si determinano dopo aver applicato tutte le modifiche ai danni. Quando una creatura subisce danni, i danni totali si determinano con i passaggi seguenti:

1. **Adding & Subtracting:**
    - **Damage Resistance X:** la Resistance X riduce i danni del valore di X (1, 2, 3, ecc.).
    - **Damage Vulnerability X:** la Vulnerability X aumenta i danni del valore di X (1, 2, 3, ecc.).
2. **Doubling & Halving:**
    - **Damage Resistance (Half):** i danni sono dimezzati (arrotondati per eccesso, riduzione minima di 1 danno).
    - **Damage Vulnerability (Double):** i danni sono raddoppiati (minimo 1 danno subito).

In sintesi: prima si applicano addizioni e sottrazioni, poi moltiplicazioni e divisioni.

Se una creatura ha Resistance e Vulnerability dello stesso tipo e della stessa entità, si annullano a vicenda (ad esempio Fire Resistance (1) e Fire Vulnerability (1), oppure Cold Resistance (Double) e Cold Vulnerability (Double)).

??? example "Esempio"
    Una creatura con Cold Resistance (1) e Cold Vulnerability (Double) subisce un Attack da 4 danni Cold: i danni scendono a 3 e poi raddoppiano a 6. Una creatura con Fire Vulnerability (1) e Fire Resistance (Half) dalla EDR dell'Armor subisce 5 danni Fire: i danni salgono a 6 e poi si dimezzano a 3.

## Managing Damage Multiples

### Multiple Damage Types

Quando subisci più tipi di danno verso cui hai Resistance (o Vulnerability), applichi le Resistance (o Vulnerability) a ciascun damage type separatamente.

??? example "Esempio"
    Con Physical Resistance (Half) dalla PDR dell'Armor subisci 3 danni Piercing e 3 danni Slashing: ciascuno viene dimezzato a 1,5 e arrotondato a 2, per un totale di 4 danni.

### Bonus Damage Against Multiple Targets

Se aggiungi danni bonus a un Attack con più bersagli, i danni bonus si applicano a un solo bersaglio a tua scelta. L'Attack beneficia comunque di Critical Hit, Heavy Hit e superiori contro ciascun bersaglio.

### Shared Damage

Quando 2 o più creature condividono dei danni, dividi i danni per il numero di creature (arrotondando per eccesso) e distribuiscili in parti uguali. Se le creature condividono danni di più tipi, calcola i danni condivisi separatamente per ciascun tipo.

!!! note "Nota"
    Poiché si arrotonda sempre per eccesso, condividere i danni può far subire al gruppo nel complesso più danni di quanti ne avrebbe subiti senza condividerli. È voluto.

??? example "Esempio"
    Un Champion si frappone tra un Attack e un alleato e condividono 5 danni: ciascuno ne subisce 3. Una creatura scagliata contro un muro subisce 10 danni Bludgeoning; se 2 creature si trovano sulla sua traiettoria, le 3 creature condividono i danni e ciascuna ne subisce 4 (3,33 arrotondato per eccesso). Con 3 danni Bludgeoning e 2 Lightning condivisi tra 2 creature, ciascuna subisce 2 Bludgeoning e 1 Lightning.
