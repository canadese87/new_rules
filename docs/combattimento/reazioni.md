# Reactions

Le Reactions sono Actions che una creatura può compiere durante il turno di un'altra creatura. Una creatura non può compiere una Reaction nel proprio turno, a meno che la Reaction non le permetta di farlo in risposta alla Reaction di un'altra creatura. Le Reactions non sono soggette al Multiple Check Penalty.

## Taking a Reaction

Una creatura può compiere una Reaction nel turno di un'altra creatura se soddisfa i requisiti per farlo. I requisiti di una Reaction sono indicati nelle sue voci Prerequisite e Trigger. Puoi compiere solo 1 Reaction per Trigger.

??? example "Esempio"
    1. Quando una creatura esce dalla portata di un PC Martial, il PC può effettuare un solo Opportunity Attack contro di essa (può comunque spendere AP per applicare Martial Enhancements all'Opportunity Attack).
    2. Quando un Attack viene effettuato entro 1 Space da un PC Martial, il PC può usare la Maneuver Parry contro l'Attack (1° Trigger). Se l'Attack colpisce comunque (2° Trigger), il PC può usare la Maneuver Protection per condividere i danni con il bersaglio.

**Multiple Reactions:** una creatura può spendere Action Points per compiere più Reactions, purché soddisfi tutte le condizioni e possa spendere risorse sufficienti.

## Reaction Requirements

**Prerequisite:** indica la Feature (Martial Feature, Spellcasting Feature o un'altra Feature) necessaria per accedere alla Reaction.

**Trigger:** indica le condizioni che devono verificarsi perché una creatura possa compiere la Reaction.

## Spending Resources

Se una Reaction ha un costo in risorse (Action Points, Mana Points, Stamina Points, ecc.), la creatura deve spendere quelle risorse per compierla.

**Regaining Resources:** le Reactions permettono a una creatura di spendere Action Points durante il turno di un'altra creatura. Se una creatura spende Action Points, avrà meno Action Points da spendere nel suo turno successivo. Gli Action Points spesi non vengono recuperati fino alla fine del turno della creatura.

??? example "Esempio"
    Se compi una Reaction spendendo 1 Action Point, nel tuo turno successivo avrai solo 3 Action Points (4 - 1 = 3).

!!! note "Nota"
    Se spendi tutti e 4 i tuoi AP prima del tuo turno, all'inizio del turno successivo avrai 0 AP. Non potendo fare nulla, il tuo turno termina immediatamente e recuperi i tuoi 4 AP.

## Types of Reactions

### Opportunity Attack

**Prerequisite:** Martial Path

**Trigger:** una creatura che puoi vedere entro la tua Melee Range usa il proprio movimento per uscire dalla tua Melee Range, estrae una Weapon o uno Spell Focus, raccoglie un oggetto da terra o compie l'Action Object.

**Reaction:** puoi spendere 1 AP per effettuare un Melee Martial Attack contro la creatura che ha provocato la Reaction.

!!! note "Nota"
    Puoi spendere AP aggiuntivi per ottenere ADV o per eseguire Maneuvers con l'Attack.

### Spell Duel

**Prerequisite:** Spellcasting Path

Durante uno Spell Duel, la creatura che lancia lo Spell è detta Caster e la creatura che si oppone è detta Challenger.

Se più creature tentano di iniziare uno Spell Duel, una di esse deve essere scelta come Challenger, mentre le altre la assistono tramite Combo Casting. Anche altre creature possono scegliere di assistere il Caster quando viene iniziato uno Spell Duel (vedi Combo Spellcasting in [Spellcaster Chapter](../magia/regole.md)).

**Trigger:** vedi un MP Effect mentre viene lanciato, purché il Caster o un bersaglio si trovi entro 5 Spaces da te.

**Reaction:** puoi spendere una quantità di AP e 1 o più MP (fino al tuo Mana Spend Limit) per tentare di fermare l'MP Effect del Caster. La quantità di AP spesa è pari al costo base in AP dell'MP Effect che stai tentando di fermare.

**Contest:** effettui uno Spell Check contrastato dallo Spell Check o dallo Spell Attack che il Caster effettua per lanciare il suo MP Effect. Se l'MP Effect del Caster non richiede un Check, il Caster deve effettuare uno Spell Check come Reaction nell'ambito dello Spell Duel. Ai fini dello Spell Duel, il Caster e il Challenger ottengono ciascuno un bonus al proprio Check pari al doppio degli MP spesi da ciascuno.

!!! note "Nota"
    Poiché i nemici non hanno costi in MP per i loro MP Effects, puoi considerare che i loro MP Effects costino una quantità di MP pari a metà del loro livello (arrotondata per eccesso).

**Outcomes:**

- **Success:** l'MP Effect del Caster fallisce e non ha alcun effetto.
- **Failure:** l'MP Effect del Caster riesce e ha effetto. Il bonus al Check ottenuto dagli MP spesi non si applica agli Success e Failure Statements dell'MP Effect.
- **Tie:** l'MP Effect del Caster fallisce, non ha alcun effetto, e ciascuno di voi tira sulla Wild Magic Surge Table (vedi sotto). L'effetto della tabella dura finché non è trascorso 1 Round.

**Resources Lost:** qualunque sia il risultato, ogni creatura spende comunque tutti gli AP, MP o altre risorse normalmente.

??? example "Esempio"
    Un Caster effettua uno Spell Attack basato su MP e un Challenger tenta di fermarlo. Lo Spell Attack del Caster costa 1 AP e 2 MP. Il Challenger deve spendere 1 AP e almeno 1 MP per tentare di fermarlo. Il Caster effettua un Attack Check (poiché è uno Spell Attack) e il Challenger uno Spell Check. Il Caster ottiene +4 all'Attack Check (2 MP spesi) e il Challenger +2 allo Spell Check (1 MP speso). Se il Caster vince il Contest, il suo MP Effect ha effetto, ma il bonus di +4 derivante dagli MP spesi non si conta per stabilire se ottiene un Heavy Hit o superiore.

## Wild Magic Table

| d20 | Wild Surge Outcome |
|---|---|
| 1 | Ti trasformi in una creatura piccola con le statistiche di una pecora (HP 2, PD e AD 5, Melee Attack +2, Damage 1). |
| 2 | Un'onda di magia esplode da te. Subisci danni True pari al tuo Prime Modifier e le creature entro 5 Spaces devono superare un Physical Save contro la tua Save DC o subire la stessa quantità di danni. |
| 3 | Sei **Stunned 3**. |
| 4 | Vieni sopraffatto da un'ondata di letargia. Hai DisADV su tutti i Checks e Saves. |
| 5 | Sei **Stunned 1**. |
| 6 | Sei **Blinded** e **Deafened**. |
| 7 | Tutte le creature viventi diventano **Invisible** per te. |
| 8 | Subisci una penalità di d4 a tutti i Checks e Saves. |
| 9 | Cresci di 1 Size, diventi 2 volte più pesante e la tua Speed si riduce di 2. |
| 10 | Una forte attrazione gravitazionale si origina da te. Tutte le creature entro 5 Spaces devono effettuare un Might Save o essere attirate di 4 Spaces verso di te. |
| 11 | Venti violenti si sprigionano da te in tutte le direzioni. Tutte le creature entro 5 Spaces (tranne te) devono effettuare un Might Save o essere spinte di 4 Spaces lontano da te. |
| 12 | Cresci di 1 Size, diventi una volta e mezza più pesante e la tua Speed aumenta di 2. |
| 13 | Ottieni un bonus di d4 a tutti i Checks e Saves. |
| 14 | Ottieni Truesight di 10 Spaces. |
| 15 | Diventi **Invisible**. |
| 16 | I tuoi AP massimi aumentano di 1 e ottieni 1 AP. |
| 17 | Vieni energizzato. Hai ADV su tutti i Checks e Saves. |
| 18 | Ottieni un'ondata di potere che ti concede +5 a tutti gli Spell Checks che effettui. |
| 19 | Trabocchi di energia vitale. Tu e le creature entro 5 Spaces recuperate HP pari al tuo Prime Modifier. |
| 20 | Ti trasformi in una creatura grande con le statistiche di un Young Purple Dragon, ma senza Breath Weapon (HP 30, PD e AD 16, Attack +10, Damage 4, Fly Speed 6). |
