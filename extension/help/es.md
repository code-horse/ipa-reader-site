---
layout: bare
title: Extensión IPA Reader - Guía de usuario
lang: es
---

# IPA Reader - Guía de usuario

> Versión: v1.4.1

## Introducción

IPA Reader es una extensión de navegador diseñada para estudiantes de inglés. Añade anotaciones de pronunciación IPA (alfabeto fonético internacional) a las palabras en inglés en páginas web y PDFs, compatible con acentos americano y británico. También incluye un diccionario de inglés integrado, texto a voz y funciones de traducción — para ayudarte a aprender la pronunciación del inglés con mayor facilidad.

---

## Características principales

- **Modo IPA página completa** — Añade anotaciones IPA a todas las palabras en inglés de la página con un solo clic, con símbolos IPA codificados por color (vocales, consonantes, acentos) para una lectura fácil
- **Diccionario al pasar el cursor** — Pasa el cursor sobre las palabras para ver definiciones en inglés (más de 82 000 palabras de WordNet), IPA con símbolos codificados por color y botones de pronunciación; elige entre modo Diccionario, modo Tooltip o Desactivado
- **Lector PDF** — Lector PDF integrado con anotaciones IPA, diccionario, voz y traducción; admite arrastrar y soltar, carga por URL y detección automática de PDF con redirección inteligente
- **Formas débiles/fuertes** — Muestra automáticamente las variantes de pronunciación débil y fuerte de palabras funcionales (p. ej. the, to, can) para dominar el habla natural
- **Acentos americano y británico** — Alterna entre IPA americano (en-US) y británico (en-GB)
- **Texto a voz** — Haz clic en el botón de altavoz para escuchar la pronunciación según tu acento seleccionado
- **Lectura de selección con efecto karaoke** — Selecciona texto en inglés: aparece una barra compacta con botones de hablar y traducir; la reproducción incluye resaltado palabra a palabra en tiempo real (efecto karaoke) sincronizado con el audio
- **Traducción de la selección** — Selecciona cualquier texto, pulsa el botón traducir de la barra para obtener traducción instantánea mediante Bing o Google Traductor, mostrada en una burbuja integrada
- **Desambiguación de homógrafos** — Identifica automáticamente palabras con múltiples pronunciaciones (p. ej. read, live) y selecciona la correcta según el contexto
- **Atajos de teclado** — Acceso rápido a las funciones principales mediante atajos personalizables
- **Interfaz multilingüe** — Compatible con 41 idiomas de interfaz

---

## Cómo usar

### Paso 1: Instalar la extensión

