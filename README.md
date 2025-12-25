# Cultureness Home

Este proyecto es la aplicación interactiva **Cultureness Home**, un portal dedicado a la **cultura participativa del bienestar**.

## Descripción del Proyecto

Cultureness Home ofrece a los usuarios herramientas para la autogestión de datos y la reflexión personal sobre sus hábitos y bienestar. Se enfoca en la privacidad, el anonimato y el empoderamiento del usuario para que tome el control de su información de bienestar.

## Valores Fundamentales

*   **Privacidad y Anonimato:** Protección de datos y no requerimiento de información personal identificable.
*   **Autogestión:** Te empoderamos para que tomes el control de tus propios datos de bienestar.
*   **Reflexión:** Fomentamos la introspección y el análisis personal a través de herramientas interactivas.
*   **Bienestar Integral:** Abordamos el bienestar desde una perspectiva cultural y emocional, no solo clínica.

## Estructura del Proyecto

El proyecto está desarrollado con React/TypeScript y utiliza `wouter` para el enrutamiento y `tailwindcss` para los estilos.

*   `src/`: Contiene el código fuente de la aplicación.
    *   `src/pages/`: Componentes de las páginas principales (Home, Contact, Privacy, etc.).
    *   `src/components/`: Componentes reutilizables (Header, BasePage, etc.).
    *   `src/contexts/`: Contextos de React para la gestión de estado (Sesión, Tema).
    *   `src/translations.ts`: Archivo de traducciones multilingüe.

## Instalación y Ejecución

1.  **Instalar dependencias:**
    ```bash
    pnpm install
    # o npm install / yarn install
    ```
2.  **Ejecutar en modo desarrollo:**
    ```bash
    pnpm dev
    # o npm run dev / yarn dev
    ```
3.  **Construir para producción:**
    ```bash
    pnpm build
    # o npm run build / yarn build
    ```

## Actualizaciones Recientes

1.  **Contacto Telefónico:** Añadido el número `643 831 241` al pie de página de contacto.
2.  **Política de Privacidad:** Implementada la página de política de privacidad y añadido un botón de conformidad en la caja de consentimiento.
3.  **Página Home:** Actualizada con una descripción detallada del proyecto y sus valores.
