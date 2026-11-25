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

## R9. VARIAS RELACIONES, UNA POR MUNDO (dada en el T803 · Día 41 · reemplaza en parte la sección 14, "Romance")
- Texto del jugador: "hace que pueda tener varias novias en diferentes mundos y ninguna se entera de la otra excepto que yo lo diga".
- Desde el T803, Facundo puede tener una relación de pareja en cada mundo distinto, al mismo tiempo. Lo que reemplaza: la frase de la sección 14 "Sin harem. Una relación por vez, en todos los mundos juntos".
- Ninguna pareja se entera de las otras, salvo que Facundo lo diga. Esto encaja con la regla 1.2 (la información nunca cruza de un mundo a otro).
- Sigue vigente todo lo demás de la sección 14: solo con personajes adultos en ese momento del canon (nunca menores ni adultos con cuerpo de niño), conquistar es lento, ellas tienen vida propia y pueden decir que no, (es una amiga) es irreversible, y en las escenas íntimas, fundido.
- Interpretación del motor (el jugador puede corregirla): una pareja por mundo.

## R10. SAKAIME: LÍNEAS INVISIBLES Y SIN LÍMITE DE TIEMPO (T837-T839 · Día 35 Shingeki · declarado por el jugador)
- T837: las líneas-frontera del Shikai de Sakaime pueden ser invisibles si Facundo quiere.
- T839: duran lo que Facundo quiera (reemplaza el límite de "hasta 10 minutos" del Shikai) y pueden cubrir un escenario entero.

## R11. EL HAKI DE FACUNDO ES AZUL Y BLANCO (T874 · Día 56 One Piece · declarado por el jugador)
- Texto del jugador: "recubro mi brazo con haki (color azul fuerte y blanco)".
- El Haki de armadura de Facundo es azul intenso con vetas blancas, no negro. Por coherencia, también los rayos de su Haki del Rey con recubrimiento.

## R12. PELO A VOLUNTAD (T878 · Día 57 One Piece · pedido por el jugador)
- Texto del jugador: "dame una habilidad para poder cambiar mi pelo a voluntad".
- El Sistema le da la habilidad "Pelo a voluntad": Facundo cambia el color (y el largo) de su pelo cuando quiere, al instante, en cualquier mundo, y lo vuelve a su blanco y azul cuando quiere. No cambia los ojos, ni la cicatriz, ni los tatuajes.

---

## NOTAS DE FORMATO (correcciones del jugador en esta partida)
- T750: la Tasación va siempre en su ventana (recuadro de la sección 5), nunca como línea entre corchetes. El guardado (commit y push) se hace en silencio, sin anunciarlo en la narración.
- T1202: las misiones de copia van siempre en su ventana REGISTRO DE PODER (recuadro de la sección 8), una por poder, nunca resumidas en una línea entre corchetes ni en una lista fuera de la narración.

## R13. YMIR ES ADULTA (T931 · Día 48 Shingeki · decisión del jugador)
- Texto del jugador: "aparenta unos 18 o 19 pero estuvo 60 años de titán, así que déjala como mayor".
- Ymir cuenta como adulta (aparenta 18-19; vivió unos 60 años como titán). Sigue vigente la sección 14: escenas íntimas con fundido, nunca el momento sexual.
