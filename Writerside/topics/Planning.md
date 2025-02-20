# Planning

## Te plannen taken

Bij het aanmaken en aanpassen van een taak, worden de te plannen taken automatisch gegenereerd.  
U kan deze terugvinden in de taak detail.

<img src="TePlannenTaken.png"  alt="Te plannen taken"/>


### Werking automatische generatie

De generatie houdt rekening met het aantal nodig personeel, het werkschema en de "herhaling informatie"
<img src="AutomatischeGeneratieParams.png"  alt="Generatie parameters"/>


Als het werkschema niet is ingevuld en er voor een "om de 3 dagen" frequentie is gekozen, wordt er telkens 
een te plannen taak aangemaakt als deze op een werkdag valt. Valt de te plannen taak in het weekend, 
dan wordt deze niet aangemaakt.

In onderstaand voorbeeld wordt de te plannen taak van 22 februari niet aangemaakt.
<img src="recurrency3daysExample.png"  alt="voorbeeld om de 3 dagen frequentie"/>
