# Aplicación socket de chat y productos

Desarrollo de un aplicación de chat socket. Gestioná información de categorias, productos, usuarios, busquedas, carga de archivos y autenticación de usuarios. Desarrollado como  tecnologías principales nodejs, expressjs, mongodb, mongoose, socket-io y google-auth.

## Instalación

```
git clone https://github.com/byZhetta/socket-chat.git
cd socket-chat
npm start
```

## Variables de entorno

Integrar las siguientes variables en un archivo .env

- `PORT` : puerto donde se ejecutará la aplicación
- `MONGODB_CNN` : URL de mongodb
- `SECRETORPRIVATEKEY` : Clave privada secreta de la aplicación (crearla)
- `GOOGLE_CLIENT_ID` : ID del cliente de google
- `GOOGLE_SECRET_ID` : ID secreto de google
- `CLOUDINARY_URL` : URL key de cloudinary (para almacenar las imágenes)

## Tecnologías principales

- cloudinary v1.24.0
- express v4.17.1
- google-auth-library v6.1.6
- jsonwebtoken v8.5.1
- mongoose v5.11.15
- socket.io v4.5.3