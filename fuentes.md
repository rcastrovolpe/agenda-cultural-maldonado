# Fuentes — Agenda Cultural Maldonado

Registro acumulado de qué fuentes funcionan, cuáles no, y qué se aprendió en cada ejecución semanal. Se actualiza al final de cada corrida.

## Ranking de fuentes (por productividad acumulada, 3 ejecuciones)

| # | Fuente | Nivel | Ejecuciones | Eventos aportados (total aprox.) | Notas |
|---|---|---|---|---|---|
| 1 | Fundación Pablo Atchugarry / MACA — https://macamuseo.org/eventosmaca (+ https://entradas.macamuseo.org/) | 1 | 3 | 5 puntuales + 2 exp (sem.3); 6 puntuales + 2 exp (sem.2); 0 + 2 exp (sem.1) | Sigue siendo la fuente institucional más confiable y detallada (fichas de evento con horario, condiciones y lugar exactos). `fundacionpabloatchugarry.org/es/eventos/` en cambio sigue mostrando solo contenido histórico 2012-2022 — dejar de consultarla por separado, usar solo macamuseo.org/eventosmaca y entradas.macamuseo.org. |
| 2 | Cadena del Mar FM 106.5 — https://cadenadelmar.uy/eventos | 2 | 3 | 6 (sem.3) / ~9 (sem.2) / 3+2exp (sem.1) | La fuente MÁS productiva de la semana 3 (6 de 8 eventos de un agente). Confirmado el patrón: mejor buscar notas específicas (`/eventos/...` o `/multicultural/...`) que la portada genérica. |
| 3 | CURE (Centro Universitario Regional Este) — https://www.cure.edu.uy | 1/2 (nueva) | 1 | 5 (cobertura detallada del Día del Patrimonio: inauguración, visitas guiadas, conferencia) | **Hallazgo fuerte de esta semana.** Cobertura universitaria con actividades y horarios muy precisos, sobre todo para patrimonio/arqueología. Agregar de forma fija, en particular las semanas con Día del Patrimonio u otras fechas académicas. |
| 4 | https://www.maldonado.gub.uy/cultura | 1 | 3 | 0 directos verificables (sem.3) / ~11 (sem.1-2) | Caída fuerte esta semana: solo dio referencias indirectas al Día del Patrimonio, sin eventos propios con fecha/hora verificable. Seguir consultando pero ya no asumir que es una de las 2 fuentes top — el paginado de contenido viejo sigue siendo un problema. |
| 5 | Semanario La Prensa / Avant-Première — https://semanariolaprensa.com | 2 | 3 | 2 (sem.3, recuperó productividad) | Dio 2 eventos verificados y bien fechados esta semana (Fiesta del Chivito, concierto Gerardo Dorado) tras 2 semanas flojas. OJO: también devolvió una nota larga de Patrimonio con fecha "sábado 1° de octubre" que en 2026 es jueves — es contenido cacheado de 2022, se descartó. Revisar siempre coherencia día-de-semana/fecha antes de usar una nota de esta fuente. |
| 6 | Correo de Punta del Este — https://correopuntadeleste.com | 2 | 3 | 0 (sem.3) / 2 (sem.2) / 0 bloqueada (sem.1) | Inconsistente: esta vez el WebFetch directo devolvió contenido vacío (no captcha, pero tampoco datos). Seguir probando pero sin prioridad alta; probar también 1-2 días después de mitad de semana. |
| 7 | ladiaria.com.uy (sección Maldonado) — https://ladiaria.com.uy/maldonado/ | 2 | 3 | 0 eventos nuevos, pero sigue sirviendo para descartar fechas | Esta semana no aportó eventos propios pero ayudó a confirmar que varios festivales ya habían pasado (CineFem, Encuentro del Chocolate, etc.) — mantener como fuente de verificación cruzada. |
| 8 | portada.com.uy (dominio general, no solo /agenda-portada) | 1/2 | 3 | 2 esta semana (Encuentro de Literatura, Paseo Autos Clásicos) vía notas específicas | La URL exacta `/agenda-portada` sigue dando 404, pero notas puntuales del dominio (vía WebSearch) SÍ aportaron datos verificados y cruzados esta semana. Ajuste: dejar de buscar la URL fija `/agenda-portada` y en su lugar hacer WebSearch `site:portada.com.uy` con términos del tema/fecha. Seguir verificando cruzado, no usar como fuente única. |
| 9 | Museo Regional Francisco Mazzoni | 1 | 3 | 0 esta semana | La exposición "Profundidad de campo" cerró el 25/9 (antes de ventana) y no se encontró qué la reemplaza en octubre — revisar la próxima semana si hay nueva muestra. |
| 10 | Cuartel de Dragones (vía maldonado.gub.uy) | 1 | 3 | 0 charlas puntuales esta semana (sí aportó vía Patrimonio/CURE) | El ciclo "Maldonado, historia, identidad y memoria" terminó en marzo de 2026 — dejar de esperar charlas regulares de ese ciclo específico; el Cuartel sigue relevante para patrimonio en fechas puntuales (Día del Patrimonio). |
| 11 | Castillo Pittamiglio / Castillo de Piria, Piriápolis | 1 | 3 | 0 puntuales / patrimonio en curso | Confirmado abierto, pero los horarios publicados se contradicen entre fuentes (mar-dom 10-18 vs. todos los días 9-17 en invierno) — pendiente de resolver, no tiene sitio propio verificable. |
| 12 | Portal de Piriápolis — https://www.piriapolisportal.com.uy | 2 | 3 | 0 (3 semanas seguidas, HTTP 503 esta vez) | Tercera semana sin aportar nada dentro de ventana — próxima semana sin aporte → pasa a Descartadas. |
| 13 | Calendario oficial PDF (vía /actividades) | 1 | 3 | 0 (el PDF vinculado ahora es "Primeros 100 días de Gobierno", ni siquiera calendario de eventos) | Fuente rota de forma más grave que antes: el link cambió de contenido por completo. Bajar prioridad fuerte, casi descartar. |
| 14 | cultura.maldonado.gub.uy/arte-y-cultura | 1 | 3 | 0, caída (error DNS) 3 semanas seguidas | Sin indicios de que se vaya a resolver — considerar dejar de intentarla cada semana y solo revisar ocasionalmente (cada 4-5 semanas) si cambia. Alternativa parcial sigue siendo www.maldonado.gub.uy/arte-cultura (desactualizada). |
| 15 | Cines del Este — API https://cde-prod-web-api.azurewebsites.net/api/shows/cinema/weekly | 3 | 3 | 0 funciones especiales, pero excelente para estrenos | Sigue funcionando perfecto con WebFetch/curl directo. Fuente más confiable de cine. |
| 16 | cartelera.montevideo.com.uy — URL directa de Life Cinemas: `/apeliculafunciones.aspx?,42,,FILM,-1,114` | 3 | 1 (URL nueva encontrada esta semana) | Útil, aísla bien la sucursal | Más preciso que la portada genérica `/cine` — usar esta URL directamente la próxima vez. |
| 17 | Grupocine — API https://grupocine.com.uy/api/peliculas | 3 | 2 | 0 eventos específicos de PDE, pero útil para cruzar estrenos y detectar flag "especial" | Catálogo nacional sin desglose por sucursal; el campo `"especial"` del JSON es útil para detectar funciones especiales marcadas por la cadena (esta semana ninguna lo estaba). |
| 18 | Cinepunta — https://cinepunta.uy/ | 1/3 | 3 | 0 actividad en ventana, pero confirma fechas de la 29ª edición | 29° Festival confirmado para 20-26/2/2027; convocatoria de films abierta hasta 31/10/2026 (no es evento para público general). |
| 19 | Songkick (venue Enjoy Punta del Este) | 5 | 3 | 0, pero el slug ya no da error | Nueva URL estable: https://www.songkick.com/venues/4485281-enjoy-punta-del-este — carga bien pero 0 shows listados. Usar esta URL de ahora en más. |
| 20 | RedTickets Uruguay → **ticketmaster.uy** (migración confirmada sem.4) | 5 | 4 (3 como RedTickets + 1 como ticketmaster.uy) | 0 | El dominio redtickets.com.uy ya no resuelve (DNS). RED UTS/RedTickets fue adquirida por Ticketmaster en agosto 2026; el sitio nuevo es ticketmaster.uy, pero da HTTP 403 — mismo resultado, nuevo nombre. Seguir probando ticketmaster.uy de ahora en más, contador de strikes reiniciado en esta semana. |
| 21 | Abitab Entradas | 5 | 3 | 0 (403 recurrente; esta semana solo aparece como canal de venta de un show de San Carlos fuera de ventana) | Tercera semana sin aporte directo — un strike más y pasa a Descartadas. |
| 22 | Tickantel | 5 | 3 | 0 (error distinto cada semana: redirecciones / 503 / sin acceso directo) | Tercera semana sin aporte directo — un strike más y pasa a Descartadas. |
| 23 | Bandsintown (4 páginas de ciudad) | 5 | 3 | 0, HTTP 403 en las 4 URLs, 3 semanas seguidas | Un strike más y pasa a Descartadas. |
| 24 | Piriápolis NET | 2 | 3 | 0, contenido archivado de 2022-2023, 3 semanas seguidas | Un strike más y pasa a Descartadas. |
| 25 | Montevideo Portal, sección Maldonado/Tiempo Libre | 2 | 3 | 0, nota más reciente indexada sigue siendo de febrero 2026, 3 semanas seguidas | Un strike más y pasa a Descartadas. |
| 26 | ligapuntadeleste.com.uy | 2 | 2 | 0 esta semana (HTTP 503 en el primer intento, luego cargó sin datos de calendario) | Segunda semana sin aporte directo de eventos puntuales — mantener 1 corrida más antes de bajar prioridad. |
| 27 | Locales Nivel 4 agrupados: Cervecería Giros, Lemon Pub, Mala Junta, Mockers, Solís Resto Pub, Piano Bar, Subsuelo (Gorlero 815) | 4 | 3 (cada uno) | 0 (cada uno), 3 semanas seguidas | Un strike más y pasan a Descartadas (Mala Junta y Piano Bar ni siquiera se pudieron confirmar como locales existentes en 2 intentos). |
| 28 | Paseo La Pasiva (Piriápolis), Club Centro Progreso/Sala Amalia Quintela (Pan de Azúcar), Espacio Cultural Ex Estación AFE (Pan de Azúcar/Garzón), Pueblo Gaucho (Maldonado) | 4 | 3 (cada uno) | 0 agenda puntual esta semana, pero confirmados como activos con programación regular (música en vivo jue-dom en La Pasiva, conciertos esporádicos en Sala Amalia Quintela, etc.) | A diferencia del grupo anterior, estos SÍ están activos — el problema es que no publican grilla semanal específica online. No van a Descartadas todavía: su música en vivo es real, solo falta encontrar dónde publican el detalle (probar Instagram vía WebSearch dirigido). |
| 29 | Moonlight (Maldonado) | 4 | 1 (confirmado como boliche existente) | 0 (excluido por regla: sin artista en vivo anunciado, solo boliche) | Existe y es identificable, pero no aporta por la propia regla de exclusión de la consigna, no por fuente caída. |

