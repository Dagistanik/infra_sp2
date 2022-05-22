## Проект: запуск docker-compose.

### Описание


#### Инструкция по развёртыванию
* Клонировать репозиторий и перейти в него в командной строке:
```python
git clone https://github.com/Dagistanik/infra_sp2.git
```
```python
cd infra_sp2
```
* Cоздать и активировать виртуальное окружение:
```python
python -m venv venv
```
```python
source venv/Scripts/activate
```
* Установить зависимости из файла requirements.txt
```python
python -m pip install --upgrade pip
```
```python
pip install -r requirements.txt
```
* Запустить сервер
```python
python manage.py runserver
```
#### Язык

* Python 3.7

#### Стек технологий

* Python 3
* ООП
* Django
* Django REST Framework
* PostgreSQL
* Git 
* Pytest
* Docker
* NGINX
