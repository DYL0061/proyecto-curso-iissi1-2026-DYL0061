# Título Proyecto

## Miembros del grupo L9-FJO

1. Amireh, Marwan
2. Angulo Pérez, Jaime
3. Medina Domínguez, Juan José
4. Rodríguez Rodríguez, Miguel Ángel

## 1. Introducción al problema

 **Gestor de Empleados**.<br>
 Con este proyecto, buscamos solucionar un problema real. Un encargado de limpieza hospitalaria que necesita una forma cómoda y simple de administrar su personal.<br>
 El producto va dirigido a jefes y responsables que necesiten llevar un control de sus empleados y organizarlos.<br>
 Partimos de una soluicón pobre y falta de funcionalidad ya implementada. Nuestro objetivo es proporcionar un sistema eficiente, escalable y mantenible en el tiempo, que pueda facilitar el registro de información, y la planificación, tanto a corto, como a largo plazo. 

## 2. Glosario de términos

• **Área**: Zona del hospital en la que existen puestos que han de ser cubiertos, como cocina,maternal,infantil o traumatología.

• **Ausencia**: Situación en la que un trabajador no acude a trabajar.Puede deberse a permiso,licencia,vacaciones,baja,accidente,etc.

• **Baja:** Periodo en el que un trabajador se encuntra ausente debido a problemas de salud principalmente.

• **Cambio de vacaciones:** Solicitud de un trabajador para modificar sus vacaciones.Se realiza mediante una solicitud escrita y, si se aprueba,se registra el cambio.

• **Contrato:** Relación pactada del trabajador con el hospital.La finalización del contrato es uno de los motivos por los que se ausenta un trabajador.

• **Cuadrante:** Tabla o documento utilizado para organizar y registrar la planificación de trabajadores,permisos,vacaciones,etc.

• **Día de descanso:** Día en el que el trabajador no ejerce porque corresponde a su descanso.En el estadillo aparece mediante D.

• **Día disfrutado:** Día en el que finalmente el trabajador disfruta un permiso que previamente había solicitado.

• **Día festivo:** Día festivo que debe tenerse en cuenta para organizar los trabajadores y los permisos.

• **Día solicitado:** Fecha en la que el trabajador solicita disfrutar un permiso o descanso.

• **Día trabajado:** Día en el que el trabajador ejerce su labor.En el estadillo se representa con X.

• **Estadillo:** Documento oficial que se envía a la oficina donde se indica la situación de cada trabajador.

• **Falta injustificada:** Ausencia del trabajador sin una causa justificada.También se registra si se marcha antes sin motivo justificado.

• **Falta justificada:** Ausencia del trabajador que tiene una causa justificada.

• **Ficha del trabajador:** Información asociada a cada trabajador donde se registran,entre otras cosas,sus permisos durante el año.

• **Fichaje(Pica Digital):** Registro de la entrada y salida de un trabajador.El sistema registra las horas mediante una tarjeta digital.

• **Hora de compensación:** Hora que el trabajador puede utilizar como compensación por determinados días,como Semana Santa, feria o Navidad.

• **Hora de entrada:** Hora a la que el trabajador comienza a trabajar,registrada mediante el sistema de fichaje.

• **Hora de salida:** Hora a la que el trabajador termina de trabajar un determinado día.

• **Hora de salida anticipada:** Hora a la que un trabajador termina de trabajar antes de lo habitual por algún motivo.

• **Horas acumuladas:** Total de horas acumuladas por un trabajador según sus registros de trabajo o fichaje.

• **Licencia:** Tipo de ausencia que puede producirse por determinadas circunstancias,como una intervención familiar,una intervención propia o un examen.

• **Permiso:** Ausencia solicitada por un trabajador.Es importante distinguir entre la fecha en que se solicita y la fecha en que finalmente se disfruta.

• **Puesto de trabajo:** Lugar que debe ser cubierto por un trabajador dentro de un área.

• **Refuerzo:** Persona de apoyo que realiza tareas complementarias y puede ocupar un puesto cuando es necesario.

