## A simple Store CRUD REST_API(Heroku Deployment)

### stores-rest-api
Items, stores and authentication REST API for deployment on Heroku.

  ## Requirements
  ___
  Python 3.7+

  ## Instalation
  ___
  First, clone this repository.
  ```
  $ git clone http://github.com/Adebowale-Morakinyo/stores-rest-api
  ```
  After:
    - Get Heroku account.
    - Create new app.
    - Connect Heroku account with your Github account(Have this repo in your account).
    - Search and select the right repo.
    - Deploy branch.
    - Test the api with your favourite API testing tool.
   
  ## About some files(configuration) 
    >runtime.txt tells Heroku what language plus version to use.
    >libaries in use are in requirements.txt(Heroku reads automatically).
    >uwsgi.ini contains configuration parameters for the uswgi(on Heroku) to run the app.
    >Procfile contains the Dyno(server) to use in Heroku.


