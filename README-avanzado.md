# Terraform - Nivel Avanzado

Enfoque en la manipulación directa del estado, resolución de conflictos y optimización de despliegues.

| Comando | Descripción |
| :--- | :--- |
| `terraform state mv` | Mueve un recurso en el estado (útil para refactorizaciones de nombres o mover a módulos). |
| `terraform state rm` | Elimina un recurso del estado para que Terraform deje de gestionarlo sin destruirlo físicamente. |
| `terraform import [addr] [id]` | Vincula infraestructura existente (creada manualmente) al código de Terraform. |
| `terraform taint [addr]` | Marca un recurso para ser destruido y recreado en la próxima ejecución. |
| `terraform force-unlock [lock-id]` | Libera manualmente el bloqueo del estado si un proceso se interrumpió abruptamente. |
| `terraform graph` | Genera una representación visual del árbol de dependencias de los recursos. |
| `terraform console` | Abre una consola interactiva para probar funciones y evaluar expresiones de HCL. |