• **Situación laboral diaria:** Situación en la que se encuentra un trabajador en un día concreto: trabaja, descanso, permiso, vacaciones, enfermedad, accidente, etc.

• **Solicitud:** Petición realizada por el trabajador, por ejemplo para solicitar un día de descanso o un cambio de vacaciones.

• **Sustituto:** Persona encargada de cubrir una labor mientras el trabajador no puede ejercer por motivo alguno.

• **Talla:** Tamaño de prenda que necesita un trabajador para cada tipo de uniforme.

• **Tarjeta:** Tarjeta identificativa y digital asociada al trabajador que se utiliza para registrar la entrada y salida.

• **Trabajador:** Persona que trabaja en el hospital y sobre la que se almacena información relativa a su trabajo, ausencias, permisos, vacaciones, fichajes, uniformes, etc.

• **Turno rotatorio:** Sistema de turnos que va rotando entre los trabajadores y condiciona, entre otras cosas,la elección de determinados días festivos.

• **Uniforme:** Ropa de trabajo asignada a los trabajadores.Se tienen casacas, pantalones, politos, chalecos y camisas.

• **Vacaciones:** Periodo en el que un trabajador deja de acudir al trabajo para disfrutar varios dias de descanso.Existe un sistema rotativo y se pueden solicitar cambios.

![alt text](hospital1.jpg) ![alt text](fichaje.jpg) ![alt text](maternal2.png)

## 3. Visión general del sistema

### 3.1. Requisitos generales

### 3.2. Usuarios del sistema

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Consultar la situación diaria de la plantilla

Como responsable de planificación quiero consultar la situación de todos los trabajadores en una fecha, con el motivo si están ausentes para saber quién trabaja, quién descansa y quién falta.

**Prueba de aceptación**

- Aparecen todos los trabajadores con su situación (trabajado, descanso, permiso, vacaciones, baja, etc.)
- Cada trabajador aparece con una única situación (R.N.01)

#### R.F.02. Listar los trabajadores disponibles en una fecha

Como responsable de planificación quiero listar los trabajadores disponibles (ni ausentes ni en descanso) en una fecha para decidir a quién puedo asignar a un puesto.

**Prueba de aceptación**

- Un trabajador de vacaciones, de baja, con permiso o con contrato finalizado no aparece.
- Se debe aplicar la regla de negocio R.N.04.

#### R.F.03. Consultar la asignación nocturna por área y puesto

Como responsable de planificación quiero consultar quién ocupa cada puesto de cada área en una noche para comprobar que el hospital tiene el personal organizado.

**Prueba de aceptación**

- Aparecen las cuatro áreas con sus trabajadores y el refuerzo diferenciado.
- Ningún trabajador aparece en dos puestos la misma noche (R.N.03)

#### R.F.04. Listar los puestos sin cubrir en una noche

Como responsable de planificación quiero listar los puestos que quedan sin cubrir en una noche concreta para buscar quien los ocupe antes de que el hospital se quede sin personal.

**Prueba de aceptación**

- Si cocina solo tiene un trabajador, aparece con un puesto sin cubrir.
- Si todo está cubierto, el listado está vacío.
- Se deben aplicar las reglas de negocio R.N.02 y R.N.04.

#### R.F.05. Consultar el calendario mensual

Como responsable de planificación quiero consultar el mes completo con la situación de cada día y los festivos para ver la planificación mensual de la plantilla.

**Prueba de aceptación**

- Se muestran todos los días del mes con la situación de cada trabajador.
- Los festivos aparecen marcados.
- Se debe aplicar la regla de negocio R.N.01.

#### R.F.06. Consultar la ficha y los permisos pendientes de un trabajador

Como responsable de planificación quiero consultar la ficha de un trabajador con sus permisos solicitados, disfrutados y pendientes para saber qué días puede coger ya y cuáles le faltan.

**Prueba de aceptación**

- Con 14 permisos por festivos y 5 disfrutados, quedan 9 hasta final de año.
- "Hasta la fecha" solo cuenta los festivos ya transcurridos: consultando después del 15 de agosto no se incluye el 12 de octubre.
- Se deben aplicar las reglas de negocio R.N.05 y R.N.06.

