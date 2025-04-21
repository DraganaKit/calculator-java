U analizi su korisceni alati SonarQube i Codalyze.

Start.java - 1 - treba pomeriti fajl u drugi paket
Start.java - 6 - treba preimenovati lokalnu promenljivu Expression (mala slova)
Start.java - 8 - treba zameniti system.out sa logger
Start.java - 19 - treba zameniti system.out sa logger
Calculator.java - 1 - treba pomeriti fajl u drugi paket
Calculator.java - 4 - dodati privatni konstruktor da bi se sakrio javni
Calculator.java - 18 - preimenovati metodu ToString jer vec postoji metoda toString
Calculator.java - 18 - preimenovati metodu u skladu sa konvencijom
Calculator.java - 24 - preimenovati metodu Run u skladu sa konvencijom
Calculator.java - 70 - nepotrebno koriscenje privremene promenjive textResult
Calculator.java - 74 - preimenovati metodu Calculate u skadu sa konvencijom
Calculator.java - 183 - ukloniti zadnji return

Neformalnim pregledom moze se primetiti da Calculator ima prilican broj if/else petlji i da postoji dosta praznih linija u samom kodu.
Iz Codalyze dobijamo detaljnu analizu koda - da funkcija evaluateExpression ima ciklomatsku kompleksnost 12, dok je preporucena vrednost 10. Funkcija Calculate ima ciklomatsku kompleksnost 12, a preporucena vrednost je 10. Osim toga ona ima 77 linija koda, dok je preporucena granica 50 linija. LOC za kompletan projekat iznosi 214.
