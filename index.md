| MODEL QUALITY |
|---|
| Tabla de contenido<br>DESCARGA E INSTALACIÓN<br>Instalación<br>USO DEL PLUGIN<br>2. GESTION DE OBSERVACIONES MEDIANTE EL PLUGIN<br>2.1. Visualización de observaciones<br>Modelo abierto corresponde con el hallazgo seleccionado<br>Modelo abierto no corresponde con el hallazgo seleccionado<br>2.2 Respuesta y cierre de observaciones:<br>2.3 Exportación de resultados<br>Este plugin permite visualizar, gestionar y dar respuesta a los requerimientos de calidad generados para cada uno de los modelos<br>desarrollados en el proyecto.<br>DESCARGA E INSTALACIÓN<br>El instalador puede descargarse desde la plataforma Autodesk Construction Cloud (ACC) en el siguiente enlace:<br>Archivos - Data Management<br>Autodesk Construction Cloud<br>https://acc.autodesk.com/docs/files/projects/7d7c9a92-3a37-4cb1-8bcc-3446ffb6535d?folderUrn=urn%253Aadsk.wipprod%2 53Afs.folder%253Aco.KygclwowQyv66...<br>Instalación<br>1. Descargue el archivo comprimido (ZIP).<br>2. Descomprima el contenido en una carpeta local.<br>3. Ejecute el instalador haciendo doble clic sobre el archivo correspondiente.<br>Importante: Revit debe estar completamente cerrado antes de iniciar la instalación para garantizar el correcto<br>funcionamiento del complemento.<br>USO DEL PLUGIN<br>1. Exportación del archivo JSON |

![MODEL_QUALITY p1 img1](img/MODEL_QUALITY_p01_01.jpg)

---

Los reportes de calidad BIM se gestionarán por medio de la plataforma BIM Quality Report - QA/QC. Para cada reporte, se generará un link, donde cada especialista podrá consultar las observaciones generadas a sus modelos tanto en formato RVT como IFC. Para interactuar con el Plugin, es necesario generar dos archivos Json a partir del reporte de calidad. * Un archivo JSÓN correspondiente a las observaciones de los modelos RVT. * Un archivo JSON correspondiente a las observaciones de los modelos IFC. A continuación se describe el procedimiento para exportar estos reportes en formato JSON.

![MODEL_QUALITY p2 img1](img/MODEL_QUALITY_p02_01.jpg)

## -

Ma duelitu Report CA/0C rrpp | BIM QUALITY REPORT Model Quality Report IFC Quality Report

## 1 2 3 4

Au files La All disciplines « Al results * | OCiearfilters | 2 Export JSON - e Overview q” [ R E B S e U ar L c T h result... -) rail results (Value colur 3 Export JSON OVERALL % FILES IN SCOPE PASS , Anresuts Export fullreport COMPLIANCE Pass Al files 8 cnecks 5 elements 83% $ Based on 510 24 451 d Pass/Fail Fall ; +5 luedk Exportcumrevnietw evaluations of 24 total files passed check! NA Onty what matches active filters e Summary by ¡item Summary per evaluated ltem (Name column in Checks). Click a row to filter the detail view betow. E Search tem. SORT BY COMPLIANCE: [ Detaut ) Highest first Lowest first O <50% E 50-75% 9 7550% E aIDO% NAME PASS FAIL NA % COMPLIANCE - O1.Codificación Modelo 24 [1] e] 166.0% | 1. Al abrir el link del reporte, se encontrará con la plataforma que se muestra en la imagen. 2. Enel campo identificado con el número 1, seleccionar el tipo de reporte que se desea exportar: * Model Quality Report para la validación de modelos RVT. * IFC Quality Report para la validación de modelos IFC. M Nota: Aunque existen dos tipos de reporte, la atención y corrección de las observaciones se realiza desde el modelo de Revit. 3. Enel segundo campo, filtrar la disciplina que desea revisar. 4. En el tercer campo, seleccionar el estado de los resultados: * Pass: elementos que cumplen los criterios de calidad. * Fail: elementos que presentan observaciones. * N/A: elementos no aplicables para la disciplina evaluada. Para el proceso de subsanación de observaciones, se recomienda filtrar únicamente los elementos con estado Fail. 5. Enel cuarto paso, seleccionar el alcance de la exportación: * Reporte completo. * Reporte filtrado según los criterios definidos en los pasos anteriores. Una vez haga clic en la opción seleccionada, automáticamente se generará el archivo JSON y se guardará en la carpeta de descargas.

## 2. GESTION DE OBSERVACIONES MEDIANTE EL PLUGIN

