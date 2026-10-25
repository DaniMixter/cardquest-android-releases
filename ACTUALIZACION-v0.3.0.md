# CardQuest Vision v0.3.0 — Notas de actualización

> **Estado:** código de la versión preparado para pruebas. **La APK v0.3.0 todavía no está publicada** en [Releases](../../releases). Estas notas NO implican que la versión ya esté instalada ni disponible para descargar.

## Novedades de la versión de pruebas

- **Mercado:** nueva pestaña independiente para consultar cotizaciones, cobertura de cartas con precio y movimientos observados, con enlaces y fechas de las fuentes.
- **Refresco de precios:** consultas desde la aplicación por tandas, con caché y revalidación al cabo de seis horas mientras está abierta o vuelve a primer plano.
- **Gráficas:** observaciones realmente guardadas en fechas distintas. Las medias de 24 h, 7 d y 30 d publicadas por el proveedor no se presentan como puntos históricos.
- **Mi colección:** separado de la exploración del catálogo y de la vista de cartas pendientes.
- **Perfil:** exportación JSON/CSV y herramienta de importación de **archivos propios de CardQuest** con revisión previa; todavía no importa directamente CSV de Collectr.
- **Fichas técnicas:** campos adicionales de Pokémon y One Piece cuando los suministra el catálogo.
- **Conservamos:** inicio de sesión con Google, inventarios separados en Firebase, cámara OCR experimental, visor holográfico y navegación Android.

## Cobertura y límites

La cotización de mercado disponible se basa en referencias Cardmarket en EUR a través de TCGdex para determinadas cartas Pokémon. **No** hay valoración automática verificada para todas las cartas, variantes, estados, graduaciones, idiomas japoneses, One Piece ni Sanrio.

La actualización **con la aplicación cerrada** no está activada: se ha preparado un experimento de feed diario externo que requiere configuración y comprobación de las condiciones de uso de los datos. No anunciarlo como funcionamiento continuo hasta desplegarlo y verificarlo.

**Amigos** y CSV de Collectr continúan como funciones futuras. La v0.3.0 es una versión de prueba, no una edición estable.

## Pasos antes de publicar la APK

1. En el ordenador donde está el proyecto privado, copiar los archivos de `src` de la v0.3.0 conservando `.env`, Firebase, Android y `package.json`.
2. En la raíz del proyecto: `npm run build`. Corregir cualquier error antes de continuar.
3. Probar Google, el inventario, la cámara, mercado e importación (hacer antes una copia JSON).
4. Ejecutar `npx cap sync android` para copiar el nuevo frontend a Android.
5. En `android`: ejecutar `.\gradlew.bat clean :app:assembleDebug` con Java de Android Studio.
6. Comprobar que existe una **APK recién compilada** en `android/app/build/outputs/apk/debug/app-debug.apk` y probarla en el teléfono.
7. Cuando la APK funcione y esté verificada, crear una versión **pre-release** en GitHub Releases con las notas y adjuntar el archivo. Las APK debug son solo para pruebas; para una distribución estable se necesitará una APK release firmada con una clave protegida y mantenida.

La carpeta pública de GitHub es solo para documentación y APK; **no publiques código privado, secretos, credenciales, ficheros `.env`, claves de firma ni inventarios**.
