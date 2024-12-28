
#   Spring MVC  

## MVC Architecture 

* MVC stands for Model-View-Controller is a design pattern that is commonly used for developing and organizing the code of the application.

* Spring MVC (Model-View-Controller) is a framework within the Spring Framework that provides a comprehensive solution for building web applications. 
  
* It follows the MVC design pattern to separate concerns: the Model handles data, the View displays the data, and the Controller processes user input.
  
* Spring MVC integrates with various view technologies(like JSP, Thymeleaf) and can handle HTTP requests via @Controller annotations.
  
* It simplifies request handling with flexible routing and robust features like data binding, form validation, and exception handling.

* Spring MVC supports RESTful APIs, making it suitable for both web and service-oriented applications.

### Model
* In MVC, model responds to the rerequest from the controller,and it retrives, manipulates data as required.
* Model notifies the view through controller with respect to changes in the data that needs to be updated in the view.

### View

* Responsible for rendering the user interface (UI). It displays the data received from the Model and updates the UI based on changes to the Model. 
  The View is the visual representation that the user interacts with.

### Controller
* Acts as an intermediary between the Model and the View.
* It listens to user input(like button clicks or form submissions), processes the input, and updates the Model as needed.
* Once the Model is updated, the Controller selects the appropriate View to present to the user.
* Example: A user submits a form to update an employee's information, and the Controller processes the form data, updates the Model, and selects a View to confirm the update.

### Flow in Spring MVC 
* User Interaction: The user interacts with the View (e.g., clicks a button or submits a form).
* Controller Processing: The Controller receives the input, processes it (e.g., validates or manipulates data), and interacts with the Model.
* Model Update: The Model updates the data based on the Controller's instructions (e.g., fetching or updating information from a database).
* View Update: The Controller then selects the appropriate View to display the updated data from the Model.
* User Sees the Updated View: The user sees the updated interface reflecting the changes made in the Model.

### References
* Spring MVC in YouTube  - [click here](https://www.youtube.com/watch?v=g2b-NbR48Jo)
* Spring MVC in Github - [click here](https://github.com/navinreddy20/Spring-MVC-Tutorial)
* Spring MVC Document - [click here](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mvc.html)


