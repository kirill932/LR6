# Лабораторная работа №6

Цель лабораторной работы: изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удалённым репозиторием.

## Ход работы

### Скриношоты представлены в папке screenshots

1. Аккаунт на github уже был.
2. Сделана копия в личное хранилище из
https://github.com/Kurtyanik/LR6/.
3. Git уже был установлен.
4. Настроен клиент git, введено имя пользователя (Группа
Фамилия И.О.) и email.

![](screenshots/screen1.png)

5. Клонирован свой личный удалённый репозиторий на компьютер.

![](screenshots/screen2.png)

6. Добавлен файл через интерфейс GitHub. Подтянуты изменения в
локальный репозиторий.

![](screenshots/screen3.png)
![](screenshots/screen4.png)

7. Получена история операций для каждой из веток.

![](screenshots/screen5.png)

8. Просмотрены последние изменения.

![](screenshots/screen6.png)

9. Выполнено слияние в ветку master, разрешён конфликт.

![](screenshots/screen7.png)

![](screenshots/screen8.png)

![](screenshots/screen9.png)

![](screenshots/screen10.png)

![](screenshots/screen11.png)

![](screenshots/screen12.png)

10. Удалена побочная ветка после успешного слияния.

![](screenshots/screen13.png)

11. Сделаны и зафиксированы изменения, оставлены комментарии.

![](screenshots/screen14.png)
![](screenshots/screen15.png)
![](screenshots/screen16.png)
![](screenshots/screen17.png)

12. Сделан откат коммита.

![](screenshots/screen18.png)

13. Создана ветка для отчёта.

![](screenshots/screen19.png)

14. Получена история операций в форматированном виде

![](screenshots/screen20.png)

## Лог команд

	git clone
	git add
	git commit -m
	git push
	git show
	git branch
	git checkout
	git log
	git merge
	git branch -d
	git revert HEAD
	git push
	git log --pretty=format:"%h %ad %an %s" --date=short
	git config --global user.name
	git config --global user.email

## Вывод

В ходе лабораторной работы были изучены базовые возможности системы управления версиями, получен опыт работы с Git Api и локальным и удаленным репозиториями, 
также был получен опыт работы с Markdown.
