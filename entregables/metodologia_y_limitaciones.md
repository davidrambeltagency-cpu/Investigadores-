# Metodología y limitaciones

**Fecha de toda la investigación:** 22 de noviembre de 2026.

## Prospectos

**1. Descubrimiento (por territorio).** Usamos búsquedas web, fichas y búsquedas de BBB y registros estatales de licencias: DBPR/myfloridalicense en Florida y CSLB en California. Encontramos 55 candidatas (unas 11 por territorio) y descartamos más de 30 por las razones listadas al final de la [base](02_base_prospectos.md):

- cadenas o franquicias con marketing centralizado;
- plataformas de capital privado;
- tamaño insuficiente;
- web inaccesible;
- licencias con incidencias.

**2. Dominios oficiales.** Un dominio se aceptó solo si un resultado del propio dominio coincidía con el nombre de la empresa y con su ciudad, teléfono o dirección. Así se corrigieron varias suposiciones iniciales (por ejemplo, johnbetlem.com y no betlem.com).

**3. Auditoría web automatizada.** Usamos Chromium (Playwright) en vista móvil iPhone 13 sobre la portada y la página de contacto de 53 webs. Cargaron 49; 4 dieron error o bloqueo anti-bots.

| Qué se registró | Detalle |
|---|---|
| Contenido visible | Título, titular principal, botones de acción en la primera pantalla |
| Canales de contacto | Teléfonos clicables, formularios y número de campos, enlaces de WhatsApp y SMS |
| Idioma | Señales de español: enlaces /es, hreflang, plugins de traducción |
| Herramientas | Firmas en scripts, enlaces y solicitudes de red, y en el contenedor público de Google Tag Manager: Google Ads, GA4, píxel de Meta, Microsoft, seguimiento de llamadas, chat, agendas, plataforma web |
| Otros | Crédito de agencia en el pie; captura móvil |

**4. Cierre de fichas.** Lectura directa de cada web (páginas de equipo, historia, contacto, español) y de los registros públicos para completar decisor, escala, idioma y oportunidades. Cada oportunidad separa el hecho observado, la hipótesis comercial y la pregunta de diagnóstico.

**5. Verificación manual.** Revisamos las capturas de las 10 empresas prioritarias para confirmar lo que la detección automática dice de la primera pantalla.

### Reglas de evidencia

- Cada hecho lleva su fuente y su método:
  - **Lectura directa:** abrimos la página.
  - **Resumen de buscador:** evidencia secundaria.
  - **Dato publicado por la empresa:** afirmación propia, sin verificar por terceros.
- Las estimaciones de terceros (ingresos, empleados) se marcan como tales. En esta base casi no se usaron.
- **Contactos:** solo teléfonos, correos y formularios comerciales publicados. Los decisores provienen de la web de la empresa, BBB o registros estatales.

### Limitaciones conocidas

**Fuentes que no pudimos consultar directamente:**

- **Google Maps y Google Business Profile:** verificación anti-bots desde el servidor de investigación. Los enlaces a Google son directos cuando la empresa los publica en su web y de búsqueda en el resto. Las cifras de reseñas de Google vienen de la web de cada empresa o de terceros, y van marcadas.
- **Instagram, Facebook y LinkedIn:** piden inicio de sesión. Registramos los enlaces que publica cada empresa, sin su actividad ni sus seguidores.
- **Campañas activas:** Meta Ad Library y Google Ads Transparency no respondieron (403). Los píxeles y etiquetas no prueban campañas activas.
- **Licencias de control de plagas en Florida (FDACS):** no consultadas.

**Límites de la detección automática:**

- La detección de chat y de botones de acción **subestima**: algunos widgets se cargan desde servidores que no respondieron. Por eso las cifras de chat y botones son mínimas.
- La ausencia de una firma **no prueba** que la herramienta no exista.

**Datos internos:**

- **Cartera de DRA:** no tuvimos acceso, así que el cruce queda pendiente en las 40.
- **Llamadas de prueba:** no hicimos llamadas ni enviamos formularios a las empresas (ni "mystery shopping"). Los tiempos de respuesta son siempre una pregunta de diagnóstico, no un hecho.

## Referencias de video

- **Búsqueda.** Búsqueda web y lectura de páginas públicas. Con acceso efectivo, solo TikTok:
  - Instagram: redirige a inicio de sesión.
  - YouTube: verificación anti-bots.
  - Facebook y Meta Ad Library: 403 y resultado vacío.
  - TikTok Creative Center: 403 o lista vacía.

  Por eso las 12 referencias son de TikTok.
- **Métricas.** Las leímos del JSON público de cada página de video (`itemStruct.stats`) el 22-11-2026.
- **Comparación con la cuenta.** Es la mediana de reproducciones de 6 a 9 videos recientes de la misma cuenta, obtenidos de la página incrustable del creador o de páginas de video individuales. Es orientativa, porque los videos más nuevos llevan menos días acumulando vistas.
- **Contenido.** Leímos la transcripción automática completa que publica TikTok (WebVTT) y 7 fotogramas por video, con ffmpeg. No equivale a ver cada segundo.
- **Uso de los videos.** Solo para análisis interno. No se redistribuyen ni se incluyen en este repositorio: solo enlaces y descripciones.
- **Ninguna métrica pública demuestra ventas ni rentabilidad.** Cuando no hay datos de conversión, explicamos por qué la referencia merece probarse.

## Guiones y rodaje

- **Textos.** Los guiones son originales. Toman de las referencias solo la estructura, el ritmo y el tipo de demostración.
- **Sin promesas.** No hay testimonios, cifras de clientes ni promesas de resultados. Las cifras que aparecen son de nuestra propia auditoría (por ejemplo, "cerca de 50 webs") o ejemplos rotulados como tales.
- **Funciones de IAVINCHI.** Las que se mencionan (respuesta automática por WhatsApp, calificación, citas, etapas, recordatorios, reporte por origen) **deben confirmarse con el equipo de producto antes de publicar.**
