## Miembros del grupo L4-FJO-9

1. Amireh, Marwan
2. Angulo Pérez, Jaime
3. Medina Domínguez, Juan José
4. Rodríguez Rodríguez, Miguel Ángel

## 1. Introducción al problema

 **Gestor de Empleados**.<br>
 Con este proyecto, buscamos solucionar un problema real. Un encargado de limpieza hospitalaria que necesita una forma cómoda y simple de administrar su personal.<br>
 El producto va dirigido a jefes y responsables que necesiten llevar un control de sus empleados y organizarlos.<br>
 Nuestro cliente es un encargado, que trabaja en el hospital Virgen del Rocío, cubriendo el turno de noche.<br>
 Partimos de una solución pobre y falta de funcionalidad ya implementada. Nuestro objetivo es proporcionar un sistema eficiente, escalable y mantenible en el tiempo, que pueda facilitar el registro de información, y la planificación, tanto a corto, como a largo plazo. 

## 2. Glosario de términos

| **Término** | **Definición** | **Imagen** |
|:---|:---|:---:|
| **Área** | Zona del hospital en la que existen puestos que han de ser cubiertos, como cocina, maternal, infantil o traumatología. | <img width="120" alt="Área hospitalaria" src="https://images.unsplash.com/photo-1519494026892-80bbd2d6fd0d?auto=format&fit=crop&w=240&h=150&q=80" /> |
| **Ausencia** | Situación en la que un trabajador no acude a trabajar. Puede deberse a permiso, licencia, vacaciones, baja, accidente, etc. | <img width="120" alt="Ausencia laboral" src="https://blog.servitalent.com/hubfs/absentismo%20laboral.jpg" /> |
| **Baja** | Periodo en el que un trabajador se encuentra ausente debido a problemas de salud, principalmente. | <img width="120" alt="Atención sanitaria" src="https://guidedimagerydownloads.com/wp-content/uploads/Dollarphotoclub_73593698.jpg" /> |
| **Cambio de vacaciones** | Solicitud de un trabajador para modificar sus vacaciones. Se realiza por escrito y, si se aprueba, se registra el cambio. | <img width="120" alt="Destino vacacional" src="https://media.istockphoto.com/id/2094317337/photo/man-looking-at-calendar-on-phone-and-laptop-early-in-the-morning-for-planning-the-day-digital.jpg?s=170667a&w=0&k=20&c=oUH7UM9xd5Qxz514nBSmv9XUZbEjLbmItLF_sjLJmx4=" /> |
| **Contrato** | Relación pactada del trabajador con el hospital. La finalización del contrato es uno de los motivos por los que se ausenta un trabajador. | <img width="120" alt="Contrato laboral" src="https://contratos.aecxa.com/wp-content/uploads/2025/08/crear-contratos-online-1-768x768.png" /> |
| **Cuadrante** | Tabla o documento utilizado para organizar y registrar la planificación de trabajadores, permisos, vacaciones, etc. | <img width="120" alt="Cuadrante de planificación" src="https://images.ctfassets.net/p03bi75xct27/1WvJ86F5UWcpMam6iTmcoY/b84cff4a8bb983e0f2262f813a873838/Plantilla_cuadrante_mensual_excel_gratis__1_.png" /> |
| **Día de descanso** | Fecha en la que el trabajador no ejerce porque corresponde a su descanso. En el estadillo aparece mediante D. | <img width="120" alt="Descanso" src="https://www.adeccoinstitute.es/wp-content/uploads/2023/07/Descansos-durante-la-jornada-laboral.jpg" /> |
| **Día disfrutado** | Fecha en la que finalmente el trabajador disfruta un permiso que previamente había solicitado. | <img width="120" alt="Día disfrutado en calendario" src="https://media.istockphoto.com/id/881217980/photo/networking-at-a-coffee-break.jpg?s=170667a&w=0&k=20&c=Jh1pCVtOGvrF13wefw6GoHM20pTuZsn2ad5x-YIPoSw=" /> |
| **Día festivo** | Fecha que debe tenerse en cuenta para organizar los trabajadores y los permisos. | <img width="120" alt="Día festivo" src="https://tse4.mm.bing.net/th/id/OIP.OLg80u5J2gPBNQ3qF06nGAHaEK?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" /> |
| **Día solicitado** | Fecha en la que el trabajador solicita disfrutar un permiso o descanso. | <img width="120" alt="Solicitud de permiso por ordenador" src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=240&h=150&q=80" /> |
| **Día trabajado** | Fecha en la que el trabajador ejerce su labor. En el estadillo se representa con X. | <img width="120" alt="Profesional trabajando en el hospital" src="https://images.unsplash.com/photo-1521737711867-e3b97375f902?auto=format&fit=crop&w=240&h=150&q=80" /> |
| **Estadillo** | Documento oficial que se envía a la oficina donde se indica la situación de cada trabajador. | <img width="120" alt="Estadillo de trabajadores con registros" src="https://www.slideteam.net/wp/wp-content/uploads/2023/07/Hoja-de-trabajo-del-empleado-con-objetivos-y-cronograma-del-proyecto-7.png" /> |
| **Falta injustificada** | Ausencia del trabajador sin una causa justificada. También se registra si se marcha antes sin motivo justificado. | <img width="120" alt="Puesto de trabajo sin cubrir" src="https://tse4.mm.bing.net/th/id/OIP.SXsFAsMSrKYNYSPVRs52LAAAAA?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" /> |
| **Falta justificada** | Ausencia del trabajador por motivos legítimos. | <img width="120" alt="Justificante médico" src="https://tse3.mm.bing.net/th/id/OIP.ZbcpNnyEVIM-4z4NwmdLpAHaEK?r=0&rs=1&pid=ImgDetMain&o=7&rm=3" /> |
| **Ficha del trabajador** | Información asociada a cada trabajador donde se registran, entre otras cosas, sus permisos durante el año. | <img width="120" alt="Ficha digital del trabajador" src="https://imgv2-2-f.scribdassets.com/img/document/866465542/original/fa743d2303/1?v=1" /> |
| **Fichaje (Pica Digital)** | Registro de la entrada y salida de un trabajador. El sistema registra las horas mediante una tarjeta digital. | <img width="120" alt="Fichaje mediante tarjeta digital" src="https://rfidtag.com/wp-content/uploads/2025/09/1.-What-is-RFID-Worker-Tracking.jpg" /> |
| **Hora de entrada** | Hora a la que el trabajador comienza a trabajar, registrada mediante el sistema de fichaje. | <img width="120" alt="Registro de entrada" src="https://www.shutterstock.com/image-photo/clock-8-oclock-260nw-281328350.jpg" /> |
| **Hora de salida** | Hora a la que el trabajador termina de trabajar un determinado día, registrada mediante el sistema de fichaje. | <img width="120" alt="Reloj que registra la hora de salida" src="https://static3.depositphotos.com/1005855/211/i/950/depositphotos_2116034-stock-photo-three-oclock.jpg" /> |
| **Hora de salida anticipada** | Registro del horario en el que un trabajador termina su jornada antes de lo habitual por algún motivo. | <img width="120" alt="Reloj de pared" src="https://fotografias.antena3.com/clipping/cmsimages01/2021/10/22/05749F08-8F3D-44F6-A485-F81C85947D02/default.jpg?crop=16:9&optimize=low&format=webply" /> |
| **Horas acumuladas** | Total de horas trabajadas por un empleado según sus registros de trabajo o fichaje. | <img width="120" alt="Gráfico de horas acumuladas" src="https://imagenes.eleconomista.com.mx/files/webp_768_768/uploads/2018/06/08/66e4e25326c3a.png" /> |
| **Licencia** | Tipo de ausencia que puede producirse por determinadas circunstancias, como una intervención familiar, una intervención propia o un examen. | <img width="120" alt="Documento de licencia" src="https://www.packagingcorp.com/wp-content/uploads/2023/06/Permiso-de-ausencia-992x661.jpg" /> |
| **Permiso** | Ausencia solicitada por un trabajador. Es importante distinguir entre la fecha en que se solicita y la fecha en que finalmente se disfruta. | <img width="120" alt="Solicitud de permiso laboral" src="https://www.bloghispanodenegocios.com/wp-content/uploads/2018/10/Requisitos-para-obtener-permiso-de-trabajo-categoria-c08-640x280.jpg" /> |
| **Puesto de trabajo** | Lugar que debe ser cubierto por un trabajador dentro de un área. | <img width="120" alt="Puesto de trabajo" src="https://tucontenidoweb.com/wp-content/uploads/Auxiliar-de-Limpieza-Hospitalaria.png" /> |
| **Refuerzo** | Persona de apoyo que realiza tareas complementarias y puede ocupar un puesto cuando es necesario. | <img width="120" alt="Equipo de profesionales sanitarios" src="https://png.pngtree.com/thumb_back/fh260/background/20230321/pngtree-the-two-male-colleagues-in-the-office-photo-image_1991854.jpg" /> |
| **Situación laboral diaria** | Situación en la que se encuentra un trabajador en un día concreto: trabaja, descanso, permiso, vacaciones, enfermedad, accidente, etc. | <img width="120" alt="Planificación diaria del personal" src="https://img.freepik.com/fotos-premium/trabajador-hospital-haciendo-limpieza-habitacion-ilustracion-generativa-ia_145713-3060.jpg?w=1380" /> |
| **Solicitud** | Petición realizada por el trabajador, por ejemplo para solicitar un día de descanso o un cambio de vacaciones. | <img width="120" alt="Solicitud realizada por ordenador" src="https://s1.abcstatics.com/abc/www/multimedia/sevilla/2023/06/09/ordenador-RHm0lEGWsLuxCkHWxF6yxcM-1200x840@abc.jpeg" /> |
| **Sustituto** | Persona encargada de cubrir una labor mientras el trabajador no puede ejercer por motivo alguno. | <img width="120" alt="Profesionales sanitarios" src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=240&h=150&q=80" /> |
| **Talla** | Tamaño de prenda que necesita un trabajador para cada tipo de uniforme. | <img width="120" alt="Ropa y prendas" src="https://images.unsplash.com/photo-1489987707025-afc232f7ea0f?auto=format&fit=crop&w=240&h=150&q=80" /> |
| **Tarjeta** | Tarjeta identificativa digital asociada al trabajador, que se utiliza para registrar la entrada y salida. | <img width="120" alt="Tarjeta identificativa" src="https://img.freepik.com/vector-premium/plantilla-tarjeta-identificacion-empleado-empresa-corporativa-moderna-creativa_630554-31.jpg?w=2000" /> |
| **Trabajador** | Persona que ejerce en el hospital y sobre la que se almacena información relativa a su trabajo, ausencias, permisos, vacaciones, fichajes, uniformes, etc. | <img width="120" alt="Profesional sanitario" src="https://images.unsplash.com/photo-1612349317150-e413f6a5b16d?auto=format&fit=crop&w=240&h=150&q=80" /> |
| **Turno rotatorio** | Sistema de turnos que va rotando entre los trabajadores y condiciona, entre otras cosas, la elección de determinados días festivos. | <img width="120" alt="Organización de turnos rotatorios" src="https://static.vecteezy.com/system/resources/previews/020/217/982/non_2x/staff-job-rotation-in-people-management-human-resources-to-manage-to-recruit-new-people-for-replacement-concept-businessman-new-hire-entering-office-while-other-resigned-for-new-job-paper-cut-style-vector.jpg" /> |
| **Uniforme** | Ropa de trabajo dada al personal. Se tienen casacas, pantalones, politos, chalecos y camisas. | <img width="120" alt="Uniforme de trabajo" src="https://sazindumentaria.com.ar/img/productos/uniformes-de-limpieza-2.jpg" /> |
| **Vacaciones** | Periodo en el que un empleado deja de acudir al trabajo para disfrutar varios días de descanso. Existe un sistema rotativo y se pueden solicitar cambios. | <img width="120" alt="Destino vacacional" src="https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?auto=format&fit=crop&w=240&h=150&q=80" /> |
## 3. Visión general del sistema

