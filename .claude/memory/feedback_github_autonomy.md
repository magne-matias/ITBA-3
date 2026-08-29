---
name: feedback_github_autonomy
description: El usuario elige manualmente qué y cuándo subir a GitHub
metadata:
  type: feedback
---

**Regla:** El usuario decide solo qué subir a GitHub y cuándo. No hacer push automático.

**Por qué:** El usuario es quien maneja los cambios en el repo; no asumir permisos sobre acciones visibles en GitHub.

**Cómo aplicar:** Si hay cambios locales sin pushear, mostrar estado y preguntar antes de cualquier operación de push. Si el usuario dice "olvidate de github", no insistir en credenciales o autenticación — el usuario ya tiene solucionado el acceso.
