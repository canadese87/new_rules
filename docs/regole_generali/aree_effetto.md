# Areas of Effect

Un'Area of Effect rappresenta una zona coperta da un effetto, come un Arc, un'Aura, un Cone, una Line, un Ring, una Sphere o una Zone.

**Point of Origin:** il Point of Origin di un'Area of Effect è sempre 1 Space, da cui l'area si estende (Arc, Cone, Line o Wall) o su cui è centrata (Aura, Ring o Sphere). Se l'Area of Effect non può essere centrata su 1 Space, è invece centrata sui 4 Spaces più centrali.

??? example "Esempio"
    Su una mappa a griglia, una Sphere con diametro di 3 Spaces è larga 3 Spaces e il suo centro è 1 Space. Una Sphere con diametro di 6 Spaces è larga 6 Spaces e il suo centro sono i 4 Spaces più centrali, perché non esiste un singolo Space che si trovi esattamente al centro.

## Arc

Un Arc forma quasi un semicerchio. La dimensione di un Arc è espressa come un raggio in Spaces che si estende in un arco di 180° dal Point of Origin, in una direzione a tua scelta. L'altezza di un Arc è 1 Space. Il Point of Origin di un Arc non è incluso nella sua Area of Effect.

## Aura

La dimensione di un'Aura indica il suo raggio in Spaces. Un'Aura si estende in linea retta in tutte le direzioni da una creatura o da un oggetto, ma non attraverso Full Cover, e si muove con esso per tutta la durata. La fonte dell'Aura sceglie se il Point of Origin è soggetto agli effetti dell'Aura.

## Cone

Un Cone si estende per 90° dal suo Point of Origin, in una direzione a tua scelta. La dimensione di un Cone indica la sua lunghezza in Spaces. Un Cone diventa più alto e più largo man mano che si allunga. Il Point of Origin di un Cone non è incluso nella sua Area of Effect.

## Line

La dimensione di una Line indica la sua lunghezza in Spaces. Una Line è alta e larga 1 Space (salvo diversa indicazione) e si estende dal suo Point of Origin in una direzione a tua scelta. Il Point of Origin di una Line non è incluso nella sua Area of Effect.

**Wall:** un Wall è una Line che si estende verticalmente verso l'alto o verso il basso per un numero specificato di Spaces.

## Ring

La dimensione di un Ring indica il suo diametro in Spaces. Un Ring si estende orizzontalmente in tutte le direzioni dal suo Point of Origin, ma non attraverso Full Cover. L'area di un Ring è alta 1 Space e comprende solo gli Spaces al bordo del suo diametro (non l'interno). Il Point of Origin di un Ring non è incluso nella sua Area of Effect.

**Ringwall:** un Ringwall è un Ring che si estende verticalmente verso l'alto o verso il basso per un numero specificato di Spaces dal bordo del suo diametro.

## Sphere

La dimensione di una Sphere indica il suo diametro in Spaces. Una Sphere si estende orizzontalmente in tutte le direzioni dal suo Point of Origin, ma non attraverso Full Cover. Il Point of Origin di una Sphere è incluso nella sua Area of Effect.

**Cylinder:** un Cylinder è una Sphere che si estende verticalmente verso l'alto o verso il basso per un numero specificato di Spaces dal bordo del suo diametro.

**Dome:** un Dome è una Sphere cava la cui area comprende solo gli Spaces al bordo della sua superficie curva (non l'interno).

## Zone

Una Zone è una serie di Spaces collegati tra loro. Ogni Space di una Zone deve essere adiacente perpendicolarmente ad almeno 1 altro Space della Zone. La dimensione di una Zone indica il numero totale dei suoi Spaces. Una Zone si estende dal suo Point of Origin in una direzione a tua scelta. Il Point of Origin di una Zone non è incluso nella sua Area of Effect.
