# DOSW_ParcialT1_SergioVega

## 6. Diagramas de contexto

![Diagrama De Contexto](docs/uml/context.png)


## 7. Requerimientos

### 7.1 Requerimientos funcionales

1. Permitir a los estudiantes de pregrado solicitar tutorias
2. El sistema debe notificar a los estudiantes acerca de si su reserva de tutoria fue asignada y confirmada
3. Permitir a los estudiantes de pregrado solicitar tutorias indicando su preferencia de tutor [FASTEST_AVAILABLE / EXPERT_FIRST / PEER_TUTORING].

### 7.2 Requerimientos no funcionales

1. El sistema debe utilizar la paleta de colores oficial del programa de Ingeniería de Sistemas de la Escuela para TutoECI en todas sus interfaces
2. La interfaz del sistema debe adaptarse a diferentes tamaños de pantalla, incluyendo móviles y computadores de escritorio.

### Criterios de aceptacion

#### Requerimiento Funcional 1

| **Campo** | **Descripción** |
| ---------------------------- | ------------------------------------------------------------------------------------- |
| **ID**                       | RF-01 |
| **Nombre del requerimiento** | Solicitar tutoria |
| **Descripción**              | El sistema debe permitir a los solicitantes (estudiantes de pregrado) solicitar una tutoría. |
| **Precondiciones**           | El solicitante debe estar inscrito a la materia de la que realiza la solicitud |
| **Flujo principal**          | 1. El solicitante selecciona la opción para solicitar una tutoria.<br>2. El sistema solicita la información del estudiante.<br>3. El sistema verifica la fecha y disponibilidad de los tutores validos.<br>4. El sistema valida la información.<br>5. El sistema registra la tutoria. |
| **Diagrama de caso de uso**  | ![Solicitar tutoria](docs/uml/caso1.png) |
| **Poscondiciones**           | La tutoria queda registrada en el sistema y disponible para revisar |

#### Requerimiento Funcional 2

| **Campo** | **Descripción** |
| ---------------------------- | ------------------------------------------------------------------------------------- |
| **ID**                       | RF-02 |
| **Nombre del requerimiento** | Notificar confirmacion |
| **Descripción**              | El sistema debe notificar a los solicitantes (estudiantes de pregrado) despues de haber realizado una solicitud de una tutoría, si esta fue confirmada. |
| **Precondiciones**           | El solicitante debe haber realizado una peticion de tutoria |
| **Flujo principal**          | 1. El sistema verifica que la tutoria exista y confirma que esta sea valida.<br>2. El sistema envia al estudiante su respectiva confirmacion. |
| **Diagrama de caso de uso**  | ![Notificar solicitud](docs/uml/caso2.png) |
| **Poscondiciones**           | El estudiante recibe en su correo la confirmacion de su tutoria |

#### Requerimiento Funcional 3

| **Campo** | **Descripción** |
| ---------------------------- | ------------------------------------------------------------------------------------- |
| **ID**                       | RF-03 |
| **Nombre del requerimiento** | Solicitar tutoria por preferencia o condicion |
| **Descripción**              | El sistema debe permitir a los solicitantes (estudiantes de pregrado) solicitar una tutoría segun su prefrerencia respecto a los tutores, como lo es el primero disonible (FASTEST_AVAILABLE), priorizar profesores (EXPERT_FIRST) o priorizar otros estudiantes (PEER_TUTORING). |
| **Precondiciones**           | El solicitante debe estar inscrito a la materia de la que realiza la solicitud y debe incluir en esta sus preferencias |
| **Flujo principal**          | 1. El solicitante selecciona la opción para solicitar una tutoria segun sus necesidades.<br>2. El sistema solicita la información del estudiante.<br>3. El sistema filtra a los tutores segun la necesidad del estudiante <br>4. El sistema verifica la fecha y disponibilidad de los tutores validos.<br>5. El sistema valida la información.<br>5. El sistema informa a el estudiante de su tutor. <br>6. El sistema registra la tutoria. |
| **Diagrama de caso de uso**  | ![Solicitar tutoria especifica](docs/uml/caso3.png) |
| **Poscondiciones**           | El estudiante es informado de su tutor y de su reserva |


## 8. Planeacion Agile

https://yazid-sanchez.atlassian.net/jira/software/projects/DPTSV/boards/3/timeline?atlOrigin=eyJpIjoiZTBkNTZlODExMmRkNDI1YjllYTM1MmM4OGMzZTczYmEiLCJwIjoiaiJ9