### Fuentes nuevas descubiertas y no listadas originalmente (agregar a la rotación)
- **www.cure.edu.uy** — cobertura universitaria (Centro Universitario Regional Este) con mucho detalle sobre patrimonio/arqueología y actividades académico-culturales. La sorpresa más grande de esta semana. Nivel 1/2, agregar de forma fija.
- **patrimoniouruguay.net** — portal nacional del Día del Patrimonio, útil sobre todo en la semana de esa fecha (principios de octubre cada año). Nivel 2, consultar en esa ventana específica.
- **URL directa de Life Cinemas Punta Shopping** en cartelera.montevideo.com.uy: `https://cartelera.montevideo.com.uy/apeliculafunciones.aspx?,42,,FILM,-1,114` — más preciso que la portada genérica `/cine`. Nivel 3, usar esta URL de ahora en más.
- **agendadeleste.com** — mencionó un evento de cine del MACA con horario distinto al oficial (15:30 vs 15:00 de macamuseo.org) — usar solo como fuente secundaria/cruce, priorizar siempre la fuente oficial del venue si hay conflicto.
- macamuseo.org/eventosmaca y entradas.macamuseo.org — confirmado 3ª semana consecutiva como fuente de alta calidad, se mantiene en el puesto 1.
- **radiovivafm.uy** — confirmado 2ª semana: calendario de eventos itinerantes de Cerveceros de Maldonado (Octobeerfest, Halloween Beer Fest).
- **piriapolisdepelicula.com.uy** — confirmado 3ª semana consecutiva: fecha de "Piriápolis de Película" estable en 16-18/10/2026, ya se puede considerar resuelta la contradicción de fechas de semanas anteriores.
- ⚠️ **portada.com.uy/agenda-portada** (URL fija): sigue sin funcionar (404). Pero el dominio portada.com.uy en general, consultado vía WebSearch con términos específicos, SÍ aportó 2 eventos verificados esta semana — cambiar el método de consulta (dejar de intentar la URL fija, usar WebSearch dirigido al dominio).

