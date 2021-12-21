## Instructions to run this project locally:  
  
1. Clone repository:  
  
```console  
$ git clone  https://github.com/mdheerasinghe/Django-restful-APIs-to-perform-CRUD-.git
```  
2.Open the console change directory to onlinestore:  
  
```console cd  onlinestore 
 
```  
3. Set up DB:   
   
```console  
	python manage.py makemigrations   
	python manage.py migrate   
```  
   
4. Run the app:   
  
```console   
	python manage.py runserver  
```   
```api urls | App superuser: --> admin/password.1
http://127.0.0.1:8000/api/categories/
http://127.0.0.1:8000/api/categories/?id=1
http://127.0.0.1:8000/api/products/
http://127.0.0.1:8000/api/products/?id=1
http://127.0.0.1:8000/api/products/?category_id=1
``` 
Thanks for reading.

