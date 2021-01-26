# Apuntes_UF2_1

**Pruebas**
+ **Dinámicas:** Requieren la ejecución de la aplicación. Permiten medir el comportamiento de la aplicación desarrollada.
+ **Estáticas:** Se realizan sin ejecutar el código de la aplicación. Se examina el código fuente.

**Estrategias de prueba**
+ **Caja negra:** Se estudia el sistema desde fuera. Son pruebas de funcionalidad.
+ **Caja blanca:** Se examina el código fuente y su ejecución. Son pruebas estructurales.

+ **Estrategias de prueba de caja negra**
    + Se estudia el sistema desde fuera.
    + Se trabaja sobre la interfaz.
    + No se tienen en cuenta los detalles internos de funcionamiento.
    +Se proporcionan entradas y se estudian las salidas.

+ **Obtención de código ejecutable**
    + Se examina el código fuente y su ejecución.
    + Se comprueban los flujos de ejecución dentro de cada unidad (función, clase, módulo, etc.).
    + También pueden comprobarse los flujos entre unidades durante la integración.
    + E incluso entre subsistemas, durante las pruebas de sistema.

**Tipos de pruebas**
+ **Funcionales:** Evaluan el cumplimiento de los requisitos.
+ **No funcionales:** Evaluan aspectos adicionales como rendimiento, seguridad, ...

**Pruebas funcionales**
+ Pruebas unitarias (o de unidad).
+ Pruebas de regresión.
+ Pruebas de integración.
+ Pruebas de humo (smoke test).
+ Pruebas del sistema.
+ Pruebas alfa y beta.
+ Pruebas de aceptación (validación por parte del cliente).

**Pruebas no funcionales**
+ Pruebas de usabilidad.
+ Pruebas de rendimiento.
+ Pruebas de stress.
+ Pruebas de seguridad.
+ Pruebas de compatibilidad.
+ Pruebas de portabilidad.

**Mecanismos de prueba**
+ **Manual:** Mediante pruebas realizadas por personal de la empresa o externo.
+ **Automático:** Mediante software que ejecuta código de forma automatizada y compara los resultados obtenidos y los resultados esperados.

**Soporte del depurador**
+ Puntos de ruptura.
+ Ejecución paso a paso.
+ Análisis de variables.

**Automatización de pruebas** 
+ Frameworks de pruebas (xUnit).
+ Aserciones.

**Frameworks para pruebas**
+ Java: JUnit, TestNG.
+ C++: CppUnit, Google Test.
+ PHP: PHPUnit.
+ Javascript: Mocha.

**TDD (Desarrollo guiado por pruebas de software, o Test-Driven Development)**
+ Escribir las pruebas primero (Test First Development).
+ Refactorización (Refactoring).
