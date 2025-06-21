 # Transcriptomics


### Inleiding

Reumatoïde artritis (RA) is een chronische gewrichtsaandoening die veel uitdagingen met zich meebrengt vanwege de mogelijkheid om onomkeerbare gewrichtsschade en invaliditeit te veroorzaken. [Smolen, J. S., Aletaha, D., & McInnes, I. B. (2016).](bronnen/pubmed-27156434.txt)RA treft ongeveer 1% van de bevolking en heeft niet alleen gevolgen voor de kwaliteit van leven van patiënten maar legt ook een aanzienlijke last op de gezondheidszorg. [Ngian G. S. (2010).](bronnen/pubmed-20877764.txt) Vroege diagnose en snelle, gerichte behandeling zijn cruciaal voor het verbeteren van de resultaten op lange termijn, vooral bij personen met risicofactoren zoals vroege gewrichtsschade. Ondanks de vooruitgang in de behandeling is er nog steeds niet een behandeling die de ziekte stopt. In dit onderzoek wordt er gekeken naar patienten met en zonder RA, doormiddel van transcriptomics aan de hand van de expressie.

### Methode

Om te kijken welke genen er worden gebruit bij RA zijn de genen met R geanaliseerd. De materialen zijn afkomstig van uit de synofium van 4 patienten met RA en 4 patienten zonder RA. Het was bevestigd met de gene die auto antistoffen hebben. Eerst werden de packages ingeladen. Nadat deze waren ingeladen is er een index gemaakt en de monsters ingeladen en gealined van het humaan genoom(HIER DE LINK ER NAAR TOE). De gemaakte bestanden werden daarna gesorteerd, er werd daarna een DESeq data set aangemaakt. Daarna werd er een vulcano plot gemaakt. Daarna werd er een KEGG pathway gemaakt en daarna is er een ggplot gemaakt voor de opregulaatie. ![transcriptomics](https://github.com/user-attachments/assets/d49d1f50-8476-4ed8-aa30-e5c20f5b51e5) 
##### Figuur 1: Flowshema van data analyse in R.

### Resultaten
Om te kijken welke genen opgereguleerd en downgereguleerd zijn is er een vulcano plot gemaakt.In het vulcano plot is the zien dat er bepaalde genen meer of minder expressie hebben. Het gen ANKRD30BL in sterk gedownreguleerd net als MT-ND6. Voor de opgereguleerde genen zoals SRGN.


![vulcano](https://github.com/user-attachments/assets/f4687d5e-166f-4584-be75-46e8c4569798) 
#### Figuur 2: Rood is signifikant en biologish relefant en groen is signifikant en biologish relefant en grijs is geen van beide.

Om te kijken welke van welke genen zijn op- en downgereguleerd werden deze vergeleken met de RA pathway. 
![hsa05323 pathview](https://github.com/user-attachments/assets/ecf85c40-c04a-404d-8216-ca4faf9b02c7) 
#### Figuur 3: 

Aan de hand van deze afbeelding is te zien dat veel genen zijn opgereguleerd zijn. Aan de hand van deze afbeelding is te zien dat Immune respone ![opgereguleerd](https://github.com/user-attachments/assets/89d66854-92d0-4d71-8925-ca0d20636555)


vertel over de plaatjes
 +- 200 woorden, inclusief correcte verwijzingen.
 
### Conclusie
Er is een duidelijk significant verschil te zien in opgereguleerde genen vooral de adaptive immune respone speelt een grote rol.


+- 200 woorden, inclusief aanbevelingen en onderzoek in context
plaatsen.


- Uitleg competentie beheren (zie voor hulpvragen het voorbeeld):
o File (bijvoorbeeld een md file) met uitleg over Data Stewardship
o File met uitleg over toepassing beheren met GitHub
