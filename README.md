<p align="center">
  <a href="./README_EN.md">
    <img src="https://img.shields.io/badge/🌐_Read_in_English-2563eb?style=for-the-badge" alt="Read in English" height="35" />
  </a>
</p>

<h1 align="center">⚡ Converto 2.0 «Filanan»</h1>

<p align="center">
  <strong>Tu centro unificado de escritorio para convertir, comprimir, unir y optimizar archivos multimedia y documentos 100% sin conexión.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.0_«Filanan»-blue?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/Tauri-v2-24C8D8?style=flat-square&logo=tauri&logoColor=white" alt="Tauri v2" />
  <img src="https://img.shields.io/badge/Svelte-Kit-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="SvelteKit" />
  <img src="https://img.shields.io/badge/Rust-Backend-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Engines-FFmpeg_%7C_ImageMagick-red?style=flat-square" alt="Engines" />
  <img src="https://img.shields.io/badge/Platform-Windows_x64-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
  <img src="https://img.shields.io/badge/Languages-19_(RTL_Supported)-10b981?style=flat-square" alt="19 Languages" />
</p>

---

## 📖 Descripción

**Converto 2.0 «Filanan»** es una aplicación de escritorio todo-en-uno para Windows, reconstruida por completo desde cero respecto a su primera versión en Python. Gracias a su nueva arquitectura nativa (**Rust + Tauri v2 + Svelte**), ofrece un rendimiento mucho más rápido, fluido y estable, con una interfaz moderna pensada tanto para usuarios casuales como para flujos de trabajo intensivos (edición de multimedia, *scanlation* de cómics/mangas, gestión documental y organización masiva de archivos).

No requiere conexión a internet ni instalaciones externas: todo el procesamiento se realiza de forma local en tu equipo con **FFmpeg** e **ImageMagick** integrados directamente en la aplicación.

---

## ✨ Características Principales

### 🛠️ 5 Motores Especializados

* **🖼️ Imágenes y Creador de Álbumes / Cómics:**
  * **Procesamiento ultrarrápido en paralelo:** Convierte lotes masivos en 5 carriles simultáneos (`JPG`, `PNG`, `WEBP`, `AVIF`, `HEIC`, `BMP`, `TIFF`, `ICO` multicapa `256×256`, `PSD`, `EPS`).
  * **Creador de Álbumes y Cómics:** Empaqueta carpetas o secuencias de imágenes directamente en **Cómic CBZ (`.cbz`)**, **CBT (`.cbt`)**, **EPUB Cómic (`.epub`)**, **TIFF Multipágina (`.tiff`)** y **GIF Animado (`.gif`)** con control de calidad dedicado.
  * Vista previa de miniaturas con altura redimensionable y selección múltiple en cola.

* **🎵 Audio y Fusión de Pistas:**
  * Conversión por lotes entre `MP3`, `WAV`, `FLAC`, `M4A`, `OGG`, `OPUS`, `AMR` y más.
  * **Extracción de audio desde video:** Arrastra cualquier archivo de video para extraer su pista de sonido al instante.
  * **Modo Unificar Audio:** Combina múltiples canciones, notas de voz o videos de forma secuencial en un único archivo de audio continuo.
  * Control granular de **Bitrate** (con detección automática de formatos *Lossless* sin pérdida), **Frecuencia de muestreo** (ajustada dinámicamente según el códec) y **Canales** (*Estéreo* / *Mono*).

* **🎬 Video y Exportación a GIF:**
  * Transcodificación fluida entre `MP4`, `MKV`, `AVI`, `MOV`, `WEBM`, `FLV`, `WMV` y **exportación directa a GIF animado**.
  * Perfiles de compresión listos para usar (*Alta Calidad*, *Equilibrada*, *Comprimido*, *Ultra Ligero*) y ajuste de resolución (incluyendo `360p` para dispositivos móviles).

* **📄 Documentos, Código y PDF:**
  * **Documentos a PDF:** Detección automática y conversión desde `.DOCX`, `.TXT`, imágenes y archivos de código fuente/scripts (`.PY`, `.JS`, `.RS`, etc.), permitiendo generar archivos PDF individuales o unir todo en un único documento.
  * **Herramientas PDF:** Une varios PDF en uno solo, extrae todo su texto a `.TXT` o convierte sus páginas a imágenes (`PNG`, `JPG`, `WEBP`) eligiendo la nitidez exacta en **DPI** (`72`, `150`, `300` o `600 DPI`).
  * **Unificar Textos:** Consolida múltiples archivos de texto plano o código en un solo documento.

* **📦 Compresión y Extracción:**
  * Empaqueta archivos y carpetas completas eligiendo el nivel de compresión (*Solo almacenar / Rápida / Normal / Máxima Ultra*) o en formato `TAR` sin compresión.
  * Extracción masiva de archivos `.ZIP`, `.RAR`, `.7Z`, `.TAR`, `.TAR.GZ`, `.TAR.BZ2` y `.TAR.XZ` conservando el nombre original o definiendo uno personalizado.

---

### 🖥️ Experiencia de Uso y Productividad

* **📊 Monitor Lateral en Tiempo Real:** Visualiza al instante el total en cola, archivos en espera, en proceso y completados, barra de progreso del lote, archivo activo e historial persistente de tareas con botón de acceso directo a la carpeta de salida.
* **📍 Exportación Dinámica Multiruta:** Procesa archivos provenientes de distintas carpetas al mismo tiempo y elige guardar cada resultado junto a su archivo original, en tus bibliotecas predeterminadas de Windows o dentro de subcarpetas organizadas.
* **🏷️ Reglas de Renombrado y Protección contra Sobrescritura:** Añade prefijos, sufijos o nombres personalizados por lote. Si un archivo ya existe en el destino, decide si deseas reemplazarlo o continuar con numeración automática (`01`, `02`...).
* **🌓 Personalización Visual y Sonora:** Barra lateral colapsable y redimensionable, modo Claro y Oscuro (manual, sincronizado con Windows o programado automáticamente por horario), sonidos personalizables de éxito/error y apertura automática del Explorador de archivos al finalizar.
* **🌍 Soporte Global en 19 Idiomas (con soporte RTL):** Español, Inglés, Portugués, Francés, Alemán, Italiano, Ruso, Japonés, Chino (Simplificado y Tradicional), Coreano, Hindi, Turco, Polaco, Neerlandés, Ucraniano, Indonesio, Vietnamita y **Árabe** (con inversión completa de interfaz de derecha a izquierda).

---

## 🚀 Descarga e Instalación

Dirígete a la sección de **[Releases](https://github.com/RogzcaMX/Converto/releases)** del repositorio y descarga la edición que prefieras para **Windows (64 bits)**:

1. **Instalador Estándar (Recomendado):**
   * Descarga `Converto.v2.0.0.x64.setup.exe` y ejecútalo. Incluye el entorno WebView2 offline y las librerías necesarias para funcionar sin internet.
2. **Versión Portable (Sin instalación):**
   * Descarga `Converto.v2.0.0.x64.Portable.zip`, extrae todo su contenido en una carpeta y ejecuta `Converto.exe`. Incluye FFmpeg e ImageMagick listos para usar.

---

## ☕ Apoya el Proyecto

Si **Converto** te ayuda y ahorra tiempo en tu flujo de trabajo diario, considera apoyar su desarrollo y futuras actualizaciones:

* **PayPal:** [Donar vía PayPal](https://www.paypal.com) *(reemplaza con tu enlace)*
* **Ko-Fi:** [Donar en Ko-Fi](https://ko-fi.com) *(reemplaza con tu enlace)*
