---
name: Artist UX Design System
colors:
  surface: '#fff7f9'
  surface-dim: '#e1d7db'
  surface-bright: '#fff7f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f5'
  surface-container: '#f6ebef'
  surface-container-high: '#f0e6e9'
  surface-container-highest: '#eae0e3'
  on-surface: '#1f1a1d'
  on-surface-variant: '#4f444a'
  inverse-surface: '#342f32'
  inverse-on-surface: '#f9eef2'
  outline: '#81737b'
  outline-variant: '#d2c2ca'
  surface-tint: '#804e73'
  primary: '#804e73'
  on-primary: '#ffffff'
  primary-container: '#c78db6'
  on-primary-container: '#532649'
  inverse-primary: '#f2b4df'
  secondary: '#546250'
  on-secondary: '#ffffff'
  secondary-container: '#d5e4ce'
  on-secondary-container: '#586655'
  tertiary: '#4e662e'
  on-tertiary: '#ffffff'
  tertiary-container: '#8da869'
  on-tertiary-container: '#273c09'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd7f0'
  primary-fixed-dim: '#f2b4df'
  on-primary-fixed: '#330a2d'
  on-primary-fixed-variant: '#66375a'
  secondary-fixed: '#d8e7d1'
  secondary-fixed-dim: '#bccbb5'
  on-secondary-fixed: '#121f11'
  on-secondary-fixed-variant: '#3d4a3a'
  tertiary-fixed: '#cfeca7'
  tertiary-fixed-dim: '#b4d08d'
  on-tertiary-fixed: '#102000'
  on-tertiary-fixed-variant: '#374d19'
  background: '#fff7f9'
  on-background: '#1f1a1d'
  surface-variant: '#eae0e3'
  cta-hover: '#A86E97'
  bg-base: '#F4F1EE'
  text-primary: '#2D2926'
  text-secondary: '#5A5450'
  surface-card: '#E7E3E0'
  dark-bg-base: '#121212'
  dark-surface-card: '#1E1E1E'
  dark-text-primary: '#E0E0E0'
  dark-text-secondary: '#BDBDBD'
typography:
  h1:
    fontFamily: Atkinson Hyperlegible
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
  h2:
    fontFamily: Atkinson Hyperlegible
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  h3:
    fontFamily: Atkinson Hyperlegible
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-gap: 8rem
  container-padding: 2rem
  card-padding: 2.5rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 3rem
---

Briefing para Diseño y Desarrollo de Portfolio Web
Perfil: Diseñador UX con formación en Bellas Artes.
Objetivo: Crear una plataforma profesional que unifique la metodología de diseño UX con la producción de obra plástica, pero de forma separada.
1. Requerimientos de Navegación y Estructura
La web debe ser totalmente responsive (Desktop, Tablet, Mobile) bajo un enfoque Mobile-First.
Página	Contenido y Funcionalidad
 
Home	Hero section con propuesta de valor clara. Menú de acceso global. Resumen de proyectos UX destacados. Un hero atractivo que de buena impresión y sea novedoso
Portfolio UX	Grid completo de casos de estudio. Cada proyecto debe detallar: Objetivo, Investigación, Fases de Diseño y Resultados.
Sobre mí	Biografía profesional que conecte Bellas Artes con UX. Listado visual de herramientas y trayectoria.
Obras (Arte)	Galería por proyectos de obras plásticas con navegación individual. Información técnica: Temática, Técnica, Año, Dimensiones y Concepto.
Contacto	Formulario de contacto accesible, limpio y funcional.
Accesibilidad	Panel de configuración: cambio de tamaño de fuente, modo alto contraste y modo oscuro. También idioma ES y EN.
Footer	Inicio | Proyectos UX | Sobre mí | Obras | Contacto | Accesibilidad │Política de privacidad │Aviso legal

