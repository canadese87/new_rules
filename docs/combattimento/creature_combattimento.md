# Creatures e Combat

## Creatures

### Creature Sizes

Il numero di Spaces occupati da una creatura ne determina la taglia ai fini delle regole che governano le interazioni tra le creature e l'ambiente. La tabella seguente riporta le 9 taglie delle creature, con esempi e il numero di Spaces occupati.

| Size | Esempi | Spaces |
|---|---|---|
| Micro | Ragno | Vedi Micro Creatures sotto |
| Tiny | Gatto | 1/4 Space (4 per Space) |
| Small | Pecora | 1 Space |
| Medium | Umano | 1 Space |
| Large | Cavallo | 4 Spaces: (2 x 2) o (4 x 1) |
| Huge | Elefante | 9 Spaces: (3 x 3), (4 x 2) o (9 x 1) |
| Gargantuan | T-Rex | 16 Spaces: (4 x 4), (5 x 3), (8 x 2) o (16 x 1) |
| Colossal | Brontosauro | 25 Spaces: (5 x 5), (6 x 4), (8 x 3), (12 x 2) o (25 x 1) |
| Titanic | Balenottera azzurra | 50 Spaces: (7 x 7), (8 x 6), (10 x 5), (12 x 4), (16 x 3), (25 x 2) o (50 x 1) |

**Micro Creatures:** le creature eccezionalmente piccole, come le formiche, possono condividere il proprio Space con altre creature. Possono terminare il turno in uno Space occupato da altre creature (e viceversa).

## Moving & Grappling Creatures

Le creature di taglie diverse hanno bonus o penalità quando tentano con mezzi ordinari di effettuare un Grapple, spingere, spostare o rendere Prone altre creature.

| Size | Check |
|---|---|
| 1+ Sizes più grande del bersaglio | ADV |
| Stessa Size del bersaglio | Normale |
| 1 Size più piccola del bersaglio | DisADV |
| 2+ Sizes più piccola del bersaglio | Impossibile |

??? example "Esempio"
    Un Champion di taglia Medium che tenta di spostare una creatura Large ha DisADV sul Check effettuato per spostarla.

### Grappled

Sei **Immobilized**.

#### Escape Grapple

Puoi spendere 1 AP per tentare di liberarti da un Grapple. Effettui un Acrobatics o Athletics Check contrastato dall'Athletics Check del Grappler. **Success:** il Grapple termina immediatamente.

Il Grapple termina anche se si verifica una delle seguenti situazioni:

- **Incapacitated:** il Grappler diventa Incapacitated.
- **Falling:** il Grappler non è in grado di sostenere il tuo peso quando inizi a cadere, a meno che non stia cadendo anche lui con te.
- **Forced Movement:** un effetto sposta forzatamente te o il Grappler, portandoti fuori dalla portata del Grappler. Se l'effetto richiede un Contested Check o un Save, è il Grappler a effettuare il Check o il Save al posto tuo. Se l'effetto bersaglia sia te sia il Grappler, il Grappler effettua 1 Check o Save per entrambi. **Success:** i bersagli non vengono spostati. **Failure:** i bersagli vengono spostati.

#### Grappled by Multiple Creatures

Una creatura Grappled da più di 1 creatura subisce gli effetti di Grappled una sola volta. Tuttavia, rimane Grappled finché non si è liberata dal Grapple di tutte le fonti.

??? example "Esempio"
    Mentre è Grappled, una creatura è Immobilized (DisADV sugli Agility Saves). Una creatura Grappled da 2 creature non ha DisADV 2 sugli Agility Saves, ma solo DisADV.

**Moving the Target:** se più creature stanno effettuando un Grapple sullo stesso bersaglio e una di esse tenta di spostarlo, deve effettuare un Contested Athletics Check contro tutte le creature che effettuano un Grapple su quel bersaglio. **Success:** termina il Grapple sul bersaglio di tutte le altre creature, e può spostare la creatura normalmente.

## Moving Through Creatures

Il fatto che una creatura ti sia amica od ostile determina se puoi attraversarne liberamente lo Space.

**Friendly Creatures:** puoi attraversare uno Space occupato da una creatura amica senza spendere movimento aggiuntivo.

**Hostile Creatures:** puoi attraversare lo Space di creature ostili di 2 Sizes più grandi o più piccole di te, ma sei considerato Slowed mentre attraversi lo Space che occupano. Se la creatura ha una taglia entro 1 Size dalla tua, non puoi attraversarne lo Space a meno che tu non compia l'Action Pass Through (vedi [Actions](azioni.md)).

**Ending Your Movement:** non puoi terminare il turno in uno Space occupato da un'altra creatura.

## Collision

Quando una creatura viene lanciata o respinta e urta un oggetto inamovibile (come un muro) o un'altra creatura, subisce danni all'impatto.

**Sudden Stop:** la creatura si ferma nello Space in cui è entrata in contatto con il bersaglio della Collision.

**Collision Damage:** la creatura e tutti i bersagli della Collision si dividono una quantità di danni Bludgeoning pari al numero di Spaces che la creatura non ha potuto percorrere (a causa della Collision).

