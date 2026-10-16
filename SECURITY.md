# Política de seguridad

## Alcance y versiones con soporte

Este repositorio publica el sitio estático de **DC-carECU**, sus recursos multimedia y sus workflows de GitHub Actions. La rama `main` es la única línea mantenida actualmente; este repositorio no contiene el código fuente de las aplicaciones Android ni publica versiones empaquetadas propias.

Las aplicaciones y APK enlazados desde el sitio pertenecen a repositorios separados. Las vulnerabilidades de esos proyectos deben reportarse en el repositorio correspondiente.

## Cómo reportar una vulnerabilidad

No abras un issue público para una vulnerabilidad ni incluyas tokens, credenciales o datos personales en una solicitud pública.

1. Usa el formulario privado de [reporte de vulnerabilidades de GitHub](https://github.com/dcg0/DC-carECU/security/advisories/new), si está disponible para este repositorio.
2. Si el formulario no está habilitado, contacta de forma privada al mantenedor mediante [el perfil de GitHub de `dcg0`](https://github.com/dcg0) y solicita un canal privado. No publiques los detalles hasta acordar su divulgación.

Incluye, cuando sea posible, el archivo o URL afectado, pasos mínimos para reproducir el problema, impacto observado y una propuesta de corrección. Redacta cualquier secreto o dato sensible antes de adjuntarlo.

Intentaremos confirmar la recepción en un plazo de 7 días y coordinaremos la corrección y divulgación con la persona que informó el problema. Esta política no garantiza una fecha de resolución concreta.

## Prácticas de divulgación

- No pruebes contra vehículos, ECU o servicios de terceros sin autorización.
- Para problemas relacionados con un APK o una aplicación enlazada, reporta el hallazgo en su repositorio de origen.
- Una vez publicada una corrección, se documentará el cambio en el historial o en una nota de versión cuando corresponda.
