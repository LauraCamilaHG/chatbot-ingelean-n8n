🤖 Chatbot INGE-LEAN - n8n Workflow

Este repositorio contiene un flujo de trabajo (`workflow`) para un chatbot desarrollado en N8N para la empresa INGE-LEAN, que ofrece soluciones en software, hardware, automatización industrial, inteligencia artificial y mantenimiento.

📂 Contenido

- `chatbot_INGELEAN_workflow.json`: Flujo exportado desde n8n.
- `README.md`: Documentación básica.
- `INGE_LEAN`: Diseño de página en html y css para interacción con el chatbot

🛠️ ¿Qué hace este flujo?

- Conecta Telegram con n8n
- Utiliza Google Gemini como modelo conversacional
- Realiza análisis de sentimientos
- Consulta una base vectorial (Qdrant) con embeddings
- Personaliza respuestas para los usuarios
- Permite interacción del usuario desde una interfaz web que lo enruta a un chat en Telgram

🏁 Cómo usarlo

1. Abre tu instancia de n8n.
2. Haz clic en los tres puntos (⋮) y selecciona Import.
3. Carga el archivo `chatbot_INGELEAN_workflow.json`.
4. Para ejecutar la interfaz web se debe cargar la carpeta en VS Code y ejecutar python -m http.server 8000

📍 Información de la empresa

- Dirección: CLL 29 #10-23 La Victoria, Pereira, Risaralda
- Teléfono: 311 4196803
- Web: https://dmpingelean.com/

---

✨ Autores:

- Laura Camila Hernández Giraldo
- Mateo Vega Castaño
- Oscar Mauricio Patiño Carvajal

Este flujo fue desarrollado en el marco de la Hakaton - Talento Tech.
