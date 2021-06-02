#### 1. Explain Django Architecture?
Django follows the MVT (**Model View Template**) pattern which is based on the Model View Controller architecture. It’s slightly different from the MVC pattern as it maintains its own conventions, so, the controller is handled by the framework itself. The template is a presentation layer. It is an HTML file mixed with Django Template Language (DTL). The developer provides the model, the view, and the template then maps it to a URL, and finally, Django serves it to the user.

* The Model is the logical data structure behind the entire application and is represented by a database(generally relational databases such as MySql, Postgres).
* The View is the user interface — what you see in your browser when you visit a website. These are represented by HTML/CSS/Javascript files.
* The Controller is the middleman that connects the view and model together, meaning that it is the one passing data from the model to the view.
