# Github / Gitlab
## Cheatsheet für Commands

### 🤔 _Was ist Git?_ 🤔
> Git ist eine Versionierungs-Software, die es erlaubt die Veränderungen eines Files zu tracken und im Notfall wieder herzustellen.
> Git eignet sich also primär für Coding-Projekte

### 👨‍💻 _Commands_ 👨‍💻
📦 _Neues lokales Repo erstellen_ 📦
```sh
cd <Ordner für neues Repo>
git init
```
🔃 _Existierendes Repo klonen_ 🔃
```sh
git clone www.github.com/pfad/zum/repo
```
📤 _Änderungen auf jetziges Repo hochladen_ 📤
```sh
git add <geändertes File>
git commit -m "Zusammenfassung der Änderungen"
git push origin <Branch für den Push>
```
🔃 _Lokales Repo syncen_ 🔃
```sh
git pull
```
🔀 _Einen Branch zum Master mergen_ 🔀
```sh
git merge <Name des zu mergenden Branches>
```
🗑️ _Ein File im Branch entfernen_ 🗑️
```sh
git rm <Name des zu entfernenden Files>
```
🔎 _Einen spezifischen String im Git-Repo finden_ 🔎
```sh
git grep "string"
```
✂️ _Lokales Repo optimisieren_ ✂️
```sh
git gc
```
🗄️ _Repo archivieren_ 🗄️
```sh
git archive --format=tar <Branch-Name>
```
🧰 _Git Filesystem prüfen_ 🧰
```sh
git fsck
```