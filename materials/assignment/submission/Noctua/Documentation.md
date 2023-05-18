# Job Portal
Django Job Portal.       


## Project Structure

```bash
< PROJECT ROOT >
   |
   |-- account/                              
   |    |-- admin.py                   
   |    |-- apps.py                        
   |    |-- forms.py                       
   |	|-- managers.py
   |    |-- models.py
   |    |-- urls.py
   |    |-- views.py
   |	
   |-- job/
   |    |-- asgi.py
   |    |-- settings.py
   |    |-- urls.py
   |    |-- wsgi.py
   |
   |-- jobapp/
   |    |-- admin.py                   
   |    |-- apps.py                        
   |    |-- forms.py                       
   |	|-- managers.py
   |    |-- models.py
   |    |-- urls.py
   |    |-- views.py             
   |    |
   |-- static/
   |    |-- <bs4, css, JS, images>         
   |    |
   |-- templates/                     
   |         |-- account/                 
   |         |    |-- employee-edit-profile.html      
   |         |    |-- employee-registration.html     
   |         |    |-- employer-registration.html     
   |         |    |-- login.html               
   |         |
   |         |-- jobapp/                   
   |         |    |-- all-applicants.html  
   |         |    |-- applicant-details.html             
   |         |    |-- dashboard.html    
   |         |    |-- employee-edit-profile.html
   |         |    |-- index.html
   |         |    |-- job-edit.html
   |         |    |-- job-list.html   
   |         |    |-- job-single.html
   |         |    |-- paginator.html
   |         |    |-- post-job.html
   |         |    |-- result.html
   |         |    |-- search.html     
   |         |
   |         |-- base.html                
   |         |-- footer.html            
   |         |-- head.html         
   |         |-- header.html
   |         |-- messages.html
   |         |-- scripts.html
   |
   |-- requirements.txt                     
   |                               
   |-- manage.py                            
   |
   |-- ************************************************************************
```
## Design Choices
The system is a job portal that allows employees to search for available jobs, apply for said jobs, while employers on the other hand, posts an opening. 

The main data models used in the application are Category, Job, Applicant, and BookmarkJob. These models can perform Create, Read, Update, Delete (CRUD) operations. Some of the tools and languages that are used include Python, which is the main programming language; Django, as the web framework; HTML, which creates the base structure of the system; and CSS, which is used for styling the system.

## Assumptions


![Settings Window](https://raw.github.com/Sany07/Django-Job-Portal/master/screenshots/screencapture-127-0-0-1-8000-2020-05-08-17_03_46.png)

![Settings Window](https://raw.github.com/Sany07/Django-Job-Portal/master/screenshots/screencapture-127-0-0-1-8000-jobs-2020-05-08-17_40_01.png)

![Settings Window](https://raw.github.com/Sany07/Django-Job-Portal/master/screenshots/screencapture-127-0-0-1-8000-job-79-2020-05-08-16_59_55.png)

![Settings Window](https://raw.github.com/Sany07/Django-Job-Portal/master/screenshots/screencapture-127-0-0-1-8000-job-create-2020-05-08-17_00_46.png)

![Settings Window](https://raw.github.com/Sany07/Django-Job-Portal/master/screenshots/screencapture-127-0-0-1-8000-dashboard-2020-05-08-17_01_07.png)

![Settings Window](https://raw.github.com/Sany07/Django-Job-Portal/master/screenshots/screencapture-127-0-0-1-8000-dashboard-employer-job-54-applicants-2020-05-08-17_01_34.png)

<div align="center">
    <h3>========Thank You=========</h3>
</div>
