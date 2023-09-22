# apirest-typescript-mongo

Este es un proyecto de una API REST en TypeScript que utiliza varias dependencias para su funcionamiento. A continuación, encontrarás información sobre cómo configurar y ejecutar este proyecto.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd apirest-ts
   ```

3. Instala las dependencias del proyecto:

   ```bash
   npm install
   ```

## Configuración

Antes de ejecutar la aplicación, asegúrate de configurar las variables de entorno necesarias. Crea un archivo `.env` en el directorio raíz del proyecto y proporciona los siguientes valores:

```env
PORT=3000  # El puerto en el que se ejecutará la aplicación
MONGODB_URI=<URL_DE_TU_BASE_DE_DATOS_MONGODB>
JWT_SECRET=<TU_CLAVE_SECRETA_PARA_JSONWEBTOKEN>
```

## Ejecución

Una vez que hayas configurado las variables de entorno, puedes ejecutar la aplicación utilizando el siguiente comando:

```bash
npm run dev
```

La aplicación se ejecutará en el puerto especificado en el archivo `.env` (por defecto, en el puerto 3000).

## Dependencias

Este proyecto utiliza las siguientes dependencias:

- [bcryptjs](https://www.npmjs.com/package/bcryptjs) - Para el hashing de contraseñas.
- [cors](https://www.npmjs.com/package/cors) - Para habilitar el CORS en la aplicación.
- [dotenv](https://www.npmjs.com/package/dotenv) - Para la gestión de variables de entorno.
- [express](https://www.npmjs.com/package/express) - Para crear la aplicación web.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Para la autenticación basada en tokens JWT.
- [mongoose](https://www.npmjs.com/package/mongoose) - Para la interacción con la base de datos MongoDB.
- [multer](https://www.npmjs.com/package/multer) - Para el manejo de archivos en las solicitudes HTTP.
- [path](https://www.npmjs.com/package/path) - Para operaciones con rutas de archivos.

## Contribución

Si deseas contribuir a este proyecto, ¡no dudes en abrir un problema o enviar una solicitud de extracción!

## Licencia

Este proyecto está bajo la Licencia ISC. Para más detalles, consulta el archivo [LICENSE](LICENSE).
```

Solo copia y pega este código en tu archivo `readme.md` y asegúrate de reemplazar `<URL_DEL_REPOSITORIO>`, `<URL_DE_TU_BASE_DE_DATOS_MONGODB>`, y `<TU_CLAVE_SECRETA_PARA_JSONWEBTOKEN>` con los valores reales de tu proyecto. Luego, personaliza y expande el README según tus necesidades específicas.