### 3.1. Requisitos generales

#### R.G.01 Gestionar la información de los empleados

(EDITAR) Como responsable de planificación, quiero tener el control de mi plantilla, y poder gestionarlos de manera cómoda.

#### R.G.02 Gestionar turnos de trabajo

(EDITAR) Como encargado del personal, quiero poder consultar y almacenar información relevante de mis empleados.

#### R.G.02 (HACER UN TERCERO)

### 3.2. Usuarios del sistema

El sistema está dirigido a dueños de negocios, encargados de personal, responsables de planificación, y, en general, a todo aquel que tenga personas a su cargo.

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Consultar la situación diaria de la plantilla

Como encargado del personal, quiero consultar la situación de todos los trabajadores en una fecha, para saber quién trabaja, quién descansa y quién falta.

**Prueba de aceptación**

- Aparecen todos los trabajadores con su situación (trabajado, descanso, permiso, vacaciones, baja, etc.)
- Cada trabajador aparece con una única situación (R.N.01)

#### R.F.02. Listar los trabajadores disponibles en una fecha

Como responsable de planificación, quiero listar los trabajadores disponibles (ni ausentes ni en descanso) en una fecha para decidir a quién puedo asignar a un puesto.

**Prueba de aceptación**

- Un trabajador de vacaciones, de baja, con permiso o con contrato finalizado no aparece.
- Se debe aplicar la regla de negocio R.N.04.

