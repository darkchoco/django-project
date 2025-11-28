# Python & Django Project

## History
[변경 이력 보기](CHANGELOG.md)

## List of projects (Alphabetical order)

### blog-bs5-django5 : Blog using BS5 and Django5
https://github.com/saintdragon2/do_it_django_a_to_z 참조.  

> [!NOTE]  
> * `django-admin`이 따로 프로젝트 루트 디렉토리를 만들지 않는다. 즉 Django 프로젝트를 만드려면 먼저 해당 폴더를 만든 후 그 안에서 진행하도록 한다.  
> * `django-admin`으로 만드는 프로젝트 이름에 `-`는 허용되지 않는다.  

```
(blog-bs5-django5) Z:\lab_ext\venv>cd ..\06-python-django\django-project\blog-bs5-django5\blog_dj5

(blog-bs5-django5) Z:\lab_ext\06-python-django\django-project\blog-bs5-django5\blog_dj5>django-admin startproject blog_dj5 .
```

## Notes

### GitHub 계정 고정
이 프로젝트는 여러 PC에서 작업 중이지만 `darkchoco` 계정으로 고정되어 있다.  
아래 내용을 참조한다.  

```Bash
$ git init

$ git remote add origin git@github_darkchoco:darkchoco/django-project.git  <-- .ssh/config 내 github_darkchoco 참조.

$ git config user.name "darkchoco"

$ git config user.email "darkchoco@..."
```
