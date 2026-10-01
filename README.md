# Filettature — Officina

App web per il controllo e la tornitura di filettature metriche, ad uso officina.

## Come usarla

Apri `index.html` in un browser (anche da telefono). Non richiede installazione ne' connessione internet dopo il primo caricamento.

## Moduli

1. **Tampone int.** — calcola le quote per realizzare un tampone maschio passa/non-passa per verificare una filettatura interna (madrevite), col metodo dei tre rulli. Classi disponibili: 5H, 6H, 7H.
2. **Accoppiamento** — confronta le classi di tolleranza vite/madrevite e calcola il gioco risultante sul diametro medio.
3. **Realizz. esterna** — quote sopra i rulli e tabella di tornitura per una filettatura esterna (vite). Classi disponibili: 5g, 6g, 6h, 6e, 7g, 8g, 4g6g.
4. **Realizz. interna** — pre-foro e tabella di tornitura per una filettatura interna (madrevite).

Il diametro nominale e il passo sono liberi: funziona sia per filettature standard ISO sia per filettature speciali (es. M23.3 passo 1.8). Per le combinazioni non standard i valori di tolleranza sono interpolati dai passi standard piu' vicini (etichetta "interpolato"); le classi non tabellate direttamente (5g, 6e, 7g, 8g, 5H, 7H) sono derivate da quelle certificate (6g/6H) con le relazioni note della norma (etichetta "classe stimata"). Le quote nominali/di base sono sempre calcolate in modo esatto.

Usa il pulsante **Stampa / PDF** per esportare la scheda corrente in formato A4 (le quote di passata sono stampate a 18pt, il resto a 14pt).

## Dati di riferimento

Limiti dimensionali secondo ISO 965 / ASME B1.13M (classi 6g, 6h, 4g6g per filettature esterne; 6H per filettature interne). Le altre classi (5g, 6e, 7g, 8g, 5H, 7H) sono stimate a partire da queste, applicando i fattori di grado e le posizioni note della norma ISO 965-1.
