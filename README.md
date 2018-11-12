# Django Personal Side Project
I have a visual portfolio running on Georgetown domains server. I took a personal initiative to use Python-Django paradigm to build the entire visual portfolio from scratch 



the link:
http://mc2153.georgetown.domains/



## Warning
1. I have not implemented any database model here, which Django is notoriously famous for using database model in backend. 
2. There are no Django tests but I highly recommend you to make them if you are using a database model to return HttpResponse
3. I have all the html codes prepared from the portfolio. All you have to do is to delete, clean, and insert Django logic into the prepared html codes with a header using jinja template


## Reminder
1. `pip3 or pip install Django`
2. `django-admin startproject mysite`
3. go to settings.py in mysite and add 'georgetown_domains' in INSTALLED_APPS 
4. go to urls.py in mysite and add ```path('', include('georgetown_domains.urls'))```