## Descartadas
(Fuentes con 4 ejecuciones seguidas sin aportar nada — se dejan de consultar cada semana, revisar solo ocasionalmente cada 4-5 semanas por si cambian de estado.)

- **Cervecería Giros, Lemon Pub, Mala Junta, Mockers, Solís Resto Pub, Piano Bar, Subsuelo** (Nivel 4) — 4 semanas seguidas en 0 (sem. 1 a 4). WebSearch no indexa sus redes sociales; sin cobertura de prensa que los mencione con agenda puntual.
- **Portal de Piriápolis** (piriapolisportal.com.uy) — 4 semanas seguidas en 0 (HTTP 503 recurrente).
- **Montevideo Portal, sección Maldonado/Tiempo Libre** — 4 semanas seguidas en 0 (solo contenido cacheado de meses anteriores).
- **Piriápolis NET** — 4 semanas seguidas en 0 (contenido archivado de 2022-2023, nunca actualizado).
- **Bandsintown** (3 URLs de ciudad: Piriápolis, Maldonado, Punta del Este) — HTTP 403 en las 3, 4 semanas seguidas.
- **Abitab Entradas** (entradas.abitab.com.uy) — HTTP 403, 4 semanas seguidas.
- **Facebook Events (búsqueda filtrada) y grupo de Facebook "Agenda Cultural Piriápolis"** — confirmado que requieren login y no son indexables por WebSearch; descartar de la rotación salvo que se consiga acceso autenticado.

(El resto de los locales Nivel 4 — Paseo La Pasiva, Club Centro Progreso/Sala Amalia Quintela, Ex Estación AFE, Pueblo Gaucho — NO son candidatos a descarte: están confirmados activos, y esta semana Pueblo Gaucho incluso aportó un evento puntual (Encuentro de Cuchillería del Este). Tickantel y Songkick tampoco se descartan: dejaron de dar error técnico, solo no tienen eventos relevantes listados todavía.)

---

## Ejecución 2026-09-17

**Nota sobre la fecha:** la tarea programada asume que se ejecuta un miércoles, pero esta corrida cayó en jueves 17/9/2026 (posible desalineación del disparador semanal). Se cubrió la ventana jueves 17 al miércoles 23 de septiembre de 2026 inclusive (7 días) en lugar de miércoles a miércoles (8 días). Ajuste sugerido: verificar el día de disparo del trigger semanal para que caiga en miércoles.

- **Fuentes productivas esta semana:**
  - https://www.maldonado.gub.uy/cultura — 5 eventos (4 del jueves 17/9 + Chimuelos Funk)
  - Calendario oficial PDF (vía /actividades) — confirmó/cruzó CINEFEM, Encuentro del Chocolate, Encuentro de Coros LGBTI+
  - Cuartel de Dragones (vía WebSearch) — 1 evento (charla "El transporte en Maldonado")
  - La Azotea de Haedo (vía WebSearch) — 1-2 eventos (charla Dostoyevski/literatura, conferencia de cine) — posible duplicado con Cadena del Mar, ver abajo
  - Cadena del Mar FM 106.5 — 3 eventos (charla Dostoyevski, ciclo Cuartel de Dragones, Grand Wine Experience —excluido por no cumplir criterio cultural) + 2 exposiciones en curso (Museo Mazzoni, Museo García Uriburu)
  - Semanario La Prensa / Avant-Première — 1-2 eventos (solapados con Cadena del Mar) + Encuentro del Chocolate
  - Portal de Piriápolis — 1 evento (Encuentro del Chocolate, tercera confirmación)
  - ladiaria.com.uy (fuente nueva, no listada originalmente) — CINEFEM / XIV Festival Internacional de Cine de la Mujer, festival de 4-5 días en Punta del Este
  - Fundación Pablo Atchugarry / MACA — 2 exposiciones en curso
  - Castillo Pittamiglio — información de visitas guiadas (patrimonio en curso)
  - Cines del Este / Life Cinemas (vía cartelera.montevideo.com.uy) — cartelera comercial completa, 2 funciones especiales detectadas (versión subtitulada de "El Corazón de la Bestia" y "Los Colores del Tiempo" en francés subtitulado)

- **Fuentes sin resultados (funcionaron pero no aportaron nada dentro de la ventana):**
  - https://www.maldonado.gub.uy/espectaculos
  - Teatro Cantegril, Punta del Este
  - Teatro de Verano Margarita Xirgú
  - Museo Regional Francisco Mazzoni (sin actividad puntual nueva, solo la exposición en curso ya contada arriba)
  - Grupocine Punta del Este (cartelera comercial normal, sin funciones especiales)
  - Cinepunta (festival ya realizado en febrero, sin novedades)
  - Montevideo Portal sección Maldonado/Tiempo Libre
  - RedTickets Uruguay
  - Songkick (venue Enjoy Punta del Este)
  - Setlist.fm (solo histórico)
  - Piriápolis NET
  - Club Centro Progreso / Sala Amalia Quintela, Pan de Azúcar (último evento hallado fue anterior a la ventana)
  - Espacio Cultural Ex Estación AFE, Pan de Azúcar (sin red social propia ni cartelera)
  - Pueblo Gaucho, Maldonado (confirma reapertura de temporada pero sin cartelera diaria publicada)

- **Fuentes caídas / URL cambiada:**
  - https://cultura.maldonado.gub.uy/arte-y-cultura — CAÍDA (error DNS, no resuelve). Alternativa parcial encontrada: https://www.maldonado.gub.uy/arte-cultura (carga pero con contenido desactualizado, marzo-agosto 2026).
  - Correo de Punta del Este — https://correopuntadeleste.com — bloqueada por captcha (`sgcaptcha`), confirmado con curl directo (HTTP 202 + redirect). Solo se pudo obtener un dato parcial no verificado vía snippet de búsqueda (La Sabrosa Funk Orchestra, viernes 19/9).
  - Piriápolis NET — https://www.piriapolis.net/category/noticias/eventos/ — devuelve consistentemente contenido archivado de enero-febrero 2023, no actualizado.
  - Abitab Entradas — entradas.abitab.com.uy — HTTP 403 Forbidden.
  - Tickantel — tickantel.com.uy/inicio — bucle de redirecciones.
  - Bandsintown — las 4 páginas de ciudad (Piriápolis, Punta del Este, Pan de Azúcar, Maldonado) — HTTP 403 Forbidden en las 4.
  - Instagram/Facebook de locales del Nivel 4 (Mala Junta, Lemon Pub, Piano Bar, Cerveceros de Maldonado, Paseo La Pasiva) — bloqueo consistente por pantalla de login o error 429 (rate limit) al usar WebFetch directo, incluso cuando WebSearch encuentra el perfil correcto.
  - Facebook Events (búsqueda general Maldonado/Punta del Este/Piriápolis) — requiere login, sin acceso.
  - Grupo de Facebook "Agenda Cultural Piriápolis" (facebook.com/groups/176331389873822/) — requiere login, sin acceso.
  - Cervecería Giros, Maldonado — no se localizó cuenta de redes sociales propia verificable (posible cambio de nombre o cuenta muy chica sin buen SEO).
  - Mockers, Moonlight, Solís Resto Pub — no se pudo confirmar siquiera la existencia/ubicación exacta de estos locales en Maldonado/Punta del Este con las búsquedas disponibles.
  - Subsuelo (Gorlero 815) — existe (aparece en setlist.fm) pero sin red social propia activa localizada.