#### R.F.07. Listar las solicitudes pendientes

Como responsable de planificación quiero listar las solicitudes de descanso y de cambio de vacaciones sin resolver para decidir cuáles puedo conceder.

**Prueba de aceptación**

- Una solicitud pendiente aparece con el trabajador, el tipo y la fecha.
- Una solicitud aprobada o rechazada no aparece.
- Se debe aplicar la regla de negocio R.N.09.

#### R.F.08. Consultar el cuadrante de vacaciones y los sustitutos necesarios

Como responsable de planificación quiero consultar, mes a mes, quién se va de vacaciones y cuántos sustitutos necesito para contratarlos a tiempo.

**Prueba de aceptación**

- Cada mes muestra los trabajadores de vacaciones y el número de sustitutos.
- Quien este año tiene julio aparece con agosto el año siguiente.
- Se deben aplicar las reglas de negocio R.N.08, R.N.09 y R.N.10.

#### R.F.09. Consultar los fichajes y las horas de un trabajador

Como responsable de planificación quiero consultar los fichajes, las horas acumuladas y las horas de compensación de un trabajador para controlar que no trabaja más ni menos de lo establecido.

**Prueba de aceptación**

- Las horas acumuladas coinciden con la suma de los fichajes.
- Quien trabajó 2 días en Semana Santa tiene 2 horas de compensación y el saldo nunca es negativo.
- Se deben aplicar las reglas de negocio R.N.11 y R.N.12.

#### R.F.10. Listar las faltas injustificadas y las salidas anticipadas

Como responsable de planificación quiero listar las faltas injustificadas y las salidas anticipadas de un periodo para anotarlas en el estadillo.

**Prueba de aceptación**

- Una salida anticipada con motivo aparece como justificada, y sin motivo como falta.
- Una ausencia sin causa justificada aparece como falta injustificada.
- Se debe aplicar la regla de negocio R.N.13.

#### R.F.11. Consultar los uniformes que hay que pedir

Como responsable de planificación quiero consultar cuántos uniformes pedir por tipo de prenda y talla, con previsión para sustitutos para solicitarlos correctamente.

**Prueba de aceptación**

- Si tres trabajadores usan equipaje de talla M, aparecen 3 equipajes de talla M más la previsión.
- El resultado se desglosa por tipo de prenda.

#### R.F.12. Consultar el estadillo mensual

Como responsable de planificación quiero consultar el estadillo de un mes con la situación de cada trabajador cada día para enviar a la oficina el documento oficial.

**Prueba de aceptación**

- Cada día aparece con su código oficial (X, D, P, V, E, A, L, EX, M o F)
- Se muestran las noches y los festivos trabajados con su tipo.
- Se deben aplicar las reglas de negocio R.N.13, R.N.14 y R.N.15.

#### 4.1.1. Requisitos de información

##### R.I.01. Trabajador y contrato

Como responsable de planificación quiero almacenar el nombre, apellidos, DNI y tipo (plantilla o sustituto) de cada trabajador, con su contrato (fecha de inicio y de fin) para saber con quién cuento y hasta cuándo.

**Prueba de aceptación**

- No se puede registrar un trabajador sin DNI ni dos con el mismo DNI.
- No se acepta un contrato con fecha de fin anterior a la de inicio.

##### R.I.02. Área y puesto de trabajo

Como responsable de planificación quiero almacenar las áreas (cocina, maternal, infantil y traumatología), sus puestos y la persona de refuerzo para saber cuántos trabajadores necesito cada noche.

**Prueba de aceptación**

- Todo puesto pertenece a un área.
- Cocina tiene 2 puestos, maternal 2, infantil 1 y traumatología 2.

##### R.I.03. Situación laboral diaria

Como responsable de planificación quiero almacenar la situación de cada trabajador cada día (trabajado, descanso, permiso, licencia, vacaciones, enfermedad, accidente, lactancia, excedencia, maternidad, falta o fin de contrato) para controlar quién acude a trabajar y quién no.

