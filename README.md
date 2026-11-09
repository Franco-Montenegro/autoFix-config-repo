# autoFix-config-repo

Archivos de configuracion que sirve el Config Server (`autoFix-config-server`) a los servicios de AutoFix.

| Archivo | Servicio |
|---|---|
| `application.yml` | Comun a todos (cliente Eureka, actuator) |
| `eureka-server.yml` | Service Discovery (puerto 8761) |
| `gateway.yml` | API Gateway (puerto 8080, rutas y CORS) |
| `ms-vehicles.yml` | M1: vehiculos |
| `ms-repair-types.yml` | M2: catalogo de reparaciones |
| `ms-repair-orders.yml` | M3: ordenes de reparacion |
| `ms-reports.yml` | M4: reportes |

No se guardan contrasenas: se leen de variables de entorno (`DB_PASSWORD`, etc.).
