# 4. Banco de 12 referencias de video

**Fecha de consulta:** 22 de noviembre de 2026.
**Objetivo:** aprender estructura, ritmo y forma de demostrar. No vamos a copiar textos ni ejecución.

## Cómo leer este banco

- **Plataforma.** Las 12 referencias son de TikTok, el único sitio donde las métricas se pudieron leer directamente desde el servidor de investigación.
  - Instagram redirige a la pantalla de inicio de sesión.
  - YouTube devuelve una verificación anti-bots.
  - Facebook y Meta Ad Library devolvieron error 403 con el resultado vacío "No ads match".
  - TikTok Creative Center respondió 403 o una lista vacía.

  Ver [metodología](metodologia_y_limitaciones.md). Esto es un sesgo de la muestra, no una recomendación de plataforma: los mismos formatos deben probarse en Reels y Facebook.
- **Métricas.** Se leyeron del JSON público de cada página de TikTok el 22-11-2026: reproducciones, me gusta, comentarios, compartidos y guardados.
  - TikTok no publica tiempo de visualización, tasa de finalización ni conversiones.
  - **Guardados** = personas que lo guardaron para volver a verlo (señal de utilidad).
  - **Compartidos** = envíos a terceros.
  - **Ninguna métrica demuestra ventas ni rentabilidad.**
- **Comparación con la cuenta.** Es la mediana de reproducciones de entre 6 y 9 videos recientes de la misma cuenta. Salen de la página pública incrustable de cada creador o de páginas de video abiertas una por una. Los videos más nuevos llevan menos días acumulando vistas, así que la comparación es orientativa.
- **Orgánico o anuncio.** Se basa en el campo `isAd` del JSON de TikTok. `isAd=false` indica publicación orgánica, pero no descarta que el autor la haya promocionado aparte (Spark Ads). `isAd=true` indica contenido autorizado para anuncios o de marca; no confirma cuánto se pautó.
- **Nivel de revisión.** "Completo (texto + fotogramas)" significa dos cosas:
  - Leímos la transcripción automática completa que publica TikTok (subtítulos WebVTT).
  - Revisamos 7 fotogramas: segundo 0,3, 1,5 y 3, y luego al 25 %, 50 %, 75 % y 95 % del video.

  No equivale a ver cada segundo. Los gestos y la edición entre fotogramas no se observaron.

## Resumen

| Ref. | Autor | Idioma | Público | Fecha | Vistas | Comparación con la cuenta | Tipo | Guion |
|---|---|---|---|---|---|---|---|---|
| R01 | Luis Fer Cáceres (Bold, agencia go-to-market) | ES | Empresarios (empresas medianas) | 2026-06-05 | 10.100 | Muy por encima de sus recientes; por debajo de sus fijados antiguos | Orgánico | G1 |
| R02 | Chance / PolyPayd (agencia de IA para oficios) | EN | Empresarios de remodelación | 2026-10-15 | 605 | 0,73× (mediana 827) | Orgánico | G1, G4 |
| R03 | Chance / PolyPayd | EN | Empresarios con anuncios | 2026-11-06 | 703 | 0,85× (mediana 827) | Orgánico | G2 |
| R04 | Emily Jambrina (entrenadora de ventas y servicio) | ES | Dueñas de tiendas | 2026-10-13 | 32.500 | 2,5× (mediana 13.200) | Orgánico | G3 |
| R05 | Emily Jambrina (sketch) | ES | Mixto (mucho consumidor) | 2026-10-16 | 1.600.000 | 121× (mediana 13.200) | Orgánico | G3 |
| R06 | Facu Prado (coach de ventas) | ES | Vendedores y emprendedores | 2026-11-11 | 9.788 | 6,4× (mediana 1.519; recientes poco maduros) | Orgánico | G5 |
| R07 | Storm Ventures Group (formación para techadores) | EN | Dueños y vendedores de techos | 2026-10-16 | 778 | 0,7× (mediana 1.087) | Orgánico | G5 |
| R08 | Tat Londono (coach inmobiliaria) | EN | Agentes inmobiliarios | 2026-06-11 | 5.027 | 4,5× (no concluyente) | Orgánico | G2 |
| R09 | Scarlett Zerafa × Jobber (CRM para servicios) | EN | Mixto (mensaje B2B, audiencia consumidora) | 2026-06-22 | 16.700 | 1,09× (mediana 15.300) | De marca (`isAd=true`) | G4 |
| R10 | marketinhouse (agencia) | ES | Pymes con web | 2026-11-17 | 734 | 0,97× (mediana 753) | Orgánico | G6 |
| R11 | Jeremy Miner (formador de ventas) | EN | Vendedores y dueños | 2026-11-01 | 42.900 | 4,3× (mediana 9.901) | Orgánico | G6 |
| R12 | Matt Easton (coach de ventas) | EN | Vendedores y dueños | 2026-11-20 | 1.506 | 0,82× (mediana 1.833; recientes poco maduros) | Orgánico | G4 |

