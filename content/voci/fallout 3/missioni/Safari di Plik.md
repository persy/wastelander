---
# Title, summary, and page position.
linktitle: TODO
summary: ""
weight: 10
icon: message-question
icon_pack: fas

# Page metadata.
title: TODO
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni di Point Lookout"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---


*Safari di Plik* è una missione secondaria del DLC *Point Lookout* di Fallout 3. È data da Plik alla grotta marina.


```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Safari di Plik</b>):::questfo3
    id2(Entra nella grotta marina)
    id3(Leggi il Diario di Plik)
    id4(Abilità extra: Ecologia ghoul):::rewardfo3
    id5(Paga 1000 tappi a Plik <br />per unirti al safari)
    id6(Entra nell'arena e <br />sopravvivi alle <br />ondate di ghoul)
    id7(Esci dall'arena e <br />parla con Plik) 
    id8(100 PE, L'accetta):::rewardfo3
    id9(Uccidi o borseggia Plik)
    id10(Parla con Plik per <br />iniziare un altro safari)
    id11(1800 tappi):::rewardfo3
    id1-->id2-->id5-->id6-->id7-->id8-->id9 & id10
    id2-->id3-->id4-->id5
    id9-->id11
    id10-->id5
    click id2 "../../luoghi/grotta-marina"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

| Tappe |       Stato        | Descrizione                                                      |
|:-----:|:------------------:| ---------------------------------------------------------------- |
|  10   |                    | Paga a Plik 1.000  tappi per partecipare a questo safari.        |
|  50   |                    | Entra nell'arena e dai il segnale a Plik per iniziare il safari. |
|  51   |                    | Sopravvivi al safari di Plik.                                    |
|  70   | :white_check_mark: | Fai sapere a Plik che sei sopravvissuto al suo safari.           |




Note:
- Il diario di Plik si trova su un tavolo, in una stanza a sinistra di Plik, nella grotta marina
- Uccidere Plik non farà guadagnare karma negativo
- La maschera ghoul è di grande aiuto in questa missione