#### R.F.03. Consultar la asignación nocturna por área y puesto

Como responsable de calidad del turno de noche, quiero consultar quién ocupa cada puesto de cada área en una noche para comprobar que el hospital tiene el personal organizado.

**Prueba de aceptación**

- Aparecen todas las áreas con sus trabajadores y el refuerzo diferenciado.
- Ningún trabajador aparece en dos puestos la misma noche (R.N.03)

#### R.F.04. Listar los puestos sin cubrir en una noche

Como responsable de planificación, quiero listar los puestos que quedan sin cubrir en una noche concreta para buscar quien los ocupe antes de que el hospital se quede sin personal.

**Prueba de aceptación**

- Si cocina solo tiene un trabajador, aparece con un puesto sin cubrir.
- Si todo está cubierto, el listado está vacío.
- Se deben aplicar las reglas de negocio R.N.02 y R.N.04.

#### R.F.05. Consultar el calendario mensual

Como responsable de planificación, quiero consultar el mes completo, con la situación de cada día, y los festivos para ver la planificación mensual de la plantilla.

**Prueba de aceptación**

- Se muestran todos los días del mes con la situación de cada trabajador.
- Los festivos aparecen marcados.
- Se debe aplicar la regla de negocio R.N.01.

#### R.F.06. Consultar la ficha y los permisos pendientes de un trabajador