**Lectura rápida.** Las cuentas de agencias y de CRM tienen poco alcance orgánico: PolyPayd, marketinhouse y, entre las reservas, HubSpot, ServiceTitan, Mercately y Clientify están entre 100 y 1.200 vistas. Las piezas con más alcance son de formadores de ventas que hablan de un problema humano reconocible (R04, R05, R06, R11). Para David conviene combinar las dos cosas:

1. Abrir con un problema humano reconocible, la mecánica de los formadores.
2. Cerrar con la demostración de sistema de las agencias y los CRM.

---

## Fichas

### R01 · "Un prospecto llena tu formulario un martes a las 11 de la noche"

- **Enlace:** https://www.tiktok.com/@luisfernandocacer3/video/7647711086245874964
- **Autor y plataforma:** Luis Fer Cáceres (@luisfernandocacer3), fundador de Bold, "growth partner" de go-to-market. TikTok, 32.600 seguidores.
- **Fechas:** publicado el 2026-06-05 (fuera de la ventana de 6 meses por 2 semanas); consultado el 2026-11-22.
- **Público:** dueños y directivos de empresas medianas. Habla de "tu vendedor", "tu empresa" y procesos B2B.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 10.100 |
  | Me gusta | 1.084 |
  | Comentarios | 0 |
  | Compartidos | 9 |
  | Guardados | 23 |
  | Duración | 153 s |
- **Comparación con la cuenta:** el investigador abrió 8 videos más.
  - Fijados antiguos: mediana 21.500.
  - Cinco de noviembre de 2026: mediana 468.

  Rinde muy por encima de los recientes y por debajo de los fijados.
- **Tipo:** orgánico (`isAd=false`).
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Plano detalle de manos en una tableta. El texto se escribe en pantalla, "Un prospecto llena tu formulario un martes a las…", mientras la voz pregunta "¿A qué hora lo contacta tu empresa?". En el segundo 4 aparece el autor a cámara, en plano medio corto.
  - **Problema.** La consulta llega fuera de horario y se atiende 8–12 horas después.
  - **Desarrollo.** "En ese tiempo pasaron tres cosas":
    1. El prospecto se enfrió.
    2. La competencia con automatización ya respondió.
    3. El vendedor invierte tiempo en un lead que ya perdió temperatura.

    Después describe la solución: un flujo automático que confirma la recepción, envía información útil y agenda.
  - **Prueba.** Ninguna demostración en pantalla. Se apoya en un escenario concreto y en lógica, sin cifras verificables.
  - **CTA.** Cierre conceptual: "la automatización… permite a una empresa mediana competir con los tiempos de respuesta de una grande". No pide una acción explícita.
  - **Qué adaptamos.** La hora exacta como gancho, la estructura "tres cosas que pasaron mientras tu equipo dormía" y el plano detalle de manos con el celular para abrir.
- **Por qué probarlo:** es el problema central del ecosistema (de la consulta a la atención), contado por una agencia para empresarios. Tiene un 10,7 % de me gusta por reproducción, una señal de aprobación alta en un nicho B2B.

### R02 · Demo en vivo: formulario → llamada del asistente de IA → visita agendada

- **Enlace:** https://www.tiktok.com/@playestchance/video/7696979022227508502
- **Autor y plataforma:** Chance (@playestchance), fundador de PolyPayd: anuncios más un "equipo de ventas con IA" para empresas de oficios en Reino Unido. TikTok, 1.553 seguidores.
- **Fechas:** publicado el 2026-10-15; consultado el 2026-11-22.
- **Público:** dueños de empresas de cocinas y baños.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 605 |
  | Me gusta | 16 |
  | Comentarios | 0 |
  | Compartidos | 0 |
  | Guardados | 1 |
  | Duración | 151 s |
