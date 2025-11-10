# Proyecto Urban Grocers 
Durante este proyecto, participé en la validación funcional y automatizada de una aplicación de mapas cuyo objetivo era calcular rutas, mostrar ubicaciones y optimizar trayectos en tiempo real.

Actividades realizadas

Analicé los requerimientos del sistema y diseñé casos de prueba funcionales para validar búsquedas de direcciones, cálculo de rutas, puntos intermedios y tiempos estimados de llegada.

Realicé pruebas manuales sobre la interfaz de usuario verificando la exactitud de los resultados de búsqueda, la correcta visualización del mapa y la respuesta ante errores de entrada.

Usé Postman para probar los endpoints del API de geolocalización, comprobando que devolvieran respuestas HTTP 200 y datos JSON consistentes.

Implementé scripts de automatización con Python y Selenium, simulando la interacción del usuario con el buscador de rutas y la selección de destinos.

Registré y gestioné los errores detectados en JIRA, documentando pasos, evidencias y su impacto en el flujo del sistema.

Fallo encontrado y resultado

Durante las pruebas detecté que, al introducir una dirección con caracteres especiales, la aplicación generaba un error en el cálculo de la ruta y no mostraba resultados. Identifiqué que el fallo provenía de una mala codificación en el envío de parámetros al servidor (UTF-8).
Tras reportarlo y verificar la corrección, el error fue resuelto y la aplicación pudo procesar correctamente direcciones internacionales, mejorando su compatibilidad y experiencia de usuario.
