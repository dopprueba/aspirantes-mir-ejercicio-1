Pasos en entorno windows:

1. Abrir la consola e imprimir la ubicación actual.
CD

2. Abrir la consola e imprimir la ubicación actual.
cd Desktop	

Crear carpeta
mkdir ejercicios

3. Cambiar la ubicación a la nueva carpeta que crearon.
cd ejercicios

4. Abrir la carpeta con VSCode.

5. Crear carpeta desde la terminal de vscode.
mkdir ejercicio1
cd ejercicio1

6. Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
echo '' > readme.md

7. Configurar nombre e email globalmente en git.
git config --global user.name "dairo"
git config --global user.email dairojop@gmail.com

8. Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
git init

9. Crear un primer commit con el mensaje “Versión Inicial”.
git commit -m "Versión Inicial"
