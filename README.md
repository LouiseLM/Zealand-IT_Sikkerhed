# Zealand-IT_Sikkerhed

Dette repo er til leg og læring til IT sikkerheds studiet i Næstved.

| **Navn**                    | **Beskrivelse**                                                                                                                               | **Security Gate**               | **Brugsområde i IT-sikkerhed**                    |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | ------------------------------------------------- |
| Ækvivalens klasser          | Gruppering af input værdier der har samme opførsel i softwaren. Test kan laves med en vilkårlig værdi fra klasse og vil få samme resultat.    | Code/Dev Gate                   | Kan erstatte værdier der kan bruges i production. |
| Grænseværdi test            | Test af grænseværdier (ligeunder, ligepå, ligeover) for at se om de opfører sig korrekt                                                       | Code/Dev Gate                   | Opretholder CIA modellen.                         |
| CRUD(L)                     | Tester om systemet kan udføre CRUD(L) operationer korrekt                                                                                     | System Security Gate            | Opretholder CIA modellen.                         |
| Cycle Process test          | Tester om et system kan køre driftsprocesser korrekt hver gang, selv efter crash eller nedbrud, uden fejl eller mangler, med korrekte output. | Release Candidate Security Gate | PDCA cyclus + CIA model.                          |
| Test Pyramiden              | Hvert lag repræsenterer forskellige former af test, og størrelsen af laget repræsenterer den ideelle proportion af disse tests.               | Code/Dev Gate                   | -                                                 |
| Decision Table test         | En tabel der skal sørge for, at alle relevante testkombinationer er overvejet, samt hvilket resultat der forventes.                           | System Security Gate            | Sørger for at alle kan tage ansvar for tests.     |
