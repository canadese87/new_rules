# Regole degli Spell

Il sistema di magia comprende:

- **Spell**: effetti magici che infliggono danni, curano ferite, alterano il terreno o influenzano le menti.
- **Spell Enhancement**: modifiche che aumentano Range, area, durata o potenza di uno Spell.

## Spells Known

Le Spellcaster Class (Bard, Cleric, Druid, Sorcerer, Spellblade\*, Warlock e Wizard) conoscono un numero di Spell pari a quanto indicato nella colonna Spells Known della propria tabella di Class, più gli Spell appresi tramite Class Feature, Talent o progressione dello Spellcaster Path (vedi [Character Paths](../personaggio/paths.md)).

### Spell List

Ogni Spellcaster Class ha una propria Spell List, che specifica i tipi di Spell che può apprendere. Le Martial Class possono ottenere accesso a una Spell List tramite la progressione dello Spellcaster Path o il Talent Spellcasting Expansion (vedi [Talents](../personaggio/talents.md)).

??? example "Esempio"
    La Class Wizard indica Arcane come Spell che può apprendere. Quando il Wizard apprende Spell dalla propria Class, dal 1° livello in poi, deve sceglierli tra gli Spell che hanno Arcane tra le Source (vedi Sources of Magic più avanti). Se ottiene un'altra Spell Source tramite il Talent Spellcaster Expansion, può apprendere nuovi Spell da qualsiasi sua Spell Source.

## Risorse degli Spell

Ogni Spell ha un numero minimo di Action Points (AP) che devono essere spesi per lanciarlo. Molti Spell richiedono inoltre un numero minimo di Mana Points (MP) da spendere per lanciarli. Questo valore è detto Base Mana Cost dello Spell.

### Action Points

Lanciare qualsiasi Spell richiede di spendere Action Points (AP). Gli Spell che influenzano un singolo bersaglio costano di norma 1 AP, quelli che influenzano più bersagli di norma 2 AP.

### Mana Points

Alcuni Spell hanno un costo in MP che devi spendere per lanciarli. La quantità massima di MP che puoi spendere per un singolo Spell deve essere pari o inferiore al tuo Mana Spend Limit (vedi [Combat Resources](../combattimento/risorse.md)).

!!! note "Nota"
    Il Mana Spend Limit è pari alla tua Combat Mastery.

## Caratteristiche degli Spell

### Components

Uno Spell può avere 3 tipi di Component: Verbal, Somatic e Material. Tutti gli Spell richiedono Component Verbal e Somatic, salvo diversa indicazione. Alcuni rari Spell richiedono Component Material. Per lanciare uno Spell devi soddisfarne i Component, come descritto di seguito.

#### Verbal

Parole e formule magiche necessarie a manifestare gli effetti dello Spell: il personaggio pronuncia alcune parole o emette un suono per lanciarlo.

- Le creature che possono sentirti si accorgono che stai lanciando uno Spell.
- Se sei ridotto al silenzio con mezzi magici o ordinari (lo Spell Muffle o un bavaglio), non puoi lanciare Spell con Component Verbal.
- Puoi comunque parlare sott'acqua per lanciare uno Spell, ma perdi il respiro (vedi Breath in [Environment](../regole_generali/ambiente.md)).

#### Somatic

Gesti, movimenti e azioni fisiche necessari a controllare le energie magiche dello Spell: il personaggio muove visibilmente le mani durante il lancio.

- Le creature che possono vederti si accorgono che stai lanciando uno Spell.
- Per soddisfare il Component Somatic devi poter muovere almeno una mano che non tenga un oggetto, oppure avere uno Spell Focus.

#### Material

Oggetti, ingredienti o altri elementi fisici necessari a lanciare lo Spell. La maggior parte degli Spell non richiede Component Material; quelli che li richiedono di solito hanno un costo elevato in monete d'oro o usano un oggetto la cui rarità è stabilita dal GM.

- Non puoi lanciare questi Spell senza il Component Material.
- Se lo Spell consuma il Component Material, devi sostituirlo prima di poterlo lanciare di nuovo.
- Il Component può avere un costo elevato in monete d'oro o essere raro da ottenere.

!!! note "Nota"
    Un giocatore può descrivere Component Material inventati per il solo colore (ad esempio la bava di rana per lo Spell Grease). Questi Component di colore non vanno usati contro il giocatore dal GM, a meno che il giocatore non voglia tenere traccia della quantità di Component posseduti.

