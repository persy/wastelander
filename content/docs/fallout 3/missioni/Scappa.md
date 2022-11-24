---
# Title, summary, and page position.
linktitle: Scappa!
summary: 'TODO'
weight: 40
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Scappa!
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni tutorial di Fallout 3"
hidden: true # Visibile nella sidebar
private: true # Nascosto dalle ricerche
---

Scappa! è la quarta missione principale del gioco.

| Luogo/i | Data da | Ricompensa | 
| ------- | ------- | ---------- | 
| Vault 101       |  Amata       | Accesso alla zona contaminata, 200 PE; karma positivo, Vestito da serpente del tunnel (opzionale)            | 

```mermaid
graph TD;
    id1[<b>Scappa!</b>]:::questfo3-->id2[Parla con Amata del suo piano per fuggire dal Vault]
    id2-->id3[Fatti strada nel Vault]
    id3-->id4[Entra nell'ufficio del Soprintendente e <br/>usa il computer del Soprintendente <br/>per accedere al tunnel segreto]
    id4-->id5[Apri la porta del Vault e fuggi]
    id3-->id7[Aiuta Butch a salvare sua madre]  
    id7-->id8[Vestito da serpente del tunnel<br/>karma positivo]:::rewardfo3
    id5-->id9[Accesso alla zona contaminata, 200 PE]:::rewardfo3
    id8-->id4
    id9-->id10[Prossima missione: <b>Seguendo le sue orme</b>]:::questfo3
    click id10 "../seguendo-le-sue-orme"
    classDef rewardfo3 fill:#f1ff8a66, stroke:#56700087;
    classDef questfo3 fill:#5f9bd35e, stroke:#255b8d91;
```

| Tappe |       Stato        | Descrizione                                                        |
| :---: | :----------------: | ------------------------------------------------------------------ |
|   5   |                    | Parla con Amata del suo piano per fuggire dal Vault.               |
|  10   |                    | Entra nell'ufficio del Soprintendente.                             |
|  40   |                    | Usa il computer del Soprintendente per accedere al tunnel segreto. |
|  50   |                    | Entra nella sala di controllo del reattore.                        |
|  60   |                    | Attiva nuovamente l'alimentazione.                                 |
|  70   |                    | Apri la porta del Vault.                                           |
|  80   | :white_check_mark: | Fuggi dal Vault.                                                   |



Note:
- A prescindere dall'esperienza guadagnata durante questa missione, non si salirà di livello fintanto che non si lascia il Vault
- E' possibile cambiare l'aspetto fisico e riassegnare gli S.P.E.C.I.A.L. e le specialità poco prima di uscire dal Vault
- Tutti possono essere uccisi, tranne Amata, Andy e Stanley
  - Se il Soprintendente muore, Amata sarà arrabbiata con il protagonista; Butch avrà la stessa reazione se Ellen muore