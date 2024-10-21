# C Notizen

- [C Notizen](#c-notizen)
  - [Allgemein](#allgemein)
    - [Klausur:](#klausur)
  - [Themen](#themen)
    - [Formatierungszeichen](#formatierungszeichen)
    - [Formatspezifizierer](#formatspezifizierer)

## Allgemein

### Klausur:

- Theoriefragen können kommen z.B. zu was macht #include
  oder was macht ein Compiler ...
- Definition (2-30) nicht relevant
- Speicherung (2-56) Gleitpunktzahlen nicht relevant

## Themen

### Formatierungszeichen

| Zeichen | Beschreibung            |
|---------|-------------------------|
| %c      | Zeichen                 |
| %s      | Zeichenkette            |
| %d / %i  | Dezimalzahl (int)       |
| %f / %.nf | Dezimalzahl (float)     |
| %u      | Unsigned Dezimalzahl    |
| %p      | Zeigeradresse           |

### Formatspezifizierer 

| Zeichen | Beschreibung            |
|---------|-------------------------|
|\n | Zeilenumbruch |
|\b | Setzt den Cursor um eine Position nach links |
|\t | Zeilenvorschub zur nächsten horizontalen Tabulatorposition (meist acht Leerzeichen weiter) |
|\r | Der Cursor springt zum Anfang der aktuellen Zeile |
|\v | Der Cursor springt zur nächsten vertikalen Tabulatorposition |
|\\ | \ wird ausgegeben |
|\" | " wird ausgegeben |
|\? | ? wird ausgegeben |
|\0 | String-Ende-Zeichen (Text, der danach kommt wird nicht mehr ausgegeben) | 