- **Comparación con la cuenta:** 0,73× la mediana de 6 videos de la cuenta, de mayo a noviembre (827).
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Pantalla partida:
    - Arriba, el tablero de oportunidades de un CRM con las columnas "New enquiry / AI calling / Quote visit booked".
    - Abajo, el autor con el teléfono en la oreja y la etiqueta "LIVE CALL".

    La primera frase es la voz del asistente: "It's Becky from Northside Kitchens… You asked for a free kitchen quote a moment ago." Empieza en medio de la acción.
  - **Problema.** "Los propietarios llaman a 3 o 4 empresas; la primera que responde se queda con la visita."
  - **Desarrollo.** Llena el formulario en vivo y el asistente lo llama. Califica propiedad, presupuesto, fecha de inicio y código postal, con una lista de verificación superpuesta, y agenda la visita. La tarjeta avanza de columna en el CRM.
  - **Prueba.** Demostración en vivo con datos de prueba y tablero visible.
  - **CTA.** "Comment SYSTEM or send me a DM."
  - **Qué adaptamos.** Pantalla partida David + IAVINCHI con **datos de ejemplo**: entra una consulta, se responde por WhatsApp en segundos y la tarjeta pasa de "Nueva consulta" a "Cita agendada". No afirmaremos tiempos que no hayamos medido en nuestra propia demo.
- **Por qué probarlo:** su alcance es bajo, pero es la mejor demostración visual del recorrido completo que encontramos, y precisamente la que necesitamos para mostrar IAVINCHI.

### R03 · "Your ads do only one job"

- **Enlace:** https://www.tiktok.com/@playestchance/video/7702482308753837334
- **Autor y plataforma:** Chance / PolyPayd (@playestchance). TikTok.
- **Fechas:** publicado el 2026-11-06; consultado el 2026-11-22.
- **Público:** dueños de negocio que pautan.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 703 |
  | Me gusta | 21 |
  | Comentarios | 0 |
  | Compartidos | 1 |
  | Guardados | 1 |
  | Duración | 76 s |
- **Comparación con la cuenta:** 0,85× la mediana (827).
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Dos textos fijos enmarcan todo el video: arriba "You're not short of leads. You're losing the ones you've got", abajo "His ads didn't work. The ads weren't the problem". Frase de apertura: "Business owners. Your ads do only one job: get people to inquire. What happens next depends on you."
  - **Problema.** Se culpa a los anuncios por un seguimiento lento.
  - **Desarrollo.** Cuenta escrita a mano en una tableta: 20 consultas al mes, respuesta lenta = 2 visitas, respuesta rápida + seguimiento = 4 visitas. Con 1 de cada 4 cerrada, salen 6 trabajos más al año "del mismo gasto". Un rótulo indica "Extra ad spend £0".
  - **Prueba.** Ejercicio aritmético **hipotético**, no un caso real.
  - **CTA.** "Comment SYSTEM."
  - **Qué adaptamos.** "Ejercicio con tus números" en el tablero, con cifras marcadas como ejemplo, y cierre con la pregunta de diagnóstico: "¿cuántas consultas te llegan y cuántas se convierten en cita?".
- **Por qué probarlo:** desarma la objeción "ya probé anuncios y no funcionó" y conecta publicidad con seguimiento, el corazón del ecosistema.

### R04 · "Tu marketing atrae clientes, tu mal servicio los espanta"

- **Enlace:** https://www.tiktok.com/@emilyjambrinaventas/video/7696000378797690132
- **Autor y plataforma:** Emily Jambrina (@emilyjambrinaventas), entrenadora de ventas y servicio al cliente. TikTok, 33.400 seguidores.
- **Fechas:** publicado el 2026-10-13; consultado el 2026-11-22.
- **Público:** dueñas de tiendas, es decir empresarias del comercio minorista.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 32.500 |
  | Me gusta | 790 |
  | Comentarios | 25 |
  | Compartidos | 199 |
  | Guardados | 186 |
  | Duración | 70 s |
