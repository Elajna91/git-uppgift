## Fråga 1:
Versionshantering betyder att man kan spara och följa förändringar i sina filer över tid. När jag sparar min fil på editorns vanliga spara-knapp så ändras filen på min egena dator men den sparar inte en historik över mina ändringar. När jag gör en commit till Git så sparas en version av mitt projekt som jag kan gå tillbaka till. 

Varje gång jag gör en commit i mitt projekt så blir det en "version" som jag kan gå tillbaka till vid en viss tidpunkt. Även om jag ändrade i filen flera gånger så finns alla tidigare versioner kvar och därav kan jag fortsätta se ala tre TODO i historiken.

## Fråga 2:
-Git status: Används för att kolla vilka filer som har ändrats och om de är redo för en commit. 
-Git add: Används för att välja vilka ändringar som ska ingå i min nästa commit. 
-Git commit: Sparar mina ändringar som en ny version i mitt projekts lokala historik.

Arbetsytan är projektet jag skriver eller ändrar min text, till exempelt ett ark. Staging är den mappen som jag lägger mina ändringar i som jag vill spara och commiten är arkivlådan är där jag lämnar min sparade version av projektet.

Om jag skriver git commit utan att skriva git add först så finns ändringarna inte i staging och kan då inte spara något, alltså göra en commit. För det finns inget som ligger förerett att sparas. 

## Fråga 3:
Mappen som är på min dator är den lokala projektmappen och den jag arbetar i och sparar mina commits. Github-repot ligger på nätet och gör det möjligt att dela med sig av sitt projekt till andra. När jag använder mig utav git push skickar jag iväg mina commits jag gör till Github. 

Projektet kan ses som en låda hemma där jag har allt sparat i en "låda" medans Github visar upp mitt projekt som i ett glasmontern. Dom ses som två separata platser eftersom om jag gör en ändring hemma på datorn syns det inte direkt på Github om jag inte skickar en commit till montern. 

Om jag gör en ändring i min fil och inte använder mig av git add innan så finns det ingen commit att git push. Att se texten Everything-up-to-date visar att det inte finns någon commit att skicka till Github. 