??? example "Esempio"
    Una creatura viene respinta di 5 Spaces e urta un muro a soli 2 Spaces di distanza. Viene scagliata di 2 Spaces contro il muro e subisce 3 danni Bludgeoning per i 3 Spaces che non ha potuto percorrere (5 - 2 = 3). Se invece urtasse un'altra creatura, le due si dividerebbero i 3 danni Bludgeoning (1,5 ciascuna, arrotondati per eccesso a 2 danni ciascuna).

**Colliding with a Target:** quando sposti forzatamente una creatura verso un bersaglio, confronti il tuo Check con la PD del bersaglio. **Hit:** la creatura spostata forzatamente e il bersaglio si dividono i danni della Collision (ciascuno ne subisce la metà). **Miss:** la creatura spostata forzatamente continua a muoversi fino alla distanza massima dello spostamento.

## Throwing

Puoi spendere 1 AP per lanciare un oggetto o una creatura su cui stai effettuando un Grapple.

### Object

Il bersaglio viene lanciato fino al numero di Spaces indicato nella Throwing Table. Ai fini del lancio, il tuo Might minimo è 1. La distanza totale è dimezzata se il lancio è verticale.

**Throw at a Target:** quando lanci un oggetto contro un bersaglio, si considera un Ranged Martial Attack con un'Improvised Weapon contro la PD del bersaglio. **Hit:** il bersaglio subisce 1 danno di un tipo stabilito dal GM. **Miss:** l'oggetto lanciato continua a muoversi fino alla tua distanza massima di lancio.

!!! note "Nota"
    Quando lanci Weapons (incluse le Improvised Weapons) prive delle Properties Toss o Thrown come parte di un Attack, effettui l'Attack con DisADV.

### Creature

Effettui un Athletics Check contro il Might Save del bersaglio. **Check Success:** il bersaglio viene lanciato fino al numero di Spaces indicato nella Throwing Table (il Grapple termina). Ai fini del lancio, il tuo Might minimo è 1. La distanza totale è dimezzata se il lancio è verticale verso l'alto.

**Throw at a Target:** quando lanci la creatura contro un bersaglio, confronti il tuo Athletics Check con la PD del bersaglio. **Hit:** la creatura lanciata e il bersaglio si dividono i danni della Collision (ciascuno ne subisce la metà). **Miss:** la creatura lanciata continua a muoversi fino alla tua distanza massima di lancio.

### Throwing Table

| Size | Spaces Thrown |
|---|---|
| 2+ Sizes più piccolo | 2 x Might |
| 1 Size più piccolo | Might |
| Stessa Size | 1/2 Might |
| Più grande | Impossibile |

??? example "Esempio"
    Una creatura Medium con Might 0 (Might minimo 1) può lanciare un oggetto Tiny fino a 2 Spaces, un oggetto Small a 1 Space e un oggetto Medium a 1 Space (0,5 arrotondato per eccesso). Con Might 6 potrebbe invece lanciare un oggetto Tiny a 12 Spaces, uno Small a 6 Spaces e uno Medium a 3 Spaces.

### Throwing Melee Weapons

Quando lanci una Weapon (o uno Shield) priva delle Properties Toss o Thrown, è considerata un'Improvised Weapon ai fini dell'Attack. Per le Weapon Properties vedi [Equipment](../regole_generali/equipaggiamento.md).

!!! note "Nota"
    La maggior parte delle Weapons sono oggetti Tiny: una creatura Medium con Might 3 può lanciare una Weapon fino a 6 Spaces.

## Improvised Weapons

Quando un oggetto che non è una Weapon viene usato come tale, è considerato un'Improvised Weapon. Salvo diversa indicazione del GM, un'Improvised Weapon infligge 1 danno di un tipo stabilito dal GM. Quando effettui un Attack con un'Improvised Weapon hai DisADV.

**Weapon Style:** salvo diversa indicazione del GM, un'Improvised Weapon non beneficia di alcuna Weapon Property né dei Weapon Enhancements concessi da una Weapon.

!!! note "Nota"
    Se un'Improvised Weapon è abbastanza simile a una vera arma, il GM può stabilire che ottenga certe Weapon Properties (come Reach) o anche un Attack Enhancement di una Weapon (come Bleed).

## Unarmed Strikes

Gli Unarmed Strikes infliggono 0 danni Bludgeoning. Un Unarmed Strike è un Melee Attack effettuato con una qualsiasi parte del corpo della creatura, come un pugno, una gomitata, un calcio, una ginocchiata o una testata.

!!! note "Nota"
    Gli Attacks che infliggono 0 danni base possono comunque beneficiare di danni bonus, come Heavy Hits, Martial Enhancements, Class Features, ecc.

## Natural Weapons

Una Natural Weapon è una parte del corpo di una creatura che conta come Weapon (come artigli, zanne e corna). Quando attacchi con una Natural Weapon, l'Attack è considerato sia un Weapon Attack sia un Unarmed Strike.

**Wielding a Natural Weapon:** una Natural Weapon è considerata impugnata dall'arto a cui è attaccata, a meno che quell'arto non stia tenendo qualcosa.