- **Fuentes nuevas descubiertas:**
  - ladiaria.com.uy, sección Maldonado — https://ladiaria.com.uy/maldonado/ — cubre cultura con buen detalle editorial (ej. nota completa sobre CINEFEM con horarios). Vale la pena agregarla como fuente de Nivel 2 para la próxima.
  - API pública de Cines del Este: `https://cde-prod-web-api.azurewebsites.net/api/shows/cinema/weekly` — permite obtener la cartelera real cuando la home (SPA) no la muestra. Anotar para reutilizar.
  - API pública de Grupocine: `https://grupocine.com.uy/api/peliculas` — catálogo de títulos activos a nivel cadena (hay que cruzar con cartelera.montevideo.com.uy para saber qué se exhibe puntualmente en Punta del Este).

- **Eventos duplicados o mal fechados detectados:**
  - La charla de Andrés Echevarría en La Azotea de Haedo el jueves 17/9 a las 18:00 fue reportada con dos títulos distintos por dos fuentes/agentes: "Taller literario: la literatura y sus autores, un espejo emocional" (vía maldonado.gub.uy) y "Dostoyevski, ¿cuál fue su influencia en el siglo XX?" (vía Cadena del Mar/La Prensa). Es muy probablemente el mismo evento (mismo día, hora, lugar y disertante) — se unificó como un solo evento en el mail, señalando ambos títulos entre corchetes.
  - CINEFEM (Festival Internacional de Cine de la Mujer): contradicción sobre el día de inicio — ladiaria.com.uy citado por un agente dice "miércoles 16 al domingo 20/9", pero la programación día por día verificada (con horarios de funciones) arranca el jueves 17/9. Se marcó la discrepancia entre corchetes en el mail.
  - Festival "Piriápolis de Película" (Argentino Hotel): tres fuentes dan fechas distintas para octubre (16-18, 22-24, 23-25). No cae dentro de la ventana de esta semana en ningún caso, así que se dejó fuera del cuerpo principal, pero se anotó la contradicción para la sección "Más adelante" — a confirmar más cerca de la fecha.
  - Varias notas indexadas por Google en maldonado.gub.uy resultaron ser de años anteriores (2023-2025) con titulares reciclados casi idénticos a los de 2026 (ej. "Teatro Cantegril ofrece dos espectáculos este fin de semana"). Hay que revisar siempre la fecha de publicación real, no solo el titular.

- **Ajuste sugerido para la próxima:** para Nivel 4 (bares/pubs con Instagram/Facebook), evitar WebFetch directo a las URLs de redes sociales (siempre da login o 429); en su lugar, usar WebSearch con términos como `site:facebook.com <nombre> eventos` o buscar coberturas de prensa que mencionen esos locales, y espaciar las consultas para no gatillar el límite de tasa.

---

## Ejecución 2026-09-24

**Nota sobre la fecha (recurrente):** de nuevo, la corrida cayó en jueves real (24/9/2026) y no en miércoles como asume el prompt — es la 2ª semana consecutiva con esta desalineación (17/9 y 24/9 fueron ambos jueves). Se cubrió la ventana jueves 24 al miércoles 30 de septiembre de 2026 inclusive (7 días), dejando el jueves 1/10 para la próxima corrida (así no queda un día sin cubrir ni se duplica). **Ajuste sugerido fuerte:** revisar la configuración del disparador semanal (cron/trigger) — si no se puede corregir para que dispare en miércoles, conviene fijar permanentemente el criterio "hoy al miércoles siguiente inclusive" (7 días) en vez de "miércoles a miércoles" (8 días), para no tener que resolver esto a mano cada semana.

**Corrección sobre el mail de la semana pasada:** no se detectaron errores retrospectivos en los eventos ya publicados (la ventana anterior terminó el 23/9 y no se encontraron cancelaciones de eventos ya pasados). Dato de contexto: "Rock del Este", que no estaba en el mail anterior porque estaba fuera de ventana, fue reprogramado del 12/9 al 17/10/2026 por mal tiempo — se incluye esta semana en "Más adelante".

- **Fuentes productivas esta semana** (cantidad aproximada de eventos aportados):
  - Fundación Pablo Atchugarry / MACA (macamuseo.org/eventosmaca) — 6 eventos puntuales + 2 exposiciones en curso. Lejos la fuente más productiva esta vez.
  - https://www.maldonado.gub.uy/cultura — ~6 eventos
  - Cadena del Mar FM 106.5 — 4 eventos + confirmación de exposición
  - Correo de Punta del Este (ya no bloqueada) — 2 eventos
  - La Azotea de Haedo (vía maldonado.gub.uy) — 2 actividades (una recurrente semanal)
  - ladiaria.com.uy — 1 evento directo + verificación cruzada de otros 2
  - Cuartel de Dragones — 1 evento (charla, confirmada por 2 fuentes)
  - Museo Regional Francisco Mazzoni — 1 charla (baja confianza, una sola fuente) + exposición en curso
  - maldonado.gub.uy/eventos — 2 eventos (festival gastronómico Glorieta del Puerto + Fiesta del Chorizo, esta última ya contada arriba)
  - Cines del Este (API weekly) + cartelera.montevideo.com.uy — sin funciones especiales propias, pero permitieron armar el resumen de estrenos y detectar 2 funciones especiales (vía maldonado.gub.uy/cine y Life Cinemas)
  - Cerveceros de Maldonado (vía radiovivafm.uy) — sin evento en esta ventana, pero 1 aporte a "Más adelante" (Octobeerfest)

