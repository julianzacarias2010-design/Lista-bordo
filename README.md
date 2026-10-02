# Lista Bordó A.J.T.T. — sitio interactivo

## Importante
La página es pública. **NO se pide login al entrar.**
Google se solicita únicamente cuando una persona intenta:
- apoyar/like una propuesta;
- comentar;
- sugerir una modificación o solicitud;
- enviar una propuesta nueva.

## Activar Google + Firestore
1. Crear un proyecto en Firebase.
2. Registrar una aplicación Web.
3. Authentication → Sign-in method → Google → habilitar.
4. Firestore Database → crear base de datos.
5. Copiar la configuración Web en `firebase-config.js`.
6. Cambiar `FIREBASE_ENABLED` a `true`.
7. Publicar las reglas de `firestore.rules`.
8. En Authentication → Settings → Authorized domains, agregar `TUUSUARIO.github.io`.

## GitHub Pages
Subí todos los archivos del proyecto al repositorio y activá:
Settings → Pages → Deploy from branch → main → / (root).

## Nota de privacidad
El correo de Google no se muestra en los comentarios. Se usa para autenticar la cuenta. Para producción conviene agregar moderación administrativa y validar roles antes de permitir que una cuenta edite contenido institucional.
