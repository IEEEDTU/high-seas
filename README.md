# High Seas (IEEE DTU API)

### Installation

* Install [Git](https://www.git-scm.com/downloads) if you haven't yet.

* Install [Node v4](https://nodejs.org/en/download/package-manager) or above.

* Install NPM v3 using ``` sudo npm install -g npm ``` after installing Node.

* Install [Sails](http://sailsjs.org/get-started#?getting-started-installation) framework.

* Install the dependencies using ``` npm install```

* Test the installation by ``` sails lift ```

### Where's the API ?

The API is available at [localhost:1337/high-seas](http://localhost:1337/high-seas). Sails actually generates a new [Model](http://sailsjs.org/documentation/concepts/models-and-orm/models) "High-seas" (file located in ```api/models/High-seas.js```) and a [Controller](http://sailsjs.org/documentation/concepts/controllers) "High-seasController" ( file located in ```api/controllers/High-seasController.js```).  

Simply add routes in controller and some schema in model, and you'll have the bare API running.