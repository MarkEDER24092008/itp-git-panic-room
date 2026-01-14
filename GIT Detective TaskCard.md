# 🕵️ Git Detective – Ermittlungsprotokoll

Ziel dieser Station ist es, das Repository zu **verstehen**, nicht es zu reparieren.

- Es wird **(noch) nichts geändert**
- Es wird **(noch) nichts repariert**
- Es wird **(noch) nichts committed**

Reparaturen folgen erst im **Panic Room** 🚨

Ausgearbeitet von: <<< Mark Eder >>>




## #1 -  Überblick über die Git-History
Welche 2 Commits fallen euch in der History bereits zu Beginn negativ auf? Und warum? 

#### Antwort: 
* Stuff – Beschreibt nichts von den Änderungen
* Update / more – Beschreibt genauso wenig

## #2 - Ab welchem Commit ist das Projekt nicht mehr stabil?
Woran erkennt ihr, dass es ab hier ein Problem gibt?
Mit welche(n) Befehl(en) könnt ihr das herausfinden?
(Antwort: Commit-ID, Message, Begründung)

##### Use of 'git log':
Antwort: 50da5b1 | Update | **tag: v2-tests-broken** | Test -Files wurden durch schlechtem Handling kaputt

## #3 - Welche Datei wurde dabei verändert?
Welche Datei(en) wurden im verdächtigen Commit verändert?
Mit welche(n) Befehlen könnt ihr das herausfinden?
(Antwort: Commit-ID, geänderte Datei(en), Kurzbeschreibung der Änderung)

#### Antwort: 50da5b1 | Calculator.java | Simplifizierung einer Funktion

## #4 - Wer hat die entscheidende Stelle verändert?
Welche Datei ist besonders relevant und warum?
Mit welche(n) Befehlen kannst du dies rausfinden? 
(Antwort: Datei, Commit-ID der relevanten Änderung, Commit Message, betroffene Code-Stelle, warum ist diese Stelle wichtig?)

#### Antwort: Calculator.java & CalculatorText.java | 50da5b1 | Update | zeile 9-12 | Eine Variable wird durch 0 dividiert

## #5: Vergleich vor und nach der Änderung
Was ist der Unterschied im Code, bevor und nachdem das Problem entstanden ist? Mit welchem Befehl kannst du das rausfinden? 

#### Antwort: Alle files werden grün angezeigt, zeigend dass diese keine Fehler aufweisen.