### Duration

Gli Spell possono avere durata istantanea o continua, e alcuni Spell devono essere mantenuti con Sustain per proseguire (vedi Sustained Action in [Actions](../combattimento/azioni.md)).

- **Instantaneous:** gli Spell istantanei hanno effetto nel momento in cui vengono eseguiti.
- **Continuous:** questi Spell durano per un tempo specificato. Spesso terminano prima quando la creatura influenzata supera (Success) un Save successivo contro l'effetto, quando essa o un'altra creatura entro 1 Space effettua un'Action per terminare l'effetto, o quando si verifica un altro metodo indicato per terminare l'effetto (ad esempio l'interruzione della linea di vista).
- **Sustained:** alcuni effetti devono essere mantenuti con Sustain, altrimenti terminano.

### Range

È la distanza entro cui deve trovarsi un bersaglio dello Spell, o l'origine della sua Area of Effect. Quando scegli i bersagli dello Spell, devono trovarsi entro la Range indicata e soddisfare ogni altro requisito indicato dallo Spell (ad esempio essere visibili o in grado di sentirti). Se lo Spell usa un'Area of Effect per determinare i bersagli, l'origine dello Spell deve trovarsi entro la Range indicata (vedi [Areas of Effect](../regole_generali/aree_effetto.md)).

## Lanciare uno Spell

Per lanciare uno Spell devi conoscerlo e spendere la quantità di risorse richiesta (Action Points e Mana Points). Quando lanci uno Spell devi effettuare un Check (ad esempio un Attack Check o uno Spell Check) per determinarne il grado di successo o fallimento. Il Check viene confrontato con la Defense del bersaglio (ad esempio PD o AD), con il DC dello Spell o con il Contested Check del bersaglio.

## Enhancement

### Spell Enhancements

Gli Spell Enhancement ti permettono di spendere AP o MP aggiuntivi per aumentare la potenza dello Spell (ad esempio danni, durata, Range, numero di bersagli o Area of Effect). Gli Spell Enhancement sono specifici di ciascuno Spell e sono riportati nella sua descrizione.

### Eseguire uno Spell Enhancement

Quando esegui uno Spell, puoi spendere MP aggiuntivi per aggiungere uno Spell Enhancement allo Spell. Se lo Spell richiede un Check (ad esempio un Attack Check o uno Spell Check), devi scegliere di aggiungere lo Spell Enhancement prima di effettuare il Check. Puoi eseguire lo stesso Spell Enhancement più volte per Spell, salvo diversa indicazione.

**Mana Points sugli AP Enhancement:** puoi spendere 1 MP per aggiungere a uno Spell AP Enhancement per un valore di 2 AP. Puoi farlo più volte per Spell.

??? example "Esempio"
    Uno Spell ha un AP Enhancement chiamato Damage che permette di spendere 1 AP per aumentare i danni dello Spell di 1. In alternativa, puoi spendere 1 MP per aggiungere AP Enhancement per un valore di 2 AP, ad esempio scegliendo Damage due volte (+2 danni in totale).

### Danni degli Enhancement

Se un Enhancement infligge danni, infligge lo stesso tipo di danni dello Spell che stai usando per effettuare l'Attack o lo Spell, salvo diversa indicazione.

## Categorie degli Spell

Ogni Spell è classificato secondo 3 categorie distinte: Source, School e Tags.

## Sources of Magic

Le Sources of Magic rappresentano l'origine della magia. Tutti gli Spell traggono potere da almeno una delle tre Source fondamentali: Arcane, Divine o Primal. Le Source determinano come uno Spellcaster accede alla magia e la incanala. Alcuni Spell indicano 2 o più Source (ad esempio Arcane e Primal per molti Spell di fuoco).

### Arcane

La magia Arcane è l'energia invisibile che permea tutta l'esistenza: un'energia pura e senza forma che può essere plasmata tramite studio, concentrazione e disciplina (formule, rune e rituali).

### Divine

La magia Divine trae potere da esseri divini (buoni, malvagi o indifferenti), come divinità maggiori e minori, i loro seguaci (angeli, arconti, ecc.) o le manifestazioni di concetti universali astratti (ordine, amore, pace, guerra, ecc.). Viene concessa ai mortali tramite fede, dovere o disperazione.

