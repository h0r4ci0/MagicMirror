# Instalación

**1. Descargar e instalar la última versión de Node.js**
```
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
```
```
sudo apt install -y nodejs
```
**2. Clonar el repositorio**
```
git clone https://github.com/MichMich/MagicMirror
```
**3. Entrar en el repositorio**
```
cd MagicMirror
```
**4. Instalar MagicMirror**
```
npm install
```
**5. Hacer una copia del archivo de muestra de la configuración**
```
cp config/config.js.sample config/config.js
```
**6. Iniciar MagicMirror**
```
npm run start
```