- **Fuentes sin resultados (funcionaron pero no aportaron nada dentro de la ventana):**
  - https://www.maldonado.gub.uy/espectaculos
  - https://www.maldonado.gub.uy/arte-cultura (alternativa de cultura.maldonado.gub.uy) — desactualizada, solo exposiciones de meses anteriores
  - Calendario PDF vía /actividades — solo se encontró la versión de abril 2026; /actividades no devolvió resultados nuevos
  - Semanario La Prensa / Avant-Première — contenido cacheado de abril 2026 o eventos ya pasados
  - Portal de Piriápolis — solo eventos ya pasados o de otros meses
  - Piriápolis NET, Montevideo Portal — sin cambios respecto a la semana pasada
  - Teatro Cantegril, Teatro de Verano Margarita Xirgú — sin programación confirmada para la ventana
  - Grupocine (API) — catálogo sin desglose por sucursal, no permite confirmar qué se exhibe puntualmente en Punta del Este
  - Cinepunta — sin anuncio oficial de próxima edición (solo un rumor de prensa sobre "Sesiones de Primavera", sin fecha confirmada — no se publicó por no estar confirmado)
  - RedTickets, Songkick, Abitab, Tickantel, Bandsintown — sin aporte, ver detalle de errores abajo
  - Locales Nivel 4 (Giros, Lemon Pub, Mala Junta, Mockers, Solís Resto Pub, Piano Bar, Subsuelo, Paseo La Pasiva, Pueblo Gaucho, Club Centro Progreso, Ex Estación AFE) — ninguno con grilla confirmada para esta ventana puntual

- **Fuentes caídas / URL cambiada:**
  - https://cultura.maldonado.gub.uy/arte-y-cultura — sigue CAÍDA (error DNS), 2ª semana consecutiva. No hay indicio de que se vaya a resolver.
  - Abitab Entradas — sigue HTTP 403.
  - Tickantel — esta vez HTTP 503 (la semana pasada fue bucle de redirecciones) — sigue sin funcionar, con distinto error.
  - Bandsintown — sigue HTTP 403 en las 4 páginas de ciudad, 2ª semana consecutiva.
  - Songkick — esta vez HTTP 404 en la URL del venue Enjoy Punta del Este (la semana pasada cargaba pero sin shows) — revisar si cambió el slug.

- **Fuentes nuevas descubiertas:**
  - macamuseo.org/eventosmaca y entradas.macamuseo.org — calendario oficial del MACA, la más productiva de la semana.
  - ligapuntadeleste.com.uy — cobertura del cierre de la residencia orquestal TEMPO.
  - radiovivafm.uy — calendario de eventos itinerantes de Cerveceros de Maldonado.
  - piriapolisdepelicula.com.uy — sitio oficial del festival de cine de Piriápolis, resolvió la contradicción de fechas de la semana pasada.
  - portada.com.uy/agenda-portada — descubierta pero marcada como POCO CONFIABLE (ver nota de fuentes nuevas en el ranking): mezcló fechas de distintos meses. Usar solo como pista a verificar.

- **Eventos duplicados o mal fechados detectados:**
  - Ciclo de cine Sala Raimondi del viernes 26/9: la fuente oficial (maldonado.gub.uy/cine) indica "Pat Garrett y Billy the Kid" (Peckinpah, 1973), mientras que portada.com.uy indicaba "Cinco tumbas al Cairo". Se priorizó la fuente oficial y se marcó la discrepancia entre corchetes en el mail.
  - "Jornadas del Patrimonio" (3 y 4 de octubre): dos fuentes (maldonado.gub.uy con "Museos en Movimiento"/"Pasaporte Cultural" y cadenadelmar.uy con la jornada especial del Museo Ralli) muy probablemente describen el mismo fin de semana nacional de patrimonio con distinto nivel de detalle — se unificaron en una sola entrada en "Más adelante".
  - "Piriápolis de Película": la contradicción de fechas de la semana pasada (3 fechas distintas circulando) quedó resuelta: fecha oficial confirmada 16 al 18 de octubre de 2026, vía sitio oficial del festival y corroborada por cadenadelmar.uy.
  - "Rock del Este": originalmente programado para el 12/9 (antes de cualquier ventana relevada), fue reprogramado por mal tiempo al 17/10/2026 — confirmado de forma independiente por tres fuentes distintas, sin contradicción real pero requirió verificación.
  - El evento "Día Internacional de la Música" (jueves 1/10) cae justo un día después del cierre de esta ventana — queda para la próxima corrida, no se incluyó en este mail para evitar que quede fuera de ambas ventanas o se duplique.

- **Ajuste sugerido para la próxima:**
  1. Resolver (o compensar de forma permanente en el prompt) la desalineación día de disparo real vs. miércoles asumido — ya son 2 semanas seguidas cayendo en jueves.
  2. Verificar el jueves 1/10 explícitamente al arrancar la próxima corrida ("Día Internacional de la Música" y la 2ª función de cine en MACA quedaron pendientes de esa fecha).
  3. Para correopuntadeleste.com, repetir la consulta directa (ya no está bloqueada) y probar también 1-2 días después de mitad de semana, cuando suele publicar su nota de agenda del fin de semana.

---

## Ejecución 2026-10-01

**Nota sobre la fecha (recurrente, 3ª semana seguida):** la corrida volvió a caer en jueves real (1/10/2026), no en miércoles. Se cubrió la ventana jueves 1 al miércoles 7 de octubre de 2026 inclusive (7 días), siguiendo el criterio ya fijado la semana pasada ("hoy al miércoles siguiente", sin intentar forzar 8 días). Se verificó explícitamente el jueves 1/10 como pedía el ajuste de la semana pasada: sí tenía actividad (Cultura Huni Kuin, cine en el MACA, puertas abiertas de la Escuela de Música, inicio del tramo final del Encuentro de Literatura).

**Corrección sobre el mail de la semana pasada:** no se verificó de forma dedicada si hubo cancelaciones retroactivas de eventos publicados la semana del 24/9 al 30/9 (no se le pidió a ningún agente revisar eso puntualmente). Sin novedades reportadas de forma espontánea por los agentes sobre esa ventana ya cerrada.

**Metodología de esta corrida:** se repartió la investigación en 5 agentes en paralelo por grupo de fuentes (institucional, prensa local, museos/patrimonio, cine comercial, locales+agregadores) en lugar de secuencial. Permitió cubrir más fuentes en el mismo tiempo; como contrapartida, aparecieron algunas superposiciones entre agentes (mismo evento reportado por 2-3 agentes con pequeñas diferencias de horario/lugar) que hubo que cruzar y reconciliar al armar el mail — ver duplicados abajo.

