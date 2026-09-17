# Fuentes — Agenda Cultural Maldonado

Registro acumulado de qué fuentes funcionan, cuáles no, y qué se aprendió en cada ejecución semanal. Se actualiza al final de cada corrida.

## Ranking de fuentes (por productividad acumulada)

| # | Fuente | Nivel | Ejecuciones | Eventos aportados (total) | Notas |
|---|---|---|---|---|---|
| 1 | https://www.maldonado.gub.uy/cultura | 1 | 1 | 5 | Buena fuente pero mezcla épocas; hay que filtrar por fecha manualmente (paginado con miles de resultados viejos). |
| 2 | Calendario oficial PDF (vía /actividades) — https://www.maldonado.gub.uy/sites/default/files/2026-09/CALENDARIO%20DE%20EVENTOS_0.pdf | 1 | 1 | 3 (confirmación cruzada) | El PDF cambia de nombre/mes cada vez; hay que volver a ubicarlo cada semana desde /actividades. |
| 3 | Cadena del Mar FM 106.5 — https://cadenadelmar.uy/eventos | 2 | 1 | 3 + 2 exposiciones | La fuente de prensa más productiva esta semana. Buena cobertura de museos/exposiciones. |
| 4 | ladiaria.com.uy (sección Maldonado) | — (no estaba en la lista original) | 1 | 1 festival (CINEFEM, multi-día) | Fuente nueva descubierta, ver abajo. |
| 5 | Cuartel de Dragones (vía WebSearch, sin sitio propio) | 1 | 1 | 1 | Solo accesible indirectamente vía maldonado.gub.uy/noticias. |
| 6 | La Azotea de Haedo (vía WebSearch, sin sitio propio) | 1 | 1 | 1-2 | Ídem, sin web propia estable. |
| 7 | Fundación Pablo Atchugarry / MACA | 1 | 1 | 0 eventos puntuales / 2 exposiciones en curso | Útil para exposiciones de largo aliento, no para agenda semanal puntual. |
| 8 | Castillo Pittamiglio, Piriápolis | 1 | 1 | 0 eventos puntuales / 1 atractivo patrimonial permanente | Sirve para la sección de patrimonio en curso. |
| 9 | Semanario La Prensa / Avant-Première — https://semanariolaprensa.com | 2 | 1 | 1-2 (parcial, solapa con Cadena del Mar) | No publica agenda consolidada de fin de semana en formato fijo; hay notas sueltas. |
| 10 | Portal de Piriápolis — https://www.piriapolisportal.com.uy | 2 | 1 | 1 | Aporte mínimo pero funcional. |
| 11 | Museo Regional Francisco Mazzoni | 1 | 1 | 0 eventos puntuales / 1 exposición en curso | Sin web propia con cartelera; datos vía WebSearch. |
| 12 | Cines del Este — https://www.cinesdeleste.com.uy/ | 3 | 1 | 0 especiales (cartelera comercial normal) | La home es un SPA vacío; funciona vía su API pública `cde-prod-web-api.azurewebsites.net/api/shows/cinema/weekly`. |
| 13 | cartelera.montevideo.com.uy/cine (Life Cinemas Punta Shopping) | 3 | 1 | 0 especiales | Única cartelera de cine en HTML estático legible directo. Muy útil como respaldo de Grupocine. |
| 14 | RedTickets Uruguay | 5 | 1 | 0 | Funciona pero no tiene oferta cultural en Maldonado, solo Montevideo y turismo. |
| 15 | Songkick (venue Enjoy Punta del Este) | 5 | 1 | 0 | Funciona pero sin shows anunciados esta vez. |

### Fuentes que funcionan pero no aportaron nada esta semana
- https://www.maldonado.gub.uy/espectaculos (1)
- https://www.maldonado.gub.uy/eventos (1) — sí aportó 1 evento (Encuentro del Chocolate), ver arriba en /cultura combinado — nota: mantenida aquí porque su aporte fue vía el PDF, no directo.
- Teatro Cantegril, Punta del Este (1) — sin programación verificable para la semana puntual.
- Teatro de Verano Margarita Xirgú (1) — teatro de temporada estival, sin actividad en septiembre.
- Grupocine Punta del Este — https://grupocine.com.uy/cartelera (3) — SPA sin cartelera en el HTML; hay que usar su API `grupocine.com.uy/api/peliculas` + cruzar con cartelera.montevideo.com.uy.
- Cinepunta — https://cinepunta.uy/ (3) — el festival ya se realizó en febrero 2026; no hay novedades hasta que anuncien la próxima edición.
- Montevideo Portal, sección Maldonado / Tiempo Libre (2) — solo trae noticias inmobiliarias/policiales, contenido cultural indexado suele ser viejo.
- Abitab Entradas / Tickantel (5) — sin eventos culturales en la zona; además con problemas de acceso (ver caídas).
- Setlist.fm (5) — es un archivo histórico, no sirve para agenda futura.

## Descartadas
(Ninguna fuente lleva todavía 4 ejecuciones seguidas sin aportar — esta es la primera ejecución. Se empezará a completar esta sección a partir de la 4ª corrida.)

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
