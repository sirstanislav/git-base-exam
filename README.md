# git-base: Esame pratico

Si richiede di creare un fork del presente progetto.

Dovranno poi essere eseguite le seguenti operazioni:

* Staccare il branch exam a partire dal branch develop.
* Modificare il file commedia/canto1.md modificando la prima riga con il testo "Provando a imparar a usar lo Git"
* Comittare la modifica
* Pushare la modifica
* Mergiare il branch exam su master
* Risolvere eventuali conflitti in modo che sul branch master locale sia presente il testo inserito al punto 2
* Pushare su master.

Riportare i comandi git usati sul file onenote dell'esame insieme all'url del repository creato


git clone https://github.com/sirstanislav/git-base-exam.git
git checkout -b develop
git checkout -b exam
git branch
git add . && git commit -m 'new feature' && git push
git push --set-upstream origin exam
git checkout master
git merge exam
git push
