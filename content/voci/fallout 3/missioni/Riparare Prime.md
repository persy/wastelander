---
# Title, summary, and page position.
linktitle: Riparare Prime
summary: ""
weight: 10
icon: message-question
icon_pack: fas

# Page metadata.
title: Riparare Prime
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni di Broken Steel"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---


*Riparare Prime* è una missione del DLC *Broken Steel* di Fallout 3. È data dallo Scriba Rothchild alla Cittadella.


```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Riparare Prime</b>):::questfo3
    id2(Parla con lo Scriba Rothchild <br />a proposito delle riparazioni <br />richieste per Libert Prime)
    id3(Chi osa vince):::questfo3
    id4(Porta una macchina fotografica)
    id5(Porta un modulo sensore)
    id6(25 PE, 100 tappi):::rewardfo3
    id7(10 PE, 75 tappi):::rewardfo3 
    id1--->id2-->id4 & id5
    id3-->id2
    id4-->id6
    id5-->id7
    click id2 "../../luoghi/cittadella"
    click id3 "../chi-osa-vince"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```




Note:
- Qualsiasi sia il numero di macchine fotografiche o moduli sensore consegnati, Liberty Prime non sarà mai riparato
- Se la Cittadella è stata distrutta durante *Chi osa vince*, non sarà possibile ottenere questa missione
