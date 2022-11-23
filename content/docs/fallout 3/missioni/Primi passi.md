---
# Title, summary, and page position.
linktitle: Primi passi
summary: 'TODO'
weight: 40
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Primi passi
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni principali di Fallout 3"
hidden: true # Visibile nella sidebar
private: true # Nascosto dalle ricerche
---

Primi passi è la prima missione principale.

| Luogo/i   | Data da | Ricompensa                        | Sfide abilità | Prossima missione | Note |
| --------- | ------- | --------------------------------- | ------------- | ----------------- | ---- |
| Vault 101 | James   | Assegnamento punti S.P.E.C.I.A.L. | -             | [Crescita rapida](../crescita-rapida)                  |      |

```mermaid
graph TD;
    id1[<b>Primi passi</b>]:::questfo3-->id2[Cammina verso papà e impara a muoverti]
    id2-->id3[Apri la porta del box]
    id3-->id4[Esci dal box]
    id4-->id5[Leggi Sei S.P.E.C.I.A.L. e seleziona le tue statistiche primarie]
    id5-->id6[Impara a prendere e buttare gli oggetti e ascolta papà]  
    id6-->id7[Segui papà fuori dalla stanza]
    id7-->id8[Ricompensa: Punti S.P.E.C.I.A.L. assegnati, progresso all'età di 10 anni]:::rewardfo3
    id8-->id9[Prossima missione: <b>Crescita rapida</b>]:::questfo3
    click id9 "../crescita-rapida"
    classDef rewardfo3 fill:#f1ff8a66, stroke:#56700087;
    classDef questfo3 fill:#5f9bd35e, stroke:#255b8d91;
```

| Tappe |       Stato        | Descrizione                       |
| :---: | :----------------: | --------------------------------- |
|  10   |                    | Vai da papà.                      |
|  20   |                    | Apri lo sportello della culla.    |
|  30   |                    | Esci dalla culla.                 |
|  40   |                    | Consulta il libro S.P.E.C.I.A.L.. |
|  80   | :white_check_mark: | Segui papà                        |
