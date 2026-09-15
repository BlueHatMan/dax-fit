# Dax Fit

PWA personal para registrar la rutina Full Body A/B de Álvaro.

## Qué incluye
- Selector Día A / Día B / Día opcional y recuerdo de la última sesión.
- Ejercicio activo con series, rango objetivo y descansos.
- Registro de peso, repeticiones/segundos y dificultad percibida.
- Temporizador automático tras cada serie, con +30 s y opción de saltarlo.
- “Máquina ocupada” para mandar el ejercicio al final de la cola.
- “Omitir ejercicio” con motivo y nota; el dolor queda registrado explícitamente.
- Historial guardado en el propio dispositivo.
- Exportación/importación de copia de seguridad JSON.
- Resumen de sesión listo para copiar y pegar en ChatGPT.
- Rutina de 4 semanas con ajuste de series en extensión de cuádriceps durante la semana 1.
- Registro inicial del Día A del 10/09/2026 con los datos comunicados en el chat.

## Uso rápido
La forma más sencilla de probarla en un ordenador es servir la carpeta con un servidor local:

```bash
python -m http.server 8000
```

Después abre `http://localhost:8000`.

Para instalarla como app en Android, súbela a cualquier alojamiento HTTPS estático (GitHub Pages, Netlify, Cloudflare Pages, etc.), abre la URL en Chrome y usa “Añadir a pantalla de inicio” / “Instalar aplicación”. Una vez instalada, puede seguir funcionando sin conexión gracias al service worker.

> Importante: los datos se guardan localmente en el navegador/dispositivo. Usa “Ajustes → Exportar datos” si quieres conservar una copia.
