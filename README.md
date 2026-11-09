# swe2_2026_uebung

Repo zur Übung in SWE2 im WiSe 2026/27

Wir testen folgendes Procedere: 

1. `feature/xyz` auschecken und dort Änderungen durchführen, inkl. Commits
2. `git fetch` ausführen, um sicherzustellen, dass die lokale Kopie von `origin/main` aktuell ist
3. im Branch `feature/xyz`: **nicht** `git push` sondern `git rebase origin/main` (**Achtung :** wenn Ihr Hauptbranch, in den Sie mergen möchten, anders heißt, z.B. `dev`, dann ist es natürlich `git rebase origin/dev`)
3. alle Konflikte (in `feature/xyz`) lösen 

    - Konfliktadatei bearbeiten, um Konfliktmarkierung zu enfernen
    - `git add <konfliktdatei>`
    - `git rebase --continue`

    Dieser Prozess wiederholt sich, bis alle Commits des Feature-Branches erfolgreich "neu angewendet" wurden. --> Commit-Messages können nicht verändert werden!

4. `feature/xyz` pushen (`git push --force-with-lease -u origin feature/xyz`) und dann `Pull request` für den FFM nach `main` in *GitHub* erstellen
5. BN: Uebung

JF: Änderung in main
JF: noch eine Änderung in main



Sa: Änderung in der branch