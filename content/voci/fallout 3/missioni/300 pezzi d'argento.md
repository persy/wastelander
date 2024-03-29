---
# Title, summary, and page position.
linktitle: 300 pezzi d'argento
summary: ""
weight: 10
icon: message-question
icon_pack: fas

# Page metadata.
title: 300 pezzi d'argento
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni nascoste di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

<div class="fo3">


*300 pezzi d'argento* è una missione nascosta di Fallout 3. È data da Silver a Springvale o da Moriarty a Megaton.

**Riassunto**:
1. (Opzionale) *Seguendo le sue orme*
2. (Opzionale) Parla con Moriarty a Megaton per ottenere informazioni su James
3. Incontra Silver a Springvale
   - Convincila con una sfida Eloquenza a darti tutti i tappi: **400 tappi**
   - Convincila a darti i soldi per Moriarty: **300 tappi**
   - Non chiederle soldi: **karma positivo**
4. (Opzionale) Uccidila e saccheggia il suo cadavere: **karma negativo**, **100 tappi**


<section class="chart-collapse">
<input type="checkbox" name="collapse2" id="handle2">
<h3 class="handle">
<label for="handle2">Clicca per mostrare il diagramma</label>
</h3>
<div class="content">

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>300 pezzi d'argento</b>):::questfo3
    id2(Incontra Silver <br />a Springvale)
    id3(<b>Seguendo le sue orme</b>):::questfo3
    id4("Parla con Moriarty a <br />Megaton per ottenere <br />informazioni su James")
    id5(Convincila con una <br />sfida Eloquenza a <br />darti tutti i tappi)
    id6(400 tappi):::rewardfo3
    id7(Convincila a <br />darti i soldi <br />per Moriarty)
    id8(300 tappi):::rewardfo3
    id9(Non chiederle <br />soldi) 
    id10(Karma positivo):::rewardfo3
    id14("(Opzionale) Uccidila e <br />saccheggia il <br />suo cadavere")
    id11(Karma negativo, 100 tappi):::rewardfo3
    id1---->id2-->id5 & id7 & id9
    id3-->id4-->id2
    id5-->id6
    id7-->id8
    id9-->id10
    id6 & id8 & id10-->id14-->id11
    
    
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

</div>
</section>



**Note**:
- Il cadavere di Silver avrà sempre 100 tappi, anche se, vincendo la sfida Eloquenza, le si estorcono tutti e 400 tappi
- Completare *Seguendo le sue orme* potrebbe rendere inottenibile la missione o impossibile da finire

</div>