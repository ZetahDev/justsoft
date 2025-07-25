📘 JustSoft - Archivo de Contexto Empresarial y de Diseño

Este archivo define el contexto central de JustSoft, y debe ser consultado por cada componente, funcionalidad, contenido o decisión técnica dentro del ecosistema de desarrollo.

✅ Este documento actúa como la "fuente única de verdad" para el desarrollo, escalamiento y representación pública de la empresa.

🏢 Identidad Corporativa

Nombre completo: JustSoft Technologies S.A.SFundación: Colombia, 2025Enfoque: Desarrollo tecnológico con alta calidad de UX, modularidad y responsabilidad digital.

Visión: Ser la marca líder colombiana en soluciones digitales modulares, accesibles y confiables.

Misión: Entregar software y servicios digitales con enfoque humano, escalables y con un diseño impecable, promoviendo la seguridad y la innovación.

Valores clave:

Calidad visual y técnica

Responsabilidad con los datos

Accesibilidad y usabilidad

Modularidad y escalabilidad

Transparencia y soporte continuo

🧩 Unidades Estratégicas

Cada una cuenta con su propia página en el sitio y estrategia.

Unidad

Nombre

Función clave

Desarrollo Web/App

JustSoft Dev

Desarrollo de apps móviles, web y plataformas SaaS

Ciberseguridad

JustSoft Shield 🔒

Pentesting, análisis de vulnerabilidades, defensa

Soporte Técnico

JustSoft Care

Mantenimiento, soporte a usuarios, acompañamiento

Diseño

JustSoft Studio

UI/UX, branding, prototipado, diseño visual

Innovación

JustSoft Lab

I+D, tecnologías emergentes, prototipos

🎨 Lineamientos de Diseño

Arquitectura Atomic Design (/atoms, /molecules, /organisms, /templates)

Framework: Astro (Island architecture)

Styling: Tailwind CSS + shadcn/ui

Animaciones: Microinteracciones suaves con GSAP o Framer Motion embebido

UX: Fluidez emocional, orientación al usuario, accesibilidad AA+

Branding: Moderno, tecnológico, confiable

Modo Oscuro predeterminado, con cambio a Claro

🌐 Estructura de Navegación del Sitio

/
├── index.astro              ← Landing principal corporativa
├── about.astro              ← Misión, visión, historia
├── incubator.astro          ← Convocatorias, proyectos, alianzas
├── contact.astro            ← Formulario de contacto + soporte
└── units/                   ← Landing individuales por unidad
    ├── dev.astro
    ├── shield.astro
    ├── care.astro
    ├── studio.astro
    └── lab.astro

🔄 Diagrama de Flujo General

graph TD
    A[Usuario llega a JustSoft] --> B[Landing principal (index.astro)]
    B --> C1[Explora Unidades de negocio]
    B --> C2[Conoce la incubadora de ideas]
    B --> C3[Contacto / Soporte directo]

    C1 --> D1[JustSoft Dev]
    C1 --> D2[JustSoft Shield 🔒]
    C1 --> D3[JustSoft Studio]
    C1 --> D4[JustSoft Lab]
    C1 --> D5[JustSoft Care]

    C2 --> E[Formulario de participación en eventos o alianzas]
    C3 --> F[Formulario + WhatsApp Business API + correo directo]

📌 Normas para Desarrollo Futuro

Cada componente debe tener su propósito bien documentado.

Cualquier funcionalidad nueva debe validarse con este archivo.

No se reutiliza React Context ni hooks innecesarios; se trabaja bajo el principio de simplicidad y legibilidad.

Todos los nombres de las rutas, variables, clases y funciones deben ser semánticos y mantener coherencia con este archivo.

👥 Público Objetivo

Startups, empresas PYMEs y grandes corporaciones tecnológicas.

Entidades gubernamentales en búsqueda de soluciones digitales o soporte técnico.

Clientes extranjeros que busquen un aliado tecnológico colombiano confiable.

🚨 Este archivo debe leerse o actualizarse siempre que:

Se cree una nueva unidad de negocio.

Se cambie el enfoque del branding o producto.

Se detecten desviaciones del propósito original.