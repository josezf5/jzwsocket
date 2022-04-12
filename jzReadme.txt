https://websockets.readthedocs.io/en/stable/intro/tutorial3.html

Este ejemplo no necesita estar en xampp\htdocs

se tuvo que crear una cuenta en heroku
10-Abr-22
Heroku
josearturo.zf@gmail.com
psswd: josehero5754_
https://dashboard.heroku.com/apps

heroku create jzwebsockets
   respondio
   https://jzwebsockets.herokuapp.com/ | https://git.heroku.com/jzwebsockets.git

Tabien se tuvo que crea otra cuenta en gitHub
https://github.com/join/recommended_plan
josearturo.zf@gmail.com
psswd: jzgghh5754_  
user: josezf5

hay un error en el turorial 
  git push heroku , debe ser 
  git push heroku main

Finalmente tuve que crear otra rama llamada
polar-temple-15218
Se instalaron los archivos en esta rama en el servifor
En el local está en C:\xampp\htdocs\HTML\websocket\jzwsocket
para probar
python -m websockets wss://polar-temple-15218.herokuapp.com/

para subir al repositorio de github
   git push -u origin master 
is used for pushing local content to GitHub.
In the code, the origin is your default remote repository name and '-u' flag is upstream, which is equivalent to '-set-upstream.' and the master is the branch, name.upstream is the repository that we have cloned the project.
Fill in your GitHub username and password.