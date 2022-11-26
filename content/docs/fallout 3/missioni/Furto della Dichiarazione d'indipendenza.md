---
# Title, summary, and page position.
linktitle: Furto della Dichiarazione d'Indipendenza
summary: ""
weight: 10
icon: messages # message-question per le missioni nascoste
icon_pack: fas

# Page metadata.
title: Furto della Dichiarazione d'Indipendenza
date: 2022-11-15
type: book # Do not modify.
commentable: true
tags: "Missioni secondarie di Fallout 3"
hidden: true # Visibile nella sidebar
private: false # Nascosto dalle ricerche
---

*Furto della Dichiarazione d'Indipendenza* è una missione secondaria di Fallout 3. Si svolge tra Rivet City, gli Archivi nazionali e la biblioteca di Arlington, ed è data da Abraham Washington o Sydney.



```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#282a36', 'primaryBorderColor': '#4eff01', 'primaryTextColor': '#fff', 'lineColor': '#4eff01', 'fontFamily': 'Jura'}}}%%
graph TD;
    id1(<b>Furto della Dichiarazione d'Indipendenza</b>):::questfo3
    id29(Parla con Abraham <br />Washington a Rivet City)
    id2(Trova gli Archivi nazionali)
    id3(Difendi la rotonda)
    id4(Ignora la rotonda)
    id5(Unisciti a Sydney)
    id6(Ignora Sydney)
    id7(Uccidi Sydney) 
    id8("#quot;Super#quot; mitragliatrice <br />da 10mm di Sydney"):::rewardfo3
    id9(Usa l'ascensore <br />della rotonda per <br />raggiungere lo <br />scantinato)
    id10(Fatti strada <br />attraverso gli Archivi <br />nazionali e raggiungi <br />lo scantinato)
    id11(Scegli un percorso <br />attraverso i corridoi <br />degli archivi)
    id12("(Opzionale) Cerca <br />nella camere <br />laterali")
    id13("Disattiva le <br />torrette con <br />Ripara") 
    id14(Magna Carta e <br />Carta dei diritti):::rewardfo3
    id15(Ripara la porta <br />di manutenzione <br />con Scienza)
    id16(Usa Scasso per <br />bypassare la <br />porta di sicurezza)
    id17(Combatti i <br />robot)
    id18(Raggiungi Button <br />Gwinnett)
    id19(Usa l'Eloquenza <br />per convincerlo <br />di essere <br />Thomas Jefferson)
    id20(Uccidilo)
    id21(Accetta d'aiutarlo)
    id22(Karma negativo):::rewardfo3
    id23(Karma positivo):::rewardfo3
    id24(Trova il contenitore per l'inchiostro alla biblioteca di Arlington)
    id24(Convinci Gwinnett <br />a continuare <br />la lotta)
    id25(Ordina a Gwinnett <br />di autodistruggersi)
    id30(Karma <br />positivo):::rewardfo3
    id31(Karma <br />negativo):::rewardfo3
    id26(Dichiarazione d'Indipendenza <br />e parrucca di Button):::rewardfo3
    id27(Torna da Abraham <br />Washington a Rivet City)
    id28(400 PE, Schemi - Sparachiodi):::rewardfo3
    id1-->id29-->id2-->id3-->id5
    id2-->id4-->id6 & id7
    id7-->id8
    id4 & id8-->id10
    id5-->id9
    id9 & id10-->id11-->id12
    id12-->id14
    id11-->id13 & id15 & id16 & id17-->id18-->id19 & id20 & id21
    id20-->id22
    id21-->id23-->id24 & id25
    id24-->id30
    id25-->id31
    id19 & id30 & id31-->id26-->id27-->id28
    id22-->id26
    click id29 "../../luoghi/rivet-city"
    click id2 "../../luoghi/archivi-nazionali"
    classDef rewardfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
    classDef questfo3 fill:#4eff01, stroke:#4eff01, color:#282a36;
```

| Tappe |       Stato        | Descrizione                                                        |
| :---: | :----------------: | ------------------------------------------------------------------ |
|  20   |                    | Recupera la Dichiarazione di Indipendenza dagli Archivi nazionali. |
|  30   |                    | Difendi la Rotonda                                                 |
|  50   |                    | (Facoltativo) Porta l'inchiostro a Button Gwinnett.                |
|  60   | :white_check_mark: | Torna da Abraham Washington a Rivet City.                          |


Note:
- Per disattivare le torrette è necessario Ripara 60, ma per poter accedere al generatore è necessario riparare la porta con Scienza 67
- Sydney non si comporta come un normale companion e la sua salute non si ripristinerà finita la battaglia ma bisognerà fornirle costantemente stimpak
    - Con il reverse-pickpocketing è possibile darle un'armatura più resistente
- E' possibile ottenere la "Super" mitragliatrice da 10mm di Sydney dandole a fine missione la nota "Una nota dal padre di Little Moonbeam"
  - La nota si trova al piano intermedio dello Statesman Hotel