??? example "Esempio"
    Un Beastborn con artigli è considerato impugnare gli artigli nelle mani, quindi queste Natural Weapons sono valide per il Dual Wielding e meccaniche simili.

## Non-Lethal Attacks

Quando effettui un Melee Attack con una Weapon o un Unarmed Strike, puoi dichiarare l'Attack Non-Lethal. Se una creatura viene ridotta a 0 HP o meno da un Non-Lethal Attack, cade invece **Unconscious** ed è considerata Stable ai fini del Death's Door.

Se una creatura cade Unconscious in questo modo, un'altra creatura può spendere 1 AP per svegliarla scuotendola. Quando la creatura si risveglia è in Death's Door a 0 HP, indipendentemente dai danni inflitti dal Non-Lethal Attack.

## Dual Wielding

Sei considerato in Dual Wielding quando impugni una Weapon distinta in ciascuna mano. Quando effettui un Attack con una delle Weapons in Dual Wielding, il tuo Attack successivo in questo turno con l'altra Weapon ignora il Multiple Check Penalty (e non fa avanzare tale penalità), purché tu sia ancora in Dual Wielding con quelle Weapons. Puoi farlo solo una volta in ciascuno dei tuoi turni.

!!! note "Nota"
    Se una delle tue mani è una Natural Weapon (come un artiglio o il beneficio Iron Palm del Monk), conta come una Weapon impugnata in quella mano ai fini del Dual Wielding.

## Flanking

Ottieni +2 aggiuntivo al tuo Melee Attack se il bersaglio è Flanked. Una creatura è Flanked quando ha entro 1 Space 2 o più nemici non adiacenti tra loro, purché non siano Incapacitated o Prone. Sei considerato in Flanking su una creatura se sei una delle creature che la rendono Flanked.

## Prone

Mentre sei Prone, subisci i seguenti effetti:

- Hai DisADV sugli Attacks, i Ranged Attacks contro di te hanno DisADV e i Melee Attacks contro di te hanno ADV.
- **Crawl Speed:** finché non ti rialzi, l'unica forma di movimento possibile è strisciare (Crawl), che costa 1 Space di movimento aggiuntivo per ogni Space percorso.

**Ending Prone:** puoi terminare la condizione Prone spendendo 2 Spaces di movimento per rialzarti.

**Prone in the Air:** quando diventi Prone, entri immediatamente in un Uncontrolled Fall a meno che tu non sia sostenuto da una superficie solida (vedi Falling in [Environment](../regole_generali/ambiente.md)).

## Hidden Creatures

Le creature Unseen o Unheard sono più difficili da individuare.

### Unseen

Sei Unseen da una creatura quando sei impercettibile ai suoi sensi visivi, ad esempio quando sei Fully Concealed, sei Invisible o essa è Blinded. Mentre sei Unseen, ottieni i seguenti effetti:

- Hai ADV sugli Attacks contro le creature che non possono vederti.
- Le creature che non possono vederti hanno DisADV sugli Attacks contro di te.

!!! note "Nota"
    Se sei Unseen perché sei dietro Full Cover, sei sotto l'effetto dello Spell Invisibility e il tuo bersaglio è Blinded, non ottieni i benefici di Unseen più volte. O sei Unseen o non lo sei.

### Unheard

Sei Unheard quando rimani in silenzio, non parli più forte di un sussurro o ti trovi in un'area influenzata dallo Spell Muffle o da un effetto simile. Mentre sei Unheard, ottieni il seguente effetto:

- Hai ADV sugli Attacks contro le creature su cui sei in Flanking e che non possono sentirti.

!!! note "Nota"
    Se sei Unheard perché rimani in silenzio o ti trovi in un'area influenzata dallo Spell Muffle, non ottieni i benefici di Unheard più volte. O sei Unheard o non lo sei.

### Hidden

Sei Hidden da una creatura quando sei sia Unseen sia Unheard da essa. La tua posizione è sconosciuta alle creature da cui sei Hidden.

!!! note "Nota"
    Se diventi Hidden per una creatura che è consapevole di te, essa conosce solo l'ultima posizione in cui sapeva che ti trovavi prima che diventassi Hidden. Le creature che possono percepire la tua presenza, anche con mezzi magici come la divinazione, non sono considerate a conoscenza della tua posizione, né in grado di vederti o sentirti, a meno che la Feature non indichi diversamente.

## Underwater Combat

Sott'acqua, le creature sono soggette alle seguenti condizioni:

**Attack Penalties:** i Martial Attacks si effettuano con DisADV a meno che la creatura non abbia una Swim Speed. Inoltre, i Ranged Attacks mancano automaticamente i bersagli oltre la gittata normale della Weapon.

**Holding Breath:** le creature che tentano di parlare mentre trattengono il respiro sott'acqua, ad esempio per soddisfare la Verbal Component di uno Spell, riducono la propria Breath Duration di 1 (vedi Holding Your Breath in [Environment](../regole_generali/ambiente.md)).

**Fire Resistance:** le creature e gli oggetti completamente immersi in acqua hanno Fire Resistance (Half) e sono immuni a Burning.
