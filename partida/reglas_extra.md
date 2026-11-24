# REGLAS EXTRA — ECLIPSE ERRANTE
Reglas agregadas durante la partida que no están en el prompt original. Si una regla de este archivo contradice al prompt original, gana la de este archivo. Cada regla nueva se agrega acá, completa, en el mismo turno en que el jugador la da. Si una regla cambia otra, se reemplaza la vieja y se anota la fecha del cambio.

---

## R1. LAS RAZAS SE COPIAN (desde T14 · reemplaza la sección 8, "Las razas no se copian")
- La copia incluye poderes y transformaciones raciales: Super Saiyajin y todas sus formas, Ozaru, regeneración namekiana, kagunes (con su kakuhou), hollowficación y formas de Hollow y Arrancar, alas, transformaciones de demonios y cualquier poder racial de cualquier mundo.
- Se copian igual que todo: ver el poder en persona, cumplir la misión de copia, recibirlo entero con dominio total; funciona en todos los mundos.
- Facundo no cambia de raza. El Sistema da el poder, no el cuerpo. Su físico normal no cambia; los rasgos de la transformación (pelo dorado, kagune, alas, máscara) aparecen solo mientras la usa.
- Sin las desventajas de la raza: la cola saiyajin no lo debilita, el kagune no lo obliga a comer carne humana ni lo debilita con comida normal, la hollowficación no le hace perder el control; nada trae maldiciones, hambre, locura ni dependencias.
- Las transformaciones con etapas (formas del Super Saiyajin, kakuja) se copian enteras aunque haya visto solo una.
- Lo que se ve, se ve: si se transforma delante de alguien, lo vio; cada mundo lo interpreta a su manera. Se registra en conocimiento.md.
- Se fusiona con todo como cualquier copia.
- Los objetos siguen sin venir con la copia.
- Recordatorio permanente: se copia todo, incluidas las razas y sus transformaciones, sin sus desventajas; los objetos no se copian.

## R2. LA COPIA INCLUYE LAS ETAPAS FUTURAS (T309 · corrección del jugador)
- La copia de un poder incluye todo lo que ese personaje llega a hacer en su canon, también las etapas que todavía no desbloqueó en el momento de la copia. Aplicado a Ichigo y a Goku (Dios, Blue, Kaio-ken sobre Blue, Ultra Instinto Señal y Dominado). Se aplica igual a toda copia.

## R3. DOMINIO DE MANECILLA INVERSA: NADIE DE AFUERA SIENTE LO DE ADENTRO (T335 · declarado por el jugador)
- Mientras el Cuadrante del Retorno está activo, nadie de afuera puede sentir lo que pasa adentro del dominio: ni reiatsu, ni sonido, ni ningún sentido de energía.

## R4. EL INVENTARIO AL MORIR (desde T341 · declarado por el jugador)
- Si Facundo muere, lo que está en el inventario dimensional se queda ahí dentro para siempre. Nada ni nadie lo puede sacar.

## R5. MULTIPLICADORES SAIYAJIN (desde T439 · fijados por el motor para coherencia de escala)
- Super Saiyajin x50 · SSJ2 x100 · SSJ3 x400 (Daizenshuu, canon) · SSJ Dios x1.000 · SSJ Blue x2.000 · Kaio-ken sobre Blue: x2 a x20 adicional sobre el Blue · Ultra Instinto Señal x3.000 (y esquiva solo) · Ultra Instinto Dominado x5.000 (ataca y esquiva solo).
- Se aplican sobre los stats base. No se combinan con la Forma Cenit salvo que el jugador lo declare.

## R6. HAKI DE OBSERVACIÓN AL MÁXIMO (T659 · declarado por el jugador)
- Facundo tiene el Haki de observación al máximo, sin entrenamiento.

## R7. INMUNIDAD A KYŌKA SUIGETSU (T159 · regla del canon aplicada)
- Facundo tocó la hoja sellada de Kyōka Suigetsu antes de ver su liberación: es inmune a su hipnosis. Aizen lo sabe.

## R8. ESTE ARCHIVO, LA ÚLTIMA ESCENA Y LA CARGA (dada después del T794 · Día 38 · regla del jugador, textual)

### 1. TODAS LAS REGLAS NUEVAS VAN A UN ARCHIVO
- Creá partida/reglas_extra.md. Escribí ahí, completas y textuales, todas las reglas que te pasé durante la partida y que no están en el prompt original (por ejemplo, la de copiar transformaciones y poderes de raza), y esta misma regla.
- Desde ahora, cada regla nueva que te pase se agrega a ese archivo, completa, en el mismo turno. Si una regla nueva cambia otra, se reemplaza la vieja y se anota la fecha del cambio.
- Si una regla de ese archivo contradice al prompt original, gana la de reglas_extra.md.

### 2. LA ÚLTIMA ESCENA SE GUARDA ENTERA
- Creá partida/ultima_escena.md. Al final de cada turno, guardá ahí tus últimas 3 respuestas completas, textuales, con sus ventanas, y los últimos 3 comandos míos. Se reescribe cada turno.
- Así el chat nuevo sabe exactamente dónde quedamos, cómo venía escrita la historia y qué estaba por pasar.

### 3. CÓMO SE CARGA LA PARTIDA EN UN CHAT NUEVO (CONTINUE)
Al recibir CONTINUE, antes de escribir nada, hacé esto en orden, leyendo cada archivo ENTERO (no por partes, no resúmenes):
1. Pull del repo.
2. partida/reglas_extra.md (todas las reglas agregadas).
3. partida/sistema.json (incluido reglas_ampliadas).
4. partida/contexto.md.
5. partida/ultima_escena.md.
6. partida/facundo.md, partida/kase.md y, si existe, partida/viajes.md.
7. Las últimas 40 líneas de partida/bitacora.md.
8. Los archivos del mundo o del lugar actual: mundo.md, cronologia.md, conocimiento.md, noticias.md y grupo.md (en el crossover, todo partida/mundos/[mundo actual]/).
9. Las fichas de todos los personajes presentes en la escena y de todos los vínculos activos que figuran en contexto.md.
10. La ficha del lugar actual.
11. El archivo de canon/ del arco en curso.
Si un archivo no existe, seguí con los demás y anotalo.

Después, respondé así y nada más:
- Una línea entre corchetes: [Partida cargada · turno N · lugar · X reglas extra · Y personajes leídos · archivos faltantes: ninguno / cuáles]
- Un recap de 3 a 5 líneas que retome exactamente donde terminó la última escena, con el mismo tono.
- La ventana.
Y esperá mi comando. No avances la historia.

### 4. EN CADA TURNO, SI DUDÁS, RELEÉ
Si en cualquier turno no estás seguro de un dato (qué sabe alguien, una regla, un poder, un número), releé el archivo en vez de suponer. Nunca inventes algo que debería estar en un archivo.

### 5. ANTES DE QUE YO CAMBIE DE CHAT
Cuando escriba /salir o /guardar, antes del commit y push, revisá que contexto.md, ultima_escena.md, reglas_extra.md, sistema.json y las fichas de los presentes estén actualizados.

---

## NOTAS DE FORMATO (correcciones del jugador en esta partida)
- T750: la Tasación va siempre en su ventana (recuadro de la sección 5), nunca como línea entre corchetes. El guardado (commit y push) se hace en silencio, sin anunciarlo en la narración.
