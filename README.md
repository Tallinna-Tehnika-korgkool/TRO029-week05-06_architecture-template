## Esitamise kord

Harjutuse edukaks esitamiseks **pead töötama oma isiklikus GitHub Classroomi repos**, mis on loodud selle nädala jaoks.

1.  **Ava ülesande link Moodle'ist:**
    - Mine kursuse Moodle'i lehele.
    - Leia sealt selle nädala (Week 05-06) ülesande juurest link oma isikliku GitHub Classroomi repositooriumi loomiseks.

2.  **Klooni enda isiklik repo GitHubist**, mille nimi sisaldab sinu GitHubi kasutajanime.
    Näide:
    ```bash
    git clone https://github.com/Tallinna-Tehnika-korgkool/TRO029-week05-06_architecture-<sinu_kasutajanimi>
    ```

3.  **Tee kõik ülesanded selles kloonitud repos.**

4.  **Lisa ja `commit`'i oma muudatused.**
    ```bash
    git add .
    git commit -m "docs: Complete week 5-6 exercise"
    git push
    ```

5.  Kui `push` on tehtud, käivituvad **automaatsed testid** (GitHub Actions) sinu repo **Actions** vahekaardil.
    - ✅ **Roheline** ✔️ tähendab, et kõik on korras.
    - ❌ **Punane** ✖️ tähendab, et midagi on puudu või valesti – paranda ja tee uus `commit` ja `push`.

> **NB!** Kui töötad väljaspool oma isiklikku Classroom repo't, siis testid ei tööta ja harjutust ei loeta esitatuks.
