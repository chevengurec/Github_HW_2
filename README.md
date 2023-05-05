# Github_HW_2
1. На локальном репозитории сделать ветки для:

- Postman         -> git branch Postman
- Jmeter          -> git branch Jmeter   
- CheckLists      -> git branch CheckLists
- Bag Reports     -> git branch BagReports
- SQL             -> git branch SQL
- Charles         -> git branch Charles
- Mobile testing  -> git branch MobileTesting



2. Запушить все ветки на внешний репозиторий 

-> git push origin --all


3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

-> git checkout BagrReports

-> cat > bag_reports.txt

-> Название: Не работает кнопка отправки заказа.

Как воспроизвести?

1. Открыть сайт *.

2. Нажать по ссылке *.

3. Пролистать до поля *.

4. Ввести значение в поле *.

5. Попытаться нажать кнопку отправки заказа.

Фактический результат: кнопка неактивна.

Ожидаемый результат: кнопка нажимается, можно сделать заказ.

-> Ctrl+C



4. Запушить структуру багрепорта на внешний репозиторий

-> git add .

-> git commit -m "adding bag_reports.txt"

-> git push -U origin BagReports


5. Вмержить ветку Bag Reports в Main

-> git checkout main

-> git merge BagReports



6. Запушить main на внешний репозиторий.

 -> git add .

 -> git push -u origin main


7.В ветке CheckLists набросать структуру чек листа.

->  git checkout CheckLists

-> cat -> checklist.txt

-> 1. ID
2. Task
3. Staus

-> Ctrl+C


8. Запушить структуру на внешний репозиторий


-> git add .


-> git commit -m "adding checklist.txt"


->  git push -u origin Checklists


9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

-> Compare & pull request 

-> merge


10. Синхронизировать Внешнюю и Локальную ветки Main

-> git checkout main
 
-> git pull
