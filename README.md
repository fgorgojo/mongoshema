# Modelado del GR
=================

>   The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
    NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
    "OPTIONAL" in this document are to be interpreted as described in
    RFC 2119.

# Nomenclatura
==============

- Las foreign Keys de los catalogos deben ser **lowerCamelCase** con el sufijo **Code**.
- Las foregin keys de otras entidades deben ser **lowerCamelCase** con el sufijo **ID**
- Las primaryKey deben ser nombre de la entidad en singular lowerCameCase con el sufijo **_ID**
- El nombre de las colecciones en MONGODB debe ser plural **lower_snake_case**
- El nombre de la entidad en el Modelo Lógico debe ser singular **lower_snake_case**
- __Timestamp__: deben ser lowerCamelCase con el sufijo **At**
- __Booleans__: deben ser lowerCamelCase con el prefijo **is / has**
- __Dates__: deben ser 

## Ejemplo:

Entidad: general_client
Colección: general_clients

```json

{
  "generalClientID": "123e4567-e89b-12d3-a456-426614174000",
  "childrenNum": 3,
  "birthdate": "1990-10-10 10:10:10",
  "prefessionCode": "123e4567-e89b-12d3-a456-426614174000",
  "occupationCode": "123e4567-e89b-12d3-a456-426614174000",
  "genderCode": "123e4567-e89b-12d3-a456-426614174000",
  "meta": {
    "createdAt": "1758552519383",
    "createdBy": "user@email.com",
    "modifiyedBy": "user@email.com",
    "modifiyedAt": "1758552519383"    
  },
  
  

}

```




