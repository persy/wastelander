---
# Title, summary, and page position.
linktitle: "Puoi dipendere da me"
summary: ""
weight: 10
icon: message-question
icon_pack: fas

# Page metadata.
title: "Puoi dipendere da me"
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni secondarie di Fallout: New Vegas"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

<div class="fnv">


*Puoi dipendere da me* è una missione secondaria di Fallout: New Vegas. È data da Alice McLafferty alla Crimson Caravan Company.

**Riassunto**:
1. Parla con Alice McLafferty alla Crimson Caravan Company
2. Porta la fattura della Crimson Caravan al Dott. Thomas Hildern a Camp McCarran
3. Occupati di Henry Jamison all'Atomic Wrangler
   - **fama per l'RNC**/**Eloquenza 50**: convincilo ad andarsene: **500 tappi**
   - Recupera 300 tappi (400 con **Baratto 50**)
   -  Uccidilo
4.  Ottieni l'offerta d'acquisto della Cassidy Caravan da Cass
5.  Prosegui in *Heartache by the Number*
   -  **Baratto 50**: pagala 750 tappi
   -  **Baratto 75**: sfidala ad una gara di bevute (servono anche 12 whiskey)
   -  **Eloquenza 75**: convincila che non è colpa sua se la carovana è stata distrutta
6.  (Opzionale) Recupera le specifiche delle armi dei Gun Runner
7.  (Opzionale) Entra furtivamente a Gun Runner, durante il cambio di guardia, fra le 22:00 e le 23:00
8.  Torna da Alice McLafferty
9.  Ricompensa: **550 PE**, **500 tappi**, **fama per l'RNC**

<section class="chart-collapse">
<input type="checkbox" name="collapse2" id="handle2">
<h3 class="handle">
<label for="handle2">Clicca per mostrare il diagramma</label>
</h3>
<div class="content">

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#ffe245', 'primaryTextColor': '#fff', 'lineColor': '#ffe245', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Puoi dipendere da me</b>):::questfnv
    id2(Parla con Alice McLafferty <br />alla Crimson Caravan Company)
    id3(Porta la fattura della <br />Crimson Caravan al <br />Dott. Thomas Hildern <br />a Camp McCarran)
    id4(Se si ha <br />già completato <br />Guarda tra l'erba):::questfnv
    id5(Impossibile consegnare <br />la fattura a Hildern a <br />causa di un bug):::questfnv
    id6(Torna da Alice McLafferty)
    id7(Occupati di Henry Jamison <br />all'Atomic Wrangler) 
    id8(Fama per l'RNC/<br />Eloquenza 50: <br />convincilo ad <br />andarsene)
    id9(500 tappi):::rewardfnv

    id11("300 tappi <br />(400 con Baratto 50)"):::rewardfnv
    id12(Uccidilo)
    id13(Ottieni l'offerta d'acquisto <br />della Cassidy Caravan da Cass)
    id14(Heartache by the Number):::questfnv
    id15(Baratto 50: <br />pagala 750 tappi)
    id16("Baratto 75: <br />sfidala ad una <br />gara di bevute <br />(servono anche <br />12 whiskey)")
    id17(Eloquenza 75: <br />convincila che non è <br />colpa sua se la carovana <br />è stata distrutta)
    id18("(Opzionale) <br />Recupera le <br />specifiche <br />delle armi dei <br />Gun Runner")
    id19("(Opzionale) <br />Entra furtivamente <br />a Gun Runner, <br />durante il cambio <br />di guardia, fra <br />le 22:00 e le 23:00")
    id20(550 PE, 500 tappi, <br />fama per l'RNC):::rewardfnv

    
    id1-->id2-->id3-->id4---->id5
    id3---->id6

    id2-->id7-->id8-->id9-->id6
    id7-->id11-->id6
    id7-->id12--->id6

    id2-->id13-->id14-->id15 & id16 & id17-->id6

    id2-->id18-->id19-->id6

    id6-->id20

    
    
    classDef rewardfnv fill:#ffe245, stroke:#ffe245, color:#282a36;
    classDef questfnv fill:#ffe245, stroke:#ffe245, color:#282a36;
```

</div>
</section>

| Tappe |       Stato        | Descrizione |
|:-----:|:------------------:| ----------- |
|                           10                          |            | Consegna la fattura della Crimson Caravan al Dottor Hildern a Camp McCarran.                                                                                                |
|                           15                          |            | Torna da Alice McLafferty e comunicale che hai consegnato la fattura.                                                                                                       |
|                           20                          |            | Alice McLafferty, proprietaria della Crimson Caravan Company, ha ulteriori lavori disponibili.                                                                              |
|                           30                          |            | Negozia con Cass per acquistare la Cassidy Caravans per la Crimson Caravan Company.                                                                                         |
|                           35                          |            | Riferisci ad Alice McLafferty che ora la Crimson Caravan Company possiede la Cassidy Caravans.                                                                              |
|                           36                          |            | Riferisci ad Alice McLafferty che Cass è morto.                                                                                                                             |
|                           40                          |            | Convinci Henry Jamison ad abbandonare il suo posto di lavoro alla Crimson Caravan Company.                                                                                  |
|                           45                          |            | Comunica ad Alice McLafferty che Henry Jamison ha abbandonato il suo posto di lavoro.                                                                                       |
|                           50                          |            | (Opzionale) Recupera le specifiche di produzione segrete dei Gun Runner dalla loro fabbrica.                                                                                |
|                           55                          | :white_check_mark: | Consegna le specifiche di produzione dei Gun Runner ad Alice McLafferty.                                                                                                    |



**Sfide abilità**:
- **Baratto 50**: per convincere Jamison a lasciare il suo lavoro e guadagnare fino a 400 tappi
- **Eloquenza 50**: per convincere Jamison a lasciare il suo lavoro e guadagnare fino a 500 tappi



**Note**:
- Completando *Guarda tra l'erba* un bug renderà impossibile consegnare la fattura a Thomas Hildern; è quindi consigliato prima consegnargliela e poi completare la missione *Guarda tra l'erba*
- Se la parte che riguarda Cass viene risolta non violentemente, ci saranno delle conseguenze per la missione *Heartache by the Number*


</div>


