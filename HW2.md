GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bug_reports
git branch SQL
git branch Charles
git branch Mobile_testing
```
***
2. Запушить все ветки на внешний репозиторий
```
git push --branches
 ```
***
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
4. Запушить структуру багрепорта на внешний репозиторий
```
$ git commit -am "bug reported"
$ git push -u origin Bug_reports  / git push --set-upstream origin Bug_reports
```
***
5. Вмержить ветку Bag Reports в Main
```
$ git checkout main
$ git merge Bug_reports
 ```
***
6. Запушить main на внешний репозиторий.
```
$ git push
 ```
***
7. В ветке CheckLists набросать структуру чек листа.
```
$ nano checklist.txt
 ```
***
8. Запушить структуру на внешний репозиторий
```
$ git commit -am "checklist added"
$ git push -u origin CheckLists / git push --set-upstream origin CheckLists
 ```
***
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main