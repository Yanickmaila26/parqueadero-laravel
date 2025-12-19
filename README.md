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
## PASO 1: CREAR REPOSITORIO EN GITHUB
<img width="484" height="423" alt="Imagen1" src="https://github.com/user-attachments/assets/0f3a661a-6af9-4791-b43b-198789459be4" />
<img width="474" height="449" alt="Imagen2" src="https://github.com/user-attachments/assets/942c80af-7818-4dac-8285-884ba73fa70c" />
<img width="709" height="457" alt="Imagen3" src="https://github.com/user-attachments/assets/0b4a1fd8-9f8e-408e-aa6d-52b32aabf5de" />

## PASO 3: CONFIGURAR BASE DE DATOS
<img width="296" height="164" alt="Imagen4" src="https://github.com/user-attachments/assets/0320e6c4-068e-4772-8877-f22127faede3" />

## PASO 4: CREAR MIGRACIÓN, MODELO Y CONTROLADOR
<img width="709" height="165" alt="Imagen5" src="https://github.com/user-attachments/assets/84725999-81c5-49ae-97e3-0930ce9ae311" />

## PASO 5: DEFINIR LA TABLA (MIGRACIÓN)
<img width="457" height="421" alt="Imagen6" src="https://github.com/user-attachments/assets/bd7afa33-4c56-40fb-947e-27fb08d113a3" />

## PASO 6: CONFIGURAR EL MODELO
<img width="449" height="674" alt="Imagen7" src="https://github.com/user-attachments/assets/1f9f5555-148c-44f2-91c3-71c6ee49803a" />

## PASO 7: CONFIGURAR LAS RUTAS
<img width="437" height="230" alt="Imagen8" src="https://github.com/user-attachments/assets/6edda56a-5544-4807-b86b-b623d693c1a1" />

## PASO 8: CREAR EL CONTROLADOR
<img width="709" height="792" alt="Imagen9" src="https://github.com/user-attachments/assets/1219af56-5d21-414f-a63a-23a102a88150" />

## PASO 13: PROBAR LA APLICACIÓN
<img width="709" height="286" alt="Imagen10" src="https://github.com/user-attachments/assets/3d2d4703-c409-4fd9-bbe9-038400e133bc" />
<img width="709" height="263" alt="Imagen11" src="https://github.com/user-attachments/assets/7f6c0bdf-2c3b-4e9b-9bcd-d14ea9f851fc" />



