# TALOS v16 — Monitor de Balizas de Tráfico

**Un vistazo a los datos que viajan por las carreteras españolas sin que nadie lo sepa.**

---

## ¿De qué va esto?

TALOS es un panel de visualización que muestra en tiempo real (o casi) la actividad de las balizas V16 en España. Esas luces naranjas que los conductores colocan en la carretera cuando tienen una avería o un accidente.

Lo que mucha gente no sabe es que estas balizas no solo emiten luz. También transmiten datos: coordenadas GPS, identificador único, carretera, municipio, orientación... Todo esto viaja por redes públicas y queda registrado.

Este proyecto nace de una pregunta incómoda: **¿qué pasa con esa información?**

---

## Por qué debería importarte

Cada vez que alguien activa una baliza V16 en España, se genera un registro con su ubicación exacta. Pensemos en lo que eso significa:

- Sabemos dónde ocurren las averías
- Sabemos a qué hora
- Sabemos en qué carretera y en qué sentido
- Podemos rastrear patrones de una misma baliza a lo largo del tiempo

Ahora imagina que esa información cae en las manos equivocadas. O que alguien con acceso decide cruzarla con otras bases de datos. O que simplemente se almacena indefinidamente sin ningún tipo de anonimización.

No estamos hablando de teorías. Estamos hablando de datos que ya existen, que ya se transmiten, y que nadie te ha preguntado si quieres compartir.

---

## Qué encontrarás aquí

El dashboard permite explorar:

- **Vista general** con métricas agregadas de actividad
- **Anomalías** detectadas automáticamente (saltos geográficos imposibles, ráfagas de señales, coordenadas fuera de España...)
- **Ranking de balizas** más activas
- **Distribución por carreteras** con sentido y orientación
- **Mapa interactivo** con todos los puntos de actividad registrados
- **Desglose por ubicación**: comunidades, provincias y municipios

Todo esto a partir de datos reales recogidos en un periodo de prueba.

---

## La pregunta que nadie hace

Cuando compraste tu baliza V16, ¿alguien te explicó que cada vez que la enciendas estarás enviando tu posición a un servidor? ¿Te preguntaron si estabas de acuerdo? ¿Sabes quién tiene acceso a esos datos y durante cuánto tiempo los conservan?

Este proyecto no pretende asustar a nadie. Pero sí creemos que la gente tiene derecho a saber qué información están generando sin darse cuenta. Y que alguien debería estar haciendo estas preguntas antes de que sea demasiado tarde.

---

## Sobre el proyecto

TALOS v16 es un proyecto de investigación y concienciación. No tiene ánimo de lucro ni pretende comercializar ningún tipo de dato.

El código fuente está disponible para que cualquiera pueda auditarlo, mejorarlo o simplemente aprender de él. Lo único que pedimos es que si lo usas, respetes la licencia y no lo utilices con fines comerciales.

---

## Autor

**Jose Miguel Martínez**

Si tienes preguntas, sugerencias o simplemente quieres hablar sobre privacidad y datos de movilidad, no dudes en abrir un issue o contactarme.

---

## Licencia

Este proyecto se distribuye bajo licencia **CC BY-NC 4.0** (Creative Commons Atribución-NoComercial 4.0 Internacional).

Puedes ver, compartir y adaptar este trabajo siempre que:
- Des crédito al autor original
- No lo uses con fines comerciales

Consulta el archivo [LICENSE](./LICENSE) para más detalles.