### Primal

La magia Primal trae potere dalle forze fisiche dell'universo (terra, aria, acqua, fuoco, piante, animali e persino i piani stessi) e dalle energie elementali del mondo.

## Schools of Magic

Le Schools of Magic classificano gli effetti magici in base a due criteri: il tipo di azione compiuta dallo Spell (ad esempio creare, evocare, alterare o distruggere) e il soggetto su cui viene compiuta (ad esempio gli elementi, il tempo, o il corpo, la mente o lo spirito di una creatura).

### Astromancy

Magia dello spazio, del tempo e della gravità. Appartengono a questa School gli Spell che alterano la gravità (invertendola, diminuendola o aumentandola), teletrasportano oggetti o creature (direttamente o tramite portali) o alterano il flusso del tempo (invertendolo, rallentandolo, accelerandolo o fermandolo).

**Spell Tags comuni:** Gravity, Motion, Teleportation, Time, Planes.

### Conjuration

Magia che evoca cose da un luogo a un altro o le fabbrica dal nulla. Appartengono a questa School gli Spell che evocano creature, creano oggetti o illusioni nell'ambiente.

**Spell Tags comuni:** Earth, Illusion, Light, Scent, Sound, Summoning, Weapon.

### Divination

Magia che rivela l'ignoto e l'invisibile, come conoscenze nascoste (passate, presenti o future) e visioni speciali (dell'invisibile, dell'illusorio o di luoghi lontani). Appartengono a questa School gli Spell che conferiscono vista magica, conoscenza o capacità di discernere la verità.

**Spell Tags comuni:** Communication, Emotions, Knowledge, Sense, Thoughts.

### Elemental

Magia degli elementi naturali, come terra, vento, fuoco, acqua, fulmine e corrosione. Appartengono a questa School gli Spell che producono effetti di manipolazione degli elementi.

**Spell Tags comuni:** Air, Corrosion, Earth, Fire, Lightning, Water.

### Enchantment

Magia che influenza la mente di altre creature, ad esempio provocando emozioni forti o dominio mentale. Appartengono a questa School gli Spell che creano illusioni nella mente di una creatura o affascinano altre creature con terrore, lealtà o amore artificiali.

**Spell Tags comuni:** Embolden, Emotions, Illusion, Psychic, Sense, Thoughts.

### Invocation

Magia dell'energia positiva, come luce, vita, guarigione e resurrezione. Appartengono a questa School gli Spell che creano luce, curano ferite, guariscono malattie, creano spiriti o resuscitano i morti.

**Spell Tags comuni:** Cleansing, Healing, Light, Radiant, Resurrection, Spirit.

### Nullification

Magia dell'energia negativa, come antimagia, anti-vita e oscurità. Appartengono a questa School gli Spell che distruggono magia, spiriti e luce.

**Spell Tags comuni:** Anti-Magic, Shadow, Spirit, Umbral.

### Transmutation

Magia che trasforma fisicamente una cosa in un'altra. Appartengono a questa School gli Spell che trasformano creature in altre creature (o oggetti in altri oggetti o creature).

**Spell Tags comuni:** Earth, Embolden, Metamorphosis, Motion, Sense, Weapon.

## Spell Tags

Gli Spell Tags descrivono le caratteristiche di uno Spell. Alcuni Tag rappresentano effetti concreti nel mondo di gioco (ad esempio la manipolazione del fuoco), altri esistono principalmente per supportare le meccaniche di gioco (ad esempio un tipo di creatura che lo Spell può bersagliare). Gli Spell Tags definiscono come uno Spell interagisce con il sistema di gioco: i danni che infligge, le Condition che applica o le creature che influenza. Alcuni Ancestry Trait, Class Feature e Talent fanno riferimento a specifici Spell Tags.

