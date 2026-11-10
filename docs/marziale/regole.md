# Maneuver ed Enhancement

Il sistema di combattimento dei personaggi marziali comprende:

- **Maneuver**: tecniche di forza, velocità e destrezza usate per controllare il campo di battaglia.
- **Enhancement**: modifiche alle Maneuver che aggiungono impatto, portata, aree d'effetto o Condition debilitanti, oppure potenziamenti dei Martial Attack che ne aumentano danni, Range o area d'effetto.

## Maneuver

### Maneuvers Known

Le Martial Class (Barbarian, Champion, Commander, Hunter, Rogue, Monk e Spellblade\*) conoscono un numero di Maneuver pari a quanto indicato nella colonna Maneuvers Known della propria tabella di Class, più le Maneuver apprese tramite Class Feature, Talent o progressione del Martial Path (vedi [Character Paths](../personaggio/paths.md)).

### Risorse delle Maneuver

Ogni Maneuver ha un numero minimo di Action Points (AP) che devono essere spesi per eseguirla. Molte Maneuver richiedono inoltre un numero minimo di Stamina Points (SP) da spendere per eseguirle. Questo valore è detto Base SP Cost della Maneuver.

### Caratteristiche delle Maneuver

#### Duration

Le Maneuver possono avere durata istantanea o continua, e alcune Maneuver devono essere mantenute con Sustain per proseguire (vedi Sustained Action in [Actions](../combattimento/azioni.md)).

- **Instantaneous:** le Maneuver istantanee hanno effetto nel momento in cui vengono eseguite.
- **Continuous:** queste Maneuver durano per un tempo specificato. Spesso terminano prima quando la creatura influenzata supera (Success) un Save successivo contro l'effetto, quando essa o un'altra creatura entro 1 Space effettua un'Action per terminare l'effetto, o quando si verifica un altro metodo indicato per terminare l'effetto (ad esempio l'interruzione della linea di vista).
- **Sustained:** alcuni effetti devono essere mantenuti con Sustain, altrimenti terminano.

#### Range

È la distanza entro cui deve trovarsi un bersaglio della Maneuver, o l'origine della sua Area of Effect. Quando scegli i bersagli della Maneuver, devono trovarsi entro la Range indicata e soddisfare ogni altro requisito indicato dalla Maneuver (ad esempio essere visibili o in grado di sentirti). Se la Maneuver usa un'Area of Effect per determinare i bersagli, l'origine della Maneuver deve trovarsi entro la Range indicata (vedi [Areas of Effect](../regole_generali/aree_effetto.md)).

### Eseguire una Maneuver

Per eseguire una Maneuver devi conoscerla e spendere la quantità di risorse richiesta (Action Points e Stamina Points). Quando esegui una Maneuver devi effettuare un Check (ad esempio un Attack Check o un Martial Check) per determinarne il grado di successo o fallimento. Il Check viene confrontato con la Defense del bersaglio (ad esempio PD o AD), con il DC della Maneuver o con il Contested Check del bersaglio.

#### Action Points

Eseguire qualsiasi Maneuver richiede di spendere Action Points (AP). Le Maneuver che influenzano un singolo bersaglio costano di norma 1 AP, quelle che influenzano più bersagli di norma 2 AP.

#### Stamina Points

Alcune Maneuver hanno un costo in SP che devi spendere per eseguirle. La quantità massima di SP che puoi spendere per una singola Maneuver deve essere pari o inferiore al tuo Stamina Spend Limit (vedi [Combat Resources](../combattimento/risorse.md)).

!!! note "Nota"
    Lo Stamina Spend Limit è pari alla tua Combat Mastery.

## Enhancement

Gli Enhancement aumentano l'efficacia offensiva: possono aumentare i danni, estendere la Range, ampliare le aree o infliggere Condition.

### Maneuver Enhancements

I Maneuver Enhancement ti permettono di spendere AP o SP aggiuntivi per aumentare la potenza della Maneuver (ad esempio danni, durata, Range, numero di bersagli o Area of Effect). I Maneuver Enhancement sono specifici di ciascuna Maneuver e sono riportati nella sua descrizione.

### Eseguire un Maneuver Enhancement

Quando esegui una Maneuver, puoi spendere SP aggiuntivi per aggiungere un Maneuver Enhancement alla Maneuver. Se la Maneuver richiede un Check (ad esempio un Attack Check o un Martial Check), devi scegliere di aggiungere il Maneuver Enhancement prima di effettuare il Check. Puoi eseguire lo stesso Maneuver Enhancement più volte per Maneuver, salvo diversa indicazione.

## Martial Enhancements

I Martial Enhancement potenziano i Martial Attack del personaggio. Alcuni Attack Enhancement richiedono un determinato tipo di Weapon (vedi [Equipment](../regole_generali/equipaggiamento.md)).

