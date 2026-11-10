# Environment

## Spaces & Distance

La distanza si misura in Spaces, come le caselle di una mappa a griglia. Uno Space può essere espresso in piedi o in metri: 1 Space equivale a 5 piedi o 1,5 metri.

**Grid Map Distance:** quando ti muovi o misuri una distanza su una mappa a griglia, il movimento in qualsiasi direzione conta 1 Space (incluso il movimento in diagonale). In alternativa puoi misurare in linea retta tra due punti, se disponi degli strumenti di misura o delle sagome necessari.

??? example "Esempio"
    La gittata normale di un Longbow è 30 Spaces: sulla mappa a griglia si contano 30 Spaces in qualsiasi direzione. La stessa gittata può essere espressa come 150 piedi o 45 metri.

Per distanze lunghe, ad esempio da una città all'altra, puoi misurare la distanza in piedi o in metri.

## Difficult Terrain

Alcuni terreni sono più difficili da attraversare a causa di ostacoli (come piante, rocce, detriti, altre creature, ecc.).

Mentre ti muovi in Difficult Terrain sei **Slowed** (ogni Space percorso costa 2 Spaces di movimento).

## Jumping

Il salto è una forma di movimento. Una creatura deve disporre di movimento per poter saltare. Se una creatura non ha movimento sufficiente per saltare la distanza massima possibile, la distanza del salto si riduce al movimento massimo disponibile.

Esistono due tipi di salto: Long Jump e High Jump. Il Long Jump rappresenta la distanza che una creatura può coprire saltando in orizzontale; l'High Jump rappresenta l'altezza dal suolo che i piedi della creatura possono raggiungere saltando in verticale.

### Jump Distance

La Jump Distance di una creatura è pari al suo Agility (minimo 1).

**Jump Distance** = Agility

**Running Jump:** dopo essersi mossa di almeno 2 Spaces, una creatura può effettuare un Long Jump (salto orizzontale) o un High Jump (salto verticale). Con un Long Jump può saltare la propria Jump Distance in Spaces. Con un High Jump può saltare la propria Jump Distance in piedi (1 piede = 30 cm).

**Standing Jump:** una creatura può saltare senza essersi prima mossa di almeno 2 Spaces, ma la sua Jump Distance massima è dimezzata per quel salto.

### Long Jump

**Long Jump** = Jump Distance (in Spaces)

??? example "Esempio"
    Una creatura ha Jump Distance 3. Se compie l'Action Move ottenendo 4 Spaces di movimento, può muoversi di 2 Spaces e poi effettuare un Long Jump di massimo 2 Spaces (il movimento rimasto). Per avere movimento sufficiente a saltare tutti e 3 gli Spaces possibili dovrebbe compiere di nuovo l'Action Move (ottenendo altri 4 Spaces di movimento).

!!! note "Nota"
    Una Jump Distance di 5 non significa che salti automaticamente 5 Spaces: la Jump Distance è il numero di Spaces che puoi coprire in un singolo salto. Devi avere movimento sufficiente (dall'Action Move, ecc.) per coprire quella distanza.

### High Jump

**High Jump** = Jump Distance (in piedi)

??? example "Esempio"
    Una creatura ha Jump Distance 3. Se compie l'Action Move ottenendo 4 Spaces di movimento, può muoversi di 2 Spaces ed effettuare un High Jump che raggiunge fino a 3 piedi (90 cm) dal suolo.

### Vertical Reach

L'altezza massima che una creatura può raggiungere con le braccia è pari a 1,5 volte la sua altezza. Una creatura alta 6 piedi (1,8 m) può raggiungere con le braccia qualcosa a 9 piedi (2,7 m) dal suolo. La portata verticale di una creatura si somma al suo High Jump per determinare quanto in alto può arrivare durante il salto.

## Falling

**Falling Damage:** quando una creatura cade da un'altezza superiore al suo Agility in Spaces (minimo 1 Space) e urta il suolo, un oggetto o una creatura, subisce danni Bludgeoning pari al numero di Spaces di caduta (fino a un massimo di 100 danni) e cade **Prone**.

**Reduced Impact:** una creatura che sta per subire danni da caduta può effettuare un Agility Save. La DC è pari a 10 + 1 per ogni Space di caduta. **Success:** riduce i danni di un ammontare pari al suo Agility (minimo 0) e non cade Prone.

??? example "Esempio"
    Un PC con Agility 1 che cade da un'altezza di 1 Space non subisce danni e non cade Prone. Se cade da 2 Spaces, può effettuare un Agility Save DC 12 (10 + caduta di 2 Spaces): con un Success subisce 1 danno (2 Spaces di caduta - 1 Agility = 1 danno) e non cade Prone; con un Failure subisce 2 danni e cade Prone.

**Falling Collision:** tutti i bersagli con cui la creatura si scontra si dividono una quantità di danni Bludgeoning pari alla metà del numero di Spaces di caduta e cadono **Prone**. Se un bersaglio è una creatura, può effettuare un Physical Save per non cadere Prone. La DC è pari a 10 + i danni subiti.

??? example "Esempio"
    Una creatura Huge cade di 10 Spaces e si scontra con due creature Medium. La creatura Huge subisce 10 danni Bludgeoning dalla caduta e cade Prone (può tentare un Agility Save DC 10 per ridurre i danni del suo Agility ed evitare di cadere Prone). Le due creature Medium si dividono 5 danni: ciascuna subisce 3 danni Bludgeoning (5 danni / 2 creature = 2,5, arrotondato per eccesso a 3) ed entrambe cadono Prone (ciascuna può tentare un Physical Save DC 13 per evitarlo).

### Controlled Falling

Se cadi intenzionalmente e hai il controllo del tuo corpo e del tuo movimento, si tratta di un Controlled Fall. Cadere in questo modo non comporta penalità aggiuntive.

### Uncontrolled Falling

Se vieni scaraventato giù da un bordo, respinto da un'esplosione, non sei in grado di reagire o sei trattenuto in qualche modo, si tratta di un Uncontrolled Fall (a discrezione del GM).

**Uncontrolled Impact:** se cadi senza controllo, la DC di Reduced Impact aumenta di 5. Inoltre subisci danni cadendo da qualsiasi altezza (indipendentemente dal tuo Agility).

??? example "Esempio"
    Un PC con Agility 3 che effettua un Controlled Fall da un'altezza di 3 Spaces può effettuare un Acrobatics Check DC 13 e, con un Success, subisce 0 danni (3 Spaces di caduta - 3 Agility = 0 danni). Se lo stesso PC effettua un Uncontrolled Fall da 3 Spaces, effettua invece un Acrobatics Check DC 18 (DC 13 + 5).

### Continuous Falling

Se alla fine del tuo turno stai ancora cadendo, cadi immediatamente di altri 100 Spaces.

### Falling While Flying

Se diventi **Prone** mentre voli, cadi immediatamente fino a 100 Spaces a meno che tu non sia sostenuto in aria con la magia. Se all'inizio del tuo turno stai ancora cadendo, puoi spendere 2 Spaces di movimento per terminare la Condition Prone su di te (come se ti rialzassi a mezz'aria).

## Climbing

Le creature prive di Climb Speed sono **Slowed 1** mentre si arrampicano. Una creatura può arrampicarsi su una scala a pioli, una corda con nodi o una parete con appigli senza effettuare un Climbing Check (Athletics). Arrampicarsi su una corda o una parete scivolosa può richiedere un Climbing Check. Le creature con Climb Speed hanno ADV sui Climbing Checks. La tabella seguente fornisce indicazioni per stabilire la DC delle scalate impegnative.

**Failure:** la creatura cade immediatamente.

| Difficoltà | DC 10 |
|---|---|
| Soffice o cedevole | +5 |
| Bagnata o ghiacciata | +5 |
| Liscia | +10 |
| A testa in giù | +10 |

!!! note "Nota"
    Arrampicarsi per lunghe distanze può essere impegnativo: il GM può chiedere a un PC di effettuare un Climbing Check DC 10 per ogni 4 Spaces di scalata oltre i primi 4, anche se la corda o la superficie è normalmente facile da scalare per brevi distanze. Le creature con Climb Speed non devono effettuare questi Checks.

## Swimming

Le creature prive di Swim Speed sono **Slowed 1** mentre nuotano. Una creatura può nuotare per 20 Spaces (100 piedi / 30 m) in acque calme senza effettuare uno Swimming Check (Athletics). Nuotare in uno specchio d'acqua agitato senza Swim Speed richiede uno Swimming Check. La tabella seguente fornisce indicazioni per stabilire la DC delle nuotate impegnative.

