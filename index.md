---
layout: default
title: Estándares BIM
---

![Portada Incidencias](img/INCIDENCIAS_p01_01.jpg)

# 🧩 INCIDENCIAS

> Registro estructurado de una observación, conflicto, no conformidad o solicitud de información detectada en los modelos o documentación del proyecto, que requiere seguimiento, asignación de responsable y resolución dentro del Entorno Común de Datos (CDE), garantizando la trazabilidad del proceso.

## Tabla de contenido

- [🚦 CREAR INCIDENCIA](#crear-incidencia)
  - [CAMPOS DE REGISTRO Y GESTIÓN DE INCIDENCIAS](#campos)

---

<a id="crear-incidencia"></a>

## 🚦 CREAR INCIDENCIA

<a id="campos"></a>

### CAMPOS DE REGISTRO Y GESTIÓN DE INCIDENCIAS

A continuación, se presentan los campos para el registro de incidencias en el CDE mediante Forma Fata Management, asegurando su correcta trazabilidad y seguimiento.

![Formulario Create issue](img/INCIDENCIAS_p02_01.jpg)

| N.º | Campo | Descripción y/o uso |
|:---:|-------|---------------------|
| 1 | **Title** | “COORDINATION” / “CLASH” |
| 2 | **Status** | **Open**: Incidencia nueva o que no ha sido atendida a la fecha.<br>**In review**: Incidencia que fue atendida y que debe ser revisada y validada por el creador.<br>**Pending**: Incidencia que no puede ser resuelta ya que está pendiente de una decisión entre las partes o terceros.<br>**Close**: Incidencia que una vez ajustada y revisada, esta se encuentra completada y resuelta. |
| 3 | **Type** | **Coordination**: Incidencia perteneciente a coordinación diseño o ajustes requeridos al modelo BIM.<br>**Clash**: Incidencia perteneciente a interferencias encontradas entre modelos. |
| 4 | **Description** | Descripción de la incidencia creada. |
| 5 | **Assigned to** | Especialistas o empresa a la cual se le asigna la incidencia. |
| 6 | Watchers | Opcional. |
| 7 | **Location** | Ubicación dentro del proyecto a la cual pertenece la incidencia.<br>Esta ubicación coincide con el campo de ubicación creado en *4.7 Nomenclatura y versionamiento*. |
| 8 | Location detail | Opcional. |
| 9 | Due date | Opcional. |
| 10 | **Start date** | Fecha de creación de la incidencia. |
| 11 | Placement | Opcional. |
| 12 | **Resolution level** | Nivel de acuerdo con lo establecido en *3.4.3 Estrategia de resolución de conflictos*. |
| 13 | Discipline | Disciplina a quién corresponde la incidencia. Esta disciplina coincide con las creadas en *4.7 Nomenclatura y versionamiento*. |
| 14 | **Attachments** | Imágenes o documentos que ayuden a entender la interferencia. Puede tener o no adjuntos. |
| 15 | **Comentarios** | Una vez la interferencia es atendida, se puede o no incluir comentarios adicionales. |

> 📌 Una vez la incidencia haya sido resuelta, el especialista responsable deberá cambiar su estado a **“In Review”**, con el fin de permitir la validación por parte de la coordinación BIM y asegurar el adecuado seguimiento del conflicto.

---

![Portada Lista de chequeo](img/INCIDENCIAS_p04_01.jpg)

# ✅ LISTA DE CHEQUEO CALIDAD BIM

## Tabla de contenido

- [MODELO NATIVOS](#modelo-nativos)
- [MODELO IFC](#modelo-ifc)
- [MODELO FEDERADO](#modelo-federado)

La presente Lista de Chequeo de Calidad BIM corresponde a una herramienta de control y validación técnica desarrollada para apoyar el proceso de revisión de los modelos digitales del proyecto, garantizando el cumplimiento de los lineamientos establecidos en el Plan de Ejecución BIM (PEB) y los criterios de calidad definidos para los entregables BIM.

La lista de chequeo se encuentra clasificada en tres tablas de evaluación correspondientes a:

- **Modelos Nativos**
- **Modelos IFC**
- **Modelo Federado**

Cada una de estas tablas contiene los ítems de verificación técnica necesarios para evaluar aspectos relacionados con la calidad del modelo, consistencia de la información, estructura de modelación, interoperabilidad, coordinación y cumplimiento de los requerimientos BIM del proyecto.

La aplicación de esta herramienta permitirá realizar revisiones estandarizadas, identificar oportunamente inconsistencias en los modelos y asegurar que los entregables digitales cumplan con las condiciones técnicas necesarias para los procesos de coordinación, revisión y gestión de información del proyecto.

<a id="modelo-nativos"></a>

## MODELO NATIVOS

| N.º | Sección | Nombre | Descripción |
|:---:|---------|--------|-------------|
| 1 | 01_GENERAL | 01_Codificación Modelo | El modelo se encuentra según codificación del PEB |
| 2 | 01_GENERAL | 02_Nombramiento y Codificación | Los campos de codificación están acordes al nombramiento y codificación del proyecto |
| 3 | 01_GENERAL | 03_Alertas | Existen warnings o alertas razonables menores a 20 |
| 4 | 01_GENERAL | 04_Familias In Situ | El modelo sólo contiene familias del sistema (no familias en sitio) |
| 5 | 01_GENERAL | 05_Formato/Versión | El modelo BIM se encuentra en el formato y versión 2026 según el PEB |
| 6 | 01_GENERAL | 06_Codificación de Planos | Los planos están codificados de acuerdo al sistema de nombramiento y codificación definido en el PEB |
| 7 | 01_GENERAL | 07_Cantidad de Planos | La cantidad de planos en PDF coincide con la cantidad de planos elaborados en el modelo. |
| 8 | 01_GENERAL | 08_Purge | El archivo se encuentra limpio o purgado |
| 9 | 01_GENERAL | 09_Tamaño Modelo | Peso del modelo menor a 250 MB |
| 10 | 01_GENERAL | 10_Vista Coordinación | El proyecto tiene la vista llamada 3D_COORDINACION creada de acuerdo con lo especificado en el PEB |
| 11 | 01_GENERAL | 11_Coordinacion | La vista Coordinacion solo contiene elementos 3D |
| 12 | 02_PUBLISH | 12_Publish 3D_COORDINACION | Vista Coordinacion está configurada en Publish |
| 13 | 02_PUBLISH | 13_Publish Planos | Planos elaborados en el modelo están configurada en Publish |
| 14 | 03_LOCALIZACION | 14_Geolocalización | El modelo se encuentra Geolocalizado según sistema de coordenadas establecido en el PEB |
| 15 | 04_OBJETOS | 15_Duplicados | No existen elementos duplicados |
| 16 | 04_OBJETOS | 16_Fase de objetos | Los elementos modelados cuentan con la información de fase (Construcción nueva, existente, demolición, etc) |
| 17 | 04_OBJETOS | 17_Materiales | Los elementos de modelado cuentan con la información mínima requerida en cuanto a sus materiales |
| 18 | 04_OBJETOS | 18_Nombre de Objetos | Validar que se haya utilizado una nomenclatura de los elementos según estándar de creación de objetos según lo indicado en el PEB |
| 19 | 04_OBJETOS | 19_Posición | Los elementos se encuentran correctamente posicionados espacialmente y/o referenciados en los niveles correspondientes. |
| 20 | 05_CATEGORIA | 20_Objetos Arquitectónicos modelados con las categorías adecuadas | Los elementos arquitectónicos se han modelado con las categoria adecuadas (muros, puertas, ventanas, etc) |
| 21 | 06_CATEGORIA | 21_Objetos Estructurales modelados con las categorías adecuadas | Los elementos estructurales se han modelado con la categoria de elemento correspondiente, Ej.: Elemento: Columna → Tipo de Familia: Pilar Estructural o Structural Column |
| 22 | 07_CATEGORIA | 22_Objetos MEP modelados con las categorías adecuadas | Los elementos MEP se han modelado con las categoria adecuadas (tuberías, ductos, accesorios, etc) |
| 23 | 07_CATEGORIA | 23_Objetos infraestructura modelados con las categorías adecuadas | Los elementos de insfraestructura se han modelado con la categoria adecuadas (3D solid, bloques 3D, aligments, surface, etc) |
| 24 | 08_COORDINACIÓN | 24_Idioma modelos | Los LOI's y data del modelo Federado están estandarizados en el idioma del proyecto (todos los modelos individuales están exportados en el mismo idioma Ingles) |
| 25 | 08_COORDINACIÓN | 25_Idioma modelos | Los LOI's y data del modelo Federado están estandarizados en el idioma del proyecto (todos los modelos individuales están exportados en el mismo idioma Ingles) |
| 26 | 09_LINKS | 26_Import Cad | No existen archivos importados en CAD |
| 27 | 09_LINKS | 27_Links Cad | No existen archivos vinculados en CAD |
| 28 | 09_LINKS | 28_Links Rvt pinados | Los links de modelos de Revit se encuentran pinados |
| 29 | 10_VISTAS Y NIVELES | 29_Nombre de Niveles | Los niveles se encuentran nombrados de acuerdo a lo indicado en el PEB |
| 30 | 10_VISTAS Y NIVELES | 30_Nombre de Vistas | Las vistas se encuentran nombradas de acuerdo a lo indicado en el PEB |
| 31 | 11_LOIN | 31_LOI_Proyecto | El modelo cumple con los LOI establecidos para esta etapa según el PEB |
| 32 | 11_LOIN | 32_LOI_ObjetosTipo | El modelo cumple con los LOI establecidos para esta etapa según el PEB |
| 33 | 11_LOIN | 33_LOI Objetos Instancia | El modelo cumple con los LOI establecidos para esta etapa según el PEB |
| 34 | 11_LOIN | 34_LOG | El modelo cumple los el LOG mínimo establecido en el PEB |

<a id="modelo-ifc"></a>

## MODELO IFC

| N.º | Sección | Nombre | Descripción |
|:---:|---------|--------|-------------|
| 1 | IFC | 01_Schema IFC | El modelo IFC se encuentra exportado en el schema 4.3 establecido en el PEB |
| 2 | IFC | 02_Ifc Project | El IFC Project está debidamente diligenciado como LOTE 1 |
| 3 | IFC | 03_Site | El modelo IFC cuenta con el Site y está diligenciado como TRAMO 0001 o TRAMO 0002 |
| 4 | IFC | 04_Facility | El modelo IFC cuenta con Building o Facility o Bridge o Railway o Road y está bien diligenciado |
| 5 | IFC | 05_Tipos de Objetos IFC | Los objetos están clasificados según el tipo IFC 4.3 según la Building Smart |
| 6 | IFC | 06_Modelo IFC integrado y geolocalizado | Al integrar los modelos IFC estos se encuentran geolozalizados y coordinados |
| 7 | IFC | 07_cPset_GeographicLocation | Están diligenciados correctamente los parámetros del cPset_GeographicLocation |
| 8 | IFC | 08_ePset_SpaceCommon | Están diligenciados correctamente los parámetros del ePset_SpaceCommon |
| 9 | IFC | 09_Pset_DoorCommon | Están diligenciados correctamente los parámetros del Pset_DoorCommon |
| 10 | IFC | 10_Pset_EnvironmentalCondition | Están diligenciados correctamente los parámetros del Pset_EnvironmentalCondition |
| 11 | IFC | 11_Pset_ManufacturerTypeInformation | Están diligenciados correctamente los parámetros del Pset_ManufacturerTypeInformation |
| 12 | IFC | 12_Pset_MaterialCommon | Están diligenciados correctamente los parámetros del Pset_MaterialCommon |
| 13 | IFC | 13_Pset_ProcessCapacity | Están diligenciados correctamente los parámetros del Pset_ProcessCapacity |
| 14 | IFC | 14_Pset_ProjectCommon | Están diligenciados correctamente los parámetros del Pset_ProjectCommon |
| 15 | IFC | 15_Pset_ServiceLife | Están diligenciados correctamente los parámetros del Pset_ServiceLife |
| 16 | IFC | 16_Pset_SpaceOccupancyRequirements | Están diligenciados correctamente los parámetros del Pset_SpaceOccupancyRequirements |
| 17 | IFC | 17_Pset_TransportElementCommon | Están diligenciados correctamente los parámetros del Pset_TransportElementCommon |
| 18 | IFC | 18_Pset_Warranty | Están diligenciados correctamente los parámetros del Pset_Warranty |
| 19 | IFC | 19_Pset_WorkControlCommon | Están diligenciados correctamente los parámetros del Pset_WorkControlCommon |
| 20 | IFC | 20_Qto_FacilityPartBaseQuantities | Están diligenciados correctamente los parámetros del Qto_FacilityPartBaseQuantities |

<a id="modelo-federado"></a>

## MODELO FEDERADO

| N.º | Sección | Nombre | Descripción |
|:---:|---------|--------|-------------|
| 1 | MODELO FEDERADO | 01_Matriz de interferencias | El modelo Federado cuenta con el análisis de interferencias de acuerdo a la Matriz de Interferencias según el PEB |
| 2 | MODELO FEDERADO | 02_Cantidad de modelos | Cantidad de modelos en Federado es igual a la cantidad de modelos Individuales |
| 3 | MODELO FEDERADO | 03_Objetos 2D | El modelos Federado no contiene información 2D |
| 4 | MODELO 4D | 04_Modelo 4D | El modelo federado contiene la simulación constructiva 4D de acuerdo a lo indicado en el PEB |
| 5 | MODELO 5D | 05_Modelo 5D | El modelo federado contiene la información 5D de acuerdo a lo indicado en el PEB |
