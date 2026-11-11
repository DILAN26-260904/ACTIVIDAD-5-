# 🛡️ Actividad 5 — Recuperación de Archivos, NMAP y Chatbot de Seguridad
DILAN FELIPE LAGOS JIMENEZ 


```
# 🔧 1. Introducción e Instalación de Recuva

---

## 📌 ¿Qué es Recuva?

> **Recuva** es un programa gratuito desarrollado por la empresa Piriform, diseñado para **recuperar archivos que han sido borrados accidentalmente** de tu computadora, memoria USB, tarjeta de memoria o disco duro externo. Funciona porque cuando borras un archivo, el sistema operativo en realidad no lo elimina por completo; solo marca ese espacio como disponible para reutilizar.

**Funciones principales:**
- ✅ Recuperar archivos borrados de la papelera de reciclaje
- ✅ Recuperar archivos de unidades externas (USB, tarjetas SD, discos externos)
- ✅ Buscar por tipo de archivo: fotos, documentos, videos, música, correos
- ✅ Dos modos de escaneo: rápido y profundo
- ✅ Vista previa de archivos recuperables

**Versiones:**
- 🆓 **Recuva Standard:** Gratuito para uso personal
- 💳 **Recuva Professional:** De pago — incluye actualizaciones automáticas, soporte técnico y recuperación de discos dañados o formateados

---

## 📥 Instalación de Recuva — Paso a Paso

### 🌐 Paso 1: Descargar desde la página oficial
1. Entra al sitio oficial: **https://www.ccleaner.com/recuva**
2. Haz clic en el botón de descarga gratuita ("Free Download")
3. Selecciona la versión gratuita y descarga el instalador

> ⚠️ **Recomendación importante:** Descarga siempre desde la página oficial para evitar versiones modificadas que puedan contener malware.

### ⚙️ Paso 2: Ejecutar el instalador
1. Haz doble clic en el archivo descargado
2. **⚠️ IMPORTANTE:** No instales Recuva en la misma unidad donde vas a recuperar archivos. Si vas a recuperar archivos de tu disco C:, instálalo en el disco D: o en una memoria USB. **Esto evita que el propio instalador sobrescriba los archivos que quieres recuperar.**
3. Selecciona tu idioma y haz clic en **Siguiente**

### 📋 Paso 3: Opciones de instalación
1. Acepta los términos de uso
2. Elige la carpeta de instalación (recuerda: unidad diferente a la que escanearás)
3. Desmarca opciones adicionales como instalar CCleaner u otras barras si no las necesitas
4. Haz clic en **Instalar**

### ✅ Paso 4: Finalizar
1. Haz clic en **Finalizar**
2. Recuva se abre automáticamente y está listo para usar

---

## 🖼️ Infografía Sugerida — Instalación Segura de Recuva

```