- **Fuentes productivas esta semana:**
  - Cadena del Mar FM 106.5 — 6 eventos (Huni Kuin, raíces indígenas y arqueología familiar, Museo Ralli, Fiesta de la Primavera, Mercado Central, Cine en los Barrios) + Rock del Este y Torre del Vigía para otras secciones.
  - MACA (macamuseo.org/eventosmaca + entradas.macamuseo.org) — 5 eventos puntuales (cine 1/10, masterclass ballet, Mujeres de raíces profundas, LO NUESTRO, masterclass de cine para "Más adelante") + 1 exposición en curso.
  - CURE (www.cure.edu.uy, fuente nueva) — 5 actividades del Día del Patrimonio con horario y lugar precisos (inauguración exposición, visitas guiadas a excavación, conferencia).
  - Semanario La Prensa — 2 eventos bien fechados (Fiesta del Chivito, concierto Gerardo Dorado).
  - portada.com.uy (vía WebSearch dirigido, no la URL fija /agenda-portada) — 2 eventos (Encuentro de Literatura confirmado cruzado, Paseo de Autos Clásicos).
  - patrimoniouruguay.net (fuente nueva) — 1 evento (Museo García Uriburu).
  - elobservador.com.uy — 1 evento (Bus Patrimonial) + contexto general del Día del Patrimonio.
  - mediospublicos.uy — resumen general del Día del Patrimonio usado para el bloque de "más recorridos sin horario puntual".
  - Cines del Este (API) + Grupocine (API) + cartelera.montevideo.com.uy — sin funciones especiales, pero permitieron armar el resumen de estrenos con buena cobertura y confirmar ausencia de ciclos/debates esta semana.
  - radiovivafm.uy — Octobeerfest y Halloween Beer Fest para "Más adelante".
  - piriapolisdepelicula.com.uy — reconfirmó fecha de Piriápolis de Película (16-18/10), 3ª semana consecutiva sin contradicción.

- **Fuentes sin resultados (funcionaron pero no aportaron nada dentro de la ventana):**
  - maldonado.gub.uy/cultura, /espectaculos, /eventos, /actividades — cargaron pero sin eventos propios verificables con fecha/hora exacta para esta ventana (caída notable de maldonado.gub.uy/cultura respecto a semanas anteriores).
  - Casa de la Cultura / ciclo de cine Sala Raimondi (vía maldonado.gub.uy/cine) — sin programación verificable de octubre 2026.
  - Museo Regional Francisco Mazzoni — exposición anterior cerró el 25/9, sin reemplazo encontrado.
  - Cuartel de Dragones — el ciclo de charlas regulares terminó en marzo 2026, sin charla puntual esta semana (sí aparece en el contexto general de Patrimonio).
  - Teatro/Sala Cantegril, Teatro de Verano Margarita Xirgú — sin programación confirmada para la ventana (sí hay 2 datos sueltos para "Más adelante", sin verificar con fuente primaria).
  - ladiaria.com.uy, Correo de Punta del Este, Portal de Piriápolis, Piriápolis NET, Montevideo Portal, ligapuntadeleste.com.uy, Semanario La Prensa (parte de su cobertura de Patrimonio, descartada por desactualizada) — sin eventos nuevos esta semana (detalle de errores abajo).
  - RedTickets, Abitab, Tickantel, Bandsintown, Songkick, Facebook Events, grupo de Facebook "Agenda Cultural Piriápolis" — sin aporte, 3ª semana seguida para casi todos.
  - Prácticamente todos los locales de Nivel 4 (Cervecería Giros, Lemon Pub, Mala Junta, Mockers, Moonlight —excluido por regla—, Solís Resto Pub, Piano Bar, Subsuelo) — sin agenda puntual confirmada para la ventana.
  - Paseo La Pasiva, Club Centro Progreso/Sala Amalia Quintela, Ex Estación AFE, Pueblo Gaucho — confirmados activos con programación regular, pero sin grilla semanal específica publicada online.

- **Fuentes caídas / URL cambiada:**
  - cultura.maldonado.gub.uy/arte-y-cultura — sigue CAÍDA (error DNS), 3ª semana consecutiva.
  - Calendario oficial PDF (vía /actividades) — esta vez el link ni siquiera apunta a un calendario: lleva a un documento de "Primeros 100 Días de Gobierno" (octubre 2025). Se rompió de forma más grave que antes.
  - Portal de Piriápolis — HTTP 503 esta semana (antes solo traía contenido viejo).
  - Songkick (venue Enjoy Punta del Este) — el slug cambió de nuevo y ahora funciona de forma estable en https://www.songkick.com/venues/4485281-enjoy-punta-del-este (ya no da 404), pero sigue sin shows listados.
  - fundacionpabloatchugarry.org/es/eventos/ — sigue mostrando solo contenido histórico 2012-2022, no refleja la agenda vigente; dejar de consultarla por separado del calendario de macamuseo.org.
  - grupocine.com.uy/cartelera (home, SPA) — sigue vacía; usar siempre la API de catálogo en su lugar.
  - portada.com.uy/agenda-portada (URL fija) — sigue dando 404; el dominio en general sigue siendo válido vía WebSearch dirigido.

- **Eventos duplicados o mal fechados detectados:**
  - Cine en el MACA (1/10): un agente, citando la fuente oficial (macamuseo.org/eventosmaca), dio las 15:00; otro, citando agendadeleste.com, dio las 15:30. Se marcó la discrepancia entre corchetes en el mail, priorizando la fuente oficial.
  - "LO NUESTRO" (tango y folclore, 4/10): discrepancia de lugar entre Teatro MACA y Fundación Pablo Atchugarry según la fuente consultada (ambas del propio MACA, con datos distintos) — señalado entre corchetes en el mail, sin resolver.
  - "Festival de la Primavera" / "Fiesta de la Primavera" en Estación Las Flores (3/10): un agente lo reportó citando cadenadelmar.uy/eventos (listado general); otro agente intentó verificarlo de forma independiente y no encontró fuente dedicada ni programación, y lo excluyó por considerarlo no verificable. Se decidió incluirlo en el mail pero con advertencia explícita de "dato débil, confirmar antes de ir", en vez de excluirlo del todo o darlo por confirmado sin más.
  - Festival "Piriápolis de Película": una búsqueda arrojó "18-20/10" como posible fecha alternativa, pero la fuente oficial del festival sigue firme en "16-18/10" por 3ª semana consecutiva — se consideró prácticamente resuelto, y se priorizó la fuente oficial marcando la discrepancia menor entre corchetes.
  - Un agente detectó que varios resultados de búsqueda sobre "programación de octubre 2026" del Teatro Sociedad Unión de San Carlos correspondían en realidad al programa de OCTUBRE DE 2025 (misma fuente de prensa, mismo titular reciclado) — se descartó correctamente.
  - Se descartó un dato que atribuía a "Las Manolas" una actuación el 4/10/2026, que correspondía en realidad al calendario del Día del Patrimonio 2025 (año anterior) — detectado y excluido.
  - Semanario La Prensa devolvió una nota larga de "Día del Patrimonio" con fecha "sábado 1° de octubre", que en el calendario 2026 cae jueves — contenido cacheado de una edición de años anteriores (aparentemente 2022), descartado en su totalidad.
  - Se descartó un supuesto "Concierto Didáctico TEMPO" en MACA para el 1 y 3/10 por contradecir el calendario oficial (TEMPO fue del 21 al 26/9) y porque la URL del evento específico dio 404.

