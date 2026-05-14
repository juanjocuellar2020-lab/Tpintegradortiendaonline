# El ancla y la Sombra - TP Integrador

[Link al proyecto 🌐](https://el-ancla-y-la-sombra.netlify.app/)

## 🛠️ Tecnologías utilizadas
- HTML5 / CSS3
- JavaScript (Modales y dinámica de carrusel)
- Git para control de versiones
- Netlify para el despliegue

## Estructura del proyecto
- index.html --> Pagina principal (Inicio)
- Categorias.html --> Seccion de categorias de por autores con cards y modales
- Contacto.html --> Formulario de contacto con nombre, mail, mensaje
- Destacados.html --> Libros destacados "vendidos y elegidos" (grid/carrusel)
- Estiloparatienda.css --> Estilos dorados y oscuros
- Imagenes/ --> Icono y fondo para la pagina (generados con Copilot)
- Libros/ --> Portadas de los libros 

## Funcionalidades implementadas
- Menú de navegación con 4 pestañas: Inicio, Categorías, Contacto, Destacados.
- Cards con imágenes y modales en Categorías.
- Formulario de contacto con validaciones básicas (`required`, formato email).
- Sección Destacados en formato grid/carrusel.
- Footer uniforme en todas las páginas.

---
 
## 📁 Estructura del proyecto
 
```
El-Ancla-y-La-Sombra/
├── index.html          # Página principal con carrusel de portadas
├── categorias.html     # Libros por autor con cards y modales
├── destacados.html     # Libros más vendidos en formato grid
├── contacto.html       # Formulario de contacto
├── styles.css          # Estilos personalizados (tema dorado y oscuro)
├── img/
│   ├── icono.png       # Logo del sitio (generado con Copilot)
│   ├── paisaje.png     # Fondo del sitio (generado con Copilot)
│   └── libros/         # Portadas de los libros
└── README.md           # Este archivo
```
 
---

## ⚙️ Control de versiones (Git)
Se aplicó un flujo de trabajo organizado para garantizar el orden del código y la colaboración:

1. **Estrategia de ramificación:** Se trabajó activamente en una rama de desarrollo denominada `feature/dev`. Esto permitió desarrollar nuevas funcionalidades y trabajar sobre las versiones del compañero de equipo sin afectar la estabilidad de la rama principal.
2. **Flujo de comandos:**
   - `git init`: Inicialización del repositorio.
   - `git checkout -b feature/dev`: Creación y cambio a la rama de desarrollo.
   - `git add .`: Preparación de cambios.
   - `git commit -m "..."`: Documentación detallada de cada avance (ej: "Agrego Contacto y Destacados, unifico navbar").
   - `git push origin feature/dev`: Carga de cambios al repositorio remoto.
   - `git merge`: Integración final de las características probadas en la rama `main`.
  
 ---

##  Estado final
- Sitio completo, responsivo y funcional.
- Documentación clara y breve.
- Git implementado para control de versiones y entrega.
