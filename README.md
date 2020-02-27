#Routes on Rails!#

###What are they?###

Routes are HTTP methods that your computer and a server use to communicate with each other over the internet.
More specifically, routes are linked to what we call CRUD actions in our Rails controllers.

1. C *Create (Post)*
2. R *Read (Get)*
3. U *Update (Put)*
4. D *Destroy (Delete)*

These CRUD actions directly relate to the Model/View/Controller pattern of app design commonly used in Rails.
Specifically, routes link the User directly to the Controller arm of the MVC framework which handles all of the CRUD operations for our app. 

```
  def index
  end

  def show
  end

  def new
  end

  def create
  end

  def edit
  end

  def update
  end

  def destroy
  end
```

This is a sample of what a Controller would look like in an MVC style application.
Our Routes take User requests (what you type in the search bar), finds the correct route for what you've chosen, then leads you to that corresponding method on the controller. 

Let's say you wanted to see the homepage of a website. Most likely you would be looking to visit the Index of that webpage which has likely been labeled as the "root" or first page a user should see upon loading. By simply typing in the url web address, a request would be sent to the Controller for that webpage, the controller would then grab the corresponding View (remember our MVC model?) and then return that View to the user. 

