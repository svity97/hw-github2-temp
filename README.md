# Home work github 2
### 1. На локальном репозитории сделать ветки для:  
Postman - Jmeter - CheckLists - Bag Reports - SQL - Charles - Mobile testing 
```
git branch postman
git branch jmeter
git branch checklists 
git branch bag_reports 
git branch sql 
git branch charles 
git branch mobile_testing
```
### 2. Запушить все ветки на внешний репозиторий
```
git push --all  
```
### 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта 
```
git checkout Bag_Reports
cat >> bag_report1.txt
```
### 4. Запушить структуру багрепорта на внешний репозиторий
```
git add .
git commit -m "add bag report1" 
git push -u origin bag_reports 
```
### 5. Вмержить ветку Bag Reports в Main 
```
git checkout main
git merge bag_reports  
```
### 6. Запушить main на внешний репозиторий. 
```
git push
```
### 7. В ветке CheckLists набросать структуру чек листа. 
```
touch checklist1.txt
subl checklist1.txt
```
### 8. Запушить структуру на внешний репозиторий 
```
git add .
git commit -m "add checklist1"
git push -u origin checklists 
```
### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  
### 10. Синхронизировать Внешнюю и Локальную ветки Main
```
git pull
```

