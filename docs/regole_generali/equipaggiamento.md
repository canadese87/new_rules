# Equipment

## Weapons

Ogni Weapon ha un Weapon Type (Melee o Ranged), un Weapon Style (Axe, Sword, Hammer, ecc.) e delle Weapon Properties (Reach, Thrown, Two-Handed, ecc.).

### Weapon Types

Esistono 2 tipi di Weapon: Melee Weapons e Ranged Weapons.

#### Melee Weapons

Le Melee Weapons usano la tua Melee Range (vedi [Attacks](../regole_base/attacchi_difese.md)).

#### Ranged Weapons

Le Ranged Weapons hanno una Range di 15/45 (vedi [Attacks](../regole_base/attacchi_difese.md)).

!!! note "Nota"
    Una Weapon con la Property Long-Ranged ha una Range di 30/90.

#### Impugnare una Weapon

Una Weapon richiede 1 mano quando attacchi con essa, a meno che non abbia la Property Two-Handed (richiede 2 mani per attaccare).

**Throwing Weapons:** quando lanci una Weapon priva delle Property Toss o Thrown, la Weapon è considerata un'Improvised Weapon ai fini dell'Attack (vedi Throwing Melee Weapons in [Creatures & Combat](../combattimento/creature_combattimento.md)).

### Weapon Styles

Ogni Weapon Style ha un damage type predefinito (tra parentesi) e un Weapon Enhancement. Quando un PC con Weapon Training effettua un Attack con una Weapon, può spendere 1 AP o 1 SP per usarne il Weapon Enhancement.

#### Lacking Weapon Training

Mentre impugni una Weapon con cui non hai Training, non puoi usarne il Weapon Enhancement.

#### Melee Weapon Styles

- **Axe** (Slashing). **Bleed:** il bersaglio effettua un Repeated Physical Save. **Failure:** il bersaglio inizia a subire **Bleeding**.
- **Fist** (Bludgeoning, Piercing o Slashing). Le Fist Weapons sono considerate una mano libera ai fini del Grapple. **Grapple:** il bersaglio effettua un Physical Save. **Failure:** il bersaglio diventa **Grappled** da te.
- **Hammer** (Bludgeoning). **Knockback:** il bersaglio effettua un Might Save. **Failure:** il bersaglio viene spinto di 1 Space lontano da te. Ogni volta che usi questo Enhancement, il bersaglio viene spinto di 1 Space aggiuntivo.
- **Pick** (Piercing). **Hinder:** il bersaglio effettua un Agility Save. **Failure:** il bersaglio diventa **Hindered** fino alla fine del suo turno successivo.
- **Spear** (Piercing). **Slow:** il bersaglio effettua un Agility Save. **Failure:** il bersaglio diventa **Slowed** fino alla fine del suo turno successivo.
- **Staff** (Bludgeoning). **Trip:** il bersaglio effettua un Physical Save. **Failure:** il bersaglio cade **Prone**.
- **Sword** (Slashing). **Accuracy:** aggiungi un d4 al tuo Attack Check (concedi al tuo Attack un Help Die d4).
- **Whip** (Slashing). **Pull:** il bersaglio effettua un Might Save. **Failure:** il bersaglio viene spostato orizzontalmente di 1 Space verso di te oppure alla tua sinistra o alla tua destra. Ogni volta che usi questo Enhancement, il bersaglio viene spostato di 1 Space aggiuntivo.

#### Ranged Weapon Styles

- **Bow** (Piercing). **Slow:** il bersaglio effettua un Agility Save. **Failure:** il bersaglio è **Slowed** fino alla fine del suo turno successivo.
- **Crossbow** (Piercing). **Accuracy:** aggiungi un d4 al tuo Attack Check (concedi al tuo Attack un Help Die d4).
- **Sling** (Bludgeoning). **Hinder:** il bersaglio effettua un Agility Save. **Failure:** il bersaglio diventa **Hindered** fino alla fine del suo turno successivo.

