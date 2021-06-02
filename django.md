#### 1. Explain Django Architecture?
Django follows the MVT (**Model View Template**) pattern which is based on the Model View Controller architecture. It’s slightly different from the MVC pattern as it maintains its own conventions, so, the controller is handled by the framework itself. The template is a presentation layer. It is an HTML file mixed with Django Template Language (DTL). The developer provides the model, the view, and the template then maps it to a URL, and finally, Django serves it to the user.

##### Model 
A model in Django refers to a class that maps to a database table or database collection. Each attribute of the Django model class represents a database field

#####  View  
is the user interface — what you see in your browser when you visit a website. These are represented by HTML/CSS/Javascript files.

#####  Controller  
is the middle man that connects the view and model together, meaning that it is the one passing data from the model to the view.
