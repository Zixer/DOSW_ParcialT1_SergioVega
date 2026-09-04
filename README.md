# DOSW_ParcialT1_SergioVega

## 6. Diagramas de contexto

![Diagrama De Contexto](docs/uml/context.png)


## 7. Requerimientos

### 1.1 Requerimientos funcionales

1. Permitir a los estudiantes de pregrado solicitar tutorias
2. El sistema debe notificar a los estudiantes acerca de si su reserva de tutoria fue asignada y confirmada

### 1.2 Requerimientos no funcionales

1. El sistema debe utilizar la paleta de colores oficial del programa de Ingeniería de Sistemas de la Escuela para TutoECI en todas sus interfaces
2. La interfaz del sistema debe adaptarse a diferentes tamaños de pantalla, incluyendo móviles y computadores de escritorio.

## 2. Diagramas de caso de uso

### 2.1 Requerimiento Funcional 1

| **Campo** | **Descripción** |
| ---------------------------- | ------------------------------------------------------------------------------------- |
| **ID**                       | RF-01 |
| **Nombre del requerimiento** | Solicitar tutoria |
| **Descripción**              | El sistema debe permitir a los solicitantes (estudiantes de pregrado) solicitar  una tutoría indicando mi preferencia de tutor (profesor o estudiante de posgrado). |
| **Precondiciones**           | El solicitante debe estar inscrito a la materia de la que realiza la solicitud |
| **Flujo principal**          | 1. El solicitante selecciona la opción para solicitar una tutoria segun sus necesidades.<br>2. El sistema solicita la información del estudiante.<br>3. El sistema verifica la fecha y disponibilidad de los tutores validos.<br>4. El sistema valida la información.<br>5. El sistema registra la tutoria.<br>6. El sistema notifica sobre la asignacion de la tutoria. |
| **Diagrama de caso de uso**  | ![Crear torneo](docs/uml/caso1.png) |
| **Poscondiciones**           | La tutoria queda registrada en el sistema y disponible para revisar |
