#### 1. Explain Django Architecture?
Django follows the MVT (**Model View Template**) pattern which is based on the Model View Controller architecture. It’s slightly different from the MVC pattern as it maintains its own conventions, so, the controller is handled by the framework itself. The template is a presentation layer. It is an HTML file mixed with Django Template Language (DTL). The developer provides the model, the view, and the template then maps it to a URL, and finally, Django serves it to the user.

##### Model 
A model in Django refers to a class that maps to a **database table** or database collection. Each attribute of the Django model class represents a **database field**

#####  View  
They generally comprise HTML, CSS, and js in which dynamic variables and information are embedded with the help of views

#####  Template  
web request and returns a web response

#### 2. What is Django ORM?
This ORM (an acronym for Object Relational Mapper) enables us to **interact with databases** in a more pythonic way like we can **avoid writing raw queries**

#### 3. Explain user authentication in Django?
Django comes with a built-in user authentication system, which handles objects like users, groups, user-permissions, and few cookie-based user sessions. Django User authentication not only authenticates the user but also authorizes him.

The system consists and operates on these objects:

Users
Permissions
Groups
Password Hashing System
Forms Validation
A pluggable backend system