- **Ajuste sugerido para la próxima:**
  1. La desalineación día de disparo (jueves real) vs. miércoles asumido por el prompt ya lleva 3 semanas seguidas — asumirla como la norma de ahora en más y dejar de tratarla como anomalía puntual en cada corrida; seguir usando el criterio "hoy al miércoles siguiente inclusive" (7 días).
  2. Agregar www.cure.edu.uy y patrimoniouruguay.net a la lista fija de fuentes de Nivel 1/2, sobre todo útiles en la semana del Día del Patrimonio (principios de octubre) y en general para contenido académico/cultural.
  3. Dejar de reintentar semana a semana las fuentes con 3 strikes seguidos en 0 (RedTickets, Abitab, Tickantel, Bandsintown, Piriápolis NET, Montevideo Portal, Portal de Piriápolis, locales Giros/Lemon Pub/Mala Junta/Mockers/Solís Resto Pub/Piano Bar/Subsuelo): si vuelven a dar 0 la próxima semana, pasan formalmente a "Descartadas" y solo se revisan cada 4-5 semanas en vez de todas las semanas, para no gastar de más.
  4. Cuando varios agentes investigan en paralelo por grupo de fuentes, está bueno seguir haciéndolo (cubre más terreno en el mismo tiempo), pero conviene pedirles explícitamente que marquen con claridad cuándo un evento podría solaparse con otro venue/fuente que esté investigando otro agente (ej. "Día del Patrimonio" tiene actividades repartidas en casi todos los grupos de fuentes) para facilitar la reconciliación final.

---

## Ejecución 2026-10-08

**Nota sobre la fecha (recurrente, 4ª semana seguida):** la corrida volvió a caer en jueves real (8/10/2026), no en miércoles. Se cubrió la ventana jueves 8 al miércoles 14 de octubre de 2026 inclusive (7 días), siguiendo el criterio ya fijado ("hoy al miércoles siguiente inclusive"). Se verificaron las fechas con `date -d` para confirmar día de semana real antes de armar el mail.

**Corrección sobre el mail de la semana pasada:** ningún agente detectó cancelaciones ni errores retroactivos sobre la ventana 1-7/10 ya publicada. Sin novedades que corregir.

**Metodología:** 5 agentes en paralelo por grupo de fuentes (institucional, MACA/CURE/patrimonio, prensa local, cine comercial, locales Nivel 4+agregadores), igual que la semana pasada. Funcionó bien para cobertura, con el inconveniente esperado de alguna superposición menor a reconciliar (ninguna esta vez, a diferencia de semanas anteriores).

**Semana floja:** la cosecha de eventos puntuales con fecha exacta fue baja (9 confirmados, 2 de ellos con fecha/hora débil) — parece ser un valle entre el Día del Patrimonio (3-4/10) y los festivales de fin de octubre (Piriápolis de Película 16-18/10, Rock del Este 17/10, Festival de la Canción ~20-28/10). Se avisó explícitamente en el mail en vez de rellenar con contenido genérico.

- **Fuentes productivas esta semana:**
  - MACA (macamuseo.org/eventosmaca + entradas.macamuseo.org) — 5 eventos puntuales (cine documental doble con repetición, masterclass de cine, 2 conciertos) + 1 exposición en curso ("Juguemos en el Bosque"). Lejos la fuente más productiva, 4ª semana consecutiva en el puesto 1.
  - CURE (cure.edu.uy) — 1 evento concreto (charla "Gestionar lo común" el 8/10 en Punta del Este) + contexto de ELERNyMA (encuentro académico, descartado por no verificar apertura al público).
  - maldonado.gub.uy/cultura — 2 eventos (Encuentro de Cuchillería del Este, EnCanto Criollo con fecha débil) + novedad de renovación del circuito de muestras en 3 sedes (Museo Mazzoni, Foyer María Emma Núñez, Museo San Fernando) con 5 exposiciones nuevas, aunque sin título/horario exacto para algunas.
  - Cadena del Mar (cadenadelmar.uy/local) — aportó el detalle completo de las 5 muestras del circuito renovado (títulos, artistas, fechas de cierre) que maldonado.gub.uy solo mencionaba de forma genérica. Muy útil para completar un hallazgo de otra fuente.
  - Semanario La Prensa (Avant-Première) — 2 datos débiles pero reales (presentación disco "Andar" sin fecha exacta, jornada "Punta Negra mira al cielo"); esta vez las fechas de los eventos comunitarios sí coincidieron con el día de semana real de 2026 (verificado explícitamente).
  - portada.com.uy (vía WebSearch dirigido) — 1 exposición en curso confirmada ("Memorias del Mar", Caja de Arte Punta Shopping).
  - Cines del Este (API) + Grupocine (API) + cartelera.montevideo.com.uy (Life Cinemas) — sin funciones de cine nacional/ciclos, pero 3 funciones especiales subtituladas detectadas en Life Cinemas (2 en inglés, 1 en italiano sin doblaje) + resumen completo de estrenos.
  - piriapolisdepelicula.com.uy — confirmó de nuevo fecha (16-18/10) y agregó dato nuevo: homenajes a Perciavalle, Sorín y Tournier, y que el acceso del público es gratuito sin entrada anticipada (solo la convocatoria a cineastas, ya cerrada, requería inscripción).
  - maldonado.gub.uy (varias páginas vía agente institucional) — descubrió el patrón de URL del PDF mensual de calendario (`sites/default/files/AAAA-MM/`) y confirmó que la versión de octubre todavía no estaba publicada al momento de la consulta (sí existe la de septiembre).