| Tag | Descrizione |
|---|---|
| Ailment | Infligge effetti biologici dannosi come malattie (Diseases) o veleni (Poisons). |
| Air | Manipola il vento e il cielo: crea raffiche, solleva creature, disperde gas o permette il volo e la levitazione. |
| Antimagic | Sopprime, dissolve o annulla effetti magici, oggetti magici o la capacità di lanciare Spell di una creatura. |
| Blood | Manipola l'essenza vitale di una creatura, estraendola, rafforzandola o usandola come mezzo di potere. Spesso associato alla magia sacrificale o allo scambio di vitalità. |
| Bludgeoning | Infligge danni da forza contundente tramite magia concussiva, onde d'urto, detriti in caduta o martelli evocati. |
| Chaos | Scatena effetti magici imprevedibili, impulsi selvaggi o forze incontrollabili, con esiti casuali e instabili. |
| Cleansing | Rimuove effetti dannosi, Conditions, Curses, Diseases o Poisons. |
| Cold | Sottrae calore per congelare i bersagli, rallentarne il movimento o ricoprire oggetti di brina e ghiaccio. |
| Communication | Permette di trasmettere pensieri, parole o immagini a distanza o superando le barriere linguistiche. |
| Conditions | Applica la Condition specificata o interagisce con essa, ad esempio Stunned, Frightened o Restrained. |
| Corrosion | Disgrega la materia fisica tramite acido o decomposizione, dissolvendo barriere, armature o persino la carne. |
| Creature Type | Bersaglia o influenza il Creature Type specificato, o interagisce con esso, ad esempio Dragon, Fiend, Humanoid o Undead. |
| Curse | Applica una debilitazione magica o una maledizione di lunga durata, che spesso richiede mezzi speciali per essere rimossa. |
| Death | Riguarda direttamente la fine della vita: prosciuga la vitalità, avvizzisce la carne o accompagna un'anima nell'aldilà. Questi Spell possono anche arrestare la morte, impedire la resurrezione o interagire con la non-morte. |
| Earth | Sfrutta pietra, suolo e metallo per modellare il terreno, formare barriere, imprigionare nemici o rafforzare le difese. |
| Embolden | Potenzia magicamente le capacità di una creatura, migliorandone statistiche, tiri o altri valori numerici. |
| Emotions | Legge, influenza o altera lo stato emotivo di un bersaglio, ad esempio placando la rabbia o incutendo paura. |
| Enfeeble | Ostacola magicamente le capacità di una creatura, riducendone statistiche, tiri o altri valori numerici. |
| Fire | Incanala fiamme per bruciare i nemici, incendiare l'ambiente o emettere calore intenso. |
| Forge | Crea, altera o potenzia materiali fisici, in particolare metallo, pietra e oggetti lavorati. Può generare armi, rinforzare armature o modellare materie prime in strumenti o strutture. |
| Gravity | Manipola la forza di gravità, permettendo di controllare cadute, levitazione o peso schiacciante. |
| Healing | Ripristina punti ferita o aumenta l'efficacia di altri effetti o Spell di guarigione. |
| Illusion | Crea input sensoriali falsi (immagini, suoni, sensazioni) che appaiono reali ai sensi. |
| Knowledge | Rivela informazioni nascoste, intuizioni, ricordi o verità sul mondo o su un bersaglio. |
| Light | Crea o manipola la luce, o interagisce con essa, spesso per la visione, la distrazione o l'illuminazione. |
| Lightning | Scatena energia elettrica per folgorare, stordire o concatenare danni tra più nemici. |
| Madness | Attacca la mente con confusione, allucinazioni, ossessioni o disperazione, incrinando la percezione della realtà di una creatura. Spesso legato a conoscenze proibite o influenze ultraterrene. |
| Metamorphosis | Cambia la forma, il movimento o le capacità di una creatura, ad esempio volare, arrampicarsi o trasformarsi completamente. |
| Motion | Permette o costringe creature od oggetti a spostarsi da uno spazio a un altro, incluse spinte, trazioni e balzi. |
| Piercing | Infligge danni fisici penetranti e concentrati, spesso legati a proiettili magici come dardi, frecce o spuntoni evocati. |
| Planes | Collega altri piani di esistenza o interagisce con essi. |
| Plants | Manipola o anima la vita vegetale, ad esempio liane che intrappolano, radici che avviluppano o flora che fiorisce di energia magica. |
| Poison | Incanala veleni, tossine o venefici per alterare le funzioni corporee e danneggiare gli organi. |
| Psychic | Attacca direttamente la mente con pensieri violenti, illusioni o dolore emotivo. |
| Radiant | Invoca una luce divina purificatrice per danneggiare i nemici o dissolvere l'oscurità. |
| Resurrection | Riporta in vita, parzialmente o completamente, una creatura morta. |
| Scent | Genera o manipola odori, utili per seguire tracce, distrarre o caratterizzare l'ambiente. |
| Sense | Rivela cose nascoste, individua magia o creature, o impedisce l'individuazione con mezzi magici. |
| Shadow | Manipola l'oscurità o oscura la luce, spesso legato alla magia furtiva. |
| Slashing | Infligge danni fisici da taglio ampi, tipicamente associati ad attacchi magici con lame o fendenti. |
| Sound | Crea, manipola o imita suoni, dai sussurri ai boati tonanti. |
| Spirit | Interagisce con le anime dei vivi o dei morti, inclusi comunicazione, guida o vincolo. |
| Strike | Potenzia gli attacchi marziali con forza magica, danni elementali o effetti soprannaturali. |
| Summoning | Richiama temporaneamente creature, oggetti o costrutti in aiuto dell'incantatore. |
| Teleportation | Trasporta istantaneamente creature od oggetti da un luogo a un altro, aggirando gli ostacoli. |
| Thoughts | Legge, altera o comunica direttamente con la mente cosciente di una creatura. |
| Time | Influenza lo scorrere del tempo, rallentando, accelerando o alterando la tempistica degli eventi. |
| Trap | Crea effetti magici o fisici che si attivano quando si verificano determinate condizioni o quando si entra in un'area. |
| Umbral | Sfrutta il potere dell'ombra profonda e dell'oscurità magica, spesso con effetti sinistri, oscuranti o indebolenti. |
| Ward | Conferisce difese magiche, Resistance, riduzioni dei danni o Immunity a effetti specifici. |
| Water | Controlla i liquidi in tutte le loro forme (onde, correnti o prigioni di ghiaccio), per attacco o supporto. |
| Weapon | Crea, potenzia o trasforma magicamente armi, per una breve durata o per un uso specifico. |