Como encargado del personal, quiero consultar la ficha de un trabajador con sus permisos solicitados, disfrutados y pendientes para saber qué días puede coger ya y cuáles le faltan.

**Prueba de aceptación**

- Con 14 permisos por festivos y 5 disfrutados, quedan 9 hasta final de año.
- "Hasta la fecha" solo cuenta los festivos ya transcurridos: consultando después del 15 de agosto no se incluye el 12 de octubre.
- Se deben aplicar las reglas de negocio R.N.05 y R.N.06.

#### R.F.07. Listar las solicitudes pendientes

Como encargado del personal, quiero listar las solicitudes de descanso y de cambio de vacaciones sin resolver para decidir cuáles puedo conceder.

**Prueba de aceptación**

- Una solicitud pendiente aparece con el trabajador, el tipo y la fecha.
- Una solicitud aprobada o rechazada no aparece.
- Se debe aplicar la regla de negocio R.N.09.

#### R.F.08. Consultar el cuadrante de vacaciones y los sustitutos necesarios

Como responsable de planificación, quiero consultar mes a mes, quién se va de vacaciones y cuántos sustitutos necesito para contratarlos a tiempo.

**Prueba de aceptación**

- Cada mes muestra los trabajadores de vacaciones y el número de sustitutos.
- Quien este año tiene julio aparece con agosto el año siguiente.
- Se deben aplicar las reglas de negocio R.N.08, R.N.09 y R.N.10.

