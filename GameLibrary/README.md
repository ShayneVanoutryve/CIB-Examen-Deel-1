3. Praktische GitHub-repository-oefening
Belangrijkste onderdeel
 Examenstijl


Dit wordt een grotere praktijkopdracht waarin je H1, H2, H3 en H4 combineert.

Je gaat zelf een repository maken, bestanden toevoegen, branches beheren, wijzigingen pushen en bewust een merge conflict veroorzaken.


Project: GameLibrary

Je gaat een kleine repository maken voor een fictieve gamebibliotheek.

Je repository moet uiteindelijk deze structuur hebben:
GameLibrary/
├── README.md
├── games.txt
├── developers.txt
└── .gitignore


Je werkt met de branches:
- main
- feature-games
- feature-developers

Deel A – Repository opstarten (H1)
1. Maak een nieuwe repository aan op GitHub met de naam GameLibrary.
2. Maak de repository lokaal aan met Git Bash.
3. Initialiseer Git.
4. Maak de vier bestanden uit de structuur hierboven aan.
5. Voeg de bestanden toe aan de staging area.
6. Maak een eerste commit.
7. Koppel je lokale repository aan GitHub.
8. Push je wijzigingen naar main.
Voorwaarden:
- Gebruik main als standaardbranch.
- Controleer regelmatig met git status.
- Gebruik correcte commit messages.
Deel B – Remote repositories en conventies (H2)
1. Controleer welke remote repositories gekoppeld zijn.
2. Zorg dat je remote origin heet.
3. Controleer de synchronisatie tussen lokaal en remote.
4. Maak een .gitignore met minstens:
   - *.log
   - temp/
   - .env
5. Voeg een bestand toe dat door .gitignore genegeerd moet worden.
6. Controleer of Git dit bestand negeert.
7. Maak een commit met een correcte Engelstalige commit message.
Deel C – Branches (H3)
Je gaat nu twee afzonderlijke functionaliteiten ontwikkelen.

Branch 1: feature-games
1. Maak de branch aan.
2. Schakel naar deze branch.
3. Voeg drie games toe aan games.txt.
4. Maak minstens twee commits.
5. Push deze branch naar GitHub.
Branch 2: feature-developers
1. Ga terug naar main.
2. Maak de tweede branch.
3. Voeg drie developers toe aan developers.txt.
4. Maak minstens twee commits.
5. Push deze branch naar GitHub.
Controle: Je hebt nu drie branches op GitHub: main, feature-games en feature-developers.
Deel D – Merges en merge conflicts (H4)
Hier wordt het interessant. Je gaat bewust een conflict veroorzaken.
1. Schakel naar main.
2. Voeg een regel toe aan README.md waarin je de favoriete game vermeldt.
3. Commit deze wijziging.
4. Push de wijziging naar GitHub.
5. Schakel naar feature-games.
6. Wijzig dezelfde regel in README.md, maar vermeld een andere favoriete game.
7. Commit en push.
8. Probeer de wijzigingen van feature-games samen te voegen met main.
Opgelet
Git zal nu een merge conflict tegenkomen omdat hetzelfde stuk tekst in beide branches gewijzigd werd.

Los het conflict zelf op:
- Open README.md.
- Zoek de conflictmarkeringen.
- Beslis welke inhoud behouden moet blijven.
- Verwijder de conflictmarkeringen.
- Stage het opgeloste bestand.
- Rond de merge af met een commit.
Deel E – GitHub
1. Open GitHub.
2. Controleer of je branches zichtbaar zijn.
3. Open een Pull Request van feature-developers naar main.
4. Bekijk de wijzigingen.
5. Merge de Pull Request.
6. Controleer of de wijzigingen op main staan.

4. Extra examenvragen voor de praktijk
Deze vragen moet je kunnen beantwoorden zonder hulp.
1. Wat is het verschil tussen een fast-forward merge en een three-way merge?
2. Waarom kan Git soms niet automatisch mergen?
3. Wat betekent origin?
4. Waarom werk je met feature branches?
5. Wat is het verschil tussen git fetch en git pull?
6. Waarom is een Pull Request nuttig?
7. Wat gebeurt er wanneer je een branch verwijdert?
8. Waarom moet je na het oplossen van een merge conflict opnieuw git add uitvoeren?
9. Wat is het verschil tussen lokaal en remote branches?
10. Waarom is een goede commit message belangrijk?