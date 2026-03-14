---
description: Sincronizar cambios locales con GitHub
---

Este flujo de trabajo permitirá que los cambios realizados en el código se suban automáticamente a tu repositorio de GitHub.

### Requisitos Previos
1. Tener **Git** instalado en el sistema.
2. Haber inicializado el repositorio y conectado el "remote" de GitHub.

### Pasos de Sincronización
1. **Agregar cambios**:
   ```powershell
   git add .
   ```
2. **Crear commit**:
   ```powershell
   git commit -m "Actualización del sitio web - Hogar en Forma"
   ```
3. **Subir a GitHub**:
   ```powershell
   git push origin main
   ```

Una vez que Git esté configurado en este terminal, podré ejecutar estos pasos automáticamente cada vez que terminemos una tarea.
