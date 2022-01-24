# 2022-django-blog-russian
Building A Blog Using Django 3.0.3
https://github.com/gurnitha/2022-django-blog-russian


#### 1. Installing django, create project and app

        modified:   README.md
        new file:   blog/__init__.py
        new file:   blog/admin.py
        new file:   blog/apps.py
        new file:   blog/migrations/__init__.py
        new file:   blog/models.py
        new file:   blog/tests.py
        new file:   blog/views.py
        new file:   manage.py
        new file:   siteblog/__init__.py
        new file:   siteblog/asgi.py
        new file:   siteblog/settings.py
        new file:   siteblog/urls.py
        new file:   siteblog/wsgi.py


#### 2. Create Homepage view/controller and urls

        modified:   README.md
        new file:   blog/urls.py
        modified:   blog/views.py
        modified:   siteblog/urls.py


#### 3. Transferring the template to the project

        modified:   README.md
        new file:   blog/templates/blog/index.html
        modified:   blog/views.py
        modified:   siteblog/settings.py
        new file:   siteblog/static/css/bootstrap.css
        ...
        new file:   siteblog/static/style.css
        new file:   templates/base.html


#### 4. Project models

        modified:   README.md
        new file:   blog/migrations/0001_initial.py
        modified:   blog/models.py


#### 5. Registration of models in the admin panel

        λ pip install django-ckeditor
        λ python -m pip install django-debug-toolbar
        λ python -m pip install Pillow

        modified:   README.md
        modified:   blog/admin.py
        modified:   siteblog/settings.py
        modified:   siteblog/urls.py


#### 6. Setting up the admin panel

        modified:   README.md
        modified:   blog/admin.py
        new file:   blog/migrations/0002_auto_20220123_2125.py
        new file:   blog/migrations/0003_auto_20220123_2133.py
        modified:   blog/models.py


#### 7. Menu template tag

        modified:   README.md
        modified:   blog/admin.py
        new file:   blog/migrations/0004_auto_20220123_2139.py
        modified:   blog/models.py
        new file:   blog/templates/blog/category.html
        new file:   blog/templates/blog/menu_tpl.html
        new file:   blog/templatetags/__init__.py
        new file:   blog/templatetags/menu.py
        modified:   blog/urls.py
        modified:   blog/views.py


#### 8. Highlight the active menu item

        modified:   blog/admin.py
        modified:   blog/models.py
        modified:   blog/urls.py
        new file:   media/photos/2022/01/24/blog-image2.jpg
        new file:   media/photos/2022/01/24/post-image1.jpg
        new file:   media/photos/2022/01/24/post-image3.jpg
        new file:   media/photos/2022/01/24/post-image9.jpg