- **Comparación con la cuenta:** 2,5× la mediana de 9 recientes (13.200).
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Plano medio sentada, estilo podcast, con micrófono. Un rótulo fijo arriba dice "Tu Marketing ATRAE Clientes, Tu Mal Servicio los ESPANTA" y abajo hay subtítulos grandes palabra por palabra. Arranca a mitad de frase: "…[el error] que están cometiendo las dueñas de tiendas de ropa es el siguiente".
  - **Problema.** Se invierte en pauta y contenido, y la atención espanta a quien llega.
  - **Desarrollo.** Nombra frases típicas que generan rechazo ("¿en qué le puedo ayudar?") y propone generar confianza antes de vender.
  - **Prueba.** Experiencia y ejemplos de frases; no hay datos.
  - **CTA.** No es explícito en el audio. La descripción refuerza el mensaje.
  - **Qué adaptamos.** La dicotomía en dos líneas como rótulo fijo, trasladada a llamadas y WhatsApp de empresas de servicios: "Tu marketing trae la consulta. Tu atención decide si se convierte en cita."
- **Por qué probarlo:** 199 compartidos y 186 guardados con 32.500 vistas indican que las empresarias lo usan y lo reenvían, y habla de inversión en marketing frente a atención.

### R05 · Sketch: "Así se espanta a una cliente"

- **Enlace:** https://www.tiktok.com/@emilyjambrinaventas/video/7697065721360026900
- **Autor y plataforma:** Emily Jambrina. TikTok.
- **Fechas:** publicado el 2026-10-16; consultado el 2026-11-22.
- **Público:** **mixto.** La descripción interpela a dueñas de tienda, pero el alcance (1,6 M) y los comentarios vienen sobre todo de consumidoras que se identifican. **Su desempeño no demuestra que funcione con empresarios.**
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 1.600.000 |
  | Me gusta | 48.100 |
  | Comentarios | 5.734 |
  | Compartidos | 3.388 |
  | Guardados | 4.412 |
  | Duración | 72 s |
- **Comparación con la cuenta:** 121× la mediana de la cuenta.
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** La clienta entra a la tienda y la vendedora se acerca: "Hola, ¿en qué le puedo ayudar?" — "Nada, gracias, solo estoy mirando". Rótulo: "Así se espanta a una cliente".
  - **Problema.** Atención invasiva.
  - **Desarrollo.** Dramatización exagerada y reconocible; al final la entrenadora explica a cámara "Vender no es perseguir, es conectar".
  - **Prueba.** La situación es reconocible para cualquiera.
  - **CTA.** "Seguime para que aprendas a vender más."
  - **Qué adaptamos.** Una dramatización mínima (10–12 s) de cómo se pierde una consulta, seguida de David explicando la causa. Ejemplo: suena el teléfono en una oficina vacía o un WhatsApp queda en "visto".
- **Por qué probarlo:** demuestra la fuerza de la escena reconocible. Para empresarios la probaríamos como **variante de gancho**, no como pieza principal.

### R06 · "Llamame la semana que viene"

- **Enlace:** https://www.tiktok.com/@desarrolloemprendedorfp/video/7707027397169696018
- **Autor y plataforma:** Facu Prado (@desarrolloemprendedorfp), coach de ventas. TikTok, 1,4 M de seguidores.
- **Fechas:** publicado el 2026-11-11; consultado el 2026-11-22.
- **Público:** vendedores, closers y emprendedores que venden por llamada (profesional, no consumidor).
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 9.788 |
  | Me gusta | 320 |
  | Comentarios | 6 |
  | Compartidos | 28 |
  | Guardados | 159 |
  | Duración | 109 s |
- **Comparación con la cuenta:** 6,4× la mediana de 9 recientes (1.519). Esos videos llevan menos días publicados, así que la comparación está sesgada a favor de este.
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** La objeción literal en un rótulo rojo, grande y centrado: "LLÁMAME LA SEMANA QUE VIENE". Habla de frente a cámara en un plano medio corto con fondo de estudio.
  - **Problema.** Seguimiento pasivo después de presentar una propuesta.
  - **Desarrollo.** Interpreta la excusa ("algo no te terminó de cerrar"), da el guion exacto para responder y pide guardar el video.
  - **Prueba.** Diálogo de ejemplo; no hay datos.
  - **CTA.** "Seguí esta cuenta."
  - **Qué adaptamos.** Abrir con la frase real que dice el cliente después de una cotización y explicar qué debe pasar en el sistema: tarea, recordatorio y mensaje de seguimiento.
