# Artificer

!!! warning "Non aggiornato"
    La Class Artificer non è stata aggiornata dalla versione 0.10 di DC20.

## Tabella della Class

| Livello | Health Points | Attribute Points | Skill Points | Trade Points | Mana Points | Spells Known | Features |
|---|---|---|---|---|---|---|---|
| 1 | +7 |  |  |  | +6 | +4 | Class Features |
| 2 | +1 |  |  |  |  |  | Class Feature, Talent, Path Progression |
| 3 | +1 | +1 | +1 | +1 | +3 | +1 | Subclass Feature |
| 4 | +1 |  |  |  |  |  | Talent, Path Progression, 2 Ancestry Points |
| 5 | +1 | +1 | +2 | +1 | +3 | +1 | Class Expert Feature |
| 6 | +1 |  | +1 |  |  |  | Talent, Path Progression |
| 7 | +1 |  |  |  | +3 | +1 | Subclass Expert Feature |
| 8 | +1 | +1 | +1 | +1 |  |  | Talent, Path Progression, 2 Ancestry Points |
| 9 | +1 |  |  |  | +3 | +1 | Class Capstone Feature |
| 10 | +1 | +1 | +2 | +1 | +3 | +1 | Subclass Capstone Feature |

## Starting Equipment

- **Arsenal:** Spell Focus, Weapon o Shield.
- **Armor:** 1 set di Light Armor.
- **Trade Tools:** 2 a scelta tra Tinkerer's Tools, Alchemist's Supplies, Blacksmith's Tools, Glassblower's Tools e Herbalist's Supplies.
- **Adventuring Pack:** 1 a scelta.

## Artificer Spellcasting Path

- **Combat Training:** Spell Focuses, Light Armor, Light Shields.
- **Spell List:** quando impari un nuovo Spell, puoi sceglierlo tra le School Conjuration, Elemental e Transmutation, oppure tra gli Spell con lo Spell Tag Strike (opzione non ufficiale).
- **Spells Known:** il numero di Spell conosciuti aumenta come indicato nella colonna Spells Known della tabella.
- **Mana Points:** i Mana Points massimi aumentano come indicato nella colonna Mana Points della tabella.

## Class Features di livello 1

### Infusion Magic

Le Infusions sono Magic Properties che puoi applicare agli oggetti per conferire loro il potere dei Magic Item. Un'Infusion è identica alla Magic Property con lo stesso nome (vedi [Magic Properties](../oggetti_magici/magic_properties.md)). Finché un oggetto porta un'Infusion, è considerato un Magic Item.

#### Infusions Known

Impari 3 Infusions a tua scelta. Puoi scegliere l'Infusion di qualsiasi Magic Property che non sia una Artifact Magic Property. Ogni volta che impareresti uno Spell, puoi invece imparare un'Infusion, anche quando ottieni questa Feature.

**Multiple Choice:** se impari un'Infusion con più opzioni, ne scegli una. Ogni volta che impari di nuovo quell'Infusion puoi scegliere un'opzione diversa.

??? example "Esempio"
    Se impari l'Infusion Skill Increase e scegli la Skill Stealth, puoi infondere un oggetto solo con un bonus ai Check di Stealth, finché non impari di nuovo quell'Infusion scegliendo un'altra Skill. Allo stesso modo, se impari l'Infusion Spellcasting e scegli lo Spell Banish, puoi infondere un oggetto solo con la capacità di lanciare Banish.

**Infusion Spell List:** quando impari un'Infusion che infonde uno Spell in un oggetto (ad esempio Spellcasting, Spell Potion o Spell Scroll), scegli uno Spell qualsiasi, che diventa uno dei tuoi Infusion Spells. Quando applichi un'Infusion di questo tipo puoi infondere uno qualsiasi dei tuoi Infusion Spells o degli Spell che conosci. Gli Infusion Spells non contano come Spell conosciuti per il normale Spellcasting.

#### Applicare un'Infusion

