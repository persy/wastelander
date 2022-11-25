---
# Title, summary, and page position.
linktitle: Futuro imperfetto
summary: ""
weight: 10
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Futuro imperfetto
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni tutorial di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

*Futuro imperfetto* è la terza missione principale di Fallout 3. Si svolge nel Vault 101 ed è data da James.


```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1[<b>Futuro imperfetto</b>]:::questfo3-->id2[Vai in classe e parla al Sig. Brotch del G.O.A.T.]
    id2-->id3[Fai il G.O.A.T.]
    id2-->id4[Convincilo a manipolare i risultati]
    id3-->id5[Restituisci il G.O.A.T. al Sig. Brotch]
    id5-->id6[Esci dalla classe]
    id5-->id4
    id6-->id7[Specializzazione in 3 abilità]:::rewardfo3  
    id4-->id7
    id7-->id8[Prossima missione: <b>Scappa!</b>]:::questfo3
    click id8 "../scappa"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

| Tappe | Stato              | Descrizione                                       |
| :---: | :----------------: | ------------------------------------------------- |
|  10   |                    | Vai in classe e parla al Sig. Brotch del G.O.A.T. |
|  40   |                    | Siediti e prendi il G.O.A.T.                      |
|  70   |                    | Restituisci il G.O.A.T. al Sig. Brotch.           |
|  80   | :white_check_mark: | Esci dalla classe.                                |


Note:
- E' possibile bypassare il G.O.A.T. semplicemente dicendo al Sig. Brotch
- E' possibile cambiare le specialità poco prima di abbandonare il Vault nella missione successiva *Scappa!*