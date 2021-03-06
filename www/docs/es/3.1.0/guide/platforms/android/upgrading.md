---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

title: Actualizar Android
---

# Actualizar Android

Esta guía le muestra cómo modificar proyectos Android para actualizar desde versiones anteriores de Córdoba. La mayoría de estas instrucciones se aplica a proyectos creados con un conjunto mayor de herramientas de línea de comandos que preceden a la utilidad de la CLI de `cordova`. Vea la interfaz de línea de comandos para información de cómo actualizar la versión de la CLI.

## Actualización a 3.1.0 de 3.0.0

Para los proyectos que se crearon con el cordova CLI:

1.  Actualización de la `cordova` versión CLI - ver la interfaz de línea de comandos 
2.  Ejecutar`cordova platform update android`

Para proyectos no creados con el cordova CLI, ejecute:

1.  `bin/actualizar < project_path >`

## Actualícese a la CLI (3.0.0) de 2.9.0 magnetohidrodinámica

1.  Crear un nuevo proyecto de Apache Cordova 3.0.0 usando el cordova CLI, tal como se describe en la interfaz de línea de comandos.

2.  Agregar tus plataformas el proyecto de la Córdoba, por ejemplo:`cordova
platform add android`.

3.  Copiar el contenido de su proyecto `www` Directorio del `www` Directorio en la raíz del proyecto cordova que acaba de crear.

4.  Copie cualquier activo nativo de su viejo proyecto en los directorios apropiados bajo `platforms/android` : este directorio es donde existe su proyecto cordova-android nativo.

5.  Utilice la herramienta CLI cordova instalar algún plugin que necesita. Tenga en cuenta que la CLI maneja todo núcleo APIs como plugins, así pueden necesitar ser agregado. Sólo 3.0.0 plugins son compatibles con la CLI.

## Actualizar a 3.0.0 desde 2.9.0 magnetohidrodinámica

1.  Crear un nuevo proyecto Apache Cordova Android.

2.  Copiar el contenido de tu `www` directorio al nuevo proyecto.

3.  Copiar cualquier nativos Android activos desde su `res` directorio al nuevo proyecto.

4.  Copia sobre algún plugin instaló desde el `src` subdirectorios en el nuevo proyecto.

5.  Asegúrese de actualizar cualquiera obsoleto `<plugin>` referencias de su vieja `config.xml` archivo a la nueva `<feature>` especificación.

6.  Actualizar todas las referencias a la `org.apache.cordova.api` paquete para ser`org.apache.cordova`.

*   **Nota:** núcleo todas las APIs se han eliminado y deben instalarse como plugins. Para detalles, véase el Plugman usando para gestionar Plugins guía.

## Actualizar a 2.9.0 magnetohidrodinámica de 2.8.0

1.  Ejecutar`bin/update <project_path>`.

## Actualizar a 2.8.0 desde 2.7.0

1.  Quitar `cordova-2.7.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.8.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova.js` archivo.

6.  Copia el `res/xml/config.xml` archivo para que coincida con`framework/res/xml/config.xml`.

7.  Actualización `framework/res/xml/config.xml` tener configuraciones similares como lo hizo anteriormente.

8.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.7.0 desde 2.6.0

1.  Quitar `cordova-2.6.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.7.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.7.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo archivo de `cordova-2.7.0.js`.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  

8.  Copiar archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.6.0 desde 2.5.0

1.  Quitar `cordova-2.5.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.6.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.6.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.6.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  Actualización `framework/res/xml/config.xml` tener configuraciones similares como lo hizo anteriormente.

8.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

Ejecutar `bin/update <project>` con la ruta del proyecto figuran en el directorio fuente Cordova.

## Actualizar a 2.5.0 desde 2.4.0

1.  Quitar `cordova-2.4.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.5.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.5.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.5.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  Actualización `framework/res/xml/config.xml` tener configuraciones similares como lo hizo anteriormente.

8.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.4.0 desde 2.3.0

1.  Quitar `cordova-2.3.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.4.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.4.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.4.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.3.0 desde 2.2.0

1.  Quitar `cordova-2.2.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.3.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.3.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.3.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.2.0 desde 2.1.0

1.  Quitar `cordova-2.1.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.2.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.2.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.2.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.1.0 desde 2.0.0

