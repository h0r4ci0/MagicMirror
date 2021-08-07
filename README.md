# MagicMirror
En este repositorio te guiaré para que puedas instalar y configurar tu Magic Mirror. Todos los plugins que añada los subiré aquí.

**1. Descargar e instalar la última versión de Node.js**

curl -sL https://deb.nodesource.com/setup_14.x | sude -e bash -

sudo apt install -y nodejs

**2. Clonar el repositorio**

git clone https://github.com/MichMich/MagicMirror

**3. Entrar en el repositorio**

cd MagicMirror

**4. Instalar MagicMirror**

npm install

**5. Hacer una copia del archivo de muestra de la configuración**

cp config/config.js.sample config/config.js

**6. Iniciar MagicMirror**

npm run start