#### Changing Damage Type

Ogni Weapon Style ha un damage type predefinito (indicato sopra), ma puoi cambiarlo con un altro tra Bludgeoning, Piercing o Slashing.

### Weapon Properties

Le Weapon hanno Property che conferiscono vantaggi o svantaggi.

- **Ammo:** la Weapon richiede munizioni per effettuare Attack. Puoi caricare la Weapon come parte di un Attack effettuato con essa.
- **Concealable:** estrarre la Weapon non provoca Opportunity Attack. Se estrai la Weapon come parte di un Attack, hai ADV sull'Attack. Puoi ottenere questo beneficio una sola volta contro ciascuna creatura per Combat.
- **Cumbersome:** estrarre, riporre o raccogliere la Weapon costa 1 AP.
- **Deft:** i Ranged Attack con questa Weapon non hanno DisADV dovuto al fatto che sei Prone.
- **Guard:** ottieni +1 PD mentre impugni la Weapon.
- **Heavy:** i danni della Weapon aumentano di 1.
- **Impact:** la Weapon infligge +1 danno sugli Heavy Hit.
- **Long-Ranged:** la Range della Weapon diventa 30/90.
- **Multi-Faceted:** la Weapon ottiene un secondo Weapon Style. Quando effettui un Attack con la Weapon, puoi usare entrambi i Weapon Enhancement e scegliere quale dei damage type dei due Weapon Style infligge.
- **Reach:** la Weapon aggiunge 1 Space alla tua Melee Range quando attacchi con essa.
- **Reload:** i danni della Weapon aumentano di 1, ma devi spendere 1 AP o 1 SP e usare una mano libera per ricaricare la Weapon. Se la Weapon smette di essere impugnata, deve essere ricaricata.
- **Returning:** (Requisito: Property Toss o Thrown) quando manchi (Miss) un Ranged Attack con la Weapon, questa ritorna nella tua mano.
- **Silent:** quando effettui un Ranged Attack con la Weapon mentre sei Hidden, rimani Unheard per le creature da cui sei Hidden.
- **Toss:** puoi lanciare la Weapon per effettuare un Ranged Martial Attack (5/10). Se la lanci oltre questa Range (vedi Throwing in [Creatures & Combat](../combattimento/creature_combattimento.md)), è considerata un'Improvised Weapon.
- **Thrown:** puoi lanciare la Weapon per effettuare un Ranged Martial Attack (10/20). Se la lanci oltre questa Range (vedi Throwing in [Creatures & Combat](../combattimento/creature_combattimento.md)), è considerata un'Improvised Weapon.
- **Two-Handed:** la Weapon richiede 2 mani quando attacchi con essa.
- **Unwieldy:** hai DisADV sugli Attack effettuati con la Weapon contro bersagli entro 1 Space da te.
- **Versatile:** la Weapon può essere impugnata con 1 o 2 mani. Quando la impugni con 2 mani, ottieni un bonus di +2 a colpire con essa.

??? example "Esempio (Multi-Faceted)"
    Un'Halberd ha i Weapon Style Axe e Pick. Quando attacchi con essa, puoi scegliere danni Slashing o Piercing. Puoi anche spendere AP o SP per aggiungere uno o entrambi i Weapon Enhancement Bleed e Hinder.

!!! note "Nota"
    - **Returning:** quando la Weapon colpisce (Hit), cade a terra.
    - **Silent:** devi essere sia Unseen sia Unheard per essere Hidden. Se diventi visto mentre effettui l'Attack, non sei più Hidden.
    - **Toss:** si usano le regole del Ranged Martial Attack: Attack normale fino a 5 Spaces e Attack con DisADV fino a 10 Spaces.

### Weapon Examples

Legenda Damage: B = Bludgeoning, P = Piercing, S = Slashing. Range: un valore singolo indica la Melee Range in Spaces; i valori X/Y indicano Range normale/lunga.