- **Fuentes sin resultados (funcionaron pero no aportaron nada dentro de la ventana):**
  - maldonado.gub.uy/espectaculos, /eventos (muy ruidoso, 419 resultados sin filtro de fecha útil), /cine (sin programación de octubre para Sala Raimondi), /arte-cultura (desactualizado, último ítem de agosto).
  - Castillo de Piria (Piriápolis) y Argentino Hotel — sin horarios ni eventos puntuales confirmados (más allá de ser sede de Piriápolis de Película).
  - radiovivafm.uy — NO reprodujo el hallazgo de semanas anteriores sobre Cerveceros de Maldonado (Octobeerfest/Halloween Beer Fest); la home no mostró agenda de eventos esta vez. Revisar la próxima semana si cambió de sección o canal.
  - Museo García Uriburu, Museo Ralli — exposiciones permanentes/temporales mencionadas pero sin fechas de vigencia confirmadas para octubre 2026 (quedaron en el mail como "sin confirmar", no como evento puntual).
  - Correo de Punta del Este — devolvió contenido vacío en los 3 intentos (portada y /agenda/).
  - ladiaria.com.uy, Liga de Punta del Este, Cuartel de Dragones, Azotea de Haedo (sin resultados vía WebSearch, posible necesidad de red social directa), Teatro Cantegril y Teatro de Verano Margarita Xirgú (sin programación de octubre, solo el Festival de la Canción para "Más adelante").
  - Tickantel — cargó sin error pero solo lista venues de Montevideo, filtro por departamento no disponible vía WebFetch.
  - Songkick (Enjoy Punta del Este) — carga bien, "0 Upcoming concerts" explícito.
  - Paseo La Pasiva, Club Centro Progreso/Sala Amalia Quintela, Ex Estación AFE — sin grilla puntual esta semana (Pueblo Gaucho sí aportó, ver arriba).

- **Fuentes caídas / URL cambiada:**
  - cultura.maldonado.gub.uy/arte-y-cultura — sigue CAÍDA (error DNS), 5ª semana consecutiva. Sin indicios de resolución; se mantiene en el prompt como fuente Nivel 1 obligatoria pero ya no amerita más que un chequeo rápido.
  - RedTickets Uruguay (redtickets.com.uy) — el dominio ya no resuelve (DNS). Investigado y confirmado: RED UTS/RedTickets fue adquirida por Ticketmaster en agosto 2026, nuevo sitio **ticketmaster.uy**, que da HTTP 403 (mismo problema, nuevo nombre). Ver fila actualizada en el ranking.
  - maldonado.gub.uy/actividades — sigue sin resultados directos; redirige a /actividades-eventos (301 → agenda-actividades-idm) y a /calendario-eventos-2026, ambas con contenido mínimo (3 eventos sin fecha/hora/precio).
  - PDF de calendario mensual de octubre (maldonado.gub.uy/sites/default/files/2026-10/...) — HTTP 404, todavía no publicado al momento de la consulta (el de septiembre sí existe). Reintentar en los próximos días.

- **Fuentes nuevas descubiertas:**
  - **maldonado.gub.uy/agenda-actividades-idm** y **maldonado.gub.uy/calendario-eventos-2026** — URLs de destino a las que redirige /actividades; tienen contenido mínimo pero vale la pena consultarlas directamente de ahora en más en vez de depender del redirect.
  - **gub.uy/tramites/festival-internacional-cine-punta-este-2027-inscripciones-maldonado** — página oficial de trámites que confirma fechas y condiciones de Cinepunta 2027.
  - **ticketmaster.uy** — reemplaza a RedTickets Uruguay (ver arriba), mismo resultado (403) pero nuevo dominio a trackear.
  - Patrón de URL del calendario mensual de la IDM: `maldonado.gub.uy/sites/default/files/AAAA-MM/CALENDARIO%20DE%20EVENTOS...pdf` — útil para intentar directamente el mes en curso en vez de depender de que /actividades lo enlace.

- **Eventos duplicados o mal fechados detectados:**
  - Concierto de saxofón y piano del domingo 11/10 en Teatro MACA: la ficha principal (macamuseo.org/eventosmaca) lo llama "Dúo Figueira–Airaudo"; la plataforma de entradas (entradas.macamuseo.org) lo llama "Concierto Dúo Nómade". Mismo día/hora/lugar, nombre distinto — no se pudo resolver cuál es el nombre artístico correcto vía búsqueda externa. Se marcó la discrepancia entre corchetes en el mail, sin descartar el evento.
  - Festival Internacional de la Canción de Punta del Este (14ª edición): una fuente de prensa (Rio Times/Ground News, citada por el agente institucional) da fechas 20-24/10; otra (mencionada por el agente de prensa local como dato de contexto sin URL propia) da 26-28/10. Ninguna fuente oficial de Maldonado lo confirma todavía. Se incluyó en "Más adelante" con la discrepancia marcada explícitamente y advertencia de no comprar/difundir sin confirmar.
  - "EnCanto Criollo" (Pueblo Gaucho): la fuente dice que el certamen es "cada sábado" pero no confirma si la edición de este sábado 10/10 puntual se realiza — se incluyó en el mail con advertencia de fecha no confirmada en vez de omitirlo o darlo por hecho.
  - Se descartó un hallazgo de un agente sobre un supuesto "Encuentro Internacional de Poesía Esteros" en el MACA (vía ladiaria.com.uy) por no poder verificarlo en ninguna otra fuente ni ubicarlo en la agenda oficial de macamuseo.org — posible error de extracción de la nota.
  - Se descartó una mención a "Oriana Sabatini" presentando su novela el viernes 9/10 por tratarse de un evento en Montevideo (feria del libro), fuera del territorio de Maldonado.
  - Se descartó una grilla de Paseo La Pasiva encontrada en Montevideo Portal ("jueves a domingo") por corresponder a una nota de febrero 2025, no de octubre 2026 (verificado por fecha de publicación).

- **Ajuste sugerido para la próxima:**
  1. Confirmar la fecha real del Festival Internacional de la Canción de Punta del Este (discrepancia 20-24 vs. 26-28/10) apenas haya fuente oficial, antes de que la semana caiga dentro de la ventana.
  2. Reintentar el PDF de calendario de octubre de la IDM (patrón de URL ya identificado) en los próximos días, puede publicarse después del 8/10.
  3. Investigar por qué radiovivafm.uy dejó de mostrar la agenda de Cerveceros de Maldonado que había sido productiva las 2 semanas anteriores — puede haber cambiado de sección/formato.
  4. Dar seguimiento a ticketmaster.uy (ex RedTickets) con prioridad baja — mismo problema de acceso (403) que su predecesor, posible que nunca sea productivo pero vale un par de semanas más antes de descartar definitivamente.
  5. Confirmar directamente con la Casa de la Cultura de Maldonado la fecha exacta de la presentación del disco "Andar" de Cristhian Ortega, mencionada por La Prensa sin precisar día — si ya pasó o se puede confirmar, corregirlo en el próximo mail.
  6. **Nota técnica/infraestructura:** esta ejecución tuvo un error humano del agente orquestador (no de las fuentes): el primer envío del mail por Gmail se hizo con el cuerpo HTML mal formado (placeholder/texto escapado en vez del HTML real), y tuvo que reenviarse correctamente. Vale la pena que la próxima ejecución verifique el `htmlBody` antes de enviar, por ejemplo con una lectura rápida del contenido ya armado antes de la llamada a la herramienta de Gmail.
