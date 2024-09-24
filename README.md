# puppeteer-daybeat
Proyecto ejecutable para diligenciar tareas diarias en Daybeat.

## Instalación
1. Clonar el repositorio.
2. Instalar las dependencias con `npm install` dentro del repositorio.
3. Crear un archivo `.env` en la raíz del proyecto con las siguientes variables:
```env
LINK_DAYBEAT='link de acceso a daybeat'
COMPANY='compañia'
USERNAME_DAYBEAT='usuario daybeat'
PASSWORD='contraseña'
```
4. Se puede probar el proyecto ejecutando `node .\index.js` dentro de la carpeta del repositorio.

## Ejecución con bat
Dentro de la raiz hay una carpeta llamada `bat` con un archivo `testBatDaybeat.bat` que ejecuta el proyecto y se puede programar para que se ejecute en un horario específico. Sin embargo, para que funcione el ejecutable siga estos pasos:
1. Abre el archivo `testBatDaybeat.bat` con un editor de texto.
2. Reemplaza la ruta `D:\PYT\apps\node\puppeteer-daybeat` por la ubicación del proyecto donde lo haya clonado.
3. Guarda los cambios.

Con esto, el archivo `.bat` ejecutará el proyecto en la ubicación donde se haya clonado.