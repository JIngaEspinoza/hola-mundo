# Hola-mundo
primer repositorio de prueba
# Comandos para clonar:
git clone url

# Para identificarse:
git config --global user.name "nombre"
git config --global user.email "correo"

# Conectar git con github con ssh key
ssh-keygen
cat ~/.ssh/id_rsa.pub

# Crear un repositorio en local y iniciar
git init

# Crear un archivo:
touch README2

# Agregar al repositorio:
git add README2

# Ver el stado
git status

# Agregar la descripcion al archivo
git commit -m "este es el primer archivo desde mi computadora"

# Conectar el repositorio local con github:
git remote add origin "url"


# Hacer un pedido al servidor:
git pull origin master(descarga el contenido del github al local)

# Enviar cambios del local al github
git push origin master(el contenido del local sube a github)


