# BIA-810 Final Project presentation

The repository contains the two subparts(as submodules) of the final submission of the "Asynchorous video analyses of candidate interviews".

## Project Contributors
<a href="https://github.com/dunkeln"> <img src="https://avatars.githubusercontent.com/dunkeln" width="60px;" alt="dunkeln"/></a>
<a href="https://github.com/Priyanshusbisen"> <img src="https://avatars.githubusercontent.com/Priyanshusbisen" width="60px;" alt="Priyanshusbisen"/></a>
<a href="https://github.com/SriLasya09"> <img src="https://avatars.githubusercontent.com/SriLasya09" width="60px;" alt="SriLasya09"/></a>


## Application Demo

https://github.com/user-attachments/assets/f00997f9-740d-45f3-bcd5-a9f5bcbf28bb


## setting up the EC2 instance

*The instance is a flask app with a postgres database, all requirements are in requirements.txt*

```bash
# initiate AWS EC2 instance and clone `bia-backend` into it
# env keys to vertex and openai are to be added individually
# user also needs to install google-cloud-sdk into the instance
$ python3 main.py
```

## building the web app
```bash
# clone the `bia-webapp` submodule
$ yarn
$ yarn dev
# after server starts press `o` and press `<Enter>`, the app should run
# update .env, reference is provided in .env.example of the submodule
```

## Our primary elements in the tech stack

<div style="display: inline-flex; gap: 35px;">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/svelte/svelte-original.svg" style="width: 35px;" />    
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" style="width: 35px;" />    
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" style="width: 35px;" />    
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" style="width: 35px;" />    
</div>
          
          
          