#### Melee Weapons: One-Handed

| Weapon | Style | Damage | Properties | Range |
|---|---|---|---|---|
| Sickle, Hand Axe, Throwing Star | Axe | 1 S | Concealable, Toss | 5/10 |
| Brass Knuckles | Fist | 1 B | Concealable, Impact | 1 |
| Club | Hammer | 1 B | Concealable, Toss | 5/10 |
| Light Hammer | Hammer | 1 B | Impact, Toss | 5/10 |
| Boomerang | Hammer | 1 B | Toss, Returning | 5/10 |
| Mining Pick | Pick | 1 P | Impact, Toss | 5/10 |
| Dart | Spear | 1 P | Concealable, Toss | 5/10 |
| Javelin | Spear | 1 P | Thrown | 10/20 |
| Throwing Dagger | Sword | 1 S | Concealable, Toss | 5/10 |
| Short Sword | Sword | 1 S | Guard, Impact | 1 |
| Rapier | Sword/Spear | 1 S/P | Guard, Multi-Faceted | 1 |
| Chain Whip | Whip | 1 S | Reach, Impact | 2 |

#### Melee Weapons: Versatile

| Weapon | Style | Damage | Properties | Range |
|---|---|---|---|---|
| Battleaxe | Axe | 1 S | Versatile, Impact | 1 |
| Flail | Hammer/Whip | 1 B/S | Versatile, Multi-Faceted | 1 |
| Morningstar, Warhammer | Hammer/Pick | 1 B/P | Versatile, Multi-Faceted | 1 |
| Pickaxe | Pick | 1 P | Versatile, Impact | 1 |
| Spear | Spear | 1 P | Versatile, Toss | 5/10 |
| Long Spear | Spear | 1 P | Versatile, Reach | 2 |
| Bo Staff | Staff | 1 B | Versatile, Guard | 1 |
| Longsword | Sword | 1 S | Versatile, Guard | 1 |
| Bastard Sword | Sword | 1 S | Versatile, Impact | 1 |
| Bull Whip | Whip | 1 S | Versatile, Reach, Unwieldy, Impact | 2 |

#### Melee Weapons: Two-Handed

| Weapon | Style | Damage | Properties | Range |
|---|---|---|---|---|
| Scythe | Axe | 2 S | Two-Handed, Heavy, Reach | 2 |
| Greataxe | Axe | 2 S | Two-Handed, Heavy, Impact | 1 |
| Halberd | Axe/Pick | 1 S/P | Two-Handed, Multi-Faceted, Reach, Impact | 2 |
| War Flail | Hammer/Whip | 2 B/S | Two-Handed, Heavy, Multi-Faceted | 1 |
| Meteor Hammer | Hammer/Whip | 2 B/S | Two-Handed, Heavy, Multi-Faceted, Reach, Unwieldy | 2 |
| Greatmaul | Hammer | 2 B | Two-Handed, Heavy, Impact | 1 |
| Pike | Spear | 2 P | Two-Handed, Heavy, Reach, Impact, Unwieldy | 2 |
| Quarterstaff | Staff | 1 B | Two-Handed, Guard, Reach, Impact | 2 |
| Glaive | Sword | 2 S | Two-Handed, Heavy, Reach | 2 |
| Greatsword | Sword | 2 S | Two-Handed, Heavy, Impact | 1 |
| Great Whip | Whip | 2 S | Two-Handed, Heavy, Reach, Impact, Unwieldy | 2 |

#### Ranged Weapons: One-Handed

| Weapon | Style | Damage | Properties | Range |
|---|---|---|---|---|
| Sling | Sling | 1 B | Ammo, Impact | 15/45 |
| Hand Crossbow | Crossbow | 2 P | Ammo, Reload, Deft, Impact | 15/45 |
| Hand Stonebow | Crossbow/Sling | 2 B/P | Ammo, Reload, Deft, Multi-Faceted | 15/45 |

#### Ranged Weapons: Two-Handed

