# CypherMedia - Repositorio Oficial de Lanzamientos

![Ultima Version](https://img.shields.io/github/v/release/FxxMorgan/CypherVersionChecker?style=for-the-badge&color=ff6b35&label=Ultima%20Version)
![Android](https://img.shields.io/badge/Android-7.0%2B-10b981?style=for-the-badge&logo=android)
![Seguridad](https://img.shields.io/badge/Integridad-SHA--256-3b82f6?style=for-the-badge)

Repositorio oficial para la descarga y verificacion de seguridad de los archivos APK de **CypherMedia**.

> **Importante**: Descarga CypherMedia unicamente desde este repositorio o desde enlaces proporcionados por el equipo oficial. Cualquier otro origen no garantiza la integridad del archivo.

---

## Que es CypherMedia

CypherMedia es una aplicacion de entretenimiento para Android disenada para ofrecer una experiencia de streaming completa, rapida y sin interrupciones. Compatible con telefonos, tablets, Android TV y dispositivos Fire TV.

---

## Caracteristicas Principales

### Reproduccion

- **Inicio de reproduccion en menos de 2 segundos** desde que presionas play, gracias al motor de video nativo ExoPlayer.
- **Soporte de formatos HLS y MP4** con resolucion automatica de calidad segun la velocidad de tu conexion.
- **Subtitulos integrados** cargados automaticamente desde el contenido disponible.
- **Pantalla siempre encendida** mientras reproduces contenido, sin que el dispositivo se suspenda.
- **Reanudacion de reproduccion**: Si sales de un capitulo o pelicula, al volver continua exactamente donde lo dejaste.

### Navegacion de Contenido

- **Catalogo completo de peliculas y series** con busqueda en tiempo real.
- **Pagina de detalles** con sinopsis, ano de estreno, generos, duracion, calificacion y listado de temporadas y episodios.
- **Seleccion de idioma por servidor**: Elige entre Latino, Subtitulado, Castellano u otros idiomas disponibles para cada titulo.
- **Varios servidores de reproduccion por titulo**: Si un servidor no funciona o esta lento, puedes cambiar a otro de forma inmediata.
- **Contenido de anime**: Soporte dedicado con fuentes especializadas y deteccion automatica de proveedores anime.

### Siguiente Episodio Automatico

- **Auto-play del siguiente episodio**: Al terminar un capitulo, aparece una cuenta regresiva de 10 segundos con la portada y titulo del siguiente episodio.
- **Opcion de cancelar o reproducir manualmente** durante la cuenta regresiva.
- **Deteccion de inactividad**: Si llevas varios episodios seguidos, la app pregunta "Sigues ahi?" antes de continuar automaticamente.

### Perfiles

- **Hasta 5 perfiles independientes** por dispositivo, cada uno con su propio nombre y avatar.
- **Historial de reproduccion separado** por perfil, para que cada persona tenga su propio progreso.
- **Seleccion de perfil al iniciar la app**, similar a la experiencia de plataformas como Netflix.

### Transmision a Otros Dispositivos (Cast)

- **Google Chromecast**: Envia el contenido directamente a tu televisor mediante Chromecast.
- **DLNA / Smart TV**: Detecta automaticamente televisores inteligentes en tu red local y transmite contenido sin necesidad de cables ni configuracion adicional.
- **Panel de dispositivos**: Busqueda automatica de dispositivos disponibles en la red local con un solo toque.

### Television en Vivo (IPTV)

- **Canales de television en vivo** organizados por categorias y region.
- **Filtro por pais**: Mexico, Argentina, Chile, Espana, Estados Unidos, Brasil y una opcion para ver todos los canales.
- **Busqueda de canales** por nombre dentro de la seccion IPTV.
- **Reproductor integrado** con los mismos controles y calidad que el reproductor principal.

### Bloqueo de Anuncios

- **Sistema de bloqueo multi-capa** que elimina ventanas emergentes, popups y redireccionamientos indeseados.
- **Filtrado a nivel de red, CSS y JavaScript** cuando se utiliza el modo WebView como respaldo.
- **Sin banners ni publicidad dentro de la aplicacion**.

### Actualizaciones

- **Actualizaciones automaticas (OTA)**: La app verifica al iniciar si existe una version mas reciente y muestra un dialogo para descargar e instalar la actualizacion sin salir de la aplicacion.
- **Actualizaciones forzadas**: En caso de parches criticos de seguridad, la app puede requerir la actualizacion antes de continuar.

### Ajustes

- **Configuracion de conexion personalizable** para usuarios avanzados.
- **Informacion de licencia y estado de suscripcion** visible desde los ajustes.
- **Verificacion manual de actualizaciones** disponible en cualquier momento.

---

## Descargas

Accede siempre a la version mas reciente en la seccion de [Releases](https://github.com/FxxMorgan/CypherVersionChecker/releases/latest).

| Arquitectura | Dispositivos compatibles | Archivo |
| :--- | :--- | :--- |
| **ARM 64-bit** (Recomendado) | Telefonos modernos, tablets, Android TV 64-bit | `app-arm64-v8a-release.apk` |
| **ARM 32-bit** | TV Box genericos, Fire TV Stick antiguos, Chromecast HD | `app-armeabi-v7a-release.apk` |
| **x86_64** | Emuladores de PC (BlueStacks, LDPlayer, Nox) | `app-x86_64-release.apk` |

**[Ir a la pagina de descargas](https://github.com/FxxMorgan/CypherVersionChecker/releases/latest)**

> **Nota**: Si no sabes cual elegir, descarga la version **ARM 64-bit**. Es compatible con la gran mayoria de dispositivos Android actuales.

---

## Verificacion de Seguridad e Integridad

Antes de instalar cualquier APK descargada fuera de la Play Store, es recomendable verificar que el archivo no haya sido alterado. Para ello, cada version publicada en las [Releases](https://github.com/FxxMorgan/CypherVersionChecker/releases) incluye las huellas digitales SHA-256 correspondientes.

### Paso 1: Obtener el hash del archivo descargado

**En Windows (PowerShell):**

```powershell
Get-FileHash app-arm64-v8a-release.apk -Algorithm SHA256
```

**En Linux, macOS o Android (Termux):**

```bash
sha256sum app-arm64-v8a-release.apk
```

### Paso 2: Comparar con el hash oficial

El resultado del comando debe coincidir exactamente con el SHA-256 publicado en la descripcion de la version correspondiente en GitHub Releases. Si los valores no coinciden, **no instales el archivo** y descargalo nuevamente desde la fuente oficial.

### Paso 3 (Opcional): Analisis en VirusTotal

Puedes verificar el archivo en [VirusTotal](https://www.virustotal.com) de dos formas:

1. **Subir el archivo APK** directamente a la plataforma.
2. **Buscar por hash**: Copia el SHA-256 obtenido en el paso anterior y pegalo en el buscador de VirusTotal para consultar si el archivo ya fue analizado.

---

## Guia de Instalacion

### Telefonos y tablets Android

1. Descarga el archivo APK correspondiente desde la seccion de [Releases](https://github.com/FxxMorgan/CypherVersionChecker/releases/latest).
2. Abre el archivo descargado. Si Android solicita permisos, activa la opcion **"Permitir desde esta fuente"** en la configuracion de seguridad.
3. Presiona **Instalar** y abre la aplicacion.

### Smart TV, Android TV o Fire TV Stick

1. Instala la aplicacion gratuita **Downloader** desde la Play Store o Amazon Appstore de tu televisor.
2. Abre Downloader e ingresa la URL directa del archivo APK desde GitHub Releases.
3. Concede los permisos de instalacion necesarios e instala CypherMedia.

---

## Privacidad y Proteccion de Datos

CypherMedia esta disenada respetando la privacidad de sus usuarios, en cumplimiento con la Ley N° 21.719 de Chile y los principios del GDPR europeo:

- **Datos minimos**: La app solo requiere una clave de licencia para funcionar. No solicita acceso a contactos, camara, microfono ni almacenamiento de archivos personales.
- **Identificadores anonimizados**: Los identificadores de dispositivo se almacenan de forma irreversible mediante hashes criptograficos HMAC SHA-256. No es posible obtener la identidad del dispositivo a partir de estos datos.
- **Sin venta ni cesion de datos**: No compartimos informacion con terceros, redes publicitarias ni plataformas de analitica.

---

## Soporte

Si encuentras algun problema o tienes sugerencias:

- Abre un reporte en la seccion de [Issues](https://github.com/FxxMorgan/CypherVersionChecker/issues).

---

CypherMedia Team. Todos los derechos reservados.
