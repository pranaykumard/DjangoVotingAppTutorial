# DjangoVotingAppTutorial  
This is a sample tutorial provided in django documentation.  
  
------------------Tutorial-1:Requests and Response -------------     
  
Initially install all the prerequisites needed for the project   
1.Django 3.2   
2.pip latest version   
3.virtual environment   
  
Run the command to create a basic site like hello world   
django-admin startproject mysite    

mysite directory is created and it contains     
1.settings.py( Change settings of site )   
2.asgi.py( Used for asgi supported servers)   
3.wsgi.py (Used for wsgi supported servers)   
4.urls.py ( This is where all the url paths are present)   
   
Check the starting website:   
python manage.py runserver   
To change port, python manage.py runserver [portnumber]   
      
Now add polls application using command(execute it at manage.py path)    
python manage.py startapp polls    
      
1.Create a view using HttpResponse   
2.Add that view to urls.py(create it as it wont be present) using path function   
3.Add this url into mysite urls.py file using include method   
  

  
  

