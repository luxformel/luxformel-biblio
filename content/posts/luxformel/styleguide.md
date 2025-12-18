---
title: "Luxformel Styleguide"
date: 2025-09-28T16:06:45+02:00
# weight: 1
# aliases: ["/first"]
tags: ["Designer Notes"]
categories: ["Luxformel"]
author: "Luxformel"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: false

math: true
---

# Luxformel Styleguide

Luxformel ass ee Site ze fannen ënnert dem link <https://luxformel.info>. De Site gouf erstallt fir d'Léieren ze vereinfachen mat Exercicer, gekierzte Coursen, an nëtzlechen Dokumenter.


## Inhaltsverzeechnes

1. [Allgemenge Stil](#allgemenge-stil)
    1. [Faarwen](#faarwen)
    1. [Schréft](#schreft)
2. [Kapitel](#kapitel)  
    1. [Kapitel Titel](#kapitel_titel)
    2. [Ëenner Titelen](#enner-titelen)
    3. [Zousaz Titelen](#zousaz-titelen)
    4. [Bemierkungen](#bemierkungen)
    5. [Text](#text)
        1. [Ënnersträichen](#ennerstraichen)
    6. [Lëschten](#leschten)
        1. [Onnumerotéiert Lëschten](#onnumerotéiert-lëschten)
        2. [Numerotéiert Lëschten](#numerotéiert-lëschten)
    7. [Tabellen](#tabellen)
3. [Archiv](#archiv)  
4. [Bibliothéik](#bibliotheik) 
5. [Change Log](#change-log)

## Allgemenge Stil {#allgemenge-stil}

### Faarwen {#faarwen}

Luformel am Helle Stil huet follgend Faarwen:
    
1. Wäiss als Hannergrond: ```#fff```
2. Schwaarz fir Text, Titelen, Formelen, etc. :```#000```   
3. Mof als spezial Faarw: ```hsl(250 100% 50% / 0.6)``` 
4. Linken sinn ausser bei ausname blo: `#0000ff` 

### Schréft {#schreft}

Déi typesch Schréft fir d'Interface op Luxformel ass: 
```css
font-family: "Roboto Mono", monospace;
```


Déi typesch Schréft fir Text, Titelen ass: 
```css
font-family: "Times New Roman", Times, serif;
```

## Kapitel {#kapitel}

### Kapitel Titel {#kapitel_titel}

De Kapitel Titel ``` <h1><\h1>```  gett ass ee generellen Numm passent bei d'Kapitel. De Kapitel Titel ass d'selwecht wéi den Titel ```<title><\title>```.

### Ënner Titel {#enner-titel}

Ënner Titelen ```<h2><\h2>``` sollen ëmmer de kierzt Méigelechen Titel hunn. Wierder ewéi: Der, Die, The, Le, La, Les,..., dierfen net benotzt ginn.

Wann et zwee Méigelechkeete gett een ënner Titel ze nennen ginn ëmmer alleguerten d'bekannte Méigelechkeete benotzt déi mat engem komma getrennt ginn.

Wann den Text ënnert dem ënner Titel op e puer Titele passt ginn alleguerten déi relevant Themen am ënner Titel opgezielt an mat engem: und, and, et, getrennt. D'Reihenfolg ass der Wichtegkeet no; vir déi mei Wichteg.

### Zousaz Titelen {#zousaz-titelen}

Zousaz Titelen ```<h3><\h3>``` gi benotzt wann een ënner Titel no nach mei Opspléckung verlaangt.

Méigelechkeeten fir den zousaaz Titel ze benennen sinn: Bemerkung(en), Remark(s), Remarque(s), Theorem(e), Theorem(s), Théorème(s), Regel(n), Rule(s), Règle(s), Herleitung(en), Proof(s), Démonstration(s), Definition(en), Definition(s), Définition(s), Schlussfolgerung(en), Conclusion(s), Conclusion(s), Formel(n), Formula(s;e), Formule(s), Reaktion(en), Reaction(s), Reaction(s), Hypothese(n), Hypothesis, Hypothèse, Konvention(en), Convention(s), Convention(s), Eiheit(en), Unit(s), Unité(s), 

Wa Méigelech soll ëmmer een ënner Kapitel benotzt ginn amplaaz vun engem zousaz Kapitel.  

### Bemierkungen {#bemierkungen}

Bemierkungen si Sätz dei kënnen mat engem ```<h3><\h3> ``` dobäi gesaat ginn wann néideg.

Bemierkungen zu Bemierkungen ginn mat engem break ``` <br> ``` getrennt.

### Text {#text}

#### Ënnersträichen {#ennerstraichen}

Wichteg Informatiounen déi usech kéinten alleng ee ganze Paragraph ofkierzen, kënnen vum Autheur Ënnerstrach ginn.


### Lëschten {#leschten}

#### Onnumerotéiert Lëschten {#onnumerotéiert-lëschten}

Wann Informatiounen nët wierklech an eng Tabell passen oder gemaach goufe fir an eng Lëscht kënnt par default eng onnumerotéiert Lëscht ```<ul></ul>```.

#### Numerotéiert Lëschten {#numerotéiert-lëschten}

Nëmme wann néideg soll eng numerotéiert Lëscht ```<ol></ol>``` benotzt ginn. An all annere Fall kënnt eng on numerotéiert Lëscht.

### Tabellen {#tabellen}

Tabellen ginn a folgende Situatioune benotzt:

 1. Eng Opzielung vu Informatiounen ass ze komplex fir an eng normal Lëscht.
 2. Et ass eng Tabell mat Werter. Beispill: [Sonnensytem](https://luxformel.info/Physik/Tabellen/sonnensystem-tabelle.html) Tabell.

Tabelle solle juste benotzt ginn wa Lëschten absolut keng Méigelechkeet sinn.

### Abbreviatiounen {#abbreviatiounen}

Abbreviatiounen gi benotzt wann eng Organisatioun opgezielt gëtt déi normalerweis mei bekannt duerch hir Ofkierzung ass wei duerch hire ganzen Numm. Beispill:

```html
<abbr title="International Electrotechnical Commission">IEC</abbr>
```

## Archiv {#archiv}

D'[Archiv](https://luxformel.info/Archiv/index.html) existéiert fir .pdf Dokumenter fir de Benotzer ze späicheren. Dat kënnen Worksheets, Angaben, Énoncéë sinn oder Léisungen zu denen Aufgaben, genau wéi och tabellaresch Dokumenter. Beispiller:

Léisung: Complex Numbers and Vector Space, an hir Angaben/Worksheet.

Worksheets, Angaben oder Énoncé sinn dei offizell Nimm déi solle Benotzt ginn fir d'Angaben.

D'Léisungen sinn ëmmer lénks vum Site, an den Énoncé ass ëmmer riets.

All Énoncé wou am Archiv ze fannen ass muss och an der Bibliothéik ze fanne sinn.

## Bibliothéik {#bibliotheik}

D'[Bibliothéik](https://biblio.luxformel.info) ass een Zousaz Site fir luxformel.info. An der Bibliothéik sinn d'Énoncéën a Form vun enger Websäit ze fannen. 

Den Énoncé an der Bibliothéik huet wann et eng Léisung gëtt ëmmer ee Link zu de geléisten Exercicer op luxformel.info.

## Change Log {#change-log}

1. Versioun 1.0 Release den 9.11.2025.