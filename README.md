# Marquito para iOS (nativo)

Este repositorio contiene una app nativa SwiftUI muy sencilla para probar la instalación en un iPhone.

## Qué hace
- Muestra el logo M, el nombre Marquito y “App creada por Marquito”.
- El botón “¡Funciona!” cambia a “¡Todo correcto! 🚀”.

## Construir el IPA desde Windows usando GitHub Actions
1. Crea una cuenta en GitHub si no tienes una.
2. Crea un repositorio nuevo llamado `Marquito-iOS`.
3. Sube todos los archivos de esta carpeta conservando las rutas, incluido `.github/workflows/build.yml`.
4. Abre la pestaña **Actions** del repositorio y ejecuta **Build Marquito iOS** (o haz un commit a `main`).
5. Cuando termine correctamente, abre la ejecución del workflow y descarga el artefacto **Marquito-unsigned-IPA**. Dentro estará `Marquito-unsigned.ipa`.

## Instalar en iPhone
El IPA generado es sin firmar; no se instala tocándolo directamente. Usa una herramienta de sideloading compatible para firmarlo con tu Apple ID gratuito. Las apps firmadas con cuenta gratuita suelen caducar a los 7 días y necesitan refrescarse.

## Importante
- Esto es código fuente y un flujo de compilación en la nube; el ZIP inicial no contiene un IPA ya compilado.
- No subas contraseñas, certificados privados ni credenciales de Apple a GitHub.
- Compatibilidad con versiones muy nuevas de iOS y herramientas de sideloading puede variar.
