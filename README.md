# 🃏 CardQuest
### Tu colección. Tu mercado. Tu universo.

**CardQuest** es una aplicación gratuita de gestión y seguimiento de cartas coleccionables, pensada para reunir **Pokémon, One Piece y Hello Kitty / Sanrio** en un mismo lugar.

Nuestro objetivo es que organizar una colección sea tan satisfactorio como ampliarla: registrar cartas, consultar su información, completar expansiones, conocer su valor orientativo y seguir la evolución del mercado desde el móvil.

> **Estado del proyecto:** desarrollo activo · versión de pruebas (alfa). Algunas funciones descritas abajo están en desarrollo y se indican como tales.

## 📦 Próxima APK para Android

Se ha verificado el archivo de prueba **CardQuest Vision v0.3.1-beta** (actualizador integrado). **Su APK todavía no está adjunta a GitHub Releases**. Consulta [notas y SHA-256](NOTAS-v0.3.1-beta.md) para saber qué se ha comprobado y cómo publicarla.

## 📦 Actualización en preparación

**CardQuest Vision v0.3.0:** nuevas secciones de Mercado, herramientas de copia/importación del álbum y fichas mejoradas. **La APK v0.3.0 todavía está pendiente de compilar y probar en Android; no está disponible en Releases.** Lee las [notas de actualización](ACTUALIZACION-v0.3.0.md) para conocer los cambios y las limitaciones.

## ✨ ¿Por qué CardQuest?

- **Tres universos en una sola app.** Catálogos organizados por franquicia, idioma, serie, expansión, número y variante, según la cobertura real de cada fuente.
- **Mi colección es mi colección.** El álbum personal muestra las cartas que tienes; una vista separada permite explorar el catálogo y las cartas que te faltan.
- **Valor económico transparente.** Precios orientativos con fuente y fecha, sin inventar cotizaciones donde no existan datos fiables.
- **Una experiencia visual propia.** Diseño oscuro, fichas técnicas y visor interactivo con efecto holográfico.
- **Coleccionar sin barreras.** Queremos mantener el proyecto gratuito y accesible, empezando por Android y la versión web.

## 📱 Funciones disponibles en las versiones de prueba

| Función | Estado |
| --- | --- |
| Inicio con resumen de la colección | ✅ Disponible |
| Inicio de sesión con Google e inventario individual sincronizado con Firebase | ✅ Disponible |
| Álbum personal y catálogo para explorar expansiones | ✅ Disponible |
| Pokémon, One Piece y Sanrio, con cobertura variable por colección e idioma | ✅ Parcial / en ampliación |
| Fichas técnicas de las cartas, cuando la fuente aporta información | ✅ Disponible |
| Visualizador de cartas con efecto holográfico e inclinación | ✅ Disponible |
| Cámara con reconocimiento OCR, selección del número y confirmación manual | 🧪 Experimental |
| Referencias de mercado Pokémon en euros mediante TCGdex / Cardmarket | 🧪 Disponible según carta y variante |
| Valor orientativo y gráfica de observaciones de precio en el dispositivo | 🧪 En pruebas |
| Versión web adaptable a móviles y escritorio y app Android | ✅ Disponible |

**Importante:** la cobertura no es idéntica para todos los juegos. La existencia de una carta en el catálogo no garantiza imagen, precio ni ficha técnica completa. Una cotización de referencia tampoco equivale a una tasación del estado físico de una carta.

## 📈 La visión: un mercado vivo

Estamos construyendo CardQuest para que el valor de una colección deje de ser una cifra aislada.

Queremos que el usuario pueda:

1. Ver el **valor orientativo de su colección** en euros y qué porcentaje de sus cartas tiene precio verificable.
2. Consultar la **gráfica histórica** de cada carta y del conjunto de su álbum.
3. Descubrir las **mayores subidas y bajadas**, tanto de sus cartas como del catálogo general.
4. Distinguir **cambios del mercado** de cambios provocados por añadir o retirar cartas.
5. Registrar cuánto pagó por cada carta y estimar su **ganancia o pérdida**.
6. Recibir novedades y alertas relevantes, con datos fechados y fuentes claras.

### Cómo estamos abordándolo