Paco-C © 2018. Todos los derechos reservados.
2. Especificaciones Técnicas (UX/UI)
●	Accesibilidad: Cumplimiento de WCAG 2.1 Nivel AA. Navegación por teclado y etiquetas ARIA correctamente implementadas.
●	Interacciones: Transiciones suaves entre páginas y microinteracciones en elementos clicables para mejorar la experiencia de usuario.
●	Rendimiento: Optimización de imágenes (especialmente en la sección de Obras y proyectos ux) para asegurar tiempos de carga rápidos.
●	Menú hamburguesa en versión móvil
●	Logo parte superior de la home
3. Identidad y Storytelling
Se busca un diseño que refleje la dualidad del autor: la precisión analítica del diseño de producto y la sensibilidad creativa de las Bellas Artes. El diseño debe ser limpio para no competir con el contenido visual de los proyectos.

3. Sistema de Diseño Artist- UX
1. Paleta de Color (Definitiva)
Colores principales
•	CTA Principal — #C78DB6 Uso: botones primarios, acciones clave.
•	Hover CTA — #A86E97 Uso: interacción, estados activos.
•	Fondo Base — #F4F1EE Uso: fondo general, secciones amplias.
•	Texto Principal — #2D2926 Uso: títulos, navegación, texto principal.
Colores secundarios
•	Acento Verde Salvia — #A9B8A3 Uso: iconos, bullets, detalles sutiles.
•	Gris Tarjetas — #E7E3E0 Uso: tarjetas, bordes, contenedores.
Reglas de accesibilidad
1.	Texto dentro de CTA malva → siempre blanco (#FFFFFF).
2.	El malva se usa solo en elementos importantes (10% de la interfaz).
3.	Mucho aire: diseño tipo “galería de arte”.
2. Tipografía (Sin solapamientos)
Títulos (H1–H3)
•	Fuente: Atkinson Hyperlegible
•	Color: #2D2926
•	Peso: 600–700
UI (botones, navegación, formularios)
•	Fuente: Inter
•	Peso: 500–600
Párrafos y textos largos
•	Fuente: Source Sans 3
•	Peso: 400–500
•	Color: #5A5450
Accesibilidad reforzada
•	Atkinson Hyperlegible para textos clave o alternativos.
👉 No hay conflicto entre estas fuentes: cada una tiene un rol claro.
3. Estrategia de CTAs (Unificada)
Botón Primario (UX)
•	Fondo: #C78DB6
•	Texto: blanco
•	Tipografía: Inter
•	Hover: #A86E97
Botón Secundario (Arte)
•	Ghost button
•	Borde: #C78DB6 o #A9B8A3
•	Texto: #2D2926
Micro interacciones
•	Efecto pincel o trazo técnico al hacer hover.
•	Animación sutil, no exagerada.
Jerarquía
•	Primario → acción principal.
•	Secundario → navegación suave.
•	Tercero → enlaces simples.
4. Reglas de Composición (Sin contradicciones)
Regla 60 30 10
•	60% fondo (#F4F1EE o blanco)
•	30% texto y elementos neutros (#2D2926, #5A5450, #E7E3E0)
•	10% acentos (malva y salvia)
White Space
•	Mucho aire entre secciones.
•	Tarjetas con padding generoso.
•	Diseño tipo “museo”.
5. Modo Oscuro (Integrado sin pisarse)
Fondos
•	Fondo principal: #121212
•	Tarjetas: #1E1E1E
Texto
•	Principal: #E0E0E0
•	Secundario: #BDBDBD
Acentos
•	Mantener malva y salvia, pero ligeramente más brillantes para compensar el fondo oscuro.
6. Componentes UI (Unificados)
Tarjetas
•	Fondo: blanco
•	Borde: #E7E3E0
•	Sombra: muy suave
•	Radio: 8px
Inputs
•	Fondo: blanco
•	Borde: #E7E3E0
•	Focus: borde #C78DB6
Separadores
•	Línea fina: #E7E3E0
•	Línea acento: #A9B8A3
7. Sistema Tipográfico (Escalas)
Títulos
•	H1: 48–64px
•	H2: 32–40px
•	H3: 24–28px
Texto
•	Párrafo: 16–18px
•	Pequeño: 14px
8. Resumen Ejecutivo para el diseñador
“Artist UX es un sistema híbrido entre arte y UX. El malva es el acento emocional, el salvia es el soporte técnico, y el fondo arena crea un espacio elegante y respirable. La tipografía combina accesibilidad (Atkinson), claridad UI (Inter) y lectura cómoda (Source Sans 3). El diseño debe sentirse como una galería: aireado, limpio y con acentos muy medidos.”

