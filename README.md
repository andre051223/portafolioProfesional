# 🚀 Portafolio Profesional - Diego López

Portafolio web personal desarrollado con HTML5, CSS3 y JavaScript vanilla. Diseño moderno, responsive y optimizado para mostrar experiencia profesional, proyectos y habilidades técnicas.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📋 Tabla de Contenidos

- [Descripción](#-descripción)
- [Características](#-características)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Secciones](#-secciones)
- [Paleta de Colores](#-paleta-de-colores)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación](#-instalación)
- [Personalización](#-personalización)
- [Responsive Design](#-responsive-design)
- [Autor](#-autor)

---

## 📖 Descripción

Este proyecto es un portafolio web profesional diseñado para presentar la trayectoria, habilidades y proyectos de Diego López como Desarrollador Web. El diseño sigue un concepto limpio y moderno con una paleta de colores blanca y verde.

---

## ✨ Características

- ✅ **Diseño Responsive** - Adaptado para móviles, tablets y desktop
- ✅ **Navbar Flotante** - Navegación elegante con efecto pill y menú hamburguesa para móvil
- ✅ **Animaciones Suaves** - Transiciones CSS para mejor experiencia de usuario
- ✅ **Barras de Progreso** - Visualización de skills con porcentajes
- ✅ **Línea de Tiempo** - Experiencia profesional y formación académica en formato timeline
- ✅ **Cards de Proyectos** - Grid responsive para mostrar trabajos destacados
- ✅ **CTAs de Contacto** - Botones para Email y WhatsApp
- ✅ **Foto de Perfil con Bandera** - Avatar circular con bandera de país

---

## 📁 Estructura del Proyecto

```
Portafolio/
├── css/
│   ├── portafolio_diego.css    # Estilos principales del portafolio
│   ├── perfilPlatzi.css        # Estilos del perfil Platzi
│   ├── platziNavbar.css        # Estilos del navbar Platzi
│   ├── platziStore.css         # Estilos de la tienda Platzi
│   └── style.css               # Estilos globales
├── img/
│   └── Diego.png               # Foto de perfil
├── js/
│   ├── app.js                  # JavaScript principal
│   └── vendor/                 # Librerías de terceros
├── portafolio_diego.html       # Página principal del portafolio
├── perfilPlatzi.html           # Página de perfil Platzi
├── platziPlatform.html         # Página de plataforma Platzi
├── platziNavbar.html           # Página de navbar Platzi
├── platziStore.html            # Página de tienda Platzi
├── 404.html                    # Página de error 404
├── package.json                # Dependencias del proyecto
├── webpack.common.js           # Configuración webpack común
├── webpack.config.dev.js       # Configuración webpack desarrollo
├── webpack.config.prod.js      # Configuración webpack producción
└── README.md                   # Documentación
```

---

## 📑 Secciones

### 1. **Navbar Flotante**
Navegación fija en la parte superior con diseño pill, borde verde y efecto hover. Incluye menú hamburguesa animado para dispositivos móviles.

### 2. **Hero Section (Inicio)**
Grid de 2 columnas que incluye:
- **Card de Perfil**: Foto circular con bandera de Colombia, nombre, profesión y barras de skills
- **Perfil Profesional**: Descripción personal, motivaciones y estadísticas

### 3. **Proyectos**
Grid de cards con:
- Espacio para imagen del proyecto
- Título y descripción
- Tags de tecnologías utilizadas
- Efecto hover con elevación

### 4. **Experiencia Profesional**
Línea de tiempo vertical con:
- Marcador visual
- Fecha del puesto
- Cargo y empresa
- Descripción de responsabilidades
- Tags de tecnologías

### 5. **Formación Académica**
Línea de tiempo similar a experiencia profesional para educación y certificaciones.

### 6. **Contacto**
Sección con CTAs para:
- Contacto por Email
- Contacto por WhatsApp

### 7. **Footer**
Pie de página con copyright.

---

## 🎨 Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| Verde Principal | `#67b31f` | Títulos, acentos, botones |
| Verde Oscuro | `#5a9e1b` | Hover de botones |
| Verde Claro | `#7cc934` | Gradientes |
| Blanco | `#ffffff` | Fondos principales |
| Negro | `#000000` | Textos |
| Gris Claro | `#f8f9fa` | Fondos secundarios |
| Gris Medio | `#6c757d` | Textos secundarios |

---

## 🛠 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos, Flexbox, Grid, animaciones
- **JavaScript** - Interactividad del menú móvil
- **Google Fonts** - Tipografías Inter y Poppins
- **SVG** - Iconos vectoriales

---

## 🚀 Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/portafolio.git
```

2. **Navegar al directorio**
```bash
cd portafolio
```

3. **Abrir en el navegador**
```bash
# Opción 1: Abrir directamente
open portafolio_diego.html

# Opción 2: Usar Live Server en VS Code
# Click derecho > "Open with Live Server"
```

---

## ⚙️ Personalización

### Cambiar información personal

1. **Nombre y profesión**: Editar en `portafolio_diego.html` líneas 49-50
2. **Foto de perfil**: Reemplazar `img/Diego.png`
3. **Skills**: Modificar los porcentajes en las barras de progreso
4. **Perfil profesional**: Actualizar el texto en la sección `professional-profile`
5. **Proyectos**: Agregar imágenes y enlaces a tus proyectos
6. **Experiencia/Formación**: Completar los items del timeline
7. **Contacto**: Actualizar email y número de WhatsApp

### Cambiar colores

Modificar las variables CSS en `css/portafolio_diego.css`:

```css
:root {
    --primary-green: #67b31f;      /* Color principal */
    --primary-green-dark: #5a9e1b; /* Color hover */
    --primary-green-light: #7cc934; /* Gradientes */
}
```

---

## 📱 Responsive Design

El portafolio está optimizado para:

| Dispositivo | Breakpoint |
|-------------|------------|
| Desktop | > 1024px |
| Tablet | 768px - 1024px |
| Móvil | < 768px |

### Adaptaciones móviles:
- Navbar se convierte en menú hamburguesa
- Grid de 2 columnas pasa a 1 columna
- Cards de proyectos en stack vertical
- Botones de contacto en columna
- Tipografías ajustadas

---

## 👤 Autor

**Diego López**

- 🌐 Desarrollador Web
- 🎓 Estudiante de Ingeniería de Sistemas
- 🇨🇴 Colombia

### Redes Sociales
- [LinkedIn](https://www.linkedin.com/in/diego-andr%C3%A9s-lopez/)
- [GitHub](https://github.com/andre051223)
- [Platzi](https://platzi.com/p/Diego.2206/)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE.txt](LICENSE.txt) para más detalles.

---

⭐ Si te gustó este proyecto, ¡no olvides darle una estrella!
