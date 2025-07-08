
| Selektoren                     | Spezifität         | Beschreibung                                   |
|--------------------------------|--------------------|------------------------------------------------|
| li a                           | 0,0,0,2 Wert = 2   | 2 Typselektoren                                |
| #body #article02 a:link        | 0,2,1,1 Wert = 211 | 2 ID-Selektoren 1 Pseudoklasse 1 Typselektor   |
| #body #article02 li>a:link     | 0,2,1,2 Wert = 212 | 2 ID-Selektoren 1 Pseudoklasse 2 Typselektoren |
| #article02 a                   | 0,1,0,1 Wert = 101 | 1 ID-Selektor 1 Typselektor                    |
| .center                        | 0,0,1,0 Wert = 10  | 1 Klassenselektor                              |
| p>span.important               | 0,0,1,2 Wert = 12  | 1 Klassenselektor 2 Typselektoren              |
| span.important                 | 0,0,1,1 Wert = 11  | 1 Klassenselektor 1 Typselektor                |
| #wrapper>#body>#article03 span | 0,3,0,1 Wert = 301 | 3 ID-Selektoren 1 Typselektor                  |