- **Por qué probarlo:** 159 guardados sobre 9.788 vistas (1,6 %) indican contenido útil. Además, la frase-objeción como gancho es muy fácil de grabar.

### R07 · "POV: the homeowner hasn't responded in 3 days"

- **Enlace:** https://www.tiktok.com/@stormventuresgroup/video/7697389708132748558
- **Autor y plataforma:** Storm Ventures Group (@stormventuresgroup), formación y comunidad para contratistas de techos. TikTok, 302 seguidores.
- **Fechas:** publicado el 2026-10-16; consultado el 2026-11-22.
- **Público:** dueños y vendedores de empresas de techos.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 778 |
  | Me gusta | 22 |
  | Comentarios | 0 |
  | Compartidos | 1 |
  | Guardados | 1 |
  | Duración | 24 s |
- **Comparación con la cuenta:** 0,7× la mediana (1.087). La cuenta tiene una pieza cómica de julio con 70.900 vistas.
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Rótulo "POV: the homeowner hasn't responded in 3 days". Un hombre abatido mira el celular y su pareja lo consuela: "Babe, you have to let her go."
  - **Problema.** El prospecto desaparece después de la visita o la cotización.
  - **Desarrollo.** Malentendido tipo ruptura amorosa con remate: "the homeowner from Tuesday".
  - **Prueba.** Humor reconocible para el gremio.
  - **CTA.** Ninguno.
  - **Qué adaptamos.** La metáfora de "ruptura" como gancho de 5 s para el guion de seguimiento de cotizaciones.
- **Por qué probarlo:** aunque su desempeño es bajo, es el único gancho humorístico del gremio que encontramos sobre seguimiento. Lo incluimos por el mecanismo, no por las métricas.

### R08 · "Lead generation ≠ lead conversion"

- **Enlace:** https://www.tiktok.com/@tatlondono/video/7650261585386163473
- **Autor y plataforma:** Tat Londono (@tatlondono), coach de agentes inmobiliarios. TikTok, 2,7 M de seguidores.
- **Fechas:** publicado el 2026-06-11 (2 semanas fuera de la ventana de 6 meses); consultado el 2026-11-22.
- **Público:** agentes inmobiliarios, profesionales con cartera propia.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 5.027 |
  | Me gusta | 274 |
  | Comentarios | 4 |
  | Compartidos | 7 |
  | Guardados | 37 |
  | Duración | 56 s |
- **Comparación con la cuenta:** 4,5× la mediana de 10 videos de 1 a 4 días. **No concluyente.**
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Selfie en el auto: "It's guaranteed: if you post every day you'll get a ton of leads. But…"
  - **Problema.** Confundir generar prospectos con convertirlos.
  - **Desarrollo.** Define "generación" mostrando capturas de su propio contenido y separa "conversión". Remata: "terminas culpando a las agencias, al coach de redes… a todos menos a ti".
  - **Prueba.** Sus propias publicaciones como ejemplo.
  - **CTA.** Implícito: "antes de invertir en generar prospectos, asegúrate de saber convertirlos".
  - **Qué adaptamos.** Dos palabras escritas en el tablero, **GENERAR | CONVERTIR**, con una flecha que las une: el ecosistema une ambas columnas. Su frase sobre culpar a la agencia sirve para la objeción "ya tuve agencia".
- **Por qué probarlo:** es una distinción conceptual simple, con un buen porcentaje de me gusta (5,5 %), dirigida a un público que vende servicios de alto valor.

### R09 · "#1 Tool I Use": de la cotización al cobro, dentro del software

- **Enlace:** https://www.tiktok.com/@scarlett_zerafa/video/7654043320083041566
- **Autor y plataforma:** Scarlett Zerafa (@scarlett_zerafa), cofundadora de Hess Cleaning (limpieza de ventanas). Contenido de marca de Jobber. TikTok, 71.600 seguidores.
- **Fechas:** publicado el 2026-06-22 (fuera de la ventana por 1 mes; se incluye por ser la única demo de CRM con caso propio y buen alcance); consultado el 2026-11-22.
- **Público:** **mixto.** Habla a dueños de servicios, pero la audiencia de la cuenta viene de videos de limpieza para consumidores.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 16.700 |
  | Me gusta | 341 |
  | Comentarios | 13 |
  | Compartidos | 10 |
  | Guardados | 45 |
  | Duración | 69 s |