Puoi applicare un'Infusion che conosci a un oggetto comune che stai toccando (ad esempio una Weapon, un set di Armor o uno Shield) spendendo 1 AP e un numero di MP pari al Magic Power dell'Infusion (minimo 1 MP). Se l'Infusion ha un Magic Power variabile (Variable), scegli tu il valore.

- **Charges:** le Infusions che conferiscono Charges a un oggetto ne conferiscono tante quanti sono gli MP spesi.
- **Duration:** un'Infusion dura finché non spendi 1 AP per terminarla, o finché non sei morto da più di 8 ore.
- **MP Reduction:** quando applichi un'Infusion, i tuoi MP massimi si riducono degli MP spesi. La riduzione termina solo quando termina l'Infusion. Non recuperi gli MP persi quando i tuoi MP massimi vengono ripristinati.

### Magical Craftsman

Ottieni i seguenti benefici:

- **Rituals:** impari i Ritual Identify, Mending, Restore Magic Charges e Transpose Magic Property (descritti sotto).
- **Trade Expertise:** il tuo Trade Mastery Limit aumenta di 1, fino a Grandmaster (+10). Un Trade può beneficiare di un solo aumento del suo limite di Mastery. Inoltre ottieni 2 Trade Points.
- **Artisan's Resistance:** ottieni Resistance (Half) a un tipo di danno Elemental a tua scelta.

#### Ritual: Identify

**Cast Time:** 1 Minute

