## Requerimientos funcionales

En base al alcance del proyecto y las necesidades del público objetivo se han identificado las funcionalidades que el sistema debe presentar, las cuales se listan a continuación agrupadas en módulos conceptuales.

### Módulo A - Consulta y visualización de rutas

| ID    | Requerimiento                                                                                                                                                            | Actor         |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| RF-01 | El sistema deberá permitir a los usuarios consultar rutas del transporte público del área metropolitana de Cochabamba.                                                   | Usuario final |
| RF-02 | El sistema deberá permitir a los usuarios visualizar información detallada de una línea, incluyendo rutas, horarios y tarifas, cuando dicha información esté disponible. | Usuario final |

### Módulo B - Planificación de viajes

| ID    | Requerimiento                                                                                                                                   | Actor         |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF-03 | El sistema deberá permitir a los usuarios ingresar un punto de origen y un punto de destino para la planificación de un viaje.                  | Usuario final |
| RF-04 | El sistema deberá calcular posibles rutas entre un origen y un destino, considerando transbordos entre diferentes líneas de transporte público. | Sistema       |
| RF-05 | El sistema deberá presentar al usuario itinerarios posibles basados en rutas y horarios disponibles.                                            | Usuario final |

### Módulo C - Actualización de información mediante crowdsourcing

| ID    | Requerimiento                                                                                                                                                   | Actor         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF-06 | El sistema deberá permitir a los usuarios registrar reportes de cambios en líneas, rutas, tarifas u horarios del transporte público.                            | Usuario final |
| RF-07 | El sistema deberá aplicar controles básicos de validación para verificar la coherencia de la información ingresada por los usuarios antes de su almacenamiento. | Sistema       |
| RF-08 | El sistema deberá almacenar las contribuciones realizadas por los usuarios para su posterior revisión por los administradores.                                  | Sistema       |

### Módulo D - Administración del sistema

| ID    | Requerimiento                                                                                                                             | Actor         |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF-09 | El sistema deberá permitir a los administradores registrar y almacenar información oficial de líneas, rutas y tarifas.                    | Administrador |
| RF-10 | El sistema deberá permitir a los administradores registrar variaciones de líneas, como cambios parciales de ruta o tarifas según la zona. | Administrador |
| RF-11 | El sistema deberá permitir a los administradores revisar las contribuciones realizadas por los usuarios.                                  | Administrador |
| RF-12 | El sistema deberá permitir a los administradores aprobar, modificar o rechazar las contribuciones registradas por los usuarios.           | Administrador |

## Requerimientos no funcionales


| ID     | Requerimiento                                                                        |
| ------ | ------------------------------------------------------------------------------------ |
| RNF-01 | El sistema deberá ejecutarse en dispositivos móviles con sistema operativo Android.  |
| RNF-02 | El sistema deberá requerir conexión a Internet para la consulta y registro de rutas. |

