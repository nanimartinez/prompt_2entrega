Instalación de la librería: !pip install -U -q google-generativeai instala la librería de Google Generative AI.
Configuración de la API key: Se obtiene la API key de tu cuenta de Google Cloud y se guarda en la variable GOOGLE_API_KEY.
Creación del modelo: Se define el modelo a usar (gemini-1.5-flash) y se configura la generación de texto con generation_config.
Instrucciones del sistema: Se establecen las instrucciones para el modelo, explicando que es el asistente virtual de CIICAP y cuál es su rol.
Inicio del chat: Se inicia una sesión de chat y se crea una lista para almacenar el historial de mensajes.
Función chat(): Define el loop principal del chat.
Obtiene la entrada del usuario.
Envia el mensaje al modelo.
Imprime la respuesta del modelo.
Actualiza el historial de chat.