??? example "Esempio"
    Quando effettui un Attack con un'ascia (Axe) contro 3 creature usando la Maneuver Whirlwind, puoi spendere 1 AP per aggiungere il Martial Enhancement Damage e 1 AP per aggiungere l'Attack Enhancement Bleeding, disponibile solo per le Axe. 1 bersaglio a tua scelta subisce +1 danno dall'Attack e un altro bersaglio a tua scelta (può essere lo stesso) deve effettuare un Save contro il tuo Save DC per evitare il Bleeding.

### Eseguire un Martial Enhancement

Quando effettui un Martial Attack, puoi spendere 1 AP o SP aggiuntivo per aggiungere un Martial Enhancement all'Attack. Devi scegliere di aggiungere il Martial Enhancement prima di effettuare l'Attack Check. Puoi eseguire lo stesso Enhancement più volte per Attack, salvo diversa indicazione.

!!! note "Nota"
    Qualsiasi personaggio può spendere 1 AP aggiuntivo per ottenere ADV al proprio Attack Check.

### Elenco dei Martial Enhancements

Tutti i personaggi con Weapon Combat Training hanno accesso ai seguenti Martial Enhancement:

- **Damage:** l'Attack infligge +1 danno a 1 bersaglio dell'Attack.
- **Range:** la Range dell'Attack aumenta di 1 Space se è un Melee Attack, o di 5 Spaces se è un Ranged Attack. Questo Enhancement può essere eseguito una sola volta per Attack.
- **Daze:** una creatura a tua scelta bersaglio dell'Attack effettua un Might Save contro il tuo Save DC. **Save Failure:** il bersaglio diventa **Dazed** fino alla fine del suo turno successivo.

!!! note "Nota"
    Una creatura Dazed non può mantenere con Sustain alcun effetto all'inizio del proprio turno. Un personaggio marziale non può impedire il lancio di uno Spell come fa uno Spellcaster con lo Spell Duel, ma può interrompere uno Spell Sustained facendo perdere la concentrazione allo Spellcaster.

??? example "Esempio"
    Spendi 2 AP e 1 SP per un Attack contro una creatura nemica: 1 AP per l'Action Attack (1 Attack Check), 1 AP per aggiungere il Martial Enhancement Damage (+1 danno) e 1 SP per aggiungere il Martial Enhancement Range.

## Maneuver Types

Esistono diversi tipi di Maneuver (vedi l'[elenco delle Maneuver](maneuvers.md)).

### Attack

Le Attack Maneuver infliggono danni e costituiscono la base dell'arsenale offensivo del personaggio marziale.

### Defense

Le Defense Maneuver aumentano la resistenza e la sopravvivenza: parare i colpi, resistere alla forza o deviare gli attacchi, proteggendo se stessi o gli alleati.

### Grapple

Le Grapple Maneuver sono specializzate nel controllo ravvicinato: immobilizzare, trattenere o lanciare i nemici, controllandone movimento e azioni.

### Utility

Le Utility Maneuver offrono versatilità sul campo di battaglia oltre al combattimento diretto: riposizionamento, movimento, interazione con l'ambiente, intimidazione o preparazione di azioni per gli alleati.

## Advanced Maneuvers

### Combo Maneuvers

**Prerequisito:** Martial Path

Durante una Combo Maneuver, la creatura che esegue l'SP Effect è detta Performer, mentre le altre creature che la assistono sono dette Participants.

**Trigger:** vedi eseguire un SP Effect che conosci, purché il Performer dell'SP Effect o un bersaglio si trovi entro 2 Spaces da te.

**Reaction:** puoi spendere una quantità di AP pari al costo base in AP dell'SP Effect che stai tentando di assistere. Quando lo fai, l'SP Effect ottiene un bonus di +2 al suo Check e al suo Save DC per questo turno.

**Spendere SP:** puoi scegliere di spendere 1 o più SP per aggiungere SP Enhancement all'SP Effect del Performer (fino al tuo Stamina Spend Limit).

??? example "Esempio"
    I marziali A e B hanno ciascuno uno Stamina Spend Limit di 3. A spende 1 AP e 3 SP per eseguire la Maneuver Bash. B può spendere anch'egli 1 AP e 3 SP come Reaction, portando il totale di SP spesi sulla Maneuver a 6 (la somma degli Stamina Spend Limit dei due). A ottiene quindi un bonus di +2 al proprio Martial Attack.

!!! note "Nota"
    Per eseguire una Combo Maneuver i marziali devono trovarsi entro 2 Spaces l'uno dall'altro, ma possono spendere Stamina Points fino ai rispettivi Stamina Spend Limit sommati. Gli Spellcaster che eseguono una Combo Spellcasting possono farlo da una distanza di 5 Spaces, ma possono spendere in totale solo una quantità di Mana Points pari al Mana Spend Limit del Caster (vedi [Combo Spellcasting](../magia/regole.md)).