En las versiones de prueba, la consulta de mercado se realiza desde la aplicación; las gráficas solo reflejan observaciones realmente disponibles y parte del historial se guarda en el propio dispositivo.

**La actualización central diaria, incluso con la app cerrada, todavía está pendiente de activación y despliegue.** La prioridad es implementarla con servicios gratuitos y respetando los límites y condiciones de cada proveedor. No mostraremos movimientos históricos inventados ni mezclaremos ediciones o idiomas sin verificar la correspondencia.

## 🗺️ Próximas implementaciones

**Prioridad alta**

- [ ] Mercado independiente, con más filtros, cobertura y movimientos verificables.
- [ ] Sincronización central gratuita de precios y creación de historial compartido.
- [ ] Gráfica del valor total de cada colección, diferenciando movimientos de mercado y cambios de inventario.
- [ ] Copias de seguridad e importación/exportación de colecciones en CSV y JSON, con revisión previa.
- [ ] Mayor precisión del escáner y búsqueda de cartas sin conocer la expansión.

**Siguientes etapas**

- [ ] Amigos con invitaciones y permiso de lectura de álbumes, sin poder editar colecciones ajenas.
- [ ] Detección de cartas repetidas, comparación de faltantes y herramientas de intercambio.
- [ ] Más fuentes y mejor cobertura económica para One Piece y Sanrio.
- [ ] Seguimiento de estado de conservación, cartas graduadas (PSA, BGS, CGC) y precio de compra.
- [ ] Alertas configurables de variación de precios y novedades del mercado.
- [ ] Ampliación de catálogos, variantes, idiomas e imágenes verificadas.

**Ideas para explorar a futuro**

- [ ] Escaneo de varias cartas en una fotografía.
- [ ] Importación asistida desde archivos exportados por otras aplicaciones, cuando sea compatible y esté permitido.
- [ ] Listas de deseos, objetivos de colección y estadísticas compartibles.
- [ ] [Añadir aquí nuevas ideas de la comunidad].

Esta hoja de ruta expresa objetivos de desarrollo, no fechas de entrega ni funcionalidades ya garantizadas.

## 🔒 Nuestros principios

**Gratuito por diseño.** Evitar funciones esenciales de pago y controlar las cuotas de los servicios externos.

**Datos reales antes que cifras bonitas.** Mostrar de dónde procede cada precio y cuándo fue actualizado; identificar claramente las referencias ausentes o antiguas.

**Colecciones privadas.** Cada usuario conserva el control de su inventario. La futura función de amigos requerirá autorización y permisos de solo lectura.

**Respeto a las fuentes.** No copiar catálogos de terceros sin permiso ni presentar contenido comunitario como oficial. Las imágenes y nombres de las franquicias pertenecen a sus respectivos titulares.

**Una experiencia sencilla.** Rápida, visual y cómoda tanto para coleccionistas nuevos como para quienes administran miles de cartas.

## ⬇️ Descargar CardQuest

Este repositorio, **`cardquest-android-releases`**, está dedicado a las **APK y actualizaciones de Android**, así como a las novedades públicas del proyecto. **El código fuente se mantiene en un repositorio privado.**

- **APK de Android:** consulta la pestaña [Releases](../../releases), cuando haya una versión publicada.
- **Versión web:** [CardQuest en el navegador](https://cardquest-c107d.web.app) (versión de pruebas; su disponibilidad puede variar).

Las APK de pruebas pueden contener errores. Instálalas únicamente desde la página oficial del proyecto y conserva copias de seguridad de la información importante.

## 💬 Construyamos CardQuest

Este proyecto está creciendo a partir de las necesidades reales de coleccionistas.

**¿Qué te gustaría añadir?** Puedes proponer nuevas ideas para el mercado, la cámara, la organización de álbumes, las amistades o la experiencia visual. Las iremos evaluando e incorporando a esta hoja de ruta.

---

**CardQuest es un proyecto independiente de aficionados.** No está afiliado, patrocinado ni respaldado por The Pokémon Company, Bandai, Sanrio, Cardmarket ni otras marcas mencionadas. Las cotizaciones mostradas por la aplicación son estimaciones informativas, no garantías de venta.