Una vez generados los archivos JSON, estos deben gestionarse individualmente.. 1. En Revit, ubique la pestaña "Egis Smart Tools" y seleccione el ícono "Model Quality"

---

a LEdS-<---ÓM il! =-SDA la -ó El Ez ES- + TE ANLODO7 Fo PRI9 TROCO.CTO0O EST.M30:0002 CON DATA: detached - 3D View: 3D COORDINACIÓN. — y df A ivoniesatama... VI O- ES

![MODEL_QUALITY p3 img1](img/MODEL_QUALITY_p03_01.jpg)

LUCE Architecture Structure Steel Precast Systems insert Annotaté Analyze Massing é1Site Collaborate View Manage Add-Ins InteroperabTiloitoyls BlMcollab BIMECO. EGIS Smart Tools £gis Bird Tóocis » C)-

## ea | a e EZBE

Clash Calculate Calculate Medel Create Elevar Floor Export Import Viewer Area — Volume Quality Parameters al o Clash Tools Takeoff ¡Quality BIM $ BIM Pai ( 8. Land: Pa Sync —_ Bopeves: — — — —. $ 3DCOORDINACION X 3D View: 3D_COORDINACION v ES Edit Type y, NO , 1 o View Scale 1:100 2. Al hacer clic, se desplegará la ventana principal del plugin: 3. Seleccione la opción "Open JSON" y cargue el archivo correspondiente al reporte que se desea atender.

![MODEL_QUALITY p3 img2](img/MODEL_QUALITY_p03_02.jpg)

[a Model Quality|EGIS — a] x EGIS SMART TOOLS Model Quality 1. Quality report Select the Model Quality JSON report exported from the HTML dashboard (full report). TASK CHECK SET PROJECT FILES PASS FAIL N/A COMPLIANCE ANSWERED 0 0 0 0 0% 0/0 2. Filters DISCIPLINE MODEL FILE CHECK MEM RESULT SEARCH — (AI » ] [cam * | [cam * | [Am | | Fals ony | Gear | 3. Checks O checks Result Madal file Disc Check item kKems — “Status Response Reviewer

| |

4. Review response 5. Reported elements Select the list Category Family Type Name Value | | a checkcin a Elemantid

|

STATUS RESPONSE ! v E | Zoam to | | Show all | [] Use grid selection |

|

Load a Model Quality JSON report to start. 4. Una vez cargado el reporte, se visualizará la siguiente información:

---

![MODEL_QUALITY p4 img1](img/MODEL_QUALITY_p04_01.jpg)

|* EEES e

EGIS SMART TOOLS

### Model Quality

1. Quaiity report Select the Model Quality SON report exported from the HTML deshboard (fullreporti. CAUsersV salamanca DovnioadstFE_ANI_0007,F2_PR15_TROCO_NA0O00D2 MOe_dBel IQMua_litQy fAilteLred view 20250921_1720.50nEE) TASK CHECK SET PROJECT REPORT CATE FE_ANIO007_FZ PR15_TRUO0.NAOO0_BIM_QAL_0007 Egis Colombia Check VE-891-2025 Tuesday, 15 September 2026 - 15:13:00 UTC RALES PASS FAIL NA COMPLIANCE ANSWERED o 110 25 15 81.5% 0/25

# 3

2.Filters DISCIPLINE MODEL FILE CHECK TEN RESET SEARCH [an | [000 | [Am «| [am Fails only | Caer = * Y] 3. Checks ;—l.;—“—[.Ñ LEDO 25 checas FE_ANLO007 F2 PRI9_TRO0O_CTO00_EST_M3D0004 03_Alertas 1 Pending EED re AnLo0o? 62 prisTRODO.CTO00.EST.M3D0004 08 Purge 136 | Pending

| Fail | FE_ANI_0007_F2 PRI9_TRODO_CTODO_EST_M30_0004 25Import Cad e Pending

FE_ANI_0007_F2_PR19 TRODO_CTODO_EST_M3C_0004 26_Links Cad 1 Ponding FE_ANI_0007_F2_PR19_TRODO_CTO06_EST_M3D_0004 29_Nombre de Vistas 6 Pending Fail FE_ANI_0007_F2.PR19.TRODO_CTOOO_EST_M3D_0001 03 Mertas 1 Pending FE ANI_0007_F2_ PR19_TROOO_CTO0O_EST_M3D_0001 08 Purge [1 Pending = —C—A— d. Review response 5. Reported elements STATUS

- |

RESPONSE

- E tipo | Farm tu Show all ] Use grid selection

Report ivaded: 25 checks, 25 failed. Ea) Responses CALSEriiaman Dom FE AN DOCE PRIS TROCO RZACOO Ev CAL 0002 Mardel Queiiy Gitered view 20260921 1720 responses ivonne salemanca jon 1. Nombre del reporte de calidad cargado. 2. Numero de elementos que presentan observaciones 3. Casilla para mostrar únicamente los elementos con errores. 4. Nombre del modelo donde se encuentra el hallazgo 5. ftemo validación que presenta el error. 6. Campo Status, correspondiente al estado de atención del hallazgo. 7. Campo Review Response, donde se puede consultar el detalle del hallazgo y registrar la respuesta correspondiente. 2.1. Visualización de observaciones Al seleccionar una fila del reporte en el apartado 3.Checks, pueden presentarse dos escenarios: Modelo abierto corresponde con el hallazgo seleccionado Si el archivo abierto en Revit corresponde al modelo asociado al hallazgo seleccionado: * Se mostrará la descripción del error. * Sevisualizará el detalle de los elementos reportados.

---

![MODEL_QUALITY p5 img1](img/MODEL_QUALITY_p05_01.jpg)

E Nodel Quality | EGIS EGIS SMART TODES REVIEWER Model Quality Autodesk Revit 2026 1. Quality report Select the Model Quality JSON report exported from the HTML dashboard (full report). CAUsersi salamanca Downloads FE ANI 0007_F2 PR15 TROOO NADOO BIM_QAL 0002 Model Quality filtered view 20260921 _1720json | Reload | | Open folder TASK CHECK SET PROJECT REPORT DATE FEANI_0007_FP2R15TRO0O_NAO00_BIM_Q00A0L2 Egis Colombia Check VE-891-2025 Tuesday. 15 September 2026 - 15:13:00 UTC FILES PASS FALL N/A COMPLIANCE ANSWERED 0 110 25 15 81.5% 0/25 2. Filters DISCIPLINE MODEL FILE CHECK ITEM RESULT SEARCH —

| TAN » | [am * | [cam y | [(AN | | 19] Fails onty | Clear |

3. Checks 25 ch — ecks . Result Model file Disc Check item HKems Status Response Reviewer [ Fail| FE ANL0007 F2_PRi9_TRO00_CTO00_EST_M3D 0002 28Nombrdee Niveles 1 Pending A El FE ANL0007 F2 PR19 TRODO_CTOCD_EST_M3D 0002 29_Nombre de Vistas 7 Pending FEANL_000F72 PR19TRODO_STOCO_EST_M3D_0001 08 Purge 33 Pending

| Fail| FE ANL 0007 F2 PR19TRODO_STGO0_EST_M3D_0001 25Import Cad 4 Pending

El FEANL00F027 PR19TRODO_STOCO_EST_M3D_0001 28Nombre de Niveles: 1 Pending ED FE ANL0007 F2 PR19 TRODO_STO00 EST_M3D_0001 29_Nombre de Vistas 8 Pending | »” 4. Review response 5. Reported elements 2 row(s) - 2 with a Revit element ¡d 28Nombre de Niveles ” Category Family Type ' Name Value Element Id FE_ANL0007_F2PR19_TRO0O_CTO00_EST_M3D_0002 | Losniveles Mi se encuentran nombrados de acuerdo a lo indicado en el PEB Views Floor Plan NENIVEL-CUMBRERA+648m MOTA —_ — Views Floor Plan NE NIVEL-CIMENTACIÓN_-0... 1719085 Existen niveles que na están nombrados de acuerdo a la —

- - —-

codificación del PEB Tabla 55. Nomenclatura niveles ,

### oSTAT US NEL... |.

Report loaded: 75 checks, 25 failed. - Responses: CAUserstisalamanca Downloads FE_ANI_0007F2 PRI5 TRO0O NADCO BIM_CIAL 0002 Model Quality filtered view 20260921 1720.responses.vonnesalamanca.json A Modelo abierto no corresponde con el hallazgo seleccionado Si el archivo abierto no corresponde al modelo asociado al hallazgo: * Se mostrará un mensaje indicando que el modelo abierto no coincide con la observación seleccionada. No será posible visualizar el detalle de los elementos reportados hasta abrir el modelo correcto.

![MODEL_QUALITY p5 img2](img/MODEL_QUALITY_p05_02.jpg)

a Made! Ouality | EGIS EGIS SMART TOOLS Model Quality 1. Quality report Select the Model Quality JSON report exported from the HTML dashboard (full report). CAUsersiisalamaDnocwanl|oadsFE ANI_0007 F2_PR15_TRO00_NAOOO BIM_QAL 0002 Model Quality filtered view 20260921 1720json Reload | | Open folder

|

TASK CHECK SET PROJECT REPORT DATE FE_ANL0007 F2_PRi5TROCO_NACOO_BIM_C00AL02 Egis Colombia Check VE-891-2025 Tuesday, 15 September 2026 - 15:13:00 UTC FILES PASS FALL N/A COMPLIANCE ANSWERED 0 110 25 15 81.5% 0/25 |

| 2. Filters

DISCIPLINE MODEL FILE THECK ITEM RESULT SEARCH — —— [AD * ] [am *] [AD *] [an "E WI

| Faisony | Clear

U

| 3. Checks 25 checks

Result Madel file Disc. — Checkitam Items — Status ” Response Reviewer [Fai | FEANL0007_F2_PR19_TROC0_CTO0O_EST_M3D_0002 28Nombre de Niveles Pending A Fail FEANL0007_F2 PR19_TRO00_CTODO_EST_M3D_0002 29_Nombre de Vistas 7 Pending E FE_ANL0007_F2PR19_TRODO_STOOO_EST_M3D_0001 08 Purge 33 Pending El FEANL000F72 PR19 TRODO_STO0O EST_M3D 0001 25 Import Cad 4 Pending [ Fail| FEANLO0F027 . PR19_TRO00_STOOO,EST_M3D.0001 28Nombre de Niveles Pending |

| Fail| FE ANI 0007 F2 PR19 TRODO_STOJO EST_M3D 0001 29Nombre de Vistas 8 Pending |

|

v

|

| 4. Review response 5. Reported elements 4 rows) - 3 with a Revit element id

- 25Import Cad la These elements belong to FE ANI 0007F2_PR19_TROO0_STODO_EST_M3D0001.The active document is

| FE ANL0007_F2 PR19-TROCO STOO0EST_M3D_0001 | No existen FE_ANI_0F020 7PR19TRODO_CTODO_EST_M3D_0002 CON DATA detached, so Select/Isolate will probably find nothing.

archivos importados en CAD — —

| Madelo tiene CADy/o Links importandos | Ca — t egory - Family T d i it - Name , Value Element id —

| Imports in Families -2000196 Lo)

Defncints pPraemuns ding E 1663952 e | selec | | solate | Zoomto | Show all | [] Use grid setection ] ODCSOoONMNEC Report loaded: 25 checks, 25 failed. Responses: CAUseriisalamanca Downloads FE_ANI_0007_F2 PR15 TRODO NADCG BIM_QAL DOO? Model Quality filtered view 20260921 1720.responses.vonnesalamancajson —

---

### 2.2 Respuesta y cierre de observaciones:

Una vez se inicie la atención de las observaciones, en la casilla 4 se debe: 1. Actualizar el campo Status con el estado correspondiente. 2. Registrar los comentarios o aclaraciones necesarias en el campo Response. 3. Hacer clic en "Save Response" para guardar la información.

![MODEL_QUALITY p6 img1](img/MODEL_QUALITY_p06_01.jpg)

Le

- 4, Review response

03_Alertas

| FE ANLO00F27 PRI9TRONCOTO00_EST_M3D 0002 | Existen

¡ wamings o alertas razonables menores a 20 i Revisar las alertas | RESPONSE Se eliminan alertas Last update 2025-09-21 37:42, » Importante: La acción "Save response" permitirá conservar las respuestas registradas y continuar con la revisión en una sesión posterior si es necesario. Una vez guardada la respuesta: * El estado de la observación se actualizará automáticamente. * Se almacenará la respuesta registrada. * Se guardará el nombre del responsable que realizó la revisión.

![MODEL_QUALITY p6 img2](img/MODEL_QUALITY_p06_02.jpg)

3. Checks Le Y rd Result Model file Disc. Checkitem — tems Status Response Reviewer

| Fail| FE_ANL_0007_F2 PRÍS TROO0_CTO00_EST_ M3D_0002 03_Alertas 1 Corrected Se eliminan alertas ivonne.salamanca

Fail FE_ANL_0007_F2_PR19_TRODO_CTO00_EST_M3D_0002 25_ Import Cad 1 Pending

| | Fail| FE_ANL0007_F2_PR19_TRC00_CTO00_EST. M3D. 0002 28Nombre de Niveles 4 Pending

### 2.3 Exportación de resultados

Cuando todas las observaciones hayan sido atendidas: 1. Hacer clic en el botón "Export Power BI" 2. Guardar el archivo generado. 3. Remitir el archivo por correo electrónico a la Coordinación BIM para su consolidación y seguimiento. De esta manera, la Coordinación BIM podrá actualizar el estado de los hallazgos dentro del reporte general de calidad del proyecto.

---
