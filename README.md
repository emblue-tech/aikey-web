# Instrucciones para la Configuración de las Claves API

Para que este proyecto funcione correctamente, es necesario que reemplaces las claves API de prueba por tus propias claves. A continuación, encontrarás las instrucciones para realizar este cambio.

## Pasos para configurar las claves API

1. `TOGETHER_API_KEY`: Esta es la clave de API para el servicio Together. Debes obtenerla creando una cuenta en su plataforma y generando una clave en el panel de control de usuario.
   
2. `OPENAI_API_KEY`: Esta clave corresponde al servicio de OpenAI. Obtén una clave API registrándote en su sitio web y accediendo a tu perfil de desarrollador para generar una nueva clave.
   
3. `GEMINI_API_KEY`: Finalmente, la clave de Gemini Pro. Si aún no tienes una, puedes registrar una cuenta en Gemini y seguir las instrucciones para crear una clave API.

## Cómo reemplazar las claves API

Busca en tu código las siguientes líneas:

javascript
const TOGETHER_API_KEY = "<< YOUR API KEY >>";
const OPENAI_API_KEY = "<< YOUR API KEY >>";
const GEMINI_API_KEY = "<< YOUR API KEY >>";


Reemplaza `<< YOUR API KEY >>` con las claves API correspondientes que obtuviste en los pasos anteriores. Asegúrate de que la clave esté entre comillas y de no compartir tus claves API públicamente para mantener la seguridad de tu cuenta.

Una vez que hayas configurado las claves, guarda los cambios y el proyecto debería funcionar con tus credenciales de API.

