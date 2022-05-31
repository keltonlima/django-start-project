# django-start-project

1 - instalar venv python <br>
	sudo apt install python3-venv
	
2 - criar ambiente virtual <br>
	python3 -m venv django(nome_do_ambiente_virtual)
	
3 - ativar ambiente virtual <br>
	source nome_do_ambiente_virtual/bin/activate
	
4 - instalar pip no ambiente virtual <br>
	sudo apt install python3-pip
	
5 - instalar django no ambiente virtual <br>
	sudo apt install python3-django

6 - criar projeto django <br>
	sudo django-admin startproject nome_do_projeto . (por o ponto para não criar uma pasta, com o mesmo nome, dentro da outra)
	
7 - iniciar servidor 	<br>
	sudo python3 manage.py runserver