## Advanced Spellcasting

### Spell Duel

**Prerequisito:** Spellcasting Path

Durante uno Spell Duel, la creatura che lancia lo Spell è detta Caster e la creatura che vi si oppone è detta Challenger.

Se più creature tentano di iniziare uno Spell Duel, una di esse deve essere scelta come Challenger, mentre le altre la assistono tramite Combo Casting. Anche altre creature possono scegliere di assistere il Caster quando viene iniziato uno Spell Duel (vedi Combo Spellcasting più avanti).

**Trigger:** vedi lanciare un MP Effect, purché il Caster o un bersaglio si trovi entro 5 Spaces da te.

**Reaction:** puoi spendere una quantità di AP e 1 o più MP (fino al tuo Mana Spend Limit) per tentare di fermare l'MP Effect del Caster. La quantità di AP spesa è pari al costo base in AP dell'MP Effect che stai tentando di fermare.

**Contest:** effettui uno Spell Check contrapposto allo Spell Check o allo Spell Attack che il Caster effettua per lanciare il suo MP Effect. Se l'MP Effect del Caster non richiede un Check, il Caster deve effettuare uno Spell Check come Reaction nell'ambito dello Spell Duel. Ai fini dello Spell Duel, il Caster e il Challenger ottengono ciascuno un bonus al proprio Check pari al doppio degli MP spesi da ciascuno.

!!! note "Nota"
    Poiché i nemici non hanno costi in MP per i loro MP Effect, si assume che i loro MP Effect costino una quantità di MP pari alla metà del loro Level (arrotondata per eccesso).

**Esiti:**

- **Success:** l'MP Effect del Caster fallisce e non ha alcun effetto.
- **Failure:** l'MP Effect del Caster riesce e ha effetto. Il bonus al Check ottenuto dagli MP spesi non si applica ai Success e Failure Statement dell'MP Effect.
- **Tie (pareggio):** l'MP Effect del Caster fallisce, non ha alcun effetto, e ciascuno di voi tira sulla Wild Magic Table. L'effetto della tabella dura finché non è trascorso 1 Round.
- **Resources Lost:** qualunque sia il risultato, ogni creatura spende comunque normalmente tutti gli AP, gli MP o le altre risorse.

