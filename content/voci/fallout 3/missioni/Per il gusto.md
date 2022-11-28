---
# Title, summary, and page position.
linktitle: Per il gusto
summary: ""
weight: 10
icon: message-question
icon_pack: fas

# Page metadata.
title: Per il gusto
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni nascoste di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

*Per il gusto* è una missione nascosta di Fallout 3. E' data interagendo con il corpo di Winger Mercier allo stabilimento Nuka-Cola.



```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Per il gusto</b>):::questfo3
    id2(Trova lo stabilimento <br />Nuka-Cola)
    id3("Trova il corpo di <br />Winger Mercier e prendi la <br />nota "Trovare la Formula"")
    id3(Parla con Milo)
    id10(Supera una sfida Eloquenza, <br />sfrutta l'abilità extra <br />Esperto in robotica <br />o usa una tessera ID)
    id11(Uccidi Milo)
    id4(Trova la cassaforte <br />nel locale uffici)
    id5(Prendi la formula della <br />Nuka-Cola Clear)
    id6(Vai all'entrata della <br />Fabbrica Red Racer e <br />parla con il portiere Ledoux)
    id7(Dagli la formula)
    id8(250-400 tappi):::questfo3
    id9(Dagli la formula <br />e poi uccidilo)
    id12(250-400 tappi, <br />maschera da hockey di Ledoux):::questfo3
    id1-->id2-->id3-->id10 & id11-->id4-->id5-->id6-->id7-->id8
    id6-->id9-->id12
    click id2 "../../luoghi/stabilimento-nuka-cola"
    click id6 "../../luoghi/fabbrica-red-racer"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

Note:
- Non è possibile ottenere la missione se si ha già completato *La sfida di Nuka Cola*