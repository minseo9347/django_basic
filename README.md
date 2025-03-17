# django_basic

 ```
 장고 기본 익히기
 ```
# 디렉토리 만들기
```
mkdir django4_ex
cd django4_ex
```

# conda 가상환경 만들고, 활성화 하기
```
 - 이름 : dj4_env   conda create –n dj4_env python=3.12
 - Python : 3.12    conda activate dj4_env
```

# 라이브러리 설치
```
pip install django
pip install django==4.2 (특정버전)
pip show django
```

# 프로젝트 생성
```
django-admin startproject doit_django .

doit_django = 파일이름
. = 현재 디렉토리에 프로젝트를 만든다.

```

# Django 기본 DB생성 명령
```
python manage.py migrate - 생성 명령
ls = db 생성 확인
```

# django 서버 실행 및 확인
```
python manage.py runserver
사용자 페이지 = http://127.0.0.1:8000/
관리자 페이지 = http://127.0.0.1:800/admin
```

# 관리자 아이디 만들기
```
python manamge.py createsuperuser

 Id : 
 Pw : 비밀번호 8자리 이상
```
# github 레포지토리
```
 - 레포지토리 이름 : django_basic    
 - README.md, .gitignore 파일 생성   
 - 로컬 컴퓨터와 연동하기           git clone git_url
```
