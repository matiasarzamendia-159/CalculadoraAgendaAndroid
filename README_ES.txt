CALCULADORA DE AGENDAS — PROYECTO ANDROID

Este paquete contiene el proyecto fuente para compilar una APK Android con tu
calculadora HTML original dentro de una aplicación WebView. La calculadora y
sus cálculos se mantienen; el almacenamiento local (localStorage) está habilitado.

IMPORTANTE
Este paquete es el PROYECTO FUENTE, no una APK ya compilada. Para generar el
archivo APK se necesita Android Studio con Android SDK instalado.

CÓMO GENERAR LA APK
1. En una computadora, instala Android Studio desde https://developer.android.com/studio
2. Descomprime CalculadoraAgendasAndroid.zip.
3. Abre Android Studio y elige Open.
4. Selecciona la carpeta CalculadoraAgendasAndroid descomprimida.
5. Espera a que Gradle sincronice. Si pide instalar Android SDK Platform 35 o
   herramientas de compilación, acepta la instalación.
6. Ve a Build > Build Bundle(s) / APK(s) > Build APK(s).
7. Al terminar, Android Studio mostrará un aviso con la ubicación de la APK.
   Normalmente queda en app/build/outputs/apk/debug/app-debug.apk.
8. Copia esa APK al teléfono Android y ábrela para instalarla. Es posible que
   Android pida permitir instalaciones desde esa fuente.

NOTAS
- La aplicación carga la calculadora desde un archivo local, por lo que los
  cálculos no requieren conexión a Internet.
- Las fuentes tipográficas externas pueden necesitar Internet; si no hay
  conexión, se usarán las fuentes alternativas declaradas en el HTML.
- Los datos se guardan en el almacenamiento local de la aplicación. Al borrar
  los datos de la app o desinstalarla, pueden perderse.
- Para publicar la app en Google Play o distribuir una APK firmada, se requiere
  una configuración adicional de firma.