- **Comparación con la cuenta:** 1,09× la mediana de 6 videos (15.300). Sus piezas sin marca rinden más (mediana 19.400).
- **Tipo:** de marca o pautable (`isAd=true`, con mención de descuento). No se sabe cuánto se pautó.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Selfie en la camioneta: "Most home service owners think that landing bigger jobs is all about doing good work."
  - **Problema.** Cotizaciones, seguimiento, agenda y cobros desordenados frente a clientes grandes.
  - **Desarrollo.** Caso propio (afirma un contrato comercial de seis cifras al año) y recorrido en pantalla: cotización con 3 opciones, aprobación en el portal, programación, factura y pago.
  - **Prueba.** Capturas del software y el caso de la autora (no verificable por nosotros).
  - **CTA.** "Try Jobber", con enlace en la bio.
  - **Qué adaptamos.** El argumento "parecer una empresa organizada ante clientes grandes" (administradores de propiedades, comerciales) y el recorrido de pantallas de IAVINCHI con datos de ejemplo.
- **Por qué probarlo:** es la mejor referencia de CRM contado por un usuario-empresario, y conecta orden interno con ventas más grandes.

### R10 · "3 cosas de tu web que espantan a tus clientes"

- **Enlace:** https://www.tiktok.com/@marketinhouse_agencia/video/7709070567739100448
- **Autor y plataforma:** marketinhouse (@marketinhouse_agencia), agencia de marketing en España. TikTok, 4.655 seguidores.
- **Fechas:** publicado el 2026-11-17; consultado el 2026-11-22.
- **Público:** pymes con web.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 734 |
  | Me gusta | 0 |
  | Comentarios | 0 |
  | Compartidos | 1 |
  | Guardados | 0 |
  | Duración | 23 s |
- **Comparación con la cuenta:** 0,97× la mediana de 9 recientes (753).
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Un "3" gigante y el rótulo "cosas de tu web que espantan a tus clientes… y la última es la peor".
  - **Problema.** Fricción en la web.
  - **Desarrollo.** Lista rápida:
    1. Formulario eterno: "con nombre, email y teléfono basta".
    2. Varios botones que dicen casi lo mismo: "deja uno y que diga qué pasa al pulsarlo".
    3. Web lenta.
  - **Prueba.** Ninguna.
  - **CTA.** "Los 3 se pueden revisar esta misma semana; lo vemos juntos."
  - **Qué adaptamos.** El formato de lista de 3 en menos de 30 s. Nuestra auditoría encontró exactamente estos patrones (ver [resumen comercial](01_resumen_comercial.md)), así que podemos hablar con hallazgos reales y anonimizados.
- **Por qué probarlo:** el engagement es casi nulo; **es la referencia más débil en desempeño.** Se incluye porque su estructura es la más corta y fácil de producir y porque el tema coincide con nuestros hallazgos. Debe probarse, no darse por buena.

### R11 · "Why should I go with you?"

- **Enlace:** https://www.tiktok.com/@jeremy_miner/video/7703222612805127437
- **Autor y plataforma:** Jeremy Miner (@jeremy_miner), formador de vendedores (7th Level). TikTok, 324.700 seguidores.
- **Fechas:** publicado el 2026-11-01; consultado el 2026-11-22.
- **Público:** vendedores y dueños que venden.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 42.900 |
  | Me gusta | 2.621 |
  | Comentarios | 27 |
  | Compartidos | 68 |
  | Guardados | 560 |
  | Duración | 69 s |
