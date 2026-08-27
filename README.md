# Registro Auditoria Ecar

## 👥 Integrantes del equipo
- Juan Alberto Zuluaga  
- Erica Avedaño  

## 📌 Descripción breve del proyecto
El proyecto **Registro Auditoria Ecar** tiene como objetivo implementar un sistema de registro y control de auditorías internas, permitiendo gestionar de manera eficiente la información relacionada con procesos, hallazgos y seguimientos. Busca mejorar la trazabilidad, transparencia y organización en la gestión de auditorías.

## 🌿 Estrategia de ramas utilizada
Se adopta la estrategia **Git Flow**, que incluye:
- `main`: rama estable con versiones listas para producción.  
- `develop`: rama de integración para nuevas funcionalidades.  
- `feature/*`: ramas para el desarrollo de nuevas características.  
- `hotfix/*`: ramas para corrección inmediata de errores críticos en producción.  
- `release/*`: ramas para preparar versiones antes de pasar a producción.  

## 📝 Convención para realizar commits
Los commits deben seguir la convención **Conventional Commits**:
- `feat`: para nuevas funcionalidades.  
- `fix`: para corrección de errores.  
- `docs`: para cambios en documentación.  
- `style`: para cambios de formato o estilo sin afectar la lógica.  
- `refactor`: para reestructuración de código sin cambiar funcionalidad.  
- `test`: para agregar o modificar pruebas.  
- `chore`: para tareas de mantenimiento.  

## 🔀 Reglas para Pull Requests
- Todo **Pull Request (PR)** debe estar asociado a una tarea o issue.  
- El título debe ser claro y descriptivo.  
- Debe incluir una breve descripción de los cambios realizados.  
- Al menos un integrante del equipo debe revisar y aprobar antes de fusionar.  
- Se recomienda usar etiquetas como `ready-for-review`, `in-progress`, `bugfix`, etc.  

## 🔗 Reglas para fusiones (merge)
- Solo se permite hacer merge a `main` desde `release` o `hotfix`.  
- Los merges deben ser **squash** o **merge commit** según el caso:  
  - `squash`: para mantener un historial limpio en features.  
  - `merge commit`: para fusiones de ramas grandes como `release`.  
- No se permite hacer merge directo a `main` sin revisión.  

## 🤝 Otras reglas de colaboración
- Mantener la documentación actualizada en cada cambio relevante.  
- Usar **issues** para reportar errores o proponer mejoras.  
- Realizar revisiones de código con comentarios constructivos.  
- Respetar los tiempos de entrega y comunicación constante entre integrantes.  
- Seguir buenas prácticas de desarrollo seguro y eficiente.  

