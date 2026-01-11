📜 Políticas del Proyecto

Sistema de Control de Versiones Empresarial (SCV-Empresarial)

1. Objetivo del Documento

Este documento define las políticas internas que regulan el uso del repositorio, la colaboración entre los miembros del equipo y las buenas prácticas de control de versiones, con el fin de mantener un historial limpio, seguro y profesional.

2. Políticas de Control de Versiones

Todo el código fuente y documentación debe versionarse usando Git.

El repositorio oficial se aloja en GitHub.

No se permite trabajar directamente fuera del repositorio sin sincronizar los cambios.

Cada cambio significativo debe registrarse mediante un commit.

3. Políticas de Commits

Todos los commits deben seguir el estándar Conventional Commits:

<tipo>[scope]: <descripción>


Tipos permitidos:

feat: nueva funcionalidad

fix: corrección de errores

docs: documentación

style: formato, espacios, sin afectar lógica

refactor: refactorización de código

test: pruebas

chore: tareas de mantenimiento

📌 Ejemplo válido:

feat(config): add environment configuration