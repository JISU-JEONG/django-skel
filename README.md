# django-skel



## Start project

```cmd
$ django-admin startproject skel
```



### Start app

```cmd
python manage.py startapp skeleton
```



### Migrate

> 현재 migrations 폴더에 등록된 모델을 database에 등록

```cmd
python manage.py migrate
```



### makemigrations

> app에 선언한 모델을 자동적으로  migrations 폴더에 등록

```
python manage.py makemigrations
```



확실히 flask에 비해서 많이 모델을 등록하기 편한 것 같다.

flask도 alembic기반의 flask-migrate 라이브러리가 있지만 장고에 기능에 비해서는 편의성이 좋지 못한것 같기도..?