## 🚨 Falla en SonarCloud

El análisis de SonarCloud ha fallado.

### ❗ Detalles

- El contenedor `eclipse-temurin` se ejecuta como usuario `root`, lo cual es una mala práctica de seguridad.
- Revisión requerida por el equipo DevOps o de Seguridad.

### ✅ Acción recomendada

Modificar el Dockerfile base para usar un usuario no root o agregar un paso para cambiar de usuario en el contenedor final.
