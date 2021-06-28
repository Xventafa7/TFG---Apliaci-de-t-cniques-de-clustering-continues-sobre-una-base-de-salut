# TFG-CLUTERING-Xavier-Ventayol
Codi de tota la part pràctica del TFG

ARXIUS Rdata: Vaig guardar les dades en arxius Rdata per no haver de crear sempre les mostres amb la mateixa llavor
1. elsa - Base de dades elsa sense missings en cap observació
2. elsad - Mostra aleatòria de 200 dones amb els valors normals
3. elsah - Mostra aleatòria de 200 homes amb els valors normals
4. scaledat_d - Mostra de dones escalada i normalitzada per aplicar els mètodes de clustering
5. scaledat_h - Mostra d'homes escalada i normalitzada per aplicar els mètodes de clustering
6. totalelsa - Mostra de dones i homes junta (400 observacions). Només s'utilitza per fer dos gràfics de la desccriptiva miltivariant de les dades

ARXIUS Rmd: He dividit el codi del TFG ja que el meu ordinador no suportava tot el codi en un sol Rmd
1. Descriptiva de les dades.
2. Cada mètode té associat un fitxer Rmd per separat:
  - K-means
  - Jeràrquic
  - K-medoids
  - GMMs = Gaussian Mixture Models
3. ARI:
Per executar l'ARI - primer s'han de compliar tots els mètodes, o al menys les variables indicadores de cada mètode de clustering. El nom de les variables idicadores apareix al fitxer Rmd de l'ARI.