| Weapon | Style | Damage | Properties | Range |
|---|---|---|---|---|
| Shortbow | Bow | 1 P | Two-Handed, Ammo, Impact, Silent | 15/45 |
| Longbow | Bow | 1 P | Two-Handed, Ammo, Impact, Long-Ranged | 30/90 |
| Greatbow | Bow | 2 P | Two-Handed, Ammo, Impact, Heavy, Cumbersome | 15/45 |
| Blowgun (Needle) | Crossbow | 1 P | Two-Handed, Ammo, Deft, Silent | 15/45 |
| Light Crossbow | Crossbow | 3 P | Two-Handed, Ammo, Reload, Deft, Heavy | 15/45 |
| Heavy Crossbow | Crossbow | 3 P | Two-Handed, Ammo, Reload, Deft, Impact, Heavy, Cumbersome | 15/45 |
| Stonebow | Crossbow/Sling | 3 B/P | Two-Handed, Ammo, Reload, Deft, Multi-Faceted, Heavy, Cumbersome | 15/45 |
| Slingshot | Sling | 1 B | Two-Handed, Ammo, Impact, Silent | 15/45 |
| War Sling | Sling | 2 B | Two-Handed, Ammo, Heavy | 15/45 |

## Customized Weapons

Puoi creare Weapon personalizzate seguendo 3 passaggi:

1. Scegli il Weapon Type.
2. Scegli il Weapon Style e i danni.
3. Scegli le Weapon Properties.

### Step 1: Weapon Type

- **Melee Weapons:** usano la tua Melee Range e infliggono 1 danno.
- **Ranged Weapons:** hanno una Range di 15/45 e infliggono 1 danno. Ottengono inoltre automaticamente le Property Ammo e Two-Handed.

Una Weapon richiede 1 mano quando attacchi con essa, a meno che non abbia la Property Two-Handed (richiede 2 mani per attaccare).

### Step 2: Weapon Style e danni

Scegli un Weapon Style tra quelli elencati in Weapon Styles (sopra). Il damage type della Weapon è quello predefinito dello Style, eventualmente cambiato con un altro tra Bludgeoning, Piercing o Slashing (vedi Changing Damage Type).

!!! note "Nota"
    Puoi usare il Weapon Enhancement di una Weapon solo se hai Weapon Training.

### Step 3: Weapon Properties

Quando scegli una Melee Weapon o una Ranged Weapon durante la creazione del personaggio (o ne fabbrichi una in seguito), puoi conferirle Weapon Properties per un valore di 2 punti. Non puoi conferire la stessa Property più di una volta a una Weapon.

**Property Requirements:** se una Weapon Property ha un requisito, la Weapon deve soddisfarlo prima che tu possa aggiungerle quella Property.

#### Melee Weapon Properties

| Property | Costo | Requisiti e limitazioni |
|---|---|---|
| Concealable | 1 | — |
| Guard | 1 | — |
| Heavy | 2 | Requisito: Two-Handed |
| Impact | 1 | — |
| Multi-Faceted | 1 | — |
| Reach | 1 | — |
| Returning | 1 | Requisito: Toss o Thrown |
| Silent | 1 | — |
| Toss | 1 | — |
| Thrown | 2 | — |
| Two-Handed | -1 | Non può essere presa insieme a Versatile |
| Unwieldy | -1 | — |
| Versatile | 1 | Non può essere presa insieme a Two-Handed |

Per le Melee Weapons, **Silent** è formulata così: i Ranged Attack effettuati con la Weapon mentre sei Hidden non rivelano la tua posizione alle creature da cui sei Hidden.

#### Ranged Weapon Properties

Queste Property sono disponibili per le Ranged Weapons. Puoi inoltre spendere 1 punto Property per rimuovere la Property Two-Handed.

