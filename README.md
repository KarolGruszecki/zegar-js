# test-clock-js

> :ledger: Testowy projekt zegarka elektronicznego na potrzeby edukacyjne.

## Jak to działa?

 * definiujemy funkcję `odliczanie`, która będzie do kontenera w HTML wlewała łańcuch znaków
 * w jej definicji zostanie uruchomiony `setTimeout` który po sekundzie znowu uruchomi funkcję `odliczanie`
 * aby zegara wystartował po definicji funkcji `odliczanie` uruchamiamy ją!