┌──────────────────────────────────────────────────────────────┐
│       🛡️ INSTALACIÓN SEGURA DE RECUVA 🛡️                       │
├──────────────────────────────────────────────────────────────┤
│                                                                │
│  1️⃣  DESCARGAR                                                 │
│     ✅ Desde la página oficial: [ccleaner.com/recuva](https://ccleaner.com/recuva)          │
│     ❌ No usar sitios de descarga de terceros                 │
│                                                                │
│  2️⃣  UBICACIÓN DE INSTALACIÓN                                  │
│     ✅ Instala en UNIDAD DIFERENTE a la que vas a escanear    │
│     ✅ Ejemplo: Recuva en USB → Recuperar de Disco C:         │
│     ❌ NO instales en el mismo disco a recuperar               │
│     ⚠️  Razón: Evita sobrescribir datos borrados              │
│                                                                │
│  3️⃣  DURANTE LA INSTALACIÓN                                    │
│     ✅ Desmarca programas adicionales que no necesitas        │
│     ✅ Verifica que el instalador sea de confianza            │
│                                                                │
│  4️⃣  ¡LISTO!                                                   │
│     ✅ Abre Recuva y comienza tu escaneo seguro               │
│                                                                │
└──────────────────────────────────────────────────────────────┘

# 🔍 2. Uso Básico de Recuva — Escaneos y Resultados

---

## 📂 a) Selección del Tipo de Archivo a Recuperar

Al iniciar Recuva, el asistente te pregunta **qué tipo de archivos buscas**. Estas son las opciones disponibles:

| Tipo de archivo | ¿Qué busca? | ¿Cuándo usarlo? |
|-----------------|-------------|-----------------|
| 🖼️ **Imágenes** | Fotos en JPG, PNG, GIF, BMP, RAW, etc. | Cuando sabes que solo necesitas recuperar fotografías |
| 📄 **Documentos** | Word, Excel, PDF, TXT, PowerPoint, etc. | Para recuperar trabajos, apuntes o registros |
| 🎵 **Música** | MP3, WAV, FLAC, AAC, etc. | Archivos de audio y canciones |
| 🎬 **Videos** | AVI, MP4, MOV, WMV, MKV, etc. | Archivos de video pesados |
| 📧 **Correos electrónicos** | Mensajes de Outlook, Thunderbird, etc. | Recuperar correos borrados |
| 🗑️ **Todos los archivos** | Busca en formatos de todo tipo | Cuando no estás seguro del tipo de archivo |

### ⚡ ¿Por qué elegir bien el tipo de archivo?
- **Agilidad:** Si buscas solo fotos, Recuva no pierde tiempo escaneando videos o documentos
- **Precisión:** Reduce el número de resultados irrelevantes
- **Tiempo:** Un escaneo específico puede tardar minutos menos que buscar "todos los archivos"

---

## 📍 b) Selección de la Ubicación

Recuva necesita saber **dónde buscar**. Las opciones son:

| Ubicación | Para qué sirve |
|-----------|----------------|
| 🗑️ **En la Papelera de reciclaje** | Archivos que acabas de borrar y no has vaciado la papelera |
| 📁 **En Mis documentos** | Busca solo dentro de esa carpeta de usuario |
| 💻 **En toda la computadora** | Escanea todas las unidades conectadas — más lento pero más completo |
| 🔌 **En una ubicación específica** | Eliges tú la carpeta o unidad exacta — recomendado para USB o discos externos |

### ✅ Actividad: Cómo realizar un escaneo rápido

**Paso a paso:**
1. Abre **Recuva** → Haz clic en **Siguiente**
2. Selecciona el **tipo de archivo** que buscas → Siguiente
3. Selecciona **dónde buscar** (ej: en una ubicación específica → elige tu USB o carpeta de prueba) → Siguiente
4. Haz clic en **Iniciar**
5. Espera mientras Recuva escanea
6. Aparecen los resultados con círculos de colores

> 📸 **Pantallazo sugerido:** Captura la ventana principal de resultados mostrando archivos encontrados con sus colores. Guárdalo como `imagenes/escaneo_rapido.jpg` en tu repositorio.

---

## ⚡🔬 Modo Normal vs. Modo Profundo

| Característica | ⚡ Escaneo Normal | 🔬 Escaneo Profundo |
|----------------|-------------------|---------------------|
| **Velocidad** | Rápido (segundos a minutos) | Lento (minutos a horas) |
| **Qué encuentra** | Archivos recientes con registro intacto | Archivos antiguos, fragmentados, con registros dañados |
| **Profundidad** | Lee la tabla de archivos del sistema | Analiza cada sector del disco byte por byte |
| **Cuándo usarlo** | Primera opción — si no encuentras nada, pasa al profundo | Cuando el escaneo normal falla y el archivo es importante |

### 🧪 Cómo activar el escaneo profundo:
1. Realiza primero un escaneo normal
2. Si no encuentras lo que buscas, ve al menú **Opciones → Acciones**
3. Marca la casilla **Habilitar escaneo profundo**
4. Vuelve a ejecutar el escaneo — ten paciencia, tardará más tiempo

---

## 🟢🟡🔴 Interpretación de Resultados — Código de Colores

Recuva usa un sistema de **círculos de colores** para indicar el estado de cada archivo:

| Color | Estado | ¿Qué significa? | ¿Se puede recuperar? |
|-------|--------|-----------------|----------------------|
| 🟢 **Verde** | Excelente | El archivo está intacto y recuperable con alta probabilidad | ✅ Sí, casi seguro |
| 🟡 **Amarillo** | Parcialmente dañado | Parte del archivo ha sido sobrescrito o dañado — puede abrirse incompleto o con errores | ⚠️ Posiblemente parcial |
| 🔴 **Rojo** | Irrecuperable | Los datos han sido sobrescritos por otros archivos — es muy poco probable recuperarlo | ❌ Muy difícil o imposible |

### 👁️ Previsualización de archivos:
- Selecciona un archivo en la lista → aparece una miniatura en el panel derecho
- Solo funciona con formatos compatibles (imágenes, algunos documentos)
- Te permite verificar si el archivo es el correcto **antes** de recuperarlo

> 💡 **Consejo:** Si encuentras tu archivo en **verde**, recupéralo de inmediato y guárdalo en otra unidad. ¡No esperes! Cada minuto aumenta el riesgo de que se sobrescriba.


# 🌐 3. NMAP — Exploración y Escaneo de Redes con Google Colab

---

## 📌 ¿Qué es NMAP?

> **NMAP (Network Mapper)** es una herramienta de código abierto para explorar redes y realizar auditorías de seguridad. Permite descubrir qué dispositivos están conectados a una red, qué puertos y servicios están activos en ellos, e incluso identificar sistemas operativos y vulnerabilidades. Es una de las herramientas más utilizadas por administradores de redes y profesionales de ciberseguridad.

### 📋 Características Principales

| Característica | Descripción |
|----------------|-------------|
| 🔍 **Descubrimiento de hosts** | Detecta qué dispositivos están activos en una red |
| 🔌 **Escaneo de puertos** | Identifica qué puertos están abiertos y qué servicios escuchan en ellos |
| 💻 **Detección de SO** | Intenta identificar el sistema operativo del dispositivo escaneado |
| 🔧 **Detección de servicios** | Identifica nombre y versión de programas como Apache, SSH, FTP, etc. |
| 📊 **Escaneo de redes completas** | Puede analizar rangos de IPs (ej: 192.168.1.0/24) |
| 📜 **Scripts NSE** | Más de 600 scripts para detección de vulnerabilidades, ataques y pruebas avanzadas |

### 🎯 Potencial y Alcance

| Tarea | Comando básico | Alcance |
|-------|----------------|---------|
| Escaneo básico de una IP | `nmap 192.168.1.1` | Muestra puertos abiertos |
| Escaneo de red completa | `nmap 192.168.1.0/24` | Lista todos los dispositivos de la red local |
| Detección de SO y servicios | `nmap -A 192.168.1.1` | Información detallada del sistema |
| Escaneo rápido de puertos comunes | `nmap -F 192.168.1.1` | Más rápido, solo los puertos más usados |
| Escaneo completo de puertos | `nmap -p- 192.168.1.1` | Todos los 65,535 puertos — lento pero completo |

---

## 🚀 Usando NMAP en Google Colab

### ✅ Paso 1: Instalar NMAP en el Notebook
En una celda de Colab, escribe y ejecuta:

```bash
!apt update
!apt install -y nmap

**¿Qué hace?**

- `apt update`: Actualiza la lista de paquetes disponibles
- `apt install -y nmap`: Instala NMAP sin pedir confirmación manual

> 
> 📸 **Pantallazo recomendado:** Captura la salida de la instalación exitosa. Guárdala como `imagenes/nmap_instalacion.jpg`

---

### ✅ Paso 2: Realizar un Escaneo Básico

Ejecuta en una celda nueva:

### ✅ Paso 2: Realizar un Escaneo Básico

Ejecuta en una celda nueva:

```
!nmap -v scanme.nmap.org
```

**Explicación:**

- `-v`: Modo detallado (muestra más información)
- `scanme.nmap.org`: Servidor de prueba oficial de NMAP para practicar

> 
> 📸 **Pantallazo recomendado:** Captura los resultados del escaneo. Guárdala como `imagenes/nmap_escaneo_basico.jpg`

---

### ✅ Paso 3: Usar NMAP desde Python

Instala la librería python-nmap:

**Qué hace este código?**

1. Importa la librería `nmap` para Python
2. Crea un objeto escáner
3. Define a qué dirección y qué puertos escanear
4. Ejecuta el escaneo
5. Recorre y muestra los resultados de forma organizada

> 
> 📸 **Pantallazo recomendado:** Captura la salida del código en Colab. Guárdala como `imagenes/nmap_python.jpg`

---

### ✅ Paso 4: Explorar Otros Comandos de NMAP

Prueba estos en celdas separadas:

Tabla

| Comando | Qué hace |
| --- | --- |
| `!nmap -sV scanme.nmap.org` | Detecta la versión de los servicios abiertos |
| `!nmap -O scanme.nmap.org` | Intenta identificar el sistema operativo del objetivo |
| `!nmap -sn 192.168.1.0/24` | Descubre qué dispositivos están activos en una red |
| `!nmap -A scanme.nmap.org` | Escaneo completo: SO + servicios + scripts |

> 
> ⚠️ **Nota importante:** Solo escanea redes y dispositivos que te pertenecen o tienes autorización para anal