| Property | Costo | Requisiti e limitazioni |
|---|---|---|
| Heavy | 2 | Requisito: Two-Handed |
| Deft | 1 | — |
| Impact | 1 | — |
| Long-Ranged | 1 | — |
| Cumbersome | -1 | — |
| Multi-Faceted | 1 | — |
| Reload | -1 | — |
| Silent | 1 | — |

!!! note "Nota"
    - La Property Two-Handed conferita automaticamente alle Ranged Weapons non ti dà una Property aggiuntiva.
    - Se vuoi usare una meccanica di inceppamento (misfire), qualsiasi Weapon carica è a rischio di incepparsi mentre è riposta.

### Reskinning Weapons

Lo Style e le Property di una Weapon che crei sono puramente meccanici. Con l'approvazione del GM puoi ridescriverne l'aspetto a piacere: ad esempio una Weapon con l'aspetto di una Sword ma con il Weapon Style Axe, oppure un Weapon Style Axe su una Ranged Weapon.

## Spell Focuses

Devi tenere uno Spell Focus in una mano per beneficiare delle sue Property. Tenere uno Spell Focus conta come eseguire le Somatic Components, ma è comunque considerato lanciare uno Spell in modo evidente.

### Spell Focus Properties

Gli Spell Focus hanno Property che conferiscono vantaggi o svantaggi. Il numero tra parentesi è il costo usato per i Customized Focuses.

- **Channeling** (1): ottieni un bonus di +1 agli Spell Check.
- **Close Quarters** (1): i tuoi Ranged Spell Attack non hanno DisADV se sei entro la Melee Range di nemici.
- **Long-Ranged** (1): gli Spell che lanci con una Range superiore a 1 vedono la loro Range aumentare di 5 Spaces.
- **Muffled** (1): le Verbal Components degli Spell che lanci possono essere udite solo entro 5 Spaces da te.
- **Powerful** (2): i tuoi Spell Attack infliggono +1 danno a tutti i bersagli.
- **Protective** (1): la tua AD aumenta di 1.
- **Reach** (1): gli Spell che lanci con una Range di 1 vedono la loro Range aumentare di 1 Space.
- **Reactive** (1): quando sei il Challenger, o un Participant che aiuta il Challenger, in uno [Spell Duel](../magia/regole.md), il Challenger ottiene ADV sul Check per fermare lo Spell.
- **Two-Handed** (-1): lo Spell Focus richiede 2 mani per beneficiare delle sue Property.
- **Vicious** (1): ottieni un bonus di +1 a colpire con gli Spell Attack.
- **Warded** (1): hai MDR.

### Lacking Spell Focus Training

Mentre impugni uno Spell Focus con cui non hai Training, non benefici delle sue Property.

### Spell Focus Examples

| Tipo | Spell Focus | Properties |
|---|---|---|
| One-Handed | Orb | Channeling |
| One-Handed | Ceremonial Dagger | Close Quarters |
| One-Handed | Crystal | Vicious |
| One-Handed | Totem | Protective |
| One-Handed | Holy Medallion, Relic | Warded |
| One-Handed | Wand | Long-Ranged |
| One-Handed | Rod | Reach |
| One-Handed | Poppet | Muffled |
| One-Handed | Ritual Bell | Reactive |
| Two-Handed | Mage Staff, Twin Crystals | Powerful, Two-Handed |
| Two-Handed | Grimoire, Tarot Deck | Channeling, Vicious, Two-Handed |
| Two-Handed | Censer | Protective, Warded, Two-Handed |
| Two-Handed | Magical Instrument | Long-Ranged, Reactive, Two-Handed |

### Customized Focuses

Quando scegli uno Spell Focus durante la creazione del personaggio (o ne fabbrichi uno in seguito), puoi conferirgli Focus Properties per un valore di 1 punto (costi indicati in Spell Focus Properties, sopra). Non puoi conferire la stessa Property più di una volta a un Focus.

**Property Requirements:** se una Spell Focus Property ha un requisito, il Focus deve soddisfarlo prima che tu possa aggiungergli quella Property.

