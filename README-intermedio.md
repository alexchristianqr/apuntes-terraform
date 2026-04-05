# Terraform - Nivel Intermedio

Enfoque en la reutilización de código, gestión de entornos y persistencia del estado.

| Comando | Descripción |
| :--- | :--- |
| `terraform workspace list` | Enumera los espacios de trabajo existentes (útil para manejar entornos como Dev/Prod). |
| `terraform workspace select [name]` | Cambia al espacio de trabajo especificado. |
| `terraform state list` | Lista todos los recursos que están actualmente en el archivo de estado (`terraform.tfstate`). |
| `terraform state show [resource]` | Muestra detalles específicos de un recurso dentro del estado. |
| `terraform output` | Extrae y muestra los valores de salida definidos en el código. |
| `terraform get` | Descarga y actualiza los módulos utilizados en la configuración. |
| `terraform refresh` | Actualiza el estado local con respecto a la infraestructura real (sin aplicar cambios). |
