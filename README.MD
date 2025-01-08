
# Шпаргалка markdown

#  О чем файл ?
Здесь описаны шаги создания репозитория и работы с git



## создание реоизитория локально:
```
mkdir my_project
cd my_project
git init
```

###   Через интерфейс создать репозитрий на гитхаб

###  Связать удаленный и локальный репозитории

```
$ git remote add origin git@github.com:yulia-kudl/git_helper.git

```
### Проверить статус:

```
$ git remote -v

```


### Закомитить изменения ( в первый раз с флагами -u origin master


```

git push -u origin main

```

## коммит


```
git add --all
git commit -m "что измеилось"
git push
```