### Reskinning Spell Focus

Le Property di uno Spell Focus che crei sono puramente meccaniche. Con l'approvazione del GM puoi ridescriverne l'aspetto a piacere (ad esempio un Focus con l'aspetto di una Wand ma con la Property Warded). Puoi descrivere uno Spell Focus Two-Handed come due Spell Focus distinti, uno per mano, che operano insieme per creare lo stesso effetto.

!!! note "Nota"
    Se descrivi uno Spell Focus Two-Handed come 2 Focus distinti che operano in tandem, non ne ottieni i benefici a meno che entrambe le mani tengano gli Spell Focus.

## Armor

Indossare un'Armor può migliorare le tue Defense e fornire Damage Reduction. Le creature che non indossano Armor sono considerate Unarmored.

### Armor Type

Esistono 2 tipi di Armor: Light Armor e Heavy Armor.

#### Light Armor

Cappotti di cuoio, giubbe imbottite e vesti pesanti sono tipi di Light Armor.

**Non-Metal Armor:** la Light Armor può essere descritta come fatta di molti materiali, ma non contiene abbastanza metallo da essere considerata Metal Armor ai fini delle meccaniche di gioco (Feature, Spell, effetti di Weapon, ecc.), salvo diversa indicazione.

#### Heavy Armor

Armature lamellari, laminate e a piastre sono tipi di Heavy Armor.

**Metal Armor:** tutta la Heavy Armor è considerata Metal Armor ai fini delle meccaniche di gioco (Feature, Spell, effetti di Weapon, ecc.), salvo diversa indicazione.

**Impactful Unarmed Strikes:** i tuoi Unarmed Strike infliggono +1 danno sugli Heavy Hit mentre indossi Heavy Armor.

### Wearing Armor

Indossare o togliere una Light Armor richiede 1 minuto; una Heavy Armor richiede 10 minuti. Ottieni i benefici dell'Armor mentre la indossi.

### Lacking Armor Training

Mentre indossi un'Armor in cui non hai Training, hai DisADV sugli Attack Check e sugli Spell Check.

### Damage Reduction

Alcuni tipi di Armor conferiscono Physical o Elemental Damage Reduction (vedi Damage Reduction in [Damage](../regole_base/danni.md)).

### Armor Examples

| Tipo | PD | AD | PDR | Speed | Agility Checks |
|---|---|---|---|---|---|
| **Light Armor** | | | | | |
| Defensive | +1 | +1 | — | — | — |
| Deflecting | +2 | — | — | — | — |
| Fortified | — | +2 | — | — | — |
| **Heavy Armor** | | | | | |
| Defensive | +1 | +1 | Half | -1 | DisADV |
| Deflecting | +2 | — | Half | -1 | DisADV |
| Fortified | — | +2 | Half | -1 | DisADV |
| Highly Defensive | +2 | +2 | — | -1 | DisADV |

### Customized Armor

Quando scegli la tua Armor durante la creazione del personaggio (o ne fabbrichi una in seguito), scegli se è Light Armor o Heavy Armor e puoi conferirle Armor Properties disponibili per quel tipo per un valore di 2 punti. Non puoi conferire la stessa Property più di una volta a un'Armor, salvo diversa indicazione.

#### Light Armor Properties

- **PD Increase** (1): il bonus PD dell'Armor aumenta di 1. Puoi prendere questa Property due volte.
- **AD Increase** (1): il bonus AD dell'Armor aumenta di 1. Puoi prendere questa Property due volte.
- **EDR** (2): l'Armor conferisce Elemental Damage Reduction.

#### Heavy Armor Properties

- **PD Increase** (1): il bonus PD dell'Armor aumenta di 1. Puoi prendere questa Property due volte.
- **AD Increase** (1): il bonus AD dell'Armor aumenta di 1. Puoi prendere questa Property due volte.
- **PDR** (2): l'Armor conferisce Physical Damage Reduction.
- **EDR** (2): l'Armor conferisce Elemental Damage Reduction.
- **Bulky** (-1): la tua Speed è ridotta di 1.
- **Rigid** (-1): hai DisADV sugli Agility Check.

## Shields

### Shield Type

Esistono 2 tipi di Shield: Light Shields e Heavy Shields.

- **Light Shields:** semplici e facili da impugnare. Un Buckler è un tipo di Light Shield.
- **Heavy Shields:** progettati per la guerra. Un Tower Shield è un tipo di Heavy Shield.

### Wielding a Shield

Puoi spendere 1 AP per equipaggiare o riporre uno Shield. Uno Shield occupa la mano che lo impugna. Ottieni i benefici di uno Shield mentre lo impugni.

### Lacking Shield Training

Mentre impugni uno Shield in cui non hai Training, hai DisADV sugli Attack Check e sugli Spell Check.

### Attacking with Shields

Puoi effettuare un Melee Martial Attack con uno Shield in cui hai Training, infliggendo 1 danno Bludgeoning in caso di Hit.

**Throwing Shields:** quando lanci uno Shield privo della Property Toss, lo Shield è considerato un'Improvised Weapon ai fini dell'Attack (vedi Throwing in [Creatures & Combat](../combattimento/creature_combattimento.md)).

### Wielding Two Shields

Mentre impugni più Shield, si applicano i seguenti effetti:

- Ottieni i bonus di un solo Shield alla volta (a tua scelta). Puoi spendere una Minor Action per cambiare lo Shield impugnato di cui beneficiare.
- Sei immune al Flanking.

### Shield Properties

- **Grasp:** lo Shield è considerato una mano libera quando effettui un Grapple, ricarichi una Weapon o attacchi con una Versatile Weapon.
- **Mounted:** il bonus dello Shield si applica anche alla Defense della tua cavalcatura.
- **Toss:** puoi lanciare lo Shield per effettuare un Ranged Martial Attack (5/10). Se lo lanci oltre questa Range (vedi Throwing Melee Weapons in [Creatures & Combat](../combattimento/creature_combattimento.md)), è considerato un'Improvised Weapon.

### Shield Table

| Tipo | PD | AD | Speed | Agility Checks | Properties |
|---|---|---|---|---|---|
| **Light Shields** | | | | | |
| Buckler | +1 | — | — | — | Grasp |
| Round Shield | — | +1 | — | — | Toss |
| Heater Shield | +1 | +1 | — | — | — |
| **Heavy Shields** | | | | | |
| Kite Shield | +1 | +2 | -1 | DisADV | Mounted |
| Tower Shield | +2 | +2 | -1 | DisADV | — |

### Customized Shields

Quando scegli il tuo Shield durante la creazione del personaggio (o ne fabbrichi uno in seguito), scegli se è un Light Shield o un Heavy Shield e puoi conferirgli Shield Properties disponibili per quel tipo per un valore di 2 punti. Non puoi conferire la stessa Property più di una volta a uno Shield, salvo diversa indicazione.

#### Light Shield Properties

- **PD Increase** (1): il bonus PD dello Shield aumenta di 1.
- **AD Increase** (1): il bonus AD dello Shield aumenta di 1.
- **Grasp** (1): lo Shield è considerato una mano libera quando effettui un Grapple, ricarichi una Weapon o attacchi con una Versatile Weapon.
- **Toss** (1): puoi lanciare lo Shield per effettuare un Ranged Martial Attack (5/10). Se lo lanci oltre questa Range, è considerato un'Improvised Weapon.

#### Heavy Shield Properties

- **PD Increase** (1): il bonus PD dello Shield aumenta di 1. Puoi prendere questa Property due volte.
- **AD Increase** (1): il bonus AD dello Shield aumenta di 1. Puoi prendere questa Property due volte.
- **Mounted** (1): i bonus PD e AD dello Shield si applicano anche alle Defense della tua cavalcatura.
- **PDR** (2): lo Shield conferisce Physical Damage Reduction.
- **EDR** (2): lo Shield conferisce Elemental Damage Reduction.
- **Bulky** (-1): la tua Speed è ridotta di 1.
- **Rigid** (-1): hai DisADV sugli Agility Check.

## Adventuring Supplies

### Gauntlet

Puoi acquistare Gauntlet da un fabbro (oppure sono inclusi automaticamente con la Heavy Armor). Indossare un Gauntlet conferisce agli Unarmed Strike effettuati con quella mano la Weapon Property Impact (+1 danno sugli Heavy Hit).

!!! note "Nota"
    I prezzi di oggetti come i Gauntlet non sono ancora definiti; un prezzo indicativo è 5 g.

### Healing Potions

Le Healing Potions guariscono magicamente le ferite quando vengono consumate. Hanno livelli che ne aumentano potenza e costo.

| Livello | Guarigione | Prezzo |
|---|---|---|
| X | 2 × Livello in HP | — |
| 1st | 2 HP | 10 |
| 2nd | 4 HP | 25 |
| 3rd | 6 HP | 40 |
| 4th | 8 HP | 60 |
| 5th | 10 HP | 100 |

### Medicine Kit

**Uses:** un kit completo contiene 5 usi.

**Using a Kit:** puoi effettuare l'Object Action e spendere 1 uso del kit per curare le ferite di una creatura entro 1 Space, oppure per curare un Poison che la affligge.

#### Treating a Wound

Curi le ferite di una creatura. Effettua un Medicine Check DC 10. **Success:** il bersaglio recupera 1 HP. **Success (each 5):** il bersaglio recupera +1 HP.

**Limited Healing:** la guarigione fornita da questo kit non può portare gli HP di una creatura oltre la sua soglia di Bloodied.

#### Treating a Poison or Disease

Curi un Basic Poison o una Disease che affligge il bersaglio. Effettua un Medicine Check contro la DC dell'effetto. **Success:** il bersaglio è curato da quel Poison o Disease e non ne subisce più l'effetto. **Success (each 5):** la creatura recupera +1 HP.

**Advanced Poisons:** puoi invece curare un Advanced Poison, purché tu abbia il suo additivo specifico. Ogni tentativo consuma un uso di quell'additivo.

!!! note "Nota"
    Le Disease sono ancora in lavorazione. Se compaiono in avventure o creature, si curano con queste regole come se fossero Poison, salvo che il materiale relativo indichi diversamente.

#### Resupplying a Medicine Kit

**Buying Supplies:** i rifornimenti del kit si trovano nella maggior parte delle città e dei climi. Le scorte per 1 uso costano 5 gold in un emporio.

**Gathering Supplies:** puoi raccogliere rifornimenti in un clima adatto (a discrezione del GM) con un Survival Check DC 15. **Success:** il kit recupera 1 uso. **Success (each 5):** +1 uso.

### Net

Puoi lanciare la Net. Effettua un Martial Check contrapposto al Physical Save del bersaglio. La Net non ha effetto sulle creature prive di forma, più piccole di Small o più grandi di Large.

**Save Failure:** il bersaglio è **Immobilized** dalla Net finché non viene liberato. **Save Failure (5):** il bersaglio è anche **Restrained** finché non viene liberato.

Il movimento forzato non libera il bersaglio, il teletrasporto sì. Una creatura può spendere 1 AP per effettuare un Athletics Check o un Acrobatics Check DC 10. **Success:** può liberare se stessa o un'altra creatura entro la sua portata.

!!! note "Nota"
    Una creatura Medium può spendere 1 AP per lanciare una Net fino a un numero di Spaces pari al doppio della sua Might (una creatura Small può lanciarla a metà distanza). Ai fini del lancio, la tua Might minima è 1. La distanza totale si dimezza se il lancio è verticale. Vedi Throwing in [Creatures & Combat](../combattimento/creature_combattimento.md).
