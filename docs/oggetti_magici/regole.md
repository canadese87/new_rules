# Magic Items

## Magic Items

I Magic Items sono oggetti incantati con Magic Properties che conferiscono benefici a chi li usa. Non puoi usarli né beneficiarne se non li impugni (Weapon, Shield) o non li hai equipaggiati in uno dei tuoi Equipment Slots (Head, Body, Waist, ecc.).

## Magic Properties

Un Magic Item può avere al massimo 3 Magic Properties e non può avere due volte la stessa Magic Property. Le Magic Properties con lo stesso nome ma con le distinzioni Minor, Moderate o Major contano come la stessa Magic Property.

- **Artifact Magic Properties:** gli oggetti che ne hanno una sono Artifact Items. Non contano nel limite di 3, ma un oggetto può averne al massimo 1.
- **Cursed Magic Properties:** gli oggetti che ne hanno una sono Cursed Items. Non contano nel limite di 3.
- **Consumables:** le Magic Properties con il tag Consumable si possono applicare solo a oggetti composti interamente da Magic Properties Consumable. Un Consumable scompare quando esaurisce i suoi Limited Uses (di solito 1): quando viene bevuto, applicato, lanciato o bruciato.

L'elenco completo è in [Magic Properties](magic_properties.md).

## Magic Power

Ogni Magic Property ha un Magic Power che ne misura forza, efficacia e complessità. Il Magic Power di un oggetto è la somma del Magic Power di tutte le sue Magic Properties.

- **Magic Power 0:** un oggetto può avere una sola Magic Property con Magic Power 0 alla volta.
- **Variable Magic Power:** il valore viene fissato quando l'oggetto viene creato.

!!! note "Nota"
    Il Magic Power di un oggetto di norma non supera la Combat Mastery del suo creatore (metà del suo livello).

## Attunement

Se un oggetto richiede Attunement, devi esserne Attuned per ottenere i benefici delle sue Magic Properties; altrimenti funziona come un oggetto comune del suo tipo.

- **Attuning:** spendi 1 AP per legarti a un Magic Item che tieni in mano (e che nessun'altra creatura tiene in mano), o per terminare il legame.
- **Item Knowledge:** quando ti leghi a un oggetto scopri subito gli effetti che ti applica (HP, PD, Speed, ecc.) e se ha effetti attivabili (usi, Charges), ma non quali sono.
- **Contested Attunement:** se l'oggetto è già legato a un'altra creatura, effettui un Contested Flat Charisma Check contro di essa. **Success:** ti leghi all'oggetto e il legame dell'altra creatura termina. **Failure:** non puoi ritentare per 1 ora.
- **Cursed Items:** finché tieni in mano, indossi o sei Attuned a un Cursed Item ne subisci la Curse, salvo diversa indicazione. Se l'oggetto richiede Attunement, di solito la Curse si applica solo dopo che ti sei legato a esso.

!!! note "Nota"
    Se un effetto attivabile richiede un Trigger, il GM può rivelarti quale sia, a sua discrezione.

## Charges, Uses e Limited Uses

- **Charges:** alcuni oggetti hanno Charges da spendere per attivare le loro Magic Properties. Si recuperano tutte dopo 24 ore o quando chi possiede l'oggetto completa un Long Rest tenendolo con sé per tutta la durata del Rest.
- **Uses:** alcune Magic Properties si possono attivare un certo numero di volte. Gli Uses si recuperano come le Charges.
- **Limited Uses:** non si recuperano. Esauriti gli usi, la Magic Property scompare dall'oggetto.

!!! note "Nota"
    I Consumables hanno Limited Uses, ma non tutti gli oggetti con Limited Uses sono Consumables. Una Spear che lancia Lightning Bolt con 3 Limited Uses torna una Spear comune quando li esaurisce.

## Durability, requisiti e uso

- **Durability:** i Magic Items hanno Resistance (X) a tutti i danni, dove X è pari al loro Magic Power (minimo 1). I danni True non vengono ridotti.
- **Requirements:** gli eventuali requisiti sono indicati nella descrizione o nell'Attunement, ad esempio "Attunement (Harvest God Servant)" o "Attunement (Experienced Death)".
- **Uso:** attivare un oggetto richiede la Object Action, salvo diversa indicazione. Devi impugnarlo o averlo equipaggiato.

## Equipment Slots

| Slot | Esempi |
|---|---|
| Finger (×2) | anelli, smalto; uno per mano |
| Hands | guanti, bracciali, fasce, guanti d'arme |
| Feet | stivali, sandali, schinieri |
| Waist | cintura, fascia, cinturone |
| Body | armature o vesti su torso e gambe (camicia e pantaloni, tunica, corazza e gambali) |
| Shoulders | mantello, cappa, sciarpa, zaino, spallacci |
| Neck | collana, amuleto, girocollo |
| Head | occhiali, visori, cappello, cappuccio, corona, elmo |

Ogni Slot contiene 1 solo oggetto. Equipaggiare o togliere un oggetto costa 1 AP, tranne per lo Slot Body, che richiede 1 minuto.

## Assegnare Magic Items

Quando assegni un Magic Item a un PG, il suo Magic Power dovrebbe essere al massimo pari a metà del livello del PG, arrotondata per eccesso (come la Combat Mastery).

??? example "Esempio"
    A un PG di livello 5 si può assegnare un oggetto con Magic Power 3.

!!! note "Nota"
    Anche gli NPC dovrebbero avere oggetti con Magic Power non superiore a metà del loro livello, e gli NPC che creano oggetti non dovrebbero applicare Magic Properties oltre quel limite.

## Struttura di un Magic Item

- **References:** Name; Item (forma e Slot, ad esempio "Dagger, Held", "Armor, Body"); Tags (Attunement, Consumable, requisiti); Magic Power (con l'eventuale indicazione Artifact o Cursed); Charges.
- **Details:** aspetto, descrizione e lore dell'oggetto, da adattare alla campagna.
- **Capabilities:** statistiche (danni, proprietà della Weapon o dell'Armor, Defense) e Magic Properties, ciascuna con il proprio Magic Power tra parentesi nel titolo.
