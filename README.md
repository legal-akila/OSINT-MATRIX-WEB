# 🕵️‍♂️ OSINT HUB · Matrix Nexus
OSINT MATRIX WEB es un directorio web especializado que reúne, organiza y permite verificar el estado de más de 60 herramientas OSINT (inteligencia de fuentes abiertas). Está diseñado para investigadores, analistas de ciberseguridad, periodistas y entusiastas que necesitan acceder rápidamente a recursos confiables .

**Directorio de herramientas OSINT** con organización profesional (HTML, CSS, JS separados).  
Tres temas visuales: Matrix (negro/verde), Claro (blanco/verde) y Ámbar (naranja retro).  
Verificación manual de estado, persistencia en URL y localStorage. **Sin envío de datos**.

## ✨ Características

- 🎨 **Tres temas visuales**:
  - 🌙 **Matrix** (negro / verde neón)
  - ☀️ **Claro** (blanco / verde oscuro)
  - 🟠 **Ámbar** (marrón / naranja, estilo terminal retro)
    
- 🔍 **Búsqueda en tiempo real** por nombre o descripción.
  
- 🧩 **Filtros rápidos** por categoría.
  
- 📂 **10 categorías** con más de **63 herramientas OSINT**:
  - Búsqueda de dominios / WHOIS (7)
  - Redes sociales (6)
  - Correos electrónicos y usuarios (7)
  - Geolocalización y mapas (7)
  - Archivos web (Wayback Machine, Archive.today, etc.) (6)
  - Imágenes (metadatos + búsqueda inversa) (7)
  - Código fuente y repositorios (6)
  - Datos públicos gubernamentales (6)
  - Foros y dark web (superficie) (5)
  - Motores de búsqueda de infraestructura (Shodan, Censys, etc.) (6)
    
- ✅ **Verificación manual de estado**: cada herramienta tiene un botón `🔄 Verificar` que comprueba si la URL responde (método HEAD, timeout 5s). El estado se guarda en tu navegador (`localStorage`) y persiste entre sesiones.
  
- 🔗 **URL persistente**: los filtros y la búsqueda se reflejan en la URL, puedes compartir enlaces directos.
  
- 🚫 **Sin envío de datos**: no hay formularios de reporte, no hay exportaciones CSV/JSON, no se envía nada a ningún servidor. Todo queda local en tu máquina.
  
- 📱 **Diseño responsive**: funciona en móviles, tablets y escritorio.
  
- 🌍 **Desplegable en GitHub Pages** (o cualquier servidor estático).

🧠 Tecnologías utilizadas

HTML5 semántico
CSS3 (transiciones, flexbox, grid, pseudoelementos)
JavaScript vanilla (ES6+)
Fetch API con no-cors y timeout para verificación de URLs
localStorage para guardar preferencias de tema y estados personalizados
URLSearchParams para persistencia de filtros en la URL

📁 Estructura del proyecto

osint-matrix-hub/
├── index.html      # Aplicación principal (HTML, CSS, JS todo en uno)
└── README.md       # Este archivo

## 🚀 Demo en vivo

Sin envío de datos, sin formularios externos, completamente autónomo.

👉 https://legal-akila.github.io/OSINT-MATRIX-WEB/

## 🛠️ Instalación y uso local

1. Clona el repositorio o descarga los archivos:
   ```bash
   git clone https://github.com/TU-USUARIO/osint-matrix-hub.git
   cd osint-matrix-hub