**Prueba de aceptación**

- No se puede registrar una situación sin trabajador o sin fecha.
- Un trabajador no puede tener dos situaciones distintas el mismo día.

##### R.I.04. Asignación a un puesto

Como responsable de planificación quiero almacenar en qué puesto trabaja cada trabajador cada noche, con su hora de salida y el motivo si sale antes para saber quién cubre cada puesto.

**Prueba de aceptación**

- Se puede anotar la hora de salida y el motivo de una salida anticipada.
- Un trabajador no puede ser asignado a dos puestos la misma noche.

##### R.I.05. Día festivo

Como responsable de planificación quiero almacenar los festivos del año con su tipo (ordinario o especial) para organizar a los trabajadores y los permisos.

**Prueba de aceptación**

- Viernes Santo, 1 de enero y Reyes se registran como especiales.
- No pueden existir dos festivos en la misma fecha.

##### R.I.06. Ficha y permisos

Como responsable de planificación quiero almacenar los permisos anuales de cada trabajador (festivos, feria, Navidad, Semana Santa, libre disposición y un domingo), con la fecha de solicitud y la de disfrute  
para distinguir lo que pide de lo que realmente coge.

**Prueba de aceptación**

- Se puede registrar un permiso solicitado sin fecha de disfrute.
- No se acepta una fecha de disfrute anterior a la de solicitud.

##### R.I.07. Licencia

Como responsable de planificación quiero almacenar las licencias con su motivo (familiar de primer o segundo grado, propia o examen), fecha de inicio y días para registrar las ausencias justificadas por ley.

**Prueba de aceptación**

- No se acepta una licencia sin motivo.
- Un trabajador puede tener varias licencias en el mismo año.

##### R.I.08. Vacaciones y sustitución

Como responsable de planificación quiero almacenar las vacaciones de cada trabajador por año y el sustituto que cubre cada periodo para llevar la rotación y el cuadrante.

**Prueba de aceptación**

- No pueden solaparse dos periodos de vacaciones del mismo trabajador.
- Se conservan las vacaciones de años anteriores.

##### R.I.09. Solicitud

Como responsable de planificación quiero almacenar las solicitudes de descanso y de cambio de vacaciones con su estado (pendiente, aprobada o rechazada) para saber qué debo resolver.

**Prueba de aceptación**

- Una solicitud nueva queda pendiente.
- Se puede cambiar su estado a aprobada o rechazada.

##### R.I.10. Tarjeta y fichaje

Como responsable de planificación quiero almacenar la tarjeta de cada trabajador y sus fichajes con hora de entrada y de salida para controlar las horas trabajadas.

**Prueba de aceptación**

- Una tarjeta pertenece a un único trabajador.
- No se acepta una hora de salida anterior a la de entrada.

##### R.I.11. Hora de compensación

Como responsable de planificación quiero almacenar las horas de compensación que genera cada trabajador y el día en que las disfruta para saber cuántas puede utilizar para salir antes.

**Prueba de aceptación**

- Se genera una hora por día trabajado en Semana Santa, feria o Navidad.
- No se pueden disfrutar más horas de las generadas.

##### R.I.12. Uniforme y talla

Como responsable de planificación quiero almacenar la talla de cada trabajador para cada tipo de prenda (casaca, pantalón, polito, chaleco y camisa) para saber cuántos uniformes pedir.

**Prueba de aceptación**

- Un trabajador solo tiene una talla por tipo de prenda.
- Los sustitutos también tienen sus tallas registradas.

#### 4.1.2. Reglas de negocio

##### R.N.01. Una única situación por trabajador y día

Un trabajador solo puede tener una situación laboral en una fecha concreta.

##### R.N.02. Cobertura nocturna mínima

Cada noche deben estar cubiertos todos los puestos: 2 trabajadores en cocina, 2 en maternal, 1 en infantil y 2 en traumatología, más normalmente una persona de refuerzo que ocupa el puesto que quede vacío. Esto se cumple siempre, incluso ante un acontecimiento extraordinario.

