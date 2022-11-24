---
# Title, summary, and page position.
linktitle: Riprenditelo!
summary: "Riprenditelo! è la dodicesima missione principale del gioco. Si svolge tra la Cittadella e il Jefferson Memorial ed è data da Lyons l'Anziano."
weight: 40
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Riprenditelo!
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni principali di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

*Riprenditelo!* è la dodicesima missione principale del gioco. Si svolge tra la Cittadella e il Jefferson Memorial ed è data da Lyons l'Anziano.



```mermaid
graph TD;
    id1[<b>Riprenditelo!</b>]:::questfo3
    id2[Preparati per la battaglia, <br />quindi fai rapporto a Sarah Lyons]
    id3[Segui Liberty Prime mentre <br />si fa strada verso <br />il Progetto purezza]
    id4[Combatti fino alla rotonda <br />e parla con il colonnello Autumn]
    id5[Affrontalo e uccidilo]
    id6[Convincilo ad andarsene] 
    id7[Parla con la Dottoressa Li <br />attraverso l'intercom] 
    id8[Sacrificati] 
    id9[Sacrifica <br />Sarah Lyons] 
    id10["Sacrifica un seguace <br />(Broken Steel)"] 
    id11[Non fare nulla] 
    id12[Contamina l'acqua <br />con la fiala di FEV] 
    id13[1200 PE, finale di gioco]:::rewardfo3 
    id14["Prossima missione: <br /><b>Morte dall'alto</b> (Broken Steel)"]:::questfo3
    id15[Completamento <br />del gioco]:::questfo3 
    id16[Karma +2000]:::rewardfo3
    id17[Karma -1000]:::rewardfo3  
    id1-->id2-->id3-->id4-->id5-->id7-->id8-->id12
    id13-->id15
    id13-->id14
    id4-->id6-->id7
    id7-->id9-->id13
    id7-->id10-->id13
    id7-->id11-->id13
    id8-->id16-->id13
    id12-->id17-->id13
    click id14 "../morte-dallalto" %%TODO%%
    classDef rewardfo3 fill:#f1ff8a66, stroke:#56700087;
    classDef questfo3 fill:#5f9bd35e, stroke:#255b8d91;
```


| Tappe |       Stato        | Descrizione                                                    |
| :---: | :----------------: | -------------------------------------------------------------- |
|   1   |                    | Segui Lyons l'Anziano nel Laboratorio della Cittadella.        |
|  10   |                    | Parla con Sarah Lyons per il briefing della missione.          |
|  20   |                    | Preparati per la battaglia, quindi fai rapporto a Sarah Lyons. |
|  30   |                    | Segui Liberty Prime mentre si fa strada verso il purificatore. |
|  40   |                    | Raggiungi la sala di controllo del Progetto purezza.           |
|  50   |                    | Metti in sicurezza la sala di controllo del Progetto purezza.  |
|  60   | :white_check_mark: | Attiva il Progetto purezza!                                    |
|  61   | :white_check_mark: | Avvia il ciclo del compartimento stagno per Sarah.             |
|  65   | :white_check_mark: | Ordina al tuo collaboratore di avviare il purificatore.        |
|       |                    |                                                                |

Note:
- Il DLC Broken Steel inizia dopo che è finita questa missione
  - Con il DLC Broken Steel installato è possibile far entrare nel compartimento stagno un seguace
- Dire a Lyons l'Anziano che il Vault 87 è l'origine dei supermutanti farà guadagnare karma positivo
- Liberty Prime attaccherà qualsiasi carovana, considerandola ostile
- Terminata la missione è possibile che Fawkes resti inottenibile fino a *Chi osa vince*