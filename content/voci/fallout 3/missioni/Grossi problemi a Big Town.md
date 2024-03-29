---
# Title, summary, and page position.
linktitle: Grossi problemi a Big Town
summary: ""
weight: 10
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Grossi problemi a Big Town
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni secondarie di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

<div class="fo3">

*Grossi problemi a Big Town* è una missione secondaria di Fallout 3. È data da Dusty a Big Town.

**Riassunto**:
1. Puoi ottenere la missione in diversi modi 
   - Parla con Sticky a Little Lamplight; raggiungi la città con o senza Sticky
   - Trova Big Town
   - Parla con Red a Germantown
2. Chiedi agli abitanti di Big Town informazioni sui loro amici catturati 
3. Libera Red e Tappo (opzionale) dalla centrale di polizia di Germantown
   - Se Red è sopravvissuto, parlaci: **300 PE**, **300-500 tappi**, **karma positivo**
   - Se Red e Tappo non sono sopravvissuti: **200 tappi**
4. Preparati per l'attacco dei supermutanti
   - Respingi l'attacco
      - (Opzionale) Use le tue abilità **Esplosivi**, **Scienza**, **Furtivo** e/o **Armi leggere** per preparare la città all'attacco
      - Ricompensa: cure da Red, riparazioni da Pappy e scorte medicinali
   - Ignora l'attacco: nessuna ricompensa
  

<section class="chart-collapse">
<input type="checkbox" name="collapse2" id="handle2">
<h3 class="handle">
<label for="handle2">Clicca per mostrare il diagramma</label>
</h3>
<div class="content">

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Grossi problemi a Big Town</b>):::questfo3
    id2(Parla con Sticky <br />a Little Lamplight. <br />Raggiungi la città con <br />o senza Sticky)
    id3(Trova Big Town)
    id4(Parla con Red <br />a Germantown)
    id5(Chiedi agli abitanti <br />di Big Town informazioni <br />sui loro amici catturati )
    id6("Libera Red e <br />Tappo (opzionale) <br />dalla centrale di <br />polizia di Germantown")
    id7(Red è sopravvissuto) 
    id8(Red e Tappo <br />sono sopravvissuti)
    id9(Nè Red nè Tappo <br />sono sopravvissuti)
    id10(Parla con Red)
    id11(Parla con Papi)
    id12(300 PE, 300-500 tappi, <br />karma positivo):::rewardfo3
    id13(200 tappi):::rewardfo3
    id14(Preparati per l'attacco <br />dei supermutanti)
    id15(Respingi l'attacco)
    id16("(Opzionale) Use le tue abilità <br />Esplosivi, Scienza, Furtivo <br />e/o Armi leggere per preparare <br />la città all'attacco")
    id17(Ignora l'attacco)
    id18("Cure da Red, <br />riparazioni da Pappy <br />e scorte medicinali"):::rewardfo3
    id19(Nessuna ricompensa):::rewardfo3
    
    id1-->id2 & id3 & id4
    id2 & id3-->id5
    id4 & id5-->id6
    id6-->id7 & id8 & id9
    id7 & id8-->id10-->id12
    id9-->id11-->id13
    id12 & id13-->id14 
    id14-->id15 -->id18 
    id15-->id16-->id18
    id14-->id17-->id19
    
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

</div>
</section>

| Tappe |       Stato        | Descrizione                                                            |
| :---: | :----------------: | ---------------------------------------------------------------------- |
|  10   |                    | Chiedi alle persone di Big Town informazioni sui loro amici catturati. |
|  20   |                    | Salva i prigionieri di Big Town dai Supermutanti.                      |
|  25   |                    | Salva Red.                                                             |
|  30   |                    | Riaccompagna Red al sicuro a Big Town.                                 |
|  40   |                    | (Facoltativo) Salva Tappo.                                             |
|  45   |                    | Riaccompagna Tappo al sicuro a Big Town.                               |
|  49   | :white_check_mark: | Spiega la morte di Red alle persone di Big Town.                       |
|  50   | :white_check_mark: | Parla con Red della tua ricompensa.                                    |

**Note**:
- Con *Broken Steel* installato è possibile che un supermutante supremo compaia proprio fuori dall'uscita della stazione di polizia
- Non è possibile completare questa missione se Red è già stato schiavizzato per la missione *Solo affari*. È necessario rimuovere il collare o ucciderlo
- Avere Fawkes come Seguace ti consente di suggerire di usare dell'esplosivo per difendere la città. Ciò comporterà la comparsa di alcune mine a frammentazione intorno a Fawkes ogni 5-10 secondi


</div>