Instala **IPA Reader** desde [Chrome Web Store](https://chromewebstore.google.com/), o cárgala localmente en modo desarrollador.

### Paso 2: Abrir cualquier página web

Visita cualquier página web que contenga contenido en inglés.

### Paso 3: Activar IPA

Haz clic en el icono de la extensión en la barra de herramientas del navegador. Activa «Activar IPA» y luego «IPA página completa» para anotar todas las palabras de la página. También puedes usar el botón flotante abajo a la derecha.

### Paso 4: Ver el IPA

Pasa el cursor sobre las palabras para ver los tooltips de IPA, haz clic en el icono de altavoz para escuchar la pronunciación. En palabras con formas débiles/fuertes, el tooltip muestra ambas variantes.

### Paso 5: Hablar y traducir el texto seleccionado

Selecciona texto en inglés con el ratón. Aparece una barra compacta cerca de la selección con dos botones:
- **🔊 Hablar** — Lee el texto seleccionado en voz alta con resaltado palabra a palabra estilo karaoke
- **🌐 Traducir** — Muestra una burbuja de traducción integrada debajo de la barra

También puedes hacer clic derecho y elegir «IPA Reader > Speak Selection» o «IPA Reader > Translate Selection».

> **Consejo:** Haz clic en el icono de la extensión en la barra de herramientas del navegador para abrir el panel de ajustes y configurar el tipo de acento, velocidad de lectura, modo al pasar el cursor, motor de traducción, etc.

---

## Modo IPA página completa

Con el modo IPA página completa activado, cada palabra en inglés de la página recibe una anotación IPA encima del texto en formato ruby. Los símbolos IPA están codificados por color:

- **Vocales** — resaltadas en azul
- **Consonantes** — en gris
- **Marcas de acento** (ˈ ˌ) — resaltadas en rojo
- **Marcas de longitud** (ː) — resaltadas en morado

La extensión ajusta automáticamente el interlineado y escala el tamaño de fuente del IPA según la longitud de la palabra.

---

## Diccionario al pasar el cursor

La extensión incluye un diccionario de inglés integrado basado en WordNet (más de 82 000 palabras). Puedes elegir entre varios modos al pasar el cursor en los ajustes:

| Modo | Comportamiento |
|------|----------------|
| **Diccionario** | Al pasar el cursor: IPA + definición en inglés + botón de pronunciación |
| **Tooltip** | Al pasar el cursor: IPA + botón de pronunciación (sin definiciones) |
| **Desactivado** | Sin efecto al pasar el cursor |

En el modo **Diccionario**, el tooltip muestra:
- La palabra y su transcripción IPA
- Un botón de pronunciación (clic para escuchar)
- Definiciones en inglés de WordNet

> **Consejo:** Los datos del diccionario se cargan bajo demanda cuando el modo Diccionario está activo y se descargan al cambiar a otros modos para ahorrar memoria.

---

## Lector PDF

IPA Reader incluye un lector PDF integrado que te permite leer documentos PDF con anotaciones IPA, diccionario, voz y traducción — las mismas funciones que en páginas web, ahora también en PDF.

### Abrir un PDF

**Método 1: Desde el menú emergente**  
Haz clic en el icono de la extensión y luego en «Abrir lector PDF». Arrastra y suelta un archivo PDF o haz clic en «Elegir archivo» para abrir un PDF local. También puedes pegar una URL de PDF.

**Método 2: Menú contextual**  
Haz clic derecho en cualquier enlace `.pdf` en una página web y elige «Abrir PDF con IPA Reader».

**Método 3: Detección automática**  
Si «Detección inteligente de PDF» está activada en los ajustes, la extensión redirige automáticamente las URLs `.pdf` al lector integrado. Si se detecta un PDF pero no se redirige (p. ej. el visor integrado de Chrome), verás notificaciones e invitaciones para abrirlo en IPA Reader.

### Funciones del lector PDF

- **Anotaciones IPA** — Todas las funciones IPA funcionan en el texto del PDF, incluido el modo página completa y los tooltips al pasar el cursor
- **Diccionario por clic** — Clic en cualquier palabra para ver su definición (en PDF se usa el clic en lugar del paso del cursor para una lectura sin distracciones)
- **Barra de selección** — Selecciona texto para hablar, traducir o copiar
- **Barra lateral** — Esquema del índice y miniaturas de página
- **Búsqueda** — Busca texto en el PDF
- **Temas** — Temas de lectura oscuro, claro y sepia
- **Zoom** — Varios niveles de zoom, incluidos Automático, Ajustar página y Ancho de página
- **Atajos de teclado** — Flechas para navegar, +/- para zoom, Ctrl/Cmd+F para buscar

---

## Formas débiles/fuertes

Muchas palabras funcionales comunes en inglés tienen dos pronunciaciones:

- **Forma débil** — la pronunciación reducida en el habla natural (p. ej. «the» → /ðə/)
- **Forma fuerte** — la pronunciación plena para énfasis o en aislamiento (p. ej. «the» → /ðiː/)

Si «Mostrar formas débiles/fuertes» está activado, al pasar el cursor sobre estas palabras el tooltip muestra ambas variantes etiquetadas como «WEAK» y «STRONG».

Incluye, entre otras: artículos (the, a, an), preposiciones (to, for, of, from, at, as, than), conjunciones (and, or, but), pronombres (you, your, her, him, his, them, us, our, there), auxiliares (am, is, are, was, were, been, can, could, would, should, must, shall, will, do, does, have, has, had), y más.

---

## Lectura de selección y karaoke

La lectura de selección permite seleccionar texto en inglés y leerlo en voz alta con un solo clic — ideal para aprender la pronunciación de frases y practicar la lectura.

**Método 1: Barra de selección**  
Selecciona texto en inglés con el ratón. Aparece una barra compacta con un botón 🔊 hablar y un botón 🌐 traducir. Haz clic en hablar para reproducir. Mientras se lee, cada palabra se resalta en tiempo real (efecto karaoke).

**Método 2: Menú contextual**  
Tras seleccionar texto en inglés, clic derecho y elige «IPA Reader > Speak Selection».

**Método 3: Atajo de teclado**  
Selecciona texto y pulsa `Alt+Shift+S` (Mac: `Ctrl+Shift+S`).

> **Consejo:** El efecto karaoke funciona mejor si el navegador admite eventos de límites de palabras TTS. Si no, la extensión usa un respaldo basado en tiempo para un resaltado fluido.

---

## Traducción

Selecciona cualquier texto en la página y usa la traducción para obtener traducciones al instante.

**Método 1: Barra de selección**  
Selecciona texto y haz clic en 🌐 traducir en la barra. Aparece una burbuja debajo con el resultado y un botón copiar.

**Método 2: Menú contextual**  
Selecciona texto, clic derecho y elige «IPA Reader > Translate Selection».

**Método 3: Atajo de teclado**  
Selecciona texto y pulsa `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motores de traducción:**
- **Bing Traductor** (predeterminado) — con tecnología de Microsoft Translator
- **Google Traductor** — con tecnología de Google

Ambos motores admiten **108 idiomas de destino**.

Puedes cambiar el motor y el idioma de destino en los ajustes de la extensión. El idioma de destino se detecta automáticamente desde el idioma del navegador.

> **Consejo:** Haz clic fuera de la barra o la burbuja para cerrarlas.

---

## Atajos de teclado

| Atajo | Atajo Mac | Acción |
|----------|-------------|--------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Activar/desactivar anotaciones IPA |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Leer la selección |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traducir la selección |

> **Consejo:** Puedes personalizar estos atajos en Chrome en `chrome://extensions/shortcuts`.

---

## Guía de ajustes

| Ajuste | Descripción |
|--------|-------------|
| **Activar IPA** | Interruptor principal para activar o desactivar la función de anotación IPA |
| **IPA página completa** | Cuando está activado, muestra IPA codificado por color encima de todas las palabras en inglés |
| **Tipo de acento** | Elige entre inglés americano y británico para IPA y pronunciación |
| **Modo al pasar el cursor** | Elige el comportamiento al pasar el cursor: Diccionario (IPA + definiciones + audio), Tooltip (IPA + audio) o Desactivado |
| **Formas débiles/fuertes** | Mostrar las variantes de pronunciación débil y fuerte de palabras funcionales |
| **Velocidad de frases** | Ajusta la velocidad de lectura de frases (la pronunciación de palabras individuales no se ve afectada) |
| **Motor de traducción** | Elige entre Bing Traductor y Google Traductor |
| **Idioma de destino** | Define el idioma de destino de la traducción (detectado automáticamente desde el navegador) |
| **Detección inteligente de PDF** | Si está activada, redirige automáticamente las URLs de PDF al lector integrado y muestra notificaciones cuando se detectan PDF |

---

## Preguntas frecuentes

**P: ¿Por qué no funciona en algunas páginas?**  
R: Por razones de seguridad, las extensiones del navegador no pueden ejecutarse en páginas especiales como `chrome://`, ajustes del navegador o Chrome Web Store.

**P: ¿Qué pasa si falta IPA para algunas palabras?**  
R: El diccionario IPA cubre más de 134 000 palabras en inglés americano y más de 67 000 en inglés británico. Para palabras fuera del diccionario, la extensión genera IPA aproximado mediante lematización y G2P, marcado con ≈ o ~ en la sugerencia.

**P: ¿No hay sonido con texto a voz?**  
R: Comprueba la configuración de volumen del sistema y asegúrate de que los paquetes de voz en inglés estén instalados. El soporte de voz varía según el navegador y el sistema operativo.

**P: ¿El modo página completa afecta al diseño?**  
R: Las anotaciones IPA requieren espacio adicional. La extensión ajusta el interlineado para reducir el impacto. Si afecta a la lectura, desactiva el modo página completa y usa los tooltips al pasar el cursor.

**P: ¿Qué significan los símbolos ~ y ≈ en las sugerencias?**  
R: ~ indica que el IPA fue generado por reglas (G2P) y ≈ que fue derivado de una palabra base relacionada. Pueden ser menos precisos que las entradas del diccionario.

**P: ¿La traducción no funciona?**  
R: La traducción requiere conexión a Internet. Si Bing Traductor falla, prueba a cambiar a Google Traductor en los ajustes. Algunas redes pueden bloquear el acceso a los servicios de traducción.

**P: ¿Cómo abro un PDF con IPA Reader?**  
R: Puedes abrir PDF de varias formas: haz clic en «Abrir lector PDF» en el menú emergente, clic derecho en un enlace PDF y elige «Abrir PDF con IPA Reader», o activa «Detección inteligente de PDF» en los ajustes para redirigir automáticamente las URLs de PDF al lector integrado.

**P: Tengo activada la detección inteligente de PDF pero algunos PDF no se redirigen**  
R: La redirección automática funciona para URLs que terminan en `.pdf`. Para PDF servidos sin extensión `.pdf` o vistos en el visor integrado de Chrome, verás una notificación y una insignia que te invitan a abrirlo en IPA Reader.

**P: ¿Puedo usar el diccionario sin conexión?**  
R: Sí. El diccionario WordNet (más de 82 000 palabras) va incluido por completo en la extensión. Todas las consultas se hacen en local, sin conexión a red.

---

## Enlaces relacionados

- [Política de privacidad](../privacy-policy)
- [Soporte y comentarios](../support)

---
