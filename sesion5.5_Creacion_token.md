# Creación de token en GitHub

## Los posibles errores para los que puedes necesitar el token son:

En GitHub, si intentas realizar una operación que requiere autenticación y no proporcionas un token de acceso personal o autenticación de otra manera, es posible que obtengas uno de los siguientes errores en la consola de Git que te indicará que debes autenticarte utilizando un token:

**1. fatal:** credential-cache unavailable; no unix socket support Everything up-to-date

**2. Error 403:** Este es el código de respuesta HTTP para "Prohibido". Si intentas acceder o modificar un repositorio en el que no tienes permisos adecuados, es probable que obtengas un error 403. Esto puede ocurrir cuando intentas hacer un push o pull en un repositorio privado o cuando realizas otras operaciones que requieren autenticación.

**3. Error 401:** Este es el código de respuesta HTTP para "No autorizado". Puede ocurrir si intentas acceder a recursos protegidos sin proporcionar credenciales válidas, como un token de acceso personal. Este error generalmente significa que necesitas autenticarte para realizar la acción.

**4. Error de autenticación:** Git puede mostrar un mensaje de error específico que indica que la autenticación ha fallado. Por ejemplo, si intentas hacer un push a un repositorio remoto y no estás autenticado, podrías ver un mensaje como el que mencionaste en tu pregunta original: "fatal: Authentication failed for 'https://github.com/..."

Estos son algunos de los errores comunes que puedes encontrar en la consola de Git si no estás autenticado adecuadamente. Cuando veas uno de estos errores, es una señal de que debes proporcionar credenciales válidas, como un token de acceso personal, para autenticarte y poder realizar la operación en GitHub.

## Creación del token en Github:

**1.** Vamos a la esquina superior derecha, donde se ubica tu perfil y damos clíc.

**2.** Nos desplazamos hasta abajo y damos clic en **settings**.

**3.** En la parte izquierda de la página nos desplazamos hasta abajo  damos clic en **<> Developer settings**.

**4.** Una vez dentro, nos ubicamos en la parte izquierda y desplegamos **"personal accces token"**.

**5.** Damos clic en **tokens (classic)**, y clic en **"Generate a personal access token"**.

**6.** Damos nombre a nuestro token, (es irrelevante el nombre que le demos).

**7.** En la opción **Expiration**, podemos seleccionar el tiempo de vigencia de nuestro token, si tu pc tuvo alguno de estos errores es recomendable la opción "no expiration", de lo contrario debes volver a crear el token cada vez que caduque.

**8.** Seleccionamos los permisos que tendremos una vez accedamos al token, si es un repositorios propio, selecciona todas las opciones para tener un manejo completo de tu repositorio.

**9.** Hacemos clic en **"Generate token"** y copiamos nuestro token.

**NOTA: Una vez copiado, es recomendable guardarlo en un lugar donde no lo pierdas y puedas encontrarlo facilmente, ya que no volverá a aparecer de nuevo y tendrás que generar uno nuevo si lo pierdes (es aconsejable crear un bloc de notas y guardarlo en tu pc, donde puedas ublicarlo con mayor facilidad).**

**Puedes ver el video explicativo haciendo clic** [aquí](https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/GitHub%20-%20Google%20Chrome%202023-09-14%2017-21-21%20(online-video-cutter.com).mp4?alt=media&token=034b2ab8-2224-4b30-85bc-133d45ce3c39).

## Pasos en consola:

**1. Crea un nuevo repositorio en GitHub:**

Primero, ve a la página de inicio de GitHub (https://github.com/) y asegúrate de haber iniciado sesión en tu cuenta. Luego, haz clic en el botón "New" (Nuevo) para crear un nuevo repositorio en línea. Sigue las instrucciones para configurar el nombre y otras opciones según tus necesidades.

**2. Clona el repositorio en tu máquina local:**

Abre tu terminal o consola en tu máquina local y navega al directorio donde deseas crear el nuevo repositorio. Luego, utiliza el siguiente comando para clonar el repositorio desde GitHub a tu máquina local (reemplaza **URL_DEL_REPOSITORIO** con la URL de tu repositorio en GitHub):

```git
git clone URL_DEL_REPOSITORIO
```

**3. Abre la carpeta del repositior con el cmd**

Dentro de la carpeta del repositorio vas a la barra de direcciones de la carpeta y escribes las letras **cmd** y das enter.

**4. Configura la URL del repositorio remoto con el token de acceso personal:**

A continuación, configura la URL del repositorio remoto para que utilice el token de acceso personal en lugar de la autenticación por contraseña. Ejecuta el siguiente comando (reemplaza **TU_TOKEN** con tu token de acceso personal y **NOMBRE_DE_USUARIO** con tu nombre de usuario de GitHub):

```git 
git remote set-url origin https://NOMBRE_DE_USUARIO:<TU_TOKEN>@github.com/NOMBRE_DE_USUARIO/NOMBRE_DEL_REPOSITORIO.git
```
Esto actualizará la URL remota 'origin' con tu token de acceso personal.

**5. Agrega y realiza tu primer commit:**

Agrega tus archivos al repositorio utilizando el comando git add y luego realiza tu primer commit con el comando git commit. Por ejemplo:

```git
git add .
git commit -m "Primer commit"
```
**6. Realiza un push inicial al repositorio en GitHub:**

Por último, utiliza el comando git push para enviar tus cambios al repositorio en GitHub:

```git
git push -u origin main
```

Esto configurará la rama 'main' (o la rama principal que hayas especificado) como la rama remota predeterminada y subirá tus cambios al repositorio en línea utilizando el token de acceso personal.

Una vez completados estos pasos, habrás iniciado un repositorio en GitHub y configurado la autenticación utilizando un token de acceso personal para las operaciones remotas. Puedes continuar trabajando en tu repositorio de manera normal y tus cambios se autenticarán utilizando el token.