1.  Quitar `cordova-2.0.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.1.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.1.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.1.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

7.  Copiar los archivos de `bin/templates/cordova` para el proyecto `cordova` Directorio.

## Actualizar a 2.0.0 desde 1.9.0

1.  Quitar `cordova-1.9.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-2.0.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-2.0.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-2.0.0.js` archivo.

6.  Copia el `res/xml/config.xml` para que coincida con`framework/res/xml/config.xml`.

### Notas sobre 2.0.0 liberar

`config.xml`reemplazará a `cordova.xml` y `plugins.xml` . Este nuevo archivo es una combinación de las dos anteriores. Sin embargo, los archivos son desaprobados y mientras que actualmente todavía trabajo, dejará de trabajar en una versión futura.

## Actualizar a 1.9.0 desde 1.8.1

1.  Quitar `cordova-1.8.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.9.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.9.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo archivo de `cordova-1.9.0.js`.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

### Notas sobre 1.9.0 liberar

Debido a la introducción de la `CordovaWebView` , plugins de terceros pueden no funcionar. Estos plugins necesito un contexto de la `CordovaInterface` usando `getContext()` o `getActivity()` . Si no eres un experimentado Desarrollador Android, por favor póngase en contacto con el mantenedor del plugin y añadir esta tarea a su localizador de fallas.

## Actualizar a 1.8.0 desde 1.8.0

1.  Quitar `cordova-1.8.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.8.1.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.8.1.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-1.8.1.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

## Actualizar a 1.8.0 de 1.7.0

1.  Quitar `cordova-1.7.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.8.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.8.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-1.8.0.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

## Actualizar a 1.8.0 de 1.7.0

1.  Quitar `cordova-1.7.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.8.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.8.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `cordova-1.8.0.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

## Actualizar a 1.7.0 desde 1.6.1

1.  Quitar `cordova-1.6.1.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.7.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.7.0.js` en su proyecto.

5.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

## Actualizar a 1.6.1 desde 1.6.0

1.  Quitar `cordova-1.6.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.6.1.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.6.1.js` en su proyecto.

5.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

## Actualizar a 1.6.0 de 1.5.0

1.  Quitar `cordova-1.5.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.6.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.6.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo archivo de `cordova-1.6.0.js`.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

7.  Reemplazar `res/xml/phonegap.xml` con `res/xml/cordova.xml` para que coincida con`framework/res/xml/cordova.xml`.

## Actualizar a 1.5.0 de 1.4.0

1.  Quitar `phonegap-1.4.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `cordova-1.5.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `cordova-1.5.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo archivo de `cordova-1.5.0.js`.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

7.  Reemplazar `res/xml/phonegap.xml` con `res/xml/cordova.xml` para que coincida con`framework/res/xml/cordova.xml`.

## Actualizar a 1.4.0 de 1.3.0

1.  Quitar `phonegap-1.3.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `phonegap-1.4.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `phonegap-1.4.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `phonegap-1.4.0.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

7.  Actualización de `res/xml/phonegap.xml` para que coincida con`framework/res/xml/phonegap.xml`.

## Actualizar a 1.3.0 de 1.2.0

1.  Quitar `phonegap-1.2.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `phonegap-1.3.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `phonegap-1.3.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `phonegap-1.2.0.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

7.  Actualización de `res/xml/phonegap.xml` para que coincida con`framework/res/xml/phonegap.xml`.

## Actualizar a 1.2.0 desde 1.1.0

1.  Quitar `phonegap-1.1.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `phonegap-1.2.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `phonegap-1.2.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `phonegap-1.2.0.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

7.  Actualización de `res/xml/phonegap.xml` para que coincida con`framework/res/xml/phonegap.xml`.

## Actualizar a 1.1.0 desde 1.0.0

1.  Quitar `phonegap-1.0.0.jar` del proyecto de `libs` Directorio.

2.  Añadir `phonegap-1.1.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `phonegap-1.1.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `phonegap-1.1.0.js` archivo.

6.  Actualización de `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.

## Actualizar a 1.0.0 desde 0.9.6

1.  Quitar `phonegap-0.9.6.jar` del proyecto de `libs` Directorio.

2.  Añadir `phonegap-1.0.0.jar` del proyecto `libs` Directorio.

3.  Si usted está usando Eclipse, por favor actualice su proyecto en eclipse y hacer una limpia.

4.  Copie el nuevo `phonegap-1.0.0.js` en su proyecto.

5.  Actualizar el código HTML para usar el nuevo `phonegap-1.0.0.js` archivo.

6.  Agregar el `res/xml/plugins.xml` para que coincida con`framework/res/xml/plugins.xml`.