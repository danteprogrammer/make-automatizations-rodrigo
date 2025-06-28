README - Proyectos de Automatización en Make.com
Autor: Rodrigo Alonso Quezada Ccahuana
Fecha: 2025

Este repositorio contiene blueprints (archivos .json) exportados desde Make.com, que representan flujos de automatización funcionales desarrollados como parte de mi formación autodidacta y experiencia práctica. Estos escenarios se pueden importar directamente en Make para su revisión, análisis o reutilización.

==============================================
LISTA DE PROYECTOS
==============================================

1. 01_Enviar_Correos_desde_Google_Sheets.json
   - Envía correos electrónicos a una lista de destinatarios almacenada en una hoja de cálculo de Google Sheets.
   - Luego actualiza el estado de cada fila con “enviado” si el correo fue entregado correctamente.

2. 02_Enviar_Correos_con_Adjuntos_y_Registrar_en_Sheets_y_Drive.json
   - Permite enviar correos con archivos adjuntos.
   - Guarda un registro del envío en Google Sheets.
   - Almacena los archivos enviados en una carpeta de Google Drive.

3. 03_Enviar_Emails_con_Google_Sheets_y_Gmail.json
   - Flujo básico para enviar correos desde una hoja de Google Sheets usando Gmail.
   - Ideal para automatizaciones sencillas.

4. 04_Extraer_Datos_de_Sheets_a_Data_Store.json
   - Toma datos de Google Sheets y los guarda en un Data Store interno de Make para su posterior consulta o análisis.

5. 05_Notificacion_por_Nuevo_Archivo_en_Carpeta_Compartida.json
   - Detecta la subida de nuevos archivos en una carpeta compartida de Google Drive.
   - Envía una notificación automática por correo electrónico vía Gmail.

6. 06_Clima_RapidAI_Meteostat_GoogleSheets.json
   - Integra Rapid AI y Meteostat para obtener datos del clima.
   - Registra los resultados automáticamente en Google Sheets.

7. 07_Chatbot_en_Slack_con_OpenAI.json
   - Crea un bot funcional en Slack que responde a mensajes usando la API de OpenAI (ChatGPT).
   - Útil para casos de soporte automático o bots personales.

==============================================
IMPORTANTE:
- Estos blueprints no incluyen claves API ni datos personales.
- Para funcionar correctamente, se deben volver a configurar las conexiones a Google, Slack, Gmail, etc.
- Para importar un blueprint en Make, ve a “Create a new scenario” y selecciona “Import blueprint”.

Gracias por revisar mis proyectos. Para más información, puedes contactarme a través de mi LinkedIn:
www.linkedin.com/in/rodrigoalonso-quezadaccahuana
