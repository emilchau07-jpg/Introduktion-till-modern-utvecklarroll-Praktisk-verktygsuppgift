# Introduktion till modern utvecklarroll – Praktisk verktygsuppgift
I denna övningen introducerades jag till terminalen Git, Github och VS code. Syftet är att förstå grunderna i hur jag kan redigera och navigera mig i filsystem, dokumentation och repository. Jag har förstått att en README.md används för att ge en snabb överblick på projektet och varför det existerar.

## Git kommandon jag använt i följande ordning
- git init - Skapar ett nytt tomt Git-repository i uppgiftsmappen
- git add .- Lägger till alla filer som finns i mappen, de blir markerade och redo för nästa commit
- git commit -m "meddelande" - En kort förklaring av vad man gjort, gör den sökbar och synlig i historiken senare
- git remote add origin <url> - Talar om för mitt lokala Git-repository var på internet (Github) det ska skicka och hämta data
- git branch -M main - Byter namn på nuvarande branch till main
- git push -u origin main - Skickar mina sparande commits från min dator upp till Github

## Vad ett repository, en commit och versionshistorik är.
**Repository** – En mapp som Git håller koll på. Den innehåller dina filer plus en dold historik över alla ändringar som gjorts i dem över tid. Man kan ha ett repository lokalt på sin dator och en kopia av samma repository uppe på GitHub.

**Commit** – En sparad "ögonblicksbild" av dina filer vid en viss tidpunkt. Varje commit har ett meddelande som beskriver vad som ändrades. Commits byggs på varandra och bildar tillsammans historiken.

**Versionshistorik** – Den samlade kedjan av alla commits i ett repository, i kronologisk ordning. Den gör att man kan se exakt vad som ändrats, när, och av vem — och man kan gå tillbaka till en tidigare version om något går fel.