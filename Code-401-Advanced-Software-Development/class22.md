# Django start project 
------------------------
## In terminal 
```
-> take folder_name
-> poetry init -n
-> poetry add django
-> poetry add --dev black flake8
-> poetry shell
-> django-admin startproject project_name .
-> python manage.py migrate 
-> django-admin startapp app_name
-> code . 
```

## in vs-code 


- ### From **siting** go to **INSTALLED_APPS** and add **app_name** to list.     

- ### From views in app_name 
    - from django.views.generic import ListView_for_example
    - class NamePageListView(ListView)
    - template_name ='page_name.html'
- ### in app_name create urls.py and 
    - from django.urls import path 
    - from .views import (NamePageListView)
    - urlpattren=[
        
        path('' ,NamePageListView.as_view(), name='name_page' )
        
        ]

- ### take templates folder 
    - create pages.html 

- ### in project_name go to view 
    - import include 
    - add to -> list path(" ",include('app_name'))
- ### in sitting in  *TEMPLATES* list in 'DIRS': add
    - BASE_DIR / **'templates'**

- ### test your project
``` 
python manage.py test
```

--------------------------
--------------------------
# Django start **Model** / List View
### from app_name in models.py
```
from django.contrib.auth import get_user_model

class Name_app(models.Model):
    name = model.CharField(max_length=256)
    rating = models.IntegerField(default=0)
    reviewer = models.ForeignKey(get_user_model(),on_delete=models.CASCADE)
    def __str__(self):
        return  self.name
```   

    