**Failure:** la creatura non riesce a muoversi e affonda di 2 Spaces nello specchio d'acqua.

| Difficoltà | DC 10 |
|---|---|
| Mossa | +5 |
| Gelida | +5 |
| Paludosa | +5 |
| In tempesta | +10 |

!!! note "Nota"
    Nuotare per lunghe distanze può essere impegnativo: il GM può chiedere a un PC di effettuare uno Swimming Check DC 10 per ogni 20 Spaces di nuotata oltre i primi 20, anche se l'acqua è calma. Le creature con Swim Speed non devono effettuare questi Checks.

## Holding Your Breath

Le creature che hanno bisogno di aria per respirare possono trattenere il respiro per evitare di inalare aria tossica, annegare o soffocare nel vuoto. Una creatura che non riesce più a trattenere il respiro inizia a soffocare (Suffocating). Il tempo per cui una creatura può trattenere il respiro dipende dal tipo di stress a cui è esposta e dall'energia che sta impiegando.

Esistono due misure: Calm Hold e Stressed Hold. Il Calm Hold rappresenta la durata per cui una creatura può trattenere il respiro in un ambiente poco stressante svolgendo un'attività minima o nulla; lo Stressed Hold rappresenta il tempo per cui può trattenerlo in un ambiente molto stressante svolgendo molta attività.

### Breath Duration

La Breath Duration di una creatura è pari al suo Might (minimo 1).

**Breath Duration** = Might

### Calm Hold

**Calm Hold** = Breath Duration (in minuti)

Una creatura che svolge No Activity o Light Activity in un ambiente calmo può trattenere il respiro per un numero di minuti pari alla sua Breath Duration. Se la creatura inizia a svolgere una Strenuous Activity o una Dangerous Activity, i minuti d'aria rimanenti si convertono in un numero uguale di round.

??? example "Esempio"
    Una creatura con Breath Duration 3 che trattiene il respiro stando ferma in un ambiente calmo può trattenerlo fino a 3 minuti.

### Stressed Hold

**Stressed Hold** = Breath Duration (in round)

Una creatura che svolge una Strenuous Activity o una Dangerous Activity può trattenere il respiro per un numero di round pari alla sua Breath Duration.

??? example "Esempio"
    Una creatura con Breath Duration 3 che trattiene il respiro mentre combatte sott'acqua contro un mostro marino può trattenerlo fino a 3 round, cioè 36 secondi (1 round = 12 secondi).

### Activity Levels

- **No Activity:** stare sdraiati, meditare o riflettere restando inattivi.
- **Light Activity:** attività non faticose che richiedono poco sforzo, come leggere, bendare ferite e stare di guardia.
- **Strenuous Activity:** qualsiasi attività che richiede sforzo fisico, come viaggiare, foraggiare, fare esercizio, allenarsi o lanciare Spells.
- **Dangerous Activity:** qualsiasi attività che causa lesioni o stress estremi, come combattere contro una creatura ostile.

!!! note "Nota"
    1 Round di combattimento dura 12 secondi: 1 minuto equivale a 5 Rounds di Combat.

### Losing Your Breath

**Speaking:** le creature che tentano di parlare mentre trattengono il respiro, ad esempio per soddisfare la Verbal Component di uno Spell, riducono la propria Breath Duration di 1.

**Knocking the Wind Out:** ogni volta che subisci danni, devi effettuare un Might Save. La DC è pari a 10 o al doppio dei danni subiti (il valore più alto). **Failure:** perdi 1 round d'aria.

!!! note "Nota"
    Alcuni effetti e capacità possono far iniziare a soffocare immediatamente una creatura, di solito togliendole il fiato o stringendola.

### Suffocating

All'inizio di ciascuno dei tuoi turni, mentre stai soffocando (Suffocating), subisci i seguenti effetti:

- **Loss of Consciousness:** devi effettuare un Might Save DC 10. **Failure:** cadi **Unconscious**. **Success:** rimani cosciente, ma la DC aumenta di 5.
- **HP Reduction:** subisci danni True pari a 1/4 dei tuoi HP massimi.

Questi effetti non possono essere annullati in alcun modo finché non torni in grado di respirare.