#### R.F.09. Consultar los fichajes y las horas de un trabajador

Como responsable de calidad, quiero consultar los fichajes, las horas acumuladas y las horas de compensación de un trabajador para controlar que no trabaja más ni menos de lo establecido.

**Prueba de aceptación**

- Las horas acumuladas coinciden con la suma de los fichajes.
- Quien trabajó 2 días en Semana Santa tiene 2 horas de compensación y el saldo nunca es negativo.
- Se deben aplicar las reglas de negocio R.N.11 y R.N.12.

#### R.F.10. Listar las faltas injustificadas y las salidas anticipadas

Como encargado del personal, quiero listar las faltas injustificadas y las salidas anticipadas de un periodo para anotarlas en el estadillo.

**Prueba de aceptación**

- Una salida anticipada con motivo aparece como justificada, y sin motivo como falta.
- Una ausencia sin causa justificada aparece como falta injustificada.
- Se debe aplicar la regla de negocio R.N.13.

#### R.F.11. Consultar los uniformes que hay que pedir

Como encargado del material, quiero consultar cuántos uniformes pedir por tipo de prenda y talla, con previsión para sustitutos para solicitarlos correctamente.

**Prueba de aceptación**

- Si tres trabajadores usan ropa de talla M, aparecen 3 equipajes de talla M más la previsión.
- El resultado se desglosa por tipo de prenda.

#### R.F.12. Consultar el estadillo mensual

Como encargado del personal, quiero consultar el estadillo de un mes con la situación de cada trabajador cada día para enviar a la oficina el documento oficial.

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

Como responsable de planificación quiero almacenar los festivos del año con su tipo (ordinario o especial) para organizar a los trabajadores y los permisos. (ESPECIFICAR EN GLOSARIO ORDINARIO O ESPECIAL)

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

##### R.I.12. Uniforme y talla (NO DEBERÍA ESTAR)

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

##### R.N.05. Solicitud previa y festivos ya transcurridos (REDACTAR DE NUEVO)

Un permiso se solicita antes de disfrutarse y solo se puede disfrutar el correspondiente a un festivo que ya ha pasado (si el último fue el 15 de agosto, no se puede conceder uno por el 12 de octubre).

##### R.N.06. Permisos anuales

Cada año, cada trabajador debe disfrutar los 14 festivos, un día de feria, uno de Navidad, uno de Semana Santa, los días de libre disposición y un domingo a elegir.

##### R.N.07. Duración de las licencias

Por ley, las licencias duran 5 días por la intervención de un familiar de primer grado, 3 si es de segundo grado y 1 por motivos propios (intervención, examen, etc.). No hay límite anual.

##### R.N.08. Rotación de las vacaciones

Las vacaciones rotan cada año: julio, agosto, septiembre y vuelta a empezar. En caso de empleado nuevo, se le asignará para sus vacaciones el mes con menos falta de personal.

##### R.N.09. Solicitudes por escrito (MAL, DEBERIAN HACERSE POR LA APLICACIÓN)

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
| Planificar la plantilla | Ver quién trabaja, quién está disponible y qué puestos quedan sin cubrir | R.F.01 a R.F.05, R.I.01 a R.I.04 |
| Gestionar permisos y licencias | Ver permisos pendientes y resolver solicitudes | R.F.06, R.F.07, R.I.05 a R.I.07, R.I.09 |
| Gestionar vacaciones | Ver el cuadrante y los sustitutos necesarios | R.F.08, R.I.08 |
| Controlar horas y asistencia | Ver fichajes, compensaciones y faltas | R.F.09, R.F.10, R.I.10, R.I.11 |
| Gestionar uniformes y estadillo | Pedir uniformes y preparar el estadillo | R.F.11, R.F.12, R.I.12 |

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Código de colores del calendario**  
Como responsable de planificación quiero que el calendario use colores fijos (rosa festivo, verde permiso y licencia, amarillo vacaciones y beige baja) para identificar cada situación de un vistazo.

**R.N.F. 02. Consulta diaria y mensual en pantalla**  (ESTE REQUISITO DEBE SER FUNCIONAL)
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


