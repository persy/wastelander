---
# Title, summary, and page position.
linktitle: Morte dai cieli
summary: ""
weight: 10
icon: message-question
icon_pack: fas

# Page metadata.
title: Morte dai cieli
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni di Broken Steel"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---


<div class="fo3">

*Morte dai cieli* è una missione del DLC *Broken Steel* di Fallout 3. È data dall'Anziano Lyons alla Cittadella.


<section class="chart-collapse">
<input type="checkbox" name="collapse2" id="handle2">
<h3 class="handle">
<label for="handle2">Clicca per mostrare il diagramma</label>
</h3>
<div class="content">

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Morte dai cieli</b>):::questfo3
    id2(Svegliati nella Cittadella e <br />parla con lo Scriba Rothchild)
    id3(Incontra il Paladino Tristan <br />al tunnel di Rockland)
    id4(Accompagna il Paladino Tristan <br />e incontra Liberty Prime <br />fuori dal tunnel)
    id5(Supporta l'attacco)
    id6(Non dare alcun supporto)
    id7(Assisti alla distruzione <br />di Liberty Prime e <br />parla di nuovo con <br />Paladino Tristan) 
    id8(Recupera i dati dalla <br />stazione ripetitore <br />del satellite)
    id9(Trona alla Cittadella e <br />consegna i dati allo <br />Scriba Rothchild)
    id10(Parla con Lyons l'Anziano)
    id11(1300 PE):::rewardfo3
    id12(Prossima missione: <b>Ai generatori</b>):::questfo3
    id1-->id2-->id3-->id4-->id5 & id6-->id7-->id8-->id9-->id10-->id11-->id12
    
    
    click id12 "../ai-generatori"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

</div>
</section>

| Tappe |       Stato        | Descrizione                                         |
|:-----:|:------------------:| --------------------------------------------------- |
|  10   |                    | Parla con lo Scriba Rothchild.                      |
|  15   |                    | Incontra il Paladino Tristan al tunnel di Rockland. |
|  20   |                    | Assisti il Paladino Tristan durante l'assalto.      |
|  30   |                    | Recupera i dati dal ripetitore del satellite.       |
|  40   |                    | Consegna i dati allo Scriba Rothchild.              |
|  50   | :white_check_mark: | Fai rapporto a Lyons l'Anziano.                     |





**Note**:
- Usa il comando `player.setstage xx000802 20` nel caso non riuscissi a muoverti dal letto e `player.setstage xx000802 20` nel caso la missione non riuscisse ad avanzare



</div>