??? example "Esempio"
    Un Caster effettua uno Spell Attack basato su MP e un Challenger tenta di fermarlo. Lo Spell Attack del Caster costa 1 AP e 2 MP. Il Challenger deve spendere 1 AP e almeno 1 MP per tentare di fermarlo. Il Caster effettua un Attack Check (poiché è uno Spell Attack) e il Challenger uno Spell Check. Il Caster ottiene +4 all'Attack Check (2 MP spesi) e il Challenger +2 allo Spell Check (1 MP speso). Se il Caster vince il Contest, il suo MP Effect ha effetto, ma il bonus di +4 dagli MP spesi non viene contato per determinare se ottiene un Heavy Hit o superiore.

### Wild Magic Table

| d20 | Wild Surge Outcome |
|---|---|
| 1 | Ti trasformi in una creatura piccola con le statistiche di una pecora (HP 2, PD & AD 5, Melee Attack +2, Damage 1). |
| 2 | Un'onda di magia esplode da te. Subisci danni True pari al tuo Prime Modifier e le creature entro 5 Spaces devono superare un Physical Save contro il tuo Save DC o subire la stessa quantità di danni. |
| 3 | Sei **Stunned 3**. |
| 4 | Sei sopraffatto da un'ondata di letargia. Hai DisADV a tutti i Check e i Save. |
| 5 | Sei **Stunned 1**. |
| 6 | Sei **Blinded** e **Deafened**. |
| 7 | Tutte le creature viventi diventano **Invisible** per te. |
| 8 | Ottieni una penalità di d4 a tutti i Check e i Save. |
| 9 | Cresci di 1 taglia (size), diventi 2 volte più pesante e la tua Speed si riduce di 2. |
| 10 | Da te si origina una forte attrazione gravitazionale. Tutte le creature entro 5 Spaces devono effettuare un Might Save o essere trascinate di 4 Spaces verso di te. |
| 11 | Venti violenti si sprigionano da te in tutte le direzioni. Tutte le creature entro 5 Spaces (eccetto te) devono effettuare un Might Save o essere spinte di 4 Spaces lontano da te. |
| 12 | Cresci di 1 Size, diventi una volta e mezza più pesante e la tua Speed aumenta di 2. |
| 13 | Ottieni un bonus di d4 a tutti i Check e i Save. |
| 14 | Ottieni Truesight di 10 Spaces. |
| 15 | Diventi **Invisible**. |
| 16 | I tuoi AP massimi aumentano di 1 e ottieni 1 AP. |
| 17 | Sei pieno di energia. Hai ADV a tutti i Check e i Save. |
| 18 | Ottieni un'ondata di potere che ti conferisce +5 a tutti gli Spell Check che effettui. |
| 19 | Trabocchi di energia vitale. Tu e le creature entro 5 Spaces recuperate HP pari al tuo Prime Modifier. |
| 20 | Ti trasformi in una creatura grande con le statistiche di un Young Purple Dragon, ma senza Breath Weapon (HP 30, PD & AD 16, Attack +10, Damage 4, Fly Speed 6). |

### Combo Spellcasting

**Prerequisito:** Spellcasting Path

Durante un Combo Casting, la creatura che lancia l'MP Effect è detta Caster, mentre le altre creature che la assistono sono dette Participants.

**Trigger:** vedi lanciare un MP Effect che conosci o iniziare uno Spell Duel, purché il Caster dell'MP Effect o almeno 1 dei suoi bersagli si trovi entro 5 Spaces da te.

**Reaction:** puoi spendere una quantità di AP pari al costo base in AP dell'MP Effect che stai tentando di assistere (o di fermare, nel caso di uno Spell Duel). Quando lo fai, l'MP Effect ottiene un bonus di +2 al suo Check e al suo Save DC per questo turno. Se partecipi a uno Spell Duel, il Challenger che stai aiutando ottiene questo bonus al proprio Check per determinare il vincitore del Contest.

**Spendere MP:** puoi scegliere di spendere 1 o più MP per aggiungere MP Enhancement all'MP Effect del Caster. Il totale degli MP spesi sull'MP Effect non può superare il Mana Spend Limit del Caster.

??? example "Esempio"
    I Caster A e B hanno ciascuno un Mana Spend Limit di 3. A spende 1 AP e 1 MP per lanciare lo Spell Fire Bolt. B può spendere 1 AP e 2 MP come Reaction per aggiungere MP Enhancement per un valore di 2 MP allo Spell di A. A ottiene quindi un bonus di +2 al proprio Spell Attack e al Save DC per quello Spell.