##### R.N.03. Un único puesto por noche

Un trabajador solo puede ocupar un puesto en la misma noche.

##### R.N.04. Un trabajador ausente no puede cubrir un puesto

Quien está ausente (permiso, licencia, vacaciones, baja, accidente o contrato finalizado) no puede ser asignado a un puesto ese día.

##### R.N.05. Solicitud previa y festivos ya transcurridos

Un permiso se solicita antes de disfrutarse y solo se puede disfrutar el correspondiente a un festivo que ya ha pasado (si el último fue el 15 de agosto, no se puede conceder uno por el 12 de octubre).

##### R.N.06. Permisos anuales

Cada año, cada trabajador debe disfrutar los 14 festivos, un día de feria, uno de Navidad, uno de Semana Santa, los días de libre disposición y un domingo a elegir.

##### R.N.07. Duración de las licencias

Por ley, las licencias duran 5 días por la intervención de un familiar de primer grado, 3 si es de segundo grado y 1 por motivos propios (intervención, examen, etc.). No hay límite anual.

##### R.N.08. Rotación de las vacaciones

Las vacaciones rotan cada año: julio, agosto, septiembre y vuelta a empezar.

##### R.N.09. Solicitudes por escrito

Los días de descanso y los cambios de vacaciones se solicitan por escrito, y un cambio de vacaciones solo se anota en el cuadrante si se aprueba.

##### R.N.10. Sustitución de vacaciones

Los huecos de quienes están de vacaciones se cubren con sustitutos contratados, y el cuadrante indica cuántos hacen falta.

##### R.N.11. Horas de compensación

Se genera una hora por cada día trabajado en Semana Santa, feria o Navidad, que puede disfrutarse durante todo el año, sin superar las generadas.

##### R.N.12. Fichaje obligatorio

Todo trabajador debe fichar su entrada y su salida con su propia tarjeta, por imposición legal.

##### R.N.13. Faltas injustificadas

La ausencia sin causa justificada, o la salida anticipada sin motivo justificado, se anota como falta en el estadillo.

##### R.N.14. Festivos especiales

Todos los festivos trabajados se pagan aparte, pero Viernes Santo, 1 de enero y Reyes son especiales y el estadillo indica el tipo de cada uno.

##### R.N.15. Códigos del estadillo

El estadillo usa estos códigos: E (enfermedad), D (descanso), X (trabajado), L (lactancia), A (accidente), EX (excedencia), M (maternidad), V (vacaciones), F (falta) y P (permiso).

### 4.2. Mapa de historias de usuario (opcional)

Todas las historias son del único usuario del sistema: el **responsable de planificación**.

| Actividad | Historias de usuario | Requisitos |
| --- | --- | --- |
| Planificar la plantilla nocturna | Ver quién trabaja, quién está disponible y qué puestos quedan sin cubrir | R.F.01 a R.F.05, R.I.01 a R.I.04 |
| Gestionar permisos y licencias | Ver permisos pendientes y resolver solicitudes | R.F.06, R.F.07, R.I.05 a R.I.07, R.I.09 |
| Gestionar vacaciones | Ver el cuadrante y los sustitutos necesarios | R.F.08, R.I.08 |
| Controlar horas y asistencia | Ver fichajes, compensaciones y faltas | R.F.09, R.F.10, R.I.10, R.I.11 |
| Gestionar uniformes y estadillo | Pedir uniformes y preparar el estadillo | R.F.11, R.F.12, R.I.12 |

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Código de colores del calendario**  
Como responsable de planificación quiero que el calendario use colores fijos (rosa festivo, verde permiso y licencia, amarillo vacaciones y beige baja) para identificar cada situación de un vistazo.

**R.N.F. 02. Consulta diaria y mensual en pantalla**  
Como responsable de planificación quiero ver en una sola pantalla la situación de cada día y del mes para no recorrer varios documentos.

**R.N.F. 03. Compatibilidad con MariaDB**  
Como responsable de planificación quiero que el sistema funcione sobre un servidor MariaDB para cumplir los requisitos técnicos del proyecto.

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


