# Aplicación TTO

## Integrantes:

| Nombre   | Correo Electrónico   |
|-------------|-------------|
| Juan David Ardila  | jd.ardila12@uniandes.edu.co  |
| Diego Martin  | da.martin2@uniandes.edu.co |

## Instrucciones de Ejecución:

### Opción 1: Ejecutar el proyecto usando el APK generado

#### Paso 1: Transferir el APK al dispositivo Android
1. Copiar el APK generado desde tu computadora al dispositivo Android. Se puede transferir el archivo utilizando un cable USB.

### Paso 2: Habilitar la instalación de aplicaciones desde orígenes desconocidos
1. Abrir la configuración del dispositivo Android.
2. Ir a **Seguridad** o **Privacidad** (dependiendo de la versión de Android).
3. Activar la opción **Permitir instalaciones desde fuentes desconocidas** para el gestor de archivos o navegador que a usar para instalar el APK.

### Paso 3: Instalar el APK en el dispositivo
1. Utilizar el explorador de archivos en tu dispositivo para encontrar el APK transferido.
2. Tocar el archivo APK para iniciar la instalación.
3. Seguir las instrucciones en pantalla para completar la instalación.

### Paso 4: Ejecutar la aplicación
1. Después de que la aplicación esté instalada, abrir directamente la aplicación desde la notificación de instalación completa o buscar el ícono de la app en la lista de aplicaciones.
   

## **Opción 2: Clonar el proyecto desde GitHub y correr el código en Android Studio**

### Paso 1: Clonar el repositorio de GitHub
1. Abror una terminal de comandos en el computador.
2. Navegar hasta el directorio donde quieras clonar el proyecto.
3. Usar el siguiente comando para clonar el repositorio (cambia la URL por la de tu propio repositorio):
   
   ```bash
   git clone https://github.com/diegomartin81/MISW4302-JDA-DAM-Mobile.git
   ```

4. Una vez clonado, entra en el directorio del proyecto:

   ```bash
   cd MISW4302-JDA-DAM-Mobile
   ```
### Paso 2: Abrir el proyecto en Android Studio
1. Abrir Android Studio.
2. En la pantalla de inicio, seleccionar **File > Open**.
3. Navegar hasta la carpeta del proyecto clonado y seleccionar el directorio raíz donde está el archivo `build.gradle`. Android Studio comenzará a sincronizar las dependencias y el proyecto.
   
### Paso 3: Compilar el proyecto
1. Una vez que el proyecto esté cargado, asegurarse de que no haya errores en la sincronización.
2. Si Android Studio solicita instalar o actualizar dependencias o SDKs, permitir que lo haga.
3. Cuando el proyecto esté listo, seleccionar **Build > Make Project** o hacer clic en el botón de **Run** en la barra superior para compilar el proyecto.

### Paso 4: Ejecutar el proyecto en un emulador o dispositivo físico
1. Conectar un dispositivo Android al computador o configurar un emulador en Android Studio (hacerlo desde **Tools > AVD Manager**).
2. Seleccionar el dispositivo o emulador en la lista de dispositivos en la barra superior de Android Studio.
3. Hacer clic en el botón **Run** o seleccionar **Run > Run 'app'** para compilar y ejecutar el proyecto en el dispositivo o emulador.

---

### Notas adicionales:

- **Dependencias**: Asegurarse de que Android Studio descargue todas las dependencias necesarias especificadas en el archivo `build.gradle`. 
- **Configuración del emulador**: Se puede usar un emulador, se puede configurar uno en Android Studio desde **Tools > AVD Manager**. Seleccionar un dispositivo virtual y la versión de Android que se prefiera.
- **Problemas de sincronización**: Si se encuentra problemas de sincronización o construcción, asegurarse de tener instalada la versión correcta de Android SDK y las dependencias del proyecto.
