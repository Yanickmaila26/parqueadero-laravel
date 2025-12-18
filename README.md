# Tarea - Desarrollo en Plataformas

## Estudiante:  Yanick Maila
## Fecha:  17/12/2025
## Paralelo:  3

---

## 1. Tabla  
### Nombre de la tabla:  Vehiculos

### Campos:

| Campo | Tipo | ¿Obligatorio? |
|-------|------|----------------|
|  id     |  BigInt (Primary Key)    |       Sí         |
|   placa    |   String (10)   |        Sí        |
|  tipo     |  String (20)    |        Sí        |
|   propietario    |  String (100)    |      No (Nullable)          |
|   observaciones    |  Text   |       No (Nullable)         |
|   created_at    |   Timestamp   |       Sí (Automático)         |
|   updated_at    |   Timestamp   |      Sí (Automático)          |

---

## 2. Tipos de vehículo  
- Automóvil 
-	Motocicleta 
-	Camioneta 

---

## 3. ¿Se puede eliminar registros?  
**Respuesta:** Si, pero el hijo del cliente solicita que no se borren

**Razón (1 línea):**  Se eliminan ya que asi esta por defecto en el codigo proporcionado, pero uno de los requerimientos por parte del hijo del cliente nos solicita un borrado lógico donde solo se marca que el vehículo sale del parqueadero. Entonces para esto deberíamos agregar un nuevo campo a la tabla y modificar la función destroy del controlador.

---
