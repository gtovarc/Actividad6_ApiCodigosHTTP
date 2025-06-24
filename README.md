## Actividad 6: API Códigos HTTP 
**HTTP RESPONSES**
--
**200 OK**
La consulta o la acción se ha realizado con éxito.

---
**201 Created**
Se creó correctamente el alumno por medio de la función *nuevo_alumno* 

---

**404: Not Found**
No se encontró el alumno solicitado, ya sea para consultar, modificar o eliminar. 

---

**409: Conflict**
El alumno que se intenta agregar, ya existe.

---

**422: Unprocessable Entity**
La información proporcionada para realizar la consulta, para modificar o eliminar el registro está incompleta. Revise que el formato sea el siguiente:


     {
      "Matricula":202163329,
      "Nombre":"ALTAMIRANO, APEL NOBLE",
      "Edad":22,
      "Facultad":"Ciencias de la computación",
      "Grado":"Licenciatura",
      "Carrera":"Ing. Tecnologias de la Información",
      "Genero":"Masculino",
      "Correo":"nobb.altamirano@alumno.buap.mx",
      "Promedio":7,
      "Semestre":6
    }
