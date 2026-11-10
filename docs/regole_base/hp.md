# Health Points e Death's Door

## Health Points

Gli Health Points (HP) sono la statistica che rappresenta la capacità di una creatura di sopportare i danni.

??? example "Esempio"
    Un Commoner ha 4 HP, un Mastiff 3 HP, un Cat 2 HP e un Rat 1 HP.

### Health Points at 1st Level

Un PC ha un numero di Health Points pari a Class HP + Might. Può ottenere HP aggiuntivi dall'Ancestry, come il Trait Tough del Dwarf (+1 HP) o il Trait Frail dell'Elf (-2 HP).

**Health Point Formula:** Class HP + Might + Ancestry HP (se presenti)

??? example "Esempio"
    Un Champion di livello 1 (8 HP di Class) con Might 3 ha 11 HP (8 + 3), più o meno gli eventuali modificatori degli Ancestry Trait.

### Temporary Health Points

I Temporary Health Points (Temp HP) sono Health Points aggiuntivi che durano per un tempo limitato. Quando subisci danni, si riducono prima i Temp HP e gli eventuali danni rimanenti riducono i tuoi HP.

- **Stacking:** i Temp HP non si cumulano. Se ottieni Temp HP da effetti diversi, scegli da quale effetto ottenerli e ignori i Temp HP concessi dagli altri.
- **Duration:** i Temp HP durano finché non completi un Long Rest o finché non vengono ridotti a 0 dai danni. Un effetto che concede Temp HP può indicare una durata inferiore, come 1 minuto, fino al completamento di un Quick Rest o di uno Short Rest, o un'altra durata. Allo scadere della durata, tutti i Temp HP ottenuti svaniscono immediatamente.

### Health Thresholds

Alcune meccaniche di gioco influiscono sulle creature quando i loro HP attuali rientrano in determinate soglie. Queste soglie si determinano prima di qualsiasi modifica temporanea al massimo degli HP, come quella della Condition Doomed.

| Soglia | Condizione |
|---|---|
| Bloodied | HP pari o inferiori a 1/2 degli HP massimi |
| Well-Bloodied | HP pari o inferiori a 1/4 degli HP massimi |
| Death's Door | HP pari o inferiori a 0, fino a un minimo pari alla Death Threshold |

La Death Threshold di una creatura è pari a 0 HP meno il suo Prime Modifier e la sua Combat Mastery. Una creatura muore se i suoi HP vengono ridotti alla Death Threshold o al di sotto.

!!! note "Nota"
    Una creatura su Death's Door è considerata anche Bloodied e Well-Bloodied, perché i suoi HP sono inferiori a 1/2 e a 1/4 del massimo.

??? example "Esempio"
    Una creatura con 8 HP massimi è Bloodied a 4 HP o meno, Well-Bloodied a 2 HP o meno e su Death's Door a 0 HP o meno. Con Prime Modifier 3 e Combat Mastery 1 la sua Death Threshold è -4 HP: muore se i suoi HP scendono a -4 o meno.

## Death's Door

Quando un PC viene ridotto a 0 HP è su Death's Door. Non è privo di sensi, ma si trova in uno stato di grave debilitazione.

### Entering Death's Door

Quando vieni ridotto a 0 HP o meno, ottieni Exhaustion 1. Finché non vieni riportato a 1 HP o più, subisci i seguenti effetti:

- **Action Point Limit:** i tuoi AP attuali e massimi sono ridotti di 3.
- **Death Save:** all'inizio di ciascuno dei tuoi turni devi effettuare un Death Save DC 10.

!!! note "Nota"
    In pratica, su Death's Door puoi spendere solo 1 AP per Round di Combat, nel tuo turno o come Reaction.

### Death Saves

Quando una creatura effettua un Death Save, tira un d20 per stabilire se il Save riesce o fallisce. Al Death Save non si aggiunge la Combat Mastery.

**Success**

- **Success:** nessun cambiamento.
- **Success (5):** recuperi 1 HP.
- **Critical Success:** vieni riportato a 1 HP.

**Failure**

- **Failure:** ottieni Bleeding 1.
- **Failure (5):** ottieni invece Bleeding 2.
- **Critical Failure:** cadi inoltre **Unconscious** finché non vieni riportato a 1 HP o più.

!!! note "Nota"
    Se sei su Death's Door fuori dal Combat, ripeti invece il Death Save ogni 12 secondi (5 volte al minuto).

### Regole collegate

#### Bleeding X (Condition)

Subisci X danni True all'inizio di ciascuno dei tuoi turni.

**Ending Bleeding:** tutti gli stack della Condition terminano quando sei soggetto a un effetto che ripristina i tuoi HP. In alternativa, una creatura può tentare di rimuovere 1 o più stack della Condition compiendo la Medicine Action.

#### Medicine (Action)

Puoi spendere 1 AP per toccare una creatura e curarne le ferite. Effettua un Medicine Check DC 10.

- **Success:** termini 1 stack di Bleeding sul bersaglio.
- **Success (each 5):** termini uno stack di Bleeding aggiuntivo.

#### Medicine Kit (Equipment)

Puoi spendere 1 Charge e compiere l'Object Action per curare le ferite di una creatura Bloodied (vedi Medicine Kit in [Equipment](../regole_generali/equipaggiamento.md)). Effettua un Medicine Check DC 10.

- **Success:** la creatura bersaglio recupera 1 HP.
- **Success (each 5):** la creatura recupera +1 HP.

Vedi anche [Conditions](../regole_generali/condizioni.md).

### NPC's on Death's Door

Mostri e NPC di norma muoiono quando vengono ridotti a 0 HP. Il Game Master può però applicare Death's Door a nemici speciali: questi scendono a 1 AP e si trovano su Death's Door nello stesso stato di debilitazione.