Scegli un oggetto ed effettui uno Spell Check (DC = 5 + il doppio del Magic Power dell'oggetto).

- **Failure:** scopri i materiali di cui è fatto e gli eventuali requisiti di Attunement.
- **Success:** scopri le Magic Properties dell'oggetto che non sono Hidden né Artifact. Scopri anche se ha usi o Charges, quanti ne restano e come si attiva.
- **Success (5):** scopri l'eventuale Artifact Magic Property. A discrezione del GM puoi ottenere informazioni speciali sull'oggetto o su come rivelarne le Hidden Magic Properties.
- **Success (10):** scopri le Hidden Magic Properties e se l'oggetto è Cursed.

Dopo aver risolto il Check, non puoi ritentare Identify sullo stesso oggetto finché non sono trascorse 24 ore o non completi un Long Rest (quale delle due avviene prima).

!!! note "Nota"
    Il GM può modificare la DC in base alle caratteristiche dell'oggetto. Un oggetto può risuonare con chi tenta di identificarlo o resistergli, in base alla Class (Cleric o Warlock), all'Ancestry (Elf o Dwarf) o a scelte passate (aver tolto una vita, aver mantenuto un giuramento). Alcuni oggetti possono richiedere un luogo o un oggetto speciale. Se il giocatore non raggiunge la DC modificata, il GM può dare indizi su questi fattori nascosti.

#### Ritual: Mending

**Cast Time:** 1 Minute

Ripari un oggetto, sistemando una rottura o uno strappo non più grande di 30 cm in nessuna dimensione, purché tu abbia i materiali necessari. Se l'oggetto è magico, il Ritual non ne ripristina la magia.

#### Ritual: Restore Magic Charges

**Cost:** 1 AP + 1 MP

Ripristini un numero di Charges spese di un Magic Item pari agli MP spesi.

- **Spend More Mana** (1 MP, Repeatable): ripristini 1 Charge aggiuntiva.

#### Ritual: Transpose Magic Property

**Cast Time:** 10 Minutes

Tenendo in mano un Magic Item, trasferisci tutte le sue Magic Properties a un oggetto comune che tieni anch'esso in mano.

**Restrictions:** il Magic Item non può avere una Artifact Property, il suo Magic Power non può superare la tua Combat Mastery e l'oggetto comune deve soddisfare i requisiti delle Magic Properties (ad esempio essere una Weapon per la Magic Property Change Damage Type).

!!! note "Nota"
    Il Ritual funziona solo se il Magic Item è stato creato con il sistema delle Magic Properties.

### Tinkerer (Flavor Feature)

Puoi spendere 10 minuti per creare uno dei piccoli congegni a orologeria dell'elenco seguente. Puoi avere contemporaneamente un numero di congegni pari al tuo Prime Modifier; se ne crei uno oltre il limite, uno a tua scelta smette di esistere. Per usarli, una creatura deve tenerli in mano.

- **Igniter:** con una Object Action una creatura accende un oggetto infiammabile (una candela, una torcia) entro 1 Space.
- **Illuminator:** con una Object Action una creatura accende o spegne una Bright Light in un raggio di 1 Space.
- **Recorder:** con una Object Action una creatura registra fino a 5 minuti di audio. Con una Minor Action può riprodurre, fermare o riavvolgere la registrazione. La registrazione si sente fino a 5 Spaces di distanza.
- **Hologram:** con una Object Action una creatura registra un'immagine fissa (fino a 10 immagini). Con una Minor Action può vedere un'immagine salvata come piccolo ologramma.

## Class Features di livello 2

### Mana Core

Puoi spendere 1 minuto per attaccare un Mana Core a un set di Trade Tools o a un oggetto Tiny che stai toccando (ad esempio una Weapon, uno Spell Focus o uno Shield). Quando lo fai, l'oggetto ottiene 1 beneficio a tua scelta dalla tabella seguente. Ottieni il beneficio solo se impugni o indossi l'oggetto. Se usi di nuovo questa Feature, il Mana Core precedente diventa inerte.

**Overdrive:** puoi mandare in Overdrive il Mana Core per ottenere il beneficio Overdrive dell'opzione scelta. Puoi usare Overdrive una volta per Long Rest, e ne recuperi l'uso quando tiri l'Initiative.

| Opzione | Beneficio | Overdrive |
|---|---|---|
| Damage | Una volta per Round, un tuo Attack infligge +1 danno a tutti i bersagli. | Quando effettui un Attack, infligge +1 danno a tutti i bersagli (si somma al beneficio normale). |
| Damage Reduction | Ottieni PDR, EDR o MDR. | Quando subisci danni, puoi ridurli di un ammontare pari al tuo Prime Modifier. |
| Speed | La tua Speed aumenta di 2. | In qualsiasi momento del tuo turno puoi teletrasportarti fino a 5 Spaces in uno Space libero che vedi. |
| Focused | L'oggetto ottiene 1 Spell Focus Property. | Quando effettui uno Spell Check, ottieni +5 al Check. |

## Subclasses

Al livello 3 scegli una Subclass: Armorer, Apothecary oppure Paragon Artificer.

### Armorer

#### Arcane Armor

Ottieni Combat Training in tutte le Armor e tutti gli Shield.

Quando completi un Long Rest puoi infondere di potere arcano un set di Armor che stai toccando. Diventa la tua Arcane Armor, con i seguenti benefici:

- Le Infusions applicate alla tua Arcane Armor costano 1 MP in meno (minimo 0 MP).
- Se la tua Arcane Armor è entro 10 Spaces, puoi spendere 1 AP per richiamarla, purché non sia tenuta in mano, non sia bloccata e abbia un percorso libero verso di te. Si sfila da chi la indossa, vola da te, si equipaggia su di te e si lega a te con Attunement se può (terminando l'Attunement di altre creature). Se indossi già un'Armor o scegli di non equipaggiarla, cade ai tuoi piedi nel tuo Space.

Puoi avere una sola Arcane Armor alla volta. Smette di esserlo se spendi 1 AP per terminarla in qualsiasi momento, o se usi questa Feature su un altro set di Armor.

**Overdrive:** quando usi Overdrive, ottieni un beneficio aggiuntivo in base al tipo della tua Arcane Armor:

- **Light Armor:** per 1 Round chi la indossa diventa **Invisible** e il suo movimento non provoca Opportunity Attacks.
- **Heavy Armor:** l'Armor ottiene un'Aura di 1 Space per 1 Round. Gli Attack contro le creature che scegli all'interno dell'Aura hanno DisADV.

#### Armored Artisan (Flavor Feature)

Hai ADV ai Check per identificare origine e proprietà di Armor e Shield.

### Apothecary

#### Potions & Poisons

Ottieni 2 Trade Points da spendere in Alchemy o Herbalism. Impari le Infusions Spell Potion e Spell Bomb (vedi [Magic Properties](../oggetti_magici/magic_properties.md)).

Quando crei una pozione, una Spell Bomb o un veleno, questo ottiene 1 dei seguenti benefici aggiuntivi:

- **Bless:** il bersaglio aggiunge un d4 al prossimo Check che effettua entro 1 minuto.
- **Bane:** il bersaglio sottrae un d4 dal prossimo Check che effettua entro 1 minuto.

#### Elixir Expert (Flavor Feature)

Hai ADV ai Check per identificare erbe, pozioni, veleni o sostanze simili.

### Paragon Artificer

Al livello 3, invece di scegliere una Subclass della tua Class, puoi prendere la Subclass Paragon.

#### Novice Paragon (livello 3)

Ottieni un Class Talent a tua scelta. In alternativa puoi prendere un Multiclass Talent, purché tu scelga una Feature della tua Class che abbia più opzioni (come Cleric Order: Divine Domains). Non puoi scegliere una Feature di cui hai già tutte le opzioni. Il Class Talent o Multiclass Talent scelto non ti conferisce Talent Mastery.

**Jack of one Trade (Flavor Feature):** ottieni 1 Trade Point.

#### Adept Paragon (livello 6)

Ottieni un altro Class Talent (o Multiclass Talent) a tua scelta, alle stesse condizioni di Novice Paragon.

#### Expert Paragon (livello 9)

Ottieni un altro Class Talent (o Multiclass Talent) a tua scelta, alle stesse condizioni di Novice Paragon.

## Class Talents

Puoi prendere questi Talent con i Talent della tabella della Class (livelli 2, 4, 6, 8) o con la Subclass Paragon Artificer (vedi [Talents](../personaggio/talents.md)).

### Artifice Engine

**Requisiti:** livello 3, Infusion Magic.

Quando lanci uno Spell, puoi alimentarlo con il potere di un Magic Item che tieni in mano o indossi. Il costo in MP dello Spell si riduce del Magic Power dell'oggetto (minimo 0 MP) e hai ADV al Check per lanciarlo. Puoi usare questo Talent una volta per Long Rest, e ne recuperi l'uso quando tiri l'Initiative.

**Inert Item:** dopo l'uso, il Magic Item diventa Mundane per 12 ore o finché non completi un Long Rest (quale delle due avviene prima). Se portava un'Infusion, questa termina e non torna a meno che tu non la applichi di nuovo.

**Restrictions:** se il Magic Item richiede Attunement, devi esserne Attuned. Non puoi usare questo Talent su un oggetto con Charges o con la Magic Property o l'Infusion Spell Storing.

??? example "Esempio"
    Un Artificer ha Mana Spend Limit 4 e un Magic Item con Magic Power 5. Può spendere fino a 4 MP per lanciare uno Spell (fino al suo Mana Spend Limit); alimentandolo con l'oggetto riduce il costo di 5 MP (in pratica di 4, perché il minimo è 0) e l'oggetto diventa Mundane (le Infusions terminano). L'oggetto recupera la magia dopo 12 ore o con un Long Rest.

### Infusion Conduits

**Requisiti:** livello 3, Infusion Magic.

Finché un oggetto con una delle tue Infusions è entro 10 Spaces da te:

- conosci la sua posizione esatta;
- quando lanci uno Spell, puoi farlo come se fossi nello Space in cui si trova l'oggetto;
- puoi comunicare telepaticamente con la creatura che lo porta o lo indossa.
