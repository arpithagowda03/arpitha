git init

git config user.name "arpithagowda03"

git config user.email "arpithahm34@gmail.com"

git config --list | findstr user

git remote add origin https://github.com/arpithagowda03/updated_survival_map.git

git remote -v

git remote show origin

git branch development

git checkout development

git checkout master

git checkout -b feature/map-improvements

git add README.md
git commit -m "Add README.md - Project documentation"

git add requirements.txt
git commit -m "Add requirements.txt - Python dependencies"

git add manage.py
git commit -m "Add manage.py - Django management script"

git add setup.sh
git commit -m "Add setup.sh - Setup automation script"

git add survivalmap/__init__.py
git commit -m "Add survivalmap/__init__.py - Package initialization"

git add survivalmap/settings.py
git commit -m "Add survivalmap/settings.py - Django settings configuration"

git add survivalmap/urls.py
git commit -m "Add survivalmap/urls.py - URL routing configuration"

git add survivalmap/wsgi.py
git commit -m "Add survivalmap/wsgi.py - WSGI application entry point"

git add core/__init__.py
git commit -m "Add core/__init__.py - Core app initialization"

git add core/models.py
git commit -m "Add core/models.py - Database models for locations"

git add core/admin.py
git commit -m "Add core/admin.py - Django admin configuration"

git add core/views.py
git commit -m "Add core/views.py - View functions for map and authentication"

git add core/urls.py
git commit -m "Add core/urls.py - Core app URL patterns"

git push -u origin feature/map-improvements

git checkout development

git merge feature/map-improvements

git push -u origin development

git pull origin development

git checkout master

git merge development

git push -u origin master

git pull origin master

git branch -a

git branch -v

git branch -vv

git branch -r

git status

git log --oneline

git log --oneline --graph --all

git log --oneline --graph --all --decorate

git log --oneline --graph --all -10

git log --oneline --all | measure-object -line

