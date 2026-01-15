## Actores interesados

Los actores interesados del sistema incluyen a los usuarios finales de la aplicación y a los administradores responsables de la gestión de la información. Los usuarios finales utilizan la aplicación para consultar rutas de transporte público y contribuir con nuevas rutas mediante un enfoque de crowdsourcing. Los administradores son responsables de registrar, validar y modificar la información de las rutas, especialmente en situaciones excepcionales como desvíos por obras o manifestaciones.

Adicionalmente, el desarrollo y mantenimiento inicial del sistema es realizado por una única persona en el marco de este trabajo. No obstante, el proyecto se concibe como software de código abierto, lo que permite la incorporación futura de otros desarrolladores interesados en contribuir a su evolución y mantenimiento.

## Roles de usuario

A partir de los actores interesados identificados, se definen los siguientes roles de usuario que interactúan directamente con el sistema:

- **Usuario final**: Consulta rutas de transporte público y contribuye con nuevas rutas mediante el registro de información en la aplicación.
- **Administrador**: Gestiona la base de datos de rutas, valida las contribuciones realizadas por los usuarios y actualiza la información ante cambios excepcionales en el servicio de transporte.

## Suposiciones

Se asume que los usuarios de la aplicación cuentan con acceso a una conexión a Internet durante su utilización, dado que el sistema depende de una base de datos centralizada para el almacenamiento y consulta de información. Asimismo, se considera que los usuarios poseen conocimientos básicos sobre el uso de aplicaciones móviles y sobre el funcionamiento del transporte público en el área metropolitana de Cochabamba.

Se asume que las contribuciones realizadas por los usuarios corresponden a rutas de transporte público urbano vigentes al momento de su registro y que los usuarios participan de manera voluntaria y colaborativa en el proceso de crowdsourcing, proporcionando información veraz en la medida de lo posible.

Finalmente, se asume que la aplicación es utilizada dentro del contexto geográfico para el cual fue diseñada, es decir, el área metropolitana de Cochabamba.

## Restricciones

El sistema se limita al registro y consulta de rutas del transporte público urbano del área metropolitana de Cochabamba. No se contemplan rutas correspondientes a flotas de transporte interdepartamental ni servicios de transporte de larga distancia. Los viajes interprovinciales son considerados únicamente cuando las provincias involucradas forman parte del área metropolitana de Cochabamba.

La aplicación está orientada a dispositivos móviles con sistema operativo Android y no contempla, en esta etapa, versiones para otras plataformas. El desarrollo del sistema se encuentra acotado al período de realización del trabajo de fin de grado y es llevado a cabo por una única persona.

Asimismo, el sistema no constituye una fuente oficial de información del transporte público, por lo que la validación y actualización de las rutas registradas se realiza de forma manual por parte de los administradores.