- **Comparación con la cuenta:** 4,3× la mediana de 9 recientes (9.901).
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Rótulo fijo "THE PROBLEM WITH SALESPEOPLE". En un salón de entrenamiento pregunta "What do you sell?" — "Supplements." — "Why should I go with you?"
  - **Problema.** Todas las respuestas suenan igual; falta diferenciación.
  - **Desarrollo.** Dos o tres respuestas genéricas en ronda rápida (una es "digital marketing") y la explicación: la venta trata de cambio frente al statu quo.
  - **Prueba.** Respuestas reales del público en vivo.
  - **CTA.** Ninguno.
  - **Qué adaptamos.** La pregunta "¿Por qué deberían elegirte a ti?", hecha a cámara y respondida con las frases genéricas típicas de las webs ("calidad", "servicio", "años de experiencia") como patrón, sin citar empresas.
- **Por qué probarlo:** tiene el mejor indicador de utilidad del banco: 560 guardados (1,3 %). La pregunta conecta con la claridad de la oferta.

### R12 · El tornillo y la herramienta equivocada

- **Enlace:** https://www.tiktok.com/@officialmatteaston/video/7710287770551438606
- **Autor y plataforma:** Matt Easton (@officialmatteaston), coach de ventas. TikTok, 157.000 seguidores.
- **Fechas:** publicado el 2026-11-20 (con 2 días); consultado el 2026-11-22.
- **Público:** vendedores y dueños.
- **Métricas visibles:**

  | Métrica | Valor |
  |---|---|
  | Reproducciones | 1.506 |
  | Me gusta | 45 |
  | Comentarios | 2 |
  | Compartidos | 3 |
  | Guardados | 20 |
  | Duración | 152 s |
- **Comparación con la cuenta:** 0,82× la mediana de 9 recientes (1.833), todos con pocos días; el dato todavía va a madurar.
- **Tipo:** orgánico.
- **Revisión:** completo (texto + fotogramas).
- **Análisis:**
  - **Primeros segundos.** Rótulo fijo "How many times should you follow up with your prospect before you just become an annoyance?" y una anécdota ("I gave this same lesson to our son in the garage…").
  - **Problema.** Obsesión por cuántas veces insistir.
  - **Desarrollo.** Entrega un tornillo Allen y un destornillador plano. La herramienta no encaja: "no es cuántas vueltas, es la herramienta correcta, el proceso".
  - **Prueba.** Metáfora física con objeto.
  - **CTA.** Curso gratis, enlace en la bio.
  - **Qué adaptamos.** Una metáfora con un objeto sobre el escritorio: el problema no es insistir más, es tener el sistema correcto.
- **Por qué probarlo:** la demostración con objeto es barata de producir y memorable. Su desempeño aún no es concluyente por la edad del video.

---

## Reservas verificadas (no incluidas en las 12)

| Referencia | Datos (22-11-2026) | Por qué queda en reserva |
|---|---|---|
| Alex Hormozi, "Offer creation in two bullets" — https://www.tiktok.com/@ahormozi/video/7710687790698106126 | 2026-11-21, 49.700 vistas en ~1 día, 138 s | Fuerte en desempeño. Es un "hot seat" de diagnóstico a un abogado; útil si se quiere un formato de diagnóstico en vivo, pero exige un segundo participante |
| Soy Pablo Gio, "¿Cuántas ventas se pierden por no hacer un buen seguimiento?" — https://www.tiktok.com/@soypablogio/video/7701382037537688833 | 2026-10-27, 3.256 vistas, 42 guardados | Anécdota de seguimiento en español; solapa con R06 |
| Luis Fer Cáceres, "95 % del presupuesto persigue a quien ya quiere comprar" — https://www.tiktok.com/@luisfernandocacer3/video/7637304640253463828 | 2026-05-08, 7.223 vistas | Fuera de los 6 meses; tema de demanda, menos ligado al proceso |
| Neil Patel × HighLevel, "Hot leads don't wait" — https://www.tiktok.com/@neilpatel/video/7658364826338512141 | 2026-07-03, 2.418 vistas | Promoción de afiliados: el público son marketers, no empresarios |
| ServiceTitan, agente de IA que atiende cuando no hay personal — https://www.tiktok.com/@servicetitan/video/7707491090860903693 | 2026-11-13, ~200 vistas | Tema exacto (IA atendiendo llamadas), pero alcance mínimo y sin subtítulos |
| Clientify, "Inmobiliarias: el lead llega de noche…" — https://www.tiktok.com/@clientify/video/7696570201894112526 | 2026-10-14, 155 vistas | Tema exacto para administración de propiedades; alcance mínimo |
