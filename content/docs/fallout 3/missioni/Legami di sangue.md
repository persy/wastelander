---
# Title, summary, and page position.
linktitle: Legami di sangue
summary: ""
weight: 10
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Legami di sangue
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni secondarie di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

*Legami di sangue* è una missione secondaria di Fallout 3. Si svolge tra Arefu e la stazione metropolitana di Meresti ed è data da Lucy West ed Evan King.



```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Legami di sangue</b>):::questfo3
    id2(Parla con Evan King <br />ad Arefu a proposito <br />dei loro problemi <br />con la Famiglia)
    id3(Parla con Lucy West <br />a Megaton e accetta di <br />aiutarla a portare un <br />messaggio ad Arefu)
    id4(Controlla i residenti <br />di Arefu e trova i <br />cadaveri dei West)
    id5(Fai rapporto ad Evan King <br />e trova la Famiglia)
    id6(Cerca nel nascondiglio <br />di Hamilton)
    id7(Cerca al cinema <br />all'aperto Moonbeam) 
    id8(Cerca alla stazione <br />Seneca nord ovest)
    id9(Cerca al deposito <br />di Meresti)
    id10(Trova la Famiglia, <br />convinci Robert a <br />farti passare e <br />cerca Ian West)
    id11(Parla con i membri <br />della Famiglia <br />per ottenere la <br />password del <br />terminale)
    id12(Convinci Vance <br />a darti la <br />password del <br />terminale)
    id13(Fai una ricerca <br />sui modi del vampiro e <br />parla con Vance) 
    id21(Uccidi la Famiglia)
    id14(Parla con Ian)
    id15(Ian decide di <br />lasciare la famiglia)
    id16(Ian decide di rimanere)
    id17(Informa Vance della <br />decisione di Ian e <br />stipula una tregua con Arefu)
    id18(Schemi - Shishkebab):::rewardfo3
    id19(Torna da Evan King e <br />finalizza la tregua)
    id20(300 PE, karma positivo):::rewardfo3
    id1-->id2
    id3-->id2
    id1-->id3
    id2-->id4-->id5-->id6 & id7 & id8 & id9
    id8 & id9-->id10-->id11 & id12 & id13 & id21-->id14-->id15 & id16-->id17-->id18-->id19-->id20
    click id2 "../../luoghi/arefu"
    click id3 "../../luoghi/megaton"
    click id6 "../../luoghi/nascondiglio-di-hamilton"
    click id7 "../../luoghi/cinema-allaperto-di-moonbeam"
    click id8 "../../luoghi/stazione-seneca-nord-ovest"
    click id9 "../../luoghi/deposito-di-meresti"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

| Tappe |       Stato        | Descrizione                              |
| :---: | :----------------: | ---------------------------------------- |
|  10   |                    | Consegna il messaggio di Lucy.           |
|  15   |                    | Scopri cosa faceva la Famiglia ad Arefu. |
|  20   |                    | Controlla la Residenza West.             |
|  21   |                    | Controlla la Residenza Schenzy.          |
|  22   |                    | Controlla la Residenza Ewers.            |
|  25   |                    | Fai rapporto a Evan King.                |
|  30   |                    | Trova la Famiglia.                       |
|  40   |                    | Trova Ian West.                          |
|  50   |                    | Parla con Vance della decisione di Ian.  |
|  60   | :white_check_mark: | Torna da Evan King.                      |
| 65 |                    |     Torna da Vance per confermare l'accordo (se possibile)                                     |


Note:
- Se si va direttamente ad Arefu senza aver parlato prima con Lucy West a Megaton, più tardi potrebbe risultare impossibile convincere Ian a lasciare la Famiglia
- Se nella tregua si decide che Arefu venderà sacche si sangue in cambio di protezione, sarà possibile vendere a Vance le proprie sacche di sangue per 15 tappi ciascuna
- Se si  convince Ian a rimanere con la Famiglia tutte le opzioni di dialogo successive con Evan King saranno bugie ma non bloccheranno l'avanzamento della missione
- Uccidere un qualsiasi abitante di Arefu farà fallire la missione
- A causa di un bug se si uccidono tutti i membri della Famiglia dopo aver convinto Ian a tornare ad Arefu, gli abitanti di Arefu risulteranno ostili e non sarà possibile finire la missione. Questo perché una volta siglata la tregue la Famiglia e gli abitanti di Arefu risulteranno alleati